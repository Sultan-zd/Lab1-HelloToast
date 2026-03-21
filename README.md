# LAB 1 - HelloToast 

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)

## À propos du projet
**HelloToast** est une application Android d'introduction développée dans le cadre du cours de **Programmation Mobile : Android avec Java**. 

L'objectif principal de ce laboratoire est de se familiariser avec l'environnement Android Studio, la conception d'interfaces utilisateur en XML, et la manipulation des événements (clics) via le code Java.

## Fonctionnalités
L'application présente une interface simple composée d'un compteur central et de deux boutons interactifs :
* **Bouton "Afficher un message" :** Déclenche l'apparition d'un message éphémère (`Toast`) en bas de l'écran pour saluer l'utilisateur.
* **Bouton "Incrémenter le compteur" :** Augmente la valeur du compteur affiché à l'écran à chaque clic, démontrant la mise à jour dynamique de l'interface utilisateur (UI).

## 📸 Aperçu
![Capture d'écran de l'application](Lab.png)

## Concepts techniques abordés
Ce premier projet m'a permis de mettre en pratique plusieurs concepts fondamentaux du développement Android :
* **Conception UI (XML) :** * Utilisation du `LinearLayout` pour structurer l'écran verticalement.
  * Déclaration et paramétrage de composants visuels (`TextView`, `Button`).
  * Compréhension des dimensions dynamiques (`wrap_content` vs `match_parent`).
* **Logique Applicative (Java) :**
  * Cycle de vie de base avec la méthode `onCreate()`.
  * Liaison entre l'interface XML et le code Java grâce à `findViewById()`.
  * Écoute et gestion des événements utilisateurs avec `setOnClickListener()`.
  * Affichage de notifications avec la classe `Toast`.

## Comment lancer le projet en local
1. Clonez ce dépôt sur votre machine locale :
   git clone [https://github.com/Sultan-zd/Lab1.git](https://github.com/Sultan-zd/Lab1.git)
2. Ouvrez Android Studio.
3. Sélectionnez File > Open et choisissez le dossier du projet cloné.
4. Laissez Gradle synchroniser les dépendances.
5. Cliquez sur le bouton Run (le triangle vert) pour lancer l'application sur un émulateur ou un appareil physique.
