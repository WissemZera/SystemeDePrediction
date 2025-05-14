# 🧠 Système de Prédiction des Risques de Non-Paiement par Chèque et par Lettre de Change

Ce projet s’inscrit dans le cadre d’un projet de fin d’études en Business Intelligence et Data Science. Il a été réalisé au sein de **La Poste Tunisienne**, une entreprise publique jouant un rôle clé dans le développement économique et la transformation digitale de la Tunisie.

---

## 🏢 Organisme d’accueil : La Poste Tunisienne

Créée en janvier 1999, La Poste Tunisienne est un établissement public à caractère industriel et commercial. Elle se distingue par ses deux activités principales :

- 📬 **Services postaux** : collecte, transport et distribution du courrier
- 💳 **Services financiers** : gestion des comptes postaux et services d’épargne

La Poste Tunisienne innove également à travers de nouveaux services numériques pour les particuliers et les entreprises, dans le cadre de la stratégie nationale de digitalisation.

---

## 📌 Contexte du projet

Comme toute institution financière, La Poste Tunisienne est confrontée à des **incidents de paiement** liés aux chèques et aux lettres de change. Ces incidents peuvent entraîner des pertes financières importantes et nuire à la réputation de l’établissement. En l’absence d’un outil prédictif, il est difficile d’anticiper les risques clients.

---

## ❗ Problématique

- Taux élevé de chèques sans provision
- Faible visibilité sur les profils à risque
- Processus de prévention peu automatisé

---

## 💡 Solution proposée

Ce projet vise à **mettre en place un système de prédiction** basé sur le Machine Learning permettant de :

- 🧠 Identifier les clients les plus à risque de non-paiement
- 📈 Intégrer les résultats dans un **tableau de bord interactif Power BI**
- ✅ Aider les décideurs à **anticiper et réduire les risques financiers**

---

## 📊 Sources de données (juin 2024 → mars 2025)

### 1. Données sur les chèques
- Date de présentation  
- Numéro de chèque  
- Montant  
- Numéro de compte (émetteur / bénéficiaire)  
- Type de chèque  
- Statut (payé / rejeté)  
- Motif de rejet  

### 2. Données sur les lettres de change
- Date opération  
- RIP / RIB  
- Numéro de la lettre de change  
- Date d’échéance  
- Montant  
- Statut : payée ou rejetée  
- Motif de rejet  

### 3. Données sur l’émetteur
- Identifiant client  
- Type de client  
- Ancienneté du compte  
- Solde moyen  
- Revenus mensuels  
- Historique d’incidents de paiement  
- Secteur d’activité / fonction  
- Gouvernorat  

### 4. Données transactionnelles
- RIP  
- Fréquence des transactions  
- Nombre de chèques rejetés  
- Comportement mensuel (dépôts / retraits)

---

## ⚙️ Technologies utilisées

- Python 3.13.1  
- Pandas / NumPy  
- Scikit-learn  
- Visual Studio Code  
- Power BI (reporting et visualisation)

---

## 🎯 Objectifs principaux

- Nettoyer, fusionner et enrichir les données multi-sources  
- Entraîner un modèle de Machine Learning pour prédire les incidents  
- Implémenter un pipeline ETL pour intégrer les résultats dans Power BI  
- Fournir un outil décisionnel simple et efficace à La Poste Tunisienne

---

## 🧪 Exécution

Installez les dépendances nécessaires avec la commande suivante :

```bash
pip install -r requirements.txt
