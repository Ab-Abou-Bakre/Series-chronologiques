# Données du TP — Mauna Loa CO2

Série réelle : concentration atmosphérique de CO2 mesurée à l'observatoire de Mauna Loa, Hawaii.

- Jeu de base : `statsmodels.datasets.co2`
- Période : mars 1958 – décembre 2001
- Fréquence d'origine : hebdomadaire
- Variable : concentration de CO2 en ppmv
- Documentation : https://www.statsmodels.org/stable/datasets/generated/co2.html
- Statut indiqué par statsmodels : domaine public
- Provenance historique citée par statsmodels : Keeling & Whorf / Carbon Dioxide Information Analysis Center.

Fichiers fournis :

1. `mauna_loa_co2_weekly_1958_2001.csv` : copie tabulaire du jeu hebdomadaire chargé par statsmodels.
2. `mauna_loa_co2_monthly_raw.csv` : moyenne mensuelle calculée à partir du jeu hebdomadaire.
3. `mauna_loa_co2_monthly_clean.csv` : même série mensuelle, avec interpolation linéaire des rares valeurs manquantes pour faciliter les exercices de décomposition.

Important : la version `clean` est une série dérivée destinée au TP. Il faut conserver la version `raw` pour discuter du prétraitement et de la traçabilité.
