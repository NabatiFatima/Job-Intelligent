# Roadmap – Job Intelligent ⚡️

Plateforme intelligente de collecte, traitement et recommandation d'offres d'emploi dans le domaine de la Data. Ce projet met en pratique l'ensemble des étapes d'un pipeline Data Engineering moderne, de l'ingestion des données jusqu'à leur valorisation par des recommandations et des dashboards.

**Stack :** Python · Apache Airflow · FastAPI · MySQL · MinIO · Docker · Power BI · spaCy · NLP

---

## ✅ Réalisé

### Ingestion
- [x] Collecte automatisée d'offres d'emploi depuis plusieurs plateformes (Rekrute, Adzuna, France Travail)

### Stockage et traitement
- [x] Architecture Data Lake avec les couches Bronze, Silver et Gold (MinIO)
- [x] Pipeline ETL de nettoyage, transformation et enrichissement des données
- [x] Data Warehouse en schéma étoile avec MySQL

### Orchestration
- [x] Orchestration des workflows et automatisation avec Apache Airflow
- [x] Conteneurisation et déploiement des services avec Docker

### Valorisation
- [x] API de recommandation avec FastAPI
- [x] Analyse de CV et extraction de compétences avec spaCy (NLP)
- [x] Notifications email personnalisées pour recommander des offres
- [x] Dashboards interactifs avec Power BI

---

## 🚧 Prochaines étapes (pistes d'amélioration)

- [ ] Ajouter d'autres sources d'offres d'emploi
- [ ] Améliorer l'extraction et la normalisation des compétences (référentiel de compétences)
- [ ] Améliorer la qualité des recommandations (évaluation et ajustement du modèle)
- [ ] Ajouter des tests automatisés et un contrôle de la qualité des données
- [ ] Mettre en place une intégration continue (CI) avec GitHub Actions
- [ ] Surveiller les pipelines (alertes en cas d'échec, suivi des performances)
- [ ] Proposer une interface web pour déposer un CV et consulter les recommandations

---

## 📊 Ce que la plateforme permet

- Centraliser automatiquement les offres d'emploi liées aux métiers de la Data
- Extraire et normaliser les compétences techniques recherchées
- Recommander des offres adaptées au profil des candidats
- Visualiser les tendances du marché de l'emploi via des dashboards interactifs
