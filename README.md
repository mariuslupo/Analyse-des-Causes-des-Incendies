
# **Analyse des Causes et Facteurs des Incendies**

## **Description du Projet**
Ce projet vise à analyser si les causes d'un incendie influences ses dégats. L'objectif est de comprendre quels sont les facteurs influant sur la surface parcourue par les incendies, en utilisant des données structurées et des outils d'analyse statistique.

Ce travail peut servir de base pour des études environnementales, des politiques de prévention ou des approches de gestion des risques.

## **Technologies Utilisées**
- **Python 3.9** : Langage principal pour l'analyse.
- **Pandas** : Manipulation et nettoyage des données.
- **NumPy** : Calculs mathématiques et manipulation des matrices.
- **Matplotlib & Seaborn** : Visualisation des données.
- **Jupyter Notebook** : Environnement interactif pour l'analyse.
- **geopandas** : Utiliser pour obtenir visualiser les données sur une carte.
---

## **Données**
Les données utilisées dans ce projet proviennent de :
- https://bdiff.agriculture.gouv.fr/

> ⚠️ **Note** : Les données réelles ne sont pas incluses dans ce dépôt pour des raisons de confidentialité. Si vous souhaitez reproduire ce travail, utilisez des données similaires ou contactez l'auteur.

---

## **Résultats Principaux**
1. **Facteurs météorologiques** :
   - La vitesse du vent montre une corrélation modérée (**0.34**) avec la surface parcourue, indiquant un rôle significatif dans la propagation des incendies.
   - L’hygrométrie et la température ont des impacts limités sur l’étendue des incendies.

2. **Types de surface** :
   - Le type de surface majoritaire présente une corrélation très faible avec la surface parcourue, suggérant que d'autres facteurs contextuels sont à explorer.

3. **Causes des incendies** :
   - Les incendies dus à la malveillance montrent une légère influence, tandis que les causes inconnues sont associées à une corrélation négative.

---

## **Utilisation**
1. **Clonez ce dépôt** :
   ```bash
   git clone https://github.com/votre_nom/analyse-causes-incendies.git
   cd analyse-causes-incendies
   ```

2. **Installez les dépendances nécessaires** :
   ```bash
   pip install -r requirements.txt
   ```

3. **Exécutez le notebook** :
   Ouvrez le fichier `analyse_causes_incendies.ipynb` dans un environnement Jupyter Notebook ou sur une plateforme en ligne comme Google Colab.

---

## **Améliorations Futures**
- Construire des modèles prédictifs pour estimer la propagation en fonction des conditions.
- Étendre l’analyse avec des données supplémentaires, telles que la densité de végétation ou les infrastructures proches.

---

Si vous avez des questions ou des suggestions pour améliorer ce projet, n'hésitez pas à me contacter ! 😊
