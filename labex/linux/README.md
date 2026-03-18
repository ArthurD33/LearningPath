# Administration Linux - Synthèse des commandes

## Gestion des Répertoires et Navigation
* **ls** : Liste le contenu (Options : `-l` détails, `-a` cachés, `-R` récursif).
* **cd** : Change de répertoire (`..` pour le parent, `-` pour le précédent).
* **mkdir** : Crée un répertoire (`-p` pour créer les parents).
* **rmdir** : Supprime un répertoire vide.
* **man** : Affiche le manuel d'une commande.

## Gestion des Utilisateurs et Groupes
* **useradd** : Crée un utilisateur (`-m` pour créer le home directory).
* **usermod** : Modifie un compte (`-d` répertoire, `-aG` ajouter à un groupe).
* **passwd** : Gère les mots de passe (`-l` pour verrouiller).
* **userdel** : Supprime un utilisateur.
* **su** : Change d'utilisateur.
* **whoami** : Affiche l'utilisateur actuel.
* **id** : Affiche les identifiants UID et GID.
* **groups** : Affiche les groupes de l'utilisateur.

## Manipulation de Fichiers
* **touch** : Crée un fichier vide ou met à jour l'horodatage.
* **cp** : Copie des fichiers ou répertoires (`-r` pour le récursif).
* **mv** : Déplace ou renomme un fichier.
* **rm** : Supprime des fichiers (`-i` confirmation, `-r` récursif).
* **echo** : Affiche du texte ou redirige vers un fichier (`>` écraser, `>>` ajouter).
* **chown** : Change le propriétaire et le groupe (`-R` récursif).
* **chmod** : Modifie les permissions (Ex: `700`). Rappel : 4 (r), 2 (w), 1 (x).

## Lecture et Comparaison
* **cat** : Affiche le contenu complet (`-n` pour numéroter les lignes).
* **head** / **tail** : Affiche le début ou la fin d'un fichier.
* **grep** : Filtre le contenu d'un fichier (`-w` pour le mot exact).
* **diff** : Compare deux fichiers.
* **vimdiff** : Compare des fichiers avec l'interface Vim.

## Système et Flux
* **uname** : Affiche le nom du noyau.
* **uptime** : Affiche le temps de fonctionnement du système.
* **top** : Affiche les processus en cours en temps réel.
* **&&** : Permet d'exécuter deux commandes à la suite.
* **| (Pipe)** : Transmet la sortie d'une commande à une autre.

18 mars 2026