# Online Convex Optimization – Implémentation de l’algorithme OGD

Ce notebook présente une implémentation pédagogique de l'algorithme **Online Gradient Descent (OGD)** dans le cadre de l’optimisation convexe en ligne.

## 📘 Contexte
L'optimisation convexe en ligne est une méthode utilisée dans les systèmes d'apprentissage adaptatifs, où une séquence de fonctions convexes est révélée au fil du temps, et l'objectif est de minimiser le **regret** par rapport à la meilleure décision fixe a posteriori.

## ⚙️ Contenu
- Implémentation de l’algorithme OGD
- Simulation sur une fonction quadratique dynamique
- Évolution du regret cumulé et comparaison avec la borne théorique
- Visualisation des trajectoires $x_t$ et $theta_t$
- Analyse log-log du regret

## 🛠️ Outils
- Python (NumPy, Matplotlib)
- Jupyter Notebook

## 📈 Résultat
L'algorithme OGD converge avec un regret \( O(\sqrt{T}) \), confirmé numériquement via la courbe log-log.

