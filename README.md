# Wanisse Ladj
### Finance, Quantitative Modeling & Data Analytics
**MSc Finance & Big Data @ NEOMA Business School** | **Masters en Finance & Recherche Opérationnelle**

Bienvenue sur mon portfolio technique. À l'interface de la **Finance**, des **Méthodes Quantitatives** et de la **Data Science**, je conçois des outils d'aide à la décision, des tableaux de bord financiers et des modèles prédictifs orientés performance métier.

Mon approche repose sur un principe simple : **la technique n'a de valeur que si elle éclaire une décision financière ou opérationnelle.** Qu'il s'agisse d'isoler des effets prix/volume sous Power BI, de structurer des requêtes SQL complexes ou de déployer un pipeline Scikit-Learn, je privilégie la rigueur méthodologique, l'interprétabilité des résultats et la reproductibilité.

🎯 **Objectif actuel :** À la recherche d'une **alternance ** en **Finance & Data, Contrôle de Gestion / FP&A, Business Intelligence, Data Analytics ou Analyse de Risque**.

---

## Piliers de Compétences & Valeur Ajoutée

* 📊 **Finance, Pilotage de la Performance & BI**
  * Analyse du chiffre d'affaires, décomposition des moteurs de revenus (effets volume/mix/prix), suivi des KPIs commerciaux et financiers (*AOV, UPO, marges*).
  * Conception de tableaux de bord décisionnels sous **Power BI** : modélisation en étoile (*Star Schema*), mesures **DAX** sécurisées et visualisation orientée *Executive*.
* 🧮 **Recherche Opérationnelle & Modélisation Quantitative**
  * Modélisation mathématique, probabilités, statistiques appliquées, gestion des risques et prévision de la demande sur séries temporelles.
  * Traitement rigoureux de la multicolinéarité, encodage trigonométrique de variables cycliques ($\sin/\cos$) et validation croisée chronologique ou stratifiée.
* ⚙️ **Ingénierie Analytique, SQL & Machine Learning**
  * **Python** appliqué à la Data : manipulation et nettoyage (`pandas`, `numpy`), visualisation (`matplotlib`, `seaborn`), modélisation supervisée (`scikit-learn`).
  * Conception de **Pipelines de bout en bout** (`ColumnTransformer`, imputation, standardisation, encodage ordinal/one-hot) garantissant l'absence de *data leakage*.
  * **SQL analytique :** sous-requêtes complexes, CTEs, fonctions de fenêtrage (`ROW_NUMBER()`, `DENSE_RANK()`, `LAG/LEAD`) et agrégations glissantes / cumulées.

---

## Sélection de Projets Réalisés

Chaque dépôt ci-dessous contient l'intégralité du code ou du fichier source, le jeu de données associé et une documentation détaillée présentant le contexte métier, la méthodologie et les limites analytiques.

| Projet & Lien vers le Dépôt | Domaine & Cible Métier | Stack Vérifiée | Problématique & Résultats Clés |
| :--- | :--- | :--- | :--- |
| 📊 **[US Retail Electronics — Executive BI Dashboard](https://github.com/WanissL/us-electronics-sales-bi-dashboard)** | **Business Intelligence & Contrôle de Gestion** | `Power BI` `DAX` `Star Schema` `KPI Design` | **Pilotage d'un réseau de distribution ($34,49M de CA, 178k commandes) :**<br>• Analyse de la concentration du CA (61 % généré par le hardware haut de gamme vs produits d'appel à fort volume).<br>• Identification d'une saisonnalité marquée au T4 (+153 % entre janvier et décembre) et d'une distribution horaire bimodale (pics à 12h et 19h).<br>• Évaluation du panier moyen (**AOV : 193,30 $**) et de la vente croisée (**UPO : 1,17**). |
| 📈 **[London Bike-Sharing Demand Forecasting](https://github.com/WanissL/london-bike-demand-forecasting)** | **Modélisation Quantitative & Prévision de Demande** | `Python` `Scikit-Learn` `Random Forest` `Time Series` | **Prévision horaire de flux urbains (17 414 observations) :**<br>• Création de variables cycliques ($\sin/\cos$ heure et mois) et élimination de la colinéarité thermique.<br>• Découpage chronologique strict (80/20) respectant la structure séquentielle.<br>• Benchmark de 4 algorithmes et optimisation par *GridSearchCV* : **$R^2 = 0,925$** et **RMSE = 309** sur le jeu de test. |
| 🎯 **[Airline Passenger Satisfaction & Drivers](https://github.com/WanissL/airline-passenger-satisfaction-ml)** | **Machine Learning & Analyse Client / Risque** | `Python` `Scikit-Learn` `Pipelines` `Explainable AI` | **Classification supervisée et explicabilité sur 129 880 passagers :**<br>• Architecture `ColumnTransformer` automatisant le traitement de 22 variables mixtes.<br>• Comparaison de 6 modèles (LogReg, SVM, Decision Tree, Random Forest, Voting Classifier) : **Accuracy de 96,2 %**, **F1-Score de 0,956** et **ROC-AUC de 0,994**.<br>• Extraction des leviers opérationnels prioritaires via *Permutation Importance* (impact critique du parcours digital et de la connectivité à bord). |
| 🧪 **[Python & Statistical Foundations](https://github.com/WanissL/Mes-challenges-Python)** | **Statistiques, Probabilités & Data Wrangling** | `Python` `Pandas` `NumPy` `Seaborn` `Jupyter` | **Socle mathématique et algorithmique :**<br>• Études probabilistes et statistiques appliquées sur données météorologiques.<br>• Défis d'analyse exploratoire (EDA), visualisation multi-variée et manipulation avancée de structures matricielles et tabulaires. |

---

## Parcours Académique & Formation

* 🎓 **MSc Finance & Big Data** — *NEOMA Business School* (Paris / Reims)
* 🎓 **Master en Finance** — *Université de Lille*
* 🎓 **Master en Recherche Opérationnelle (Management, Risque & Négociation)** — *USTHB*
* 💻 **Bootcamp Intensif Data Scientist (6 mois)** — *Code213*

---

## Environnement Technique

```text
Langages & Requêtes   : Python (Pandas, NumPy, Scikit-Learn, SciPy), SQL (CTEs, Window Functions), DAX
BI & Visualisation    : Microsoft Power BI Desktop, Matplotlib, Seaborn, Excel, Looker Studio (Data Studio)
Outils & Workflow     : Git / GitHub, VS Code, Jupyter Notebook, Environnements macOS & Windows
