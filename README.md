# 🏃‍♂️ Chrono EPS - Gestion de Course

Une application web progressive (PWA) conçue pour les professeurs d'EPS. Elle permet de chronométrer, classer et gérer les arrivées des élèves lors de courses (cross, demi-fond), le tout **sans connexion internet** sur iPad ou smartphone.

## ✨ Fonctionnalités

- **100% Hors Ligne** : Une fois installée, fonctionne en mode avion (idéal pour le stade/gymnase).
- **Import CSV** : Chargement rapide des listes d'élèves.
- **Gestion Multi-courses** : Gérez plusieurs vagues de départ.
- **Classements Automatiques** :
  - Individuel (Temps/Position)
  - Par classe
  - Challenge inter-classes (calcul de points automatique)
- **Export CSV** : Récupérez tous les résultats pour vos tableurs (Excel/Numbers).

## 📱 Installation (iPad / iPhone)

1. Ouvrez **Safari** et allez à l'adresse du projet : [INSÉRER LE LIEN GITHUB PAGES ICI]
2. Appuyez sur le bouton **Partager** (carré avec une flèche vers le haut).
3. Faites défiler et choisissez **"Sur l'écran d'accueil"**.
4. Validez en cliquant sur **Ajouter**.
5. L'application est maintenant installée comme une app native. **Lancez-la une fois avec internet**, puis vous pouvez passer en **Mode Avion**.

## 💻 Installation (Android / Chrome)

1. Ouvrez l'application dans Chrome.
2. Une bannière "Ajouter à l'écran d'accueil" peut apparaître, ou allez dans le menu (3 points) > **"Installer l'application"**.

## 📋 Format du fichier CSV (Import)

Pour importer vos élèves, préparez un fichier `.csv` simple (sans en-tête obligatoire, mais recommandé) respectant cet ordre :
`Dossard, Prénom, Nom, Genre, Classe`

Exemple :
```csv
1,Jean,Dupont,M,3A
2,Marie,Curie,F,3B
3,Thomas,Pesquet,M,3A