Création d’un outil, segmenté par catégories d’études (financière, sportive, humaine) afin d’identifier les clubs les plus “bankables” dans le but d’orienter nos clients investisseurs dans leur choix de club.

### Contributions 💪

**Outils :**

- BigQuery  pour le stockage, nettoyage et transformation des données.
- Looker Studio pour la réalisation du dashboard et les visualisations.

**Contexte :**

- + de 20 tables différentes au format CSV
- Aucune PK entre les différentes tables —> Création manuelle de PK (via les noms des clubs) entre les différentes tables afin de permettre les jointures

**Étapes clés :**

1. **Exploration et nettoyage des données :** compréhension, valeurs manquantes, uniformisation (dates, chiffres, format des cellules).
2. **Transformation des données :** complétion et jonction des tables aux clés similaires(club_id, player_id) et calcul des KPIs clés (Taux de croissance, Taux de remplissage, ROI financier, Coefficient de performance, Ratio d’engagement).
3. **Analyse descriptive et segmentée par catégorie:** financier, sportive, popularité.
4. **Insights et recommandations** : identification des championnats les plus attractifs, clubs les plus rentables, clubs les plus performants sportivement, clubs à la popularité la plus élevée et la corrélation entres ces différents facteurs. Enfin nos recommandations sur le club à cibler.
