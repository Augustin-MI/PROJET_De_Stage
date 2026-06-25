# JCK_Analysis - Audit Transactionnel & Gouvernance des Données

## 📌 Description
Ce dépôt contient le notebook d'audit des données transactionnelles de l'entreprise JCK, réalisé dans le cadre d'une mission d'analyse de données et de business intelligence.

L'objectif est de collecter, nettoyer, analyser et visualiser les données de 4 800 transactions pour identifier les leviers de croissance, sécuriser la santé financière et fournir des recommandations stratégiques à la direction.

## 📁 Fichiers

| Fichier | Description |
|---------|-------------|
| `Analyses.ipynb` | Notebook principal - Audit complet des données JCK |
| `Audit_Strategique_JCK_Complet.png` | Dashboard final des 12 indicateurs stratégiques |
| `Audit_Strategique_JCK_Complet.pdf` | Version PDF du dashboard |
| `requirements.txt` | Dépendances Python |
| `README.md` | Documentation du projet |

## 📊 Résultats du Diagnostic Données

| Indicateur | Valeur |
|------------|--------|
| Nombre total de transactions | 4 800 |
| Nombre de colonnes | 19 |
| Taux de remplissage | 100% |
| Valeurs nulles | 0 |
| Doublons détectés | 0 |

## 📊 Résultats de l'Analyse Financière

| Indicateur | Valeur (CFA) | Valeur (Euro) |
|------------|--------------|---------------|
| Chiffre d'Affaires Total | 164 521 000 CFA | 250 809.50 € |
| Reste à Recouvrer | 54 735 000 CFA | 83 442.59 € |
| Panier Moyen | 34 275 CFA | 52.25 € |
| Taux de Recouvrement | 66.73% | - |

## 📊 Résultats de l'Analyse Commerciale

| Indicateur | Résultat |
|------------|----------|
| **Segmentation** | Diaspora : 30% (1 439) / Local : 70% (3 361) |
| **Top Articles** | Kit Scolaire (2 416), Pack Particulier (1 178), Pack Restau (606), Pack Maquis (600) |
| **Satisfaction Client** | 9.85 / 10 - ✅ Excellence Client |

## 📊 Résultats de l'Analyse des Canaux & Paiements

| Canal de Vente | Clients | Revenus (CFA) | Part |
|----------------|---------|---------------|------|
| Facebook | 1 674 | 56 322 000 | 34.9% |
| Site Web | 1 572 | 53 922 000 | 32.8% |
| WhatsApp | 1 554 | 54 277 000 | 32.4% |

| Mode de Paiement | Transactions | Part |
|------------------|--------------|------|
| Cash | 2 547 | 53.1% |
| Crédit | 1 133 | 23.6% |
| Tontine | 1 120 | 23.3% |

## 📊 Résultats du Dashboard (12 Indicateurs)

| # | Indicateur | Observation Clé |
|---|------------|-----------------|
| 1 | Analyse Temporelle | Pic d'activité constaté au Q4 (périodes festives) |
| 2 | Performance Régionale | Kpalimé en tête (2 372K CFA) |
| 3 | Origine des Fonds | Diaspora : 75% du CA généré |
| 4 | Secteurs d'Activité | Éducation, Restaurant, Alimentaire |
| 5 | Santé Financière | Taux de recouvrement : 66.73% |
| 6 | Visibilité Numérique | Corrélation forte entre visibilité et CA |
| 7 | Canaux de Vente | WhatsApp : 42% d'engagement |
| 8 | Variabilité des Profits | Secteur Éducation le plus stable |
| 9 | Cartographie RH | Forte intensité le week-end |
| 10 | Synthèse KPI | Excellence en S.A.V et Fiabilité |
| 11 | Évolution Annuelle | Croissance constante 2023-2026 |
| 12 | Modes de Paiement | Cash prédominant (53.1%) |

## 💡 Recommandations Stratégiques

### 🔴 Actions Prioritaires
| Action | Description |
|--------|-------------|
| Automatisation CRM | Intégrer un chatbot WhatsApp Business |
| Ciblage Géographique | Concentrer les campagnes sur Kpalimé et Kara |
| Recouvrement | Mettre en place des rappels automatiques pour les crédits |

### 🟡 Optimisations
| Action | Description |
|--------|-------------|
| Structure de Coûts | Renégocier les contrats fournisseurs |
| Digital | Standardiser le rythme de publication sur les réseaux sociaux |
| Logistique | Mobiliser les flux dès Août pour anticiper la saisonnalité |

### 🟢 Projets Stratégiques
| Action | Description |
|--------|-------------|
| Data Protection | Mise en conformité avec la loi togolaise |
| Analyse des Coûts | Intégrer les frais de livraison pour le calcul de marge réelle |
| Expansion | Déployer une campagne de notoriété sur Aného |

## 📊 Visualiser le Notebook

Cliquez sur les liens ci-dessous pour visualiser le notebook avec **nbviewer** (affichage garanti) :

| Notebook | Lien nbviewer |
|----------|---------------|
| Analyse JCK | [![nbviewer](https://img.shields.io/badge/View-nbviewer-orange)](https://nbviewer.org/github/AugustinMI/JCK_Analysis/blob/main/Analyses.ipynb) |

Lien direct :
- https://nbviewer.org/github/AugustinMI/JCK_Analysis/blob/main/Analyses.ipynb

## 🔧 Compétences mises en œuvre

| Étape | Compétences |
|-------|-------------|
| Audit de Données | Vérification doublons, valeurs nulles, intégrité |
| Data Wrangling | Nettoyage, transformation, conversion dates |
| Analyse Financière | Calcul CA, panier moyen, taux de recouvrement |
| Segmentation Client | Analyse Diaspora vs Local |
| EDA Python | pandas, matplotlib, seaborn |
| Visualisation | Création de dashboard 12 graphiques |
| Feature Engineering | Agrégations, calculs KPIs |
| Data Storytelling | Interprétation et recommandations |

## 🛠️ Technologies utilisées

| Technologie | Version |
|-------------|---------|
| Python | 3.8+ |
| Pandas | 2.0+ |
| Matplotlib | 3.5+ |
| Seaborn | 0.12+ |
| NumPy | 1.24+ |
| Jupyter Notebook | - |

## ⚠️ Note Importante

**Les données brutes (JCK_DATABASE.csv) ne sont pas incluses** dans ce dépôt pour des raisons de confidentialité. Le code est entièrement fonctionnel avec vos propres données si vous respectez la structure décrite dans le notebook.

## 👤 Auteur

**Augustin MI** (Alomadiakpedede Koffivi Augustin)
- 🎓 Data Analyst | Data Scientist
- 📊 Spécialisé en Audit de Données & Business Intelligence

### 🔗 Me suivre

| Plateforme | Lien |
|------------|------|
| 🌐 **Portfolio** | [https://helpful-sorbet-9aba87.netlify.app/](https://helpful-sorbet-9aba87.netlify.app/) |
| 🐙 **GitHub** | [github.com/AugustinMI](https://github.com/AugustinMI) |


## 📅 Projet réalisé pour
**JCK** - Audit & Gouvernance de la Base Transactionnelle

---

*Dernière mise à jour : 2026*
