
# **Agent dans un Labyrinthe : Environnement-Capteur-Actionneur-Agent**

Ce projet implémente un **agent intelligent** qui se déplace dans un **labyrinthe** en suivant l'architecture **Environnement-Capteur-Actionneur-Agent**. L’objectif est que l’agent parte d’une case de départ et trouve le **trésor**, en évitant les obstacles (murs).

---

## **Architecture du Projet**

Ce projet suit l'architecture **Environnement-Capteur-Actionneur-Agent** :

- **Environnement** : Le labyrinthe est représenté par un graphe (grid) avec des murs qui bloquent certains chemins.
- **Capteur** : L’agent détecte les voisins accessibles à partir de sa position actuelle.
- **Actionneur** : L’agent se déplace en fonction des directions possibles (haut, bas, gauche, droite).
- **Agent** : Utilise l’algorithme BFS (recherche en largeur) pour trouver le **chemin le plus court** vers le trésor.

---

## **Algorithme Utilisé**

L'algorithme utilisé pour résoudre ce problème est **BFS (Breadth-First Search)** :
- **Objectif** : Trouver le chemin le plus court entre la case de départ et le trésor.
- **Principe** : L’algorithme explore tous les voisins d’un nœud avant de passer aux voisins des voisins.
- **Avantages** : BFS garantit le chemin le plus court dans un graphe non pondéré (comme notre labyrinthe).
- **Nombre de niveaux** : Le chemin trouvé a une profondeur correspondant au nombre de niveaux parcourus dans le graphe.

---

## **Résultat et Animation**

L'agent part de la case **(0, 0)** et se déplace progressivement vers la case contenant le **trésor** à **(4, 4)**. L’animation affiche chaque position de l’agent en temps réel avec un délai d’une seconde entre chaque mouvement. Si un mur bloque un chemin, l'agent explore une autre route grâce à l'algorithme BFS.

---

## **Vidéo Démonstration**

[Regarder la vidéo](./Labyrinthe.mp4)

---

## **Conclusion**

Ce projet montre comment utiliser l'architecture **Environnement-Capteur-Actionneur-Agent** pour résoudre un problème de labyrinthe en utilisant l'algorithme **BFS**. L'agent se déplace efficacement vers le trésor en évitant les obstacles, et chaque étape est visualisée dans une animation fluide.

---

