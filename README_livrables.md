# 📚 BOOKSHOP — Livrables Officiels

<div align="center">

![DIT](https://img.shields.io/badge/DIT-Dakar%20Institute%20of%20Technology-teal?style=for-the-badge)
![M2 IA](https://img.shields.io/badge/Master%202-Intelligence%20Artificielle-orange?style=for-the-badge)
![Big Data](https://img.shields.io/badge/Module-Technologie%20Big%20Data-blue?style=for-the-badge)

</div>

---

## 👥 Groupe

| Nom | Rôle |
|-----|------|
| **Hamady Ngansou SABALY** | Etudiant M2 IA |
| **Ousmane SOW** | Etudiant M2 IA |
| **Doudou Malick FAYE** | Etudiant M2 IA |

**Enseignant :** Patrick NGOUNE  
**Année académique :** 2025 — 2026

---

## 📦 Livrables

| Livrable | Description | Accès |
|----------|-------------|-------|
| 📄 `rapport_bookshop.pdf` | Rapport technique complet du projet | Ce repo |
| 📊 `bookshop_presentation.pptx` | Présentation PowerPoint 9 slides | Ce repo |
| 🎬 `demo_pipeline.mp4` | Vidéo démonstration du pipeline (~8 min) | Google Drive |

---

## 🎬 Vidéo Démonstration

La vidéo est hébergée sur Google Drive en raison de sa taille :

👉 **[Cliquez ici pour voir la vidéo de démonstration](https://drive.google.com/file/d/1dQFXLr8yLGETXRqgmiAf5qvtVQMZsUct/view?usp=drive_link)**

**Contenu de la vidéo (~8 minutes) :**
1. Introduction — Présentation HTML animée
2. Snowflake — Les 4 schémas RAW → MARTS
3. DBT — dbt run avec 14 modèles SUCCESS
4. Airflow — DAG bookshop_dbt_pipeline tout vert
5. Power BI — Dashboard 5 pages analytiques
6. Conclusion

---

## 🔗 Projet Principal

Le code source complet est disponible ici :

👉 **[github.com/hamdilawo/bigdata-bookshop-m2](https://github.com/hamdilawo/bigdata-bookshop-m2)**

---

## 🏗️ Résumé du Projet

Pipeline Big Data complet pour une librairie sénégalaise :

```
PostgreSQL → Python → Snowflake RAW
                           ↓ DBT
                      STAGGING (stg_*)
                           ↓ DBT
                      WAREHOUSE (dim_* + fact_*)
                           ↓ DBT
                      MARTS (obt_sales)
                           ↓
                      Power BI Dashboard
```

**Stack :** Snowflake • DBT • Airflow • Docker • Python • Power BI

---

*Dakar Institute of Technology — Master 2 IA — 2025/2026*
