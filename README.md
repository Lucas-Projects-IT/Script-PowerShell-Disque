# Script PowerShell Vérification d’Espace Disque


<img width="933" height="146" alt="commande" src="https://github.com/user-attachments/assets/1eccd18a-12c6-4cf8-8498-e6ebf212d629" />

 
**À quoi ça sert ?**

Ce script PowerShell vérifie l’espace libre sur les disques durs de l'ordinateur.
Il affiche pour chaque disque la taille totale, l’espace libre, et le pourcentage d’espace restant.

Si un disque a moins de 20% d’espace libre (modifiable), le script affiche une alerte en rouge.


<img width="1038" height="808" alt="Disk 80_" src="https://github.com/user-attachments/assets/e01fe2f8-1de3-4676-a92e-a037bbeb5fa5" />


**Pourquoi l’utiliser ?**

- Pour savoir rapidement si tu manques d’espace sur tes disques.

- Pour éviter les problèmes liés à un disque trop plein (ralentissements, erreurs).

- Simple et rapide, pas besoin d’installer d’autres outils.

**Comment l’utiliser ?**

- Ouvre PowerShell.

- Lance le script.

- Regarde les messages pour voir si un disque est presque plein.

!! Tu peux changer le seuil d’alerte dans la variable $alertThreshold au début du script !!
