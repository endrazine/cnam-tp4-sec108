
# CNAM TP4 : Ecriture d'un exploit contre chroot()

Le but de ces Travaux Pratiques est d'écrire un exploit contre chroot().

## Resultats

Ces TPs sont notés : prière de m'envoyer vos résultats (exploit contre chroot()) sous 1 semaine, sur mon email du CNAM.

## Telechargement de l'environement

Au moyen de git, cloner le repertoire de ce TP.

### Comment entrer dans le chroot ?

	jonathan@blackbox:~/CNAM/tp4$ ls
	README.md  bin  enterchroot
	jonathan@blackbox:~/CNAM/tp4$ chmod +x enterchroot 
	jonathan@blackbox:~/CNAM/tp4$ ./enterchroot 
	[sudo] password for jonathan: 


	BusyBox v1.22.1 (Ubuntu 1:1.22.0-15ubuntu1) built-in shell (ash)
	Enter 'help' for a list of built-in commands.

	/ # 

### Exploitation

Ecrire un exploit en C, en suivant les idées du double chroot() présenté en page 21 de l'url suivante:

https://deepsec.net/docs/Slides/2015/Chw00t_How_To_Break%20Out_from_Various_Chroot_Solutions_-_Bucsay_Balazs.pdf

### Résultats

Envoyer vos résultats sur mon email du CNAM : jonathan.brossard at lecnam.net


### J'ai fini plus tôt !

Good for you ! S'attacher à réaliser les wargames disponibles ici pour progresser: https://overthewire.org/wargames/



