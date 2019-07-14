![enter image description here](https://www.edaly.fr/wp-content/uploads/2018/08/Spotlight_PRES-5-1-1200x342.png)
# SPOTLIGHT #5 PROGRAMMEUR

Après le spotlight concernant la modélisation d'objet ou de bâtiments, nous avons consacré celui de juillet à une partie souvent cachée mais très importante du développement, le scripting. Afin de rendre interactif l'expérience de jeu sur Edaly RPG, il faut une multitude de script en tous genre qui sont développés par notre équipe de développeur.

Je travaille donc avec l'ensemble de l'équipe de développement à rendre l'expérience du jeu interactive et différente de ce que vous avez pu voir auparavant. Mais vous le verrez plus tard, afin que notre travail soit présent en jeu, il nous faut travailler avec d'autres équipes comme celle de modélisation et bien d'autres. Et les idées que nous développons viennent en général de discussion lors de réunion avec l'ensemble des membres de l'association.

Je vais donc vous parler un peu de cette partie du développement souvent peu ou mal connue. Pour commencer mieux vaut se faire un plan assez simple dans sa tête ou sur papier de ce que l'on veut réellement faire afin d'éviter de se perdre.

Ici je n’ai pas pour but de vous apprendre à faire des scripts mais bien de vous montrer la conception d’un ensemble de script ce qui correspond à un système. Je vais prendre un même exemple tout au long de ce spotlight, à savoir le système médical sur lequel j’ai beaucoup travaillé ces derniers temps. Un système complexe et toujours compliqué à gérer.

L'ancien système se basait uniquement sur le sang de votre personnage. Lorsque vous tombiez à 0 L de sang vous tombiez dans le coma. Ce système n'étant pas vraiment réaliste, nous avons décidé de le modifier / de l'améliorer. Notez par ailleurs que vous n'aurez plus d'indication du sang qu'il vous reste dans un souci de réalisme nous l'avons retiré, vous aurez tout de même des indices sur votre état de santé (vision trouble, état de choc, etc).

![Spotlight_5_IMG_1](https://www.edaly.fr/wp-content/uploads/2018/08/Spotlight_5_IMG_1-400x225.png)![Spotlight_5_IMG_2](https://www.edaly.fr/wp-content/uploads/2018/08/Spotlight_5_IMG_2-400x225.png)

Or, Arma 3 met à notre disposition ce que l'on appelle des "hitpoints", c'est-à-dire des parties d'un personnage (ou de n'importe quel autre objet) qui sont sensibles au dégât et c'était du gâchis de ne pas les utiliser. Ainsi pour un personnage nous pouvons récupérer l'état de chaque partie de son corps afin d'ensuite lui attribuer un état bien précis. (Voir l’image ci-dessous)

![Spotlight_5_IMG_3](https://www.edaly.fr/wp-content/uploads/2018/08/Spotlight_5_IMG_3.png)

Vous pouvez nous retrouver sur :

Discord : [https://discord.me/edaly  
](https://discord.gg/SUCBQk3)Facebook : [Projets Edaly](https://www.facebook.com/Projets-Edaly-216092102257899/)  
Twitter : [https://twitter.com/edalyfr](https://twitter.com/edalyfr)
