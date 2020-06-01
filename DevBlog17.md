# DEVLOG JUIN 2020

**Bonjour à tous**, 
Demain les terrasses et les plages rouvrent, enfin !!!

De notre côté on a pas chômé, aujourd’hui nous allons vous présenter un  Devblog qui traite d’un système développé par notre équipe et qui va permettre de renforcer et d’augmenter les possibilités de RP,  les “**Item Complexe**” :o .


## Explications
Qu'est-ce qu'il se cache derrière ce nom barbare ? Ce n’est pas bien compliqué.

Prenons l’exemple d’un passeport, un objet simple que vous avez dû rencontrer sur différents serveurs. 
En votre possession, ce dernier pointera vers vos **informations**. En revanche, donnez-le à quelqu’un et vous y retrouverez ses informations. Nous pouvons en déduire qu’un passeport n’est pas **nominatif**, ce n’est qu’un objet qui sert le plus souvent à valider le fait que le joueur souhaite pouvoir révéler son **identité**.
Le système “d’item complexe” nous permet de créer un objet auquel peuvent s’attacher des **propriétés**. Ce n’est dans ce cas plus les informations du joueur, mais celles du passeport qui peuvent être utilisées. Cela offre également la possibilité de pouvoir échanger son passeport avec quelqu’un d’autre, encore faut-il que les informations faciales ne vous trahissent pas…

## Techniquement
La manière dont les “item complexe” fonctionnent s’inspire des radios du mod Task Force Arrowhead Radio (http://radio.task-force.ru/en/). 
Dans la config du jeu, nous créons un grand nombre de variantes d’un objet afin de pouvoir les dissocier les uns des autres. Chaque variante d’un item, unique, peut se voir associer des **attributs** qui le suivront dans son aventure, dans le serveur au sein des différents inventaires, coffres et joueurs que ce dernier visitera.

*L’exemple des passeports*

A mon arrivée sur le serveur, je recevrais un passeport qui contiendra les informations de mon personnage. Disons que la classe d’un passeport soit *Item_Passeport* et que le premier libre soit le numéro 6.
Les informations de l’item complexe *Item_Passeport_6* seraient donc : [Mon prénom, Mon nom, Mon age, Ma nationalité, ainsi de suite...]

Si je dépose mon passeport et qu’il est ramassé, une personne se retrouvera avec le passeport *Item_Passeport_6* dans son inventaire. Une fois ce dernier ramassé, les informations liées sont récupérées et le suivent, quel que soit son trajet sur le serveur.

Si la personne avec le passeport dans son inventaire se déconnecte, le contenu du passeport est **sauvegardé dans son profil** et le passeport n°6 est **libéré** afin de pouvoir être utilisé par quelqu’un d’autre. Autrement, aussi longtemps que le passeport reste dans la possession d’un joueur connecté sur le serveur, il garde en **mémoire** les informations de son propriétaire originel.

Voici deux schémas pour illustrer l’exemple :  

![https://i.imgur.com/XboRs1m.png](https://i.imgur.com/XboRs1m.png)
![https://i.imgur.com/RCkgm3R.png](https://i.imgur.com/RCkgm3R.png)


Voilà qui conclu ce Devblog qui couvre une fonctionnalité importante d’Edaly RPG.
Nous espérons que celui-ci vous aura plu .
N’hésitez pas à faire vos commentaires et à discuter directement avec nous sur si vous voulez plus d’info sur l’utilité des item complexe sans oublier le reste de la communauté sur le Discord.

Rejoignez-Nous !  
Facebook : [Projets Edaly](https://www.facebook.com/Projets-Edaly-216092102257899/)  
Discord : [https://discord.me/edaly](https://discord.gg/SUCBQk3)  
Twitter : [@EdalyFR](https://twitter.com/EdalyFR)
