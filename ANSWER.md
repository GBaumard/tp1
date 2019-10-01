# Answers

Nom : BAUMARD
Prénom : Gaëtan

# 1.
Qu'est-ce qu'une instance EC2 ?  
C’est une instance créée et hébergée sur AWS.

# 2.
Qu'est-ce qu'un VPC ?  
Virtual Private Cloud, c'est une connexion d'un réseau virtuel que l'on définit nous-même. Elle permet de transférer des informations entre différentes instances présentes sur notre cloud.

# 3.
A quoi sert un NSG ?  
Network Security Group (NSG) c'est un outil de sécurité réseau, il sert à appliquer des règles au trafic réseau (il permet de paramétrer toute la stack réseau, de définir des réseaux virtuels isolés entre eux, ...). il permet également une sécurisation par firewall  

# 4.
Quelles sont les 5 propriétés désirables du cloud ?  
* Paiement à l'usage
* Elastique
* Ouvert
* Mutualisé
* Libre-service

# 5.
Qu'est-ce que l'A/B Testing ?  
Le principe est de créer plusieurs pages très légèrement différentes et de placer ses visiteurs sur l'une des deux au hasard et de vérifier des hypothèses (de performance, d'ergonomie, ...)

# 6.
Comment programmer le cloud ?  

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?  
Il existe diverses techniques pour réaliser un déploiement sans créer d'interruptions de services. L’une d'elle est de faire passer de version un environnement où aucun utilisateurs se trouvent et lorsque la version est passée, de transférer les utilisateurs sur le nouvel environnement et de passer le premier environnement de version puis de remettre tout le monde sur ces deux environnements sans distinction

# 8.
Qu'est-ce que le Canary release ?  
C’est un principe de déploiement qui consiste à passer une partie des utilisateurs sur une version différente de celle actuelle. Si tout se passe bien il fera progressivement passer tout le monde à la version nouvelle. C’est une version plus évoluée du blue/green deployment.

# 9.
Comment changer de taille de machine virtuelle ?  
On va dans les paramètres de la machine et on augmente simplement la taille que l'on souhaite attribuer. le cloud se charge du reste

# 10.
Qu'est-ce que le Blue/Green deployment ?  
c'est un principe de déploiement qui consiste à passer les utilisateurs au services supérieur en conservant l'ancienne version puis, si il y a un problème de rapatrier tout le monde sur l'ancienne version.
