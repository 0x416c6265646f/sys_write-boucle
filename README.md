# Introduction
Hey, ce dépôt est un petite exercice en nasm que j'ai fais ^^, s'est 1 syscall ^^, sys_write et une petit boucle . sys_write permet lire ce que la personne va écrire
dans la .rodata et la boucle permet de répéter plusieurs fois une instruction de façon automatisé
# Utilisation
tape ces commandes

nasm -f elf64 hello_world_boucle.s -o hello_world_boucle.o

ld hello_world_boucle.o -o hello_world_boucle

en suite exécute ton programme

./hello_world_boucle
