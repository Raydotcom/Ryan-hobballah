#  Analyse des déterminants macroéconomiques du déficit public en France

Ce projet analyse les principaux facteurs macroéconomiques qui influencent le déficit public français entre **2003 et 2023**, à partir de données issues d’Eurostat.  
L’objectif est d’identifier les variables ayant l’impact le plus significatif sur l’évolution du déficit public, en mobilisant des outils économétriques avancés sous **R**.

---

##  Objectifs du projet

- Étudier l’évolution du déficit public français sur 20 ans  
- Analyser les relations avec plusieurs déterminants macroéconomiques :
  - Taux de chômage  
  - Taux d’épargne des ménages  
  - Inflation  
  - Taux de change effectif  
  - Recettes fiscales nettes  
  - PIB  
- Estimer un **modèle de régression linéaire multiple**
- Vérifier la robustesse via :
  - Test de multicolinéarité (VIF)  
  - Test de Breusch–Pagan (hétéroscédasticité)  
  - Test RESET de Ramsey (spécification)  
  - Test de Shapiro–Wilk (normalité des résidus)  
  - Test de Durbin–Watson (autocorrélation)  

---

##  Résultats principaux

- Le modèle explique **92,46 %** de la variabilité du déficit public (`R² ajusté = 0.9246`)
- Déterminants significatifs :
  - **Taux de chômage** → impact négatif important  
  - **Taux d’épargne des ménages** → impact négatif  
  - **Taux de change effectif** → impact positif  
  - **Recettes fiscales nettes** → impact positif  
  - **Inflation** → impact positif  
- Certains effets, comme celui du PIB, apparaissent non significatifs





Ce projet combine **analyse économique**, **modélisation statistique**, **diagnostics économétriques** et **visualisations** via `ggplot2`.

---


