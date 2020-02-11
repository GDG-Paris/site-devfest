---
key: automate_all_your_workflows_with_kotlin
title: 'Automatisez vos workflows avec Kotlin'
id: vXF8zaS4FD6hB5LI51wN
language: french
format: Conference
tags:
  - 'android'

level: intermediate
speakers:
  - martin_bonnin

---

Cette présentation est un retour d'expérience sur la manière dont nous
utilisons Kotlin à toutes les étapes du développement de l’app Android
chez Dailymotion :

* Sur les machines de dev, pour la gestion des pull requests et
connection Jira.

* Sur les serveurs d'integration continue avec un runner Kotlin qui
execute la compilation, tests et publication.

* Sur un servlet Google Cloud pour monitorer les commentaires
utilisateurs du Google Play.

* Enfin, de manière générale, pour remplacer Bash et Perl par du Kotlin
partout grâce à Kscript !

Le but du talk n’est pas d’aller dans le détail de chaque technologie
mais plus de montrer l’étendue des possibles. L’écosystème kotlin rend
accessible un grand nombre de tâches.