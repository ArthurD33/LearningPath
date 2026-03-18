# 🐧 LabEx Linux Learning - Administration Système & Sécurité

## 📝 Présentation
Ce dossier compile les compétences fondamentales acquises sur **LabEx**. Ce socle technique est indispensable pour l'administration de serveurs et les opérations de cybersécurité (Forensics, durcissement système).

---

## 🛠 Compétences Validées

### 1. Gestion des Utilisateurs et des Accès (IAM)
* [cite_start]**Création et Modification :** Utilisation de `useradd -m` pour les répertoires personnels et `usermod -aG` pour la gestion des groupes[cite: 2].
* [cite_start]**Sécurité des Comptes :** Gestion des mots de passe avec `passwd` et verrouillage de comptes avec l'option `-l`[cite: 4, 7, 9].
* [cite_start]**Identification :** Audit rapide de l'identité actuelle avec `whoami`, `id` et `groups`[cite: 3, 6, 14, 16].

### 2. Manipulation Avancée de l'Arborescence
* [cite_start]**Navigation & Structure :** Maîtrise de `cd`, `mkdir -p` pour les hiérarchies complexes et `ls -la` pour l'affichage des fichiers cachés et des permissions[cite: 2].
* [cite_start]**Cycle de vie des fichiers :** Création (`touch`), copie récursive (`cp -r`), déplacement (`mv`) et suppression sécurisée (`rm -i`)[cite: 19, 20].
* [cite_start]**Recherche & Filtrage :** Utilisation de `grep -w` pour extraire des motifs exacts dans des fichiers de configuration ou des logs[cite: 2].

### 3. Redirections et Flux de Données
* [cite_start]**Gestion des Sorties :** Utilisation des opérateurs `>` (écrasement) et `>>` (incrémentation) pour documenter des résultats ou créer des fichiers[cite: 20].
* [cite_start]**Lecture sélective :** Analyse de fichiers volumineux avec `head` (début), `tail -f` (suivi de logs en temps réel) et `cat -n`[cite: 23].

### 4. Droits et Propriétés (Security Hardening)
* [cite_start]**Permissions Octales :** Application du mode `700` pour isoler des répertoires sensibles[cite: 20].
* [cite_start]**Calcul des droits :** Maîtrise du système binaire `4 (r)`, `2 (w)`, `1 (x)`[cite: 20].
* [cite_start]**Propriété :** Changement récursif des propriétaires avec `chown -R user:group`[cite: 20].

### 5. Monitoring et Comparaison
* [cite_start]**État du Système :** Surveillance des ressources avec `top` (processus) et `uptime`[cite: 13, 15, 17].
* [cite_start]**Analyse Différentielle :** Utilisation de `diff` et `vimdiff` pour comparer des versions de fichiers de configuration[cite: 23].

---

## 🚀 Prochaines étapes
- [ ] Approfondissement des **Expressions Régulières (Regex)** pour le filtrage complexe.
- [ ] Automatisation via **Scripts Bash** (boucles, conditions).
- [ ] Gestion des services et des interfaces réseau.

---
*Dernière mise à jour : 18 mars 2026*