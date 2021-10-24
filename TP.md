# TP 1 LINUX
L'objectif de ce tp de detruire des vm sous linux
🌞
## 1 
La commande "sudo rm -rf / --no-preserve-root" va nous permettre de supprimer l'integralité des fichier de la vm. Pour ce faire "sudo" pour donner les droits d’admin. Ensuite "rm-rf/" pour tout delete et "--no-preserve-root" lever la protection ou bien rm-rf/*" pour passer outre la sécurité. Au relancement la vm est complètement cassé et "no bootable"
## 2
Au début on se dit “rien que ca?” car la commande ":(){ :|:& };:" est un peu lente a la detente, mais on a creer un fichier qui fait des copies de lui meme en boucle, utilisant peu a peu plus de votre CPU jusqu’a crash et Boom plus de vm.
## 3
La commande "dd if=/dev/random of=/dev/sda"

