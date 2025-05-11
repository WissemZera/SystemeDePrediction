# 🧠 Système de Prédiction des Risques de Non-Paiement par Chèque

Ce projet vise à développer un système intelligent capable de prédire les risques de non-paiement des chèques, en se basant sur différentes sources de données collectées par La Poste Tunisienne entre juin 2024 et mars 2025. Il s'inscrit dans le cadre d'un projet de fin d'études en Business Intelligence et Data Science.

---

## 📊 Sources de Données

### 1. Données sur les chèques (01.06.2024 → 31.03.2025)
- Date de présentation du chèque  
- Numéro de chèque  
- Montant du chèque  
- Numéro du compte émetteur  
- Numéro du compte bénéficiaire  
- Type de chèque (certifié, ordinaire, etc.)  
- Statut du chèque (payé / rejeté)  
- Motif de rejet (insuffisance de solde, opposition, etc.)  

### 2. Données sur les lettres de change (01.06.2024 → 31.03.2025)
- Date opération  
- RIP  
- RIB  
- Num_LC  
- Date échéance  
- Montant  
- Statut : payée ou rejetée  
- Motif de rejet  

### 3. Données sur l’émetteur du chèque
- Identifiant client  
- Type de client (particulier / entreprise...)  
- Ancienneté du compte (date création du compte)  
- Solde moyen sur les 6 derniers mois  
- Historique des incidents de paiement  
  - Nombre de chèques impayés dans le passé  
  - Fréquence des incidents  
- Revenus mensuels  
- Secteur d’activité ou fonction  
- Date de naissance  
- Gouvernorat  

### 4. Données transactionnelles (01.06.2024 → 31.03.2025)
- RIP  
- Nombre de transactions récentes  
- Comportement mensuel (fréquence des retraits / dépôts)  
- Nombre de chèques rejetés  

---

## ⚙️ Technologies utilisées


- Python 3.13.1
- Pandas / NumPy  
- Scikit-learn  
- Visual Studio Code  
- Power BI (pour la visualisation et le reporting)

---

## 🚀 Objectifs
 
- Nettoyage, fusion et transformation des données multi-sources  
- Entraînement de modèles de Machine Learning pour la classification (chèque payé ou rejeté)  
- Intégration des prédictions dans Power BI via pipeline ETL  
- Détection proactive des comportements à risque

---

## 🧪 Exécution

Installez les dépendances avec :

```bash
pip install -r requirements.txt
