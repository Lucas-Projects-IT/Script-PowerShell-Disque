# Script PowerShell Vérification d’Espace Disque
 
À quoi ça sert ?

Ce script PowerShell vérifie l’espace libre sur les disques durs de ton ordinateur.
Il affiche pour chaque disque la taille totale, l’espace libre, et le pourcentage d’espace restant.

Si un disque a moins de 20% d’espace libre (modifiable), le script affiche une alerte en rouge.
https://github.com/Lucas-Projects-IT/Script-PowerShell---V-rification-de-l-espace-disque/blob/main/Disk%2020%25.png?raw=true

Pourquoi l’utiliser ?

Pour savoir rapidement si tu manques d’espace sur tes disques.

Pour éviter les problèmes liés à un disque trop plein (ralentissements, erreurs).

Simple et rapide, pas besoin d’installer d’autres outils.

Comment l’utiliser ?

Ouvre PowerShell.

Lance le script.

Regarde les messages pour voir si un disque est presque plein.

Tu peux changer le seuil d’alerte dans la variable $alertThreshold au début du script.
