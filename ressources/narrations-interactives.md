# Narrations interactives

Quelques exemples de narrations et installations interactives avec un lien plus ou moins direct avec notre problématique : créer du lien sur un territoire en mutation.


## *[Sur les Bancs](http://www.surlesbancs.com/)* (2015)
de Thomas Baumgartner, production Gedeon Programmes, France Culture, IRCAM, France Télévisions Nouvelles Ecritures

*Sur les Bancs* est la première application de réalité augmentée sonore qui propose des bulles de fictions géolocalisées en son 3D dans les parcs et jardins de la ville de Paris (et oui, hélas… pas de navigo, pas de bulles de fiction).

### Principe d’interaction

Je ne peux entendre le récit que si je me trouve à proximité du lieu où il a été enregistré.

### Un peu de technique

*Sur les Bancs* détourne une technique de surveillance, le géofencing ou [géorepérage](https://fr.wikipedia.org/wiki/G%C3%A9orep%C3%A9rage), qui permet de détecter la présence d’un smartphone dans un périmètre géographique donné. Ici on ne lâche pas les chiens, mais on adapte la diffusion d’un contenu à la localisation du mobinaute. S’il n’est pas à proximité du lieu où le contenu est “implanté” (c”est à dire dans le périmètre prédéfini par le créateur), il ne peut y avoir accès.

### Pour aller (beaucoup) plus loin 
Un exemple de [solution technique open source, avec du geofencing dedans](https://developers.arcgis.com/en/features/geotrigger-service/).

Bon allez, si vous êtes arrivés jusqu’ici vous les méritez bien vos bulles de fiction. En vrai, on peut [les entendre sur France Cul](http://www.franceculture.fr/emission-fictions-la-vie-moderne-1?page=3).


## *[Cinemacity](http://cinemacity.arte.tv/fr)* (2014)
de Pierre Cattan et Michel Reilhac, production Small Bang pour ARTE

*Cinemacity* est une application géolocalisée (iOS et Android) permettant de regarder sur son mobile des extraits de films exactement à l’endroit où ils ont été tournés à Paris. En amont, sur le site web de l’expérience, le mobinaute peut préparer ses balades, et choisir une époque, un réalisateur, un quartier. Il est également possible de se promener virtuellement sur le parcours, sans jamais aller sur place, mais c’est moins saisissant.

### Principe d’interaction

Je télécharge l’application et je prépare ma balade. Ensuite, je sors dans la ville, il n’y a qu’à se laisser guider : selon ma position, l’application me propose un contenu cinématographique préselectionné. Il faut être à moins de 300m du point mappé pour visionner l’extrait correspondant.

### Un peu de technique

Les technologies employées sont des plus courantes pour ce type d’expérience mobile : langage pour applications iOS et Google Play, utilisation de Google Maps et utilisation du Javascript pour le caractère dynamique du site.

### Pour aller plus loin 
Cinétévé a réalisé quelques mois plus tard une autre application mobile, *[Jaurès pas à pas](http://jaures-pas-a-pas.fr/)*, dont le principe se rapproche de celui de *Cinemacity*.


## *[Discrepances](http://www.fluxo.fr/discrepances-1/)* (2010-2014)
**de Diego Ortiz et Javiera Tejerina**

Initié en 2010, le projet *Discrépances*, utilise les technologies mobiles pour faire interagir différentes réalités d'un lieu. Dans sa dernière version, Discrépances Aubagne mêle réalités historique, poétique et cinématographique le long d'un parcours en six étapes sur les sentiers de Marcel Pagnol. 

### Principe d’interaction 
Je vis l’expérience in situ. Via mon smartphone ou une tablette, je parcoure les sentiers de Pagnol, au rythme des personnages qui passent dans le champ, enveloppé dans le son spatialisé..

### Un peu de technique
*[Discrépances Aubagne](http://www.fluxo.fr/portfolio/discrepances-aubagne/)* est une application mobile native pour Android et iOS. Des technologies de reconnaissance d'image (avec le kit de développement [Vuforia](https://www.qualcomm.com/products/vuforia/features)), de géolocalisation et de cartographie interactive ont été intégrées pour fluidifier le déclenchement des séquences et faciliter le positionnement de l'interacteur dans le parcours. 

L'immersion de l'interacteur dans l'application de cinéma augmenté s'appuie cependant toujours sur la mise en scène des séquences audiovisuelles.


## *[The Wild Path, An Icelandic adventure](http://tympanus.net/Development/StorytellingMap/)* (2015)
Une démo proposée par Codrops

[Codrops](http://tympanus.net/codrops/) est un blog (en anglais) qui rassemble tutos et démos de diverses technologies web et mobile. Ici, il s’agit avec *The Wild Path* d’illustrer la narration appuyée sur un élément du langage HTML5, l'élément [<canvas>](http://www.alsacreations.com/tuto/lire/1484-introduction.html), ou la possibilité de dessiner programmatiquement dans la fenêtre du navigateur.

### Principe d’interaction

Au fur et à mesure de ma lecture, le tracé de mon voyage se dessine sur la carte. Les photographies sont elles aussi localisées et, au passage, une ombre en faisceau matérialise le lien. Plus je scrolle et plus la page descend, plus la ligne verte de mon voyage avance.

### Un peu de technique

C’est une démo, le code est donc accessible et [téléchargeable](http://tympanus.net/Development/StorytellingMap/StorytellingMap.zip). Si vous comprenez l’anglais, [prenez le temps de la lecture](http://tympanus.net/codrops/2015/12/16/animated-map-path-for-interactive-storytelling/), l’auteur du post détaille les étapes de conception.

### Pour aller plus loin

Le scrollitelling est une forme particulièrement utilisée dans la narration interactive. Nous vous recommandons pour l’explorer ces autres beaux exemples : *[Hollow](http://hollowdocumentary.com/)*, d’Elaine Mc Million, qui retrace l’évolution du McDowel County en Virginie occidentale, aux États-Unis, une zone rurale qui a perdu les quatre cinquièmes de sa population au cours du XXe siècle, *[La Dernière Chasse](http://ladernierechasse.onf.ca/#/ladernierechasse)*, produit par l’Office national du film au Canada et enfin *[Heaulme, esquisse d’un meurtrier](http://www.franceinfo.fr/portrait-en-bd-heaulme-esquisse-d-un-meurtrier)*, produit par Radio France Nouveaux médias pour France Info.


## *[Her Story](http://www.herstorygame.com/)* (2015)
de Sam Barlow, en anglais, disponible sur Steam ou via l’AppStore, 4,99€

*Her Story* est un jeu d’enquête est constitué de 271 clips vidéo d’interrogatoire, de durée variable, datés de 1994. Viva Seifert joue le rôle d’Hannah, une femme interrogée par la police après la disparition de son mari. Nous n’avons accès qu’aux réponses, pas aux questions des enquêteurs, ce qui rend certaines clips énigmatiques. Le but du jeu est de comprendre ce qui s’est passé.

### Principe d’interaction 
J’entre des mots sur un moteur de recherche et je peux visionner les clips vidéo de l’interrogatoire. Un premier mot-clef est inscrit : murder. Peu à peu, je note divers éléments de la déposition d’Hannah, ce qui me permet de suivre des pistes en tapant d’autres mots dans le moteur de recherche. Je n’ai un accès direct qu’à 5 vidéos déjà visionnées.

### Un peu de technique
L’univers graphique et technique du jeu est minimaliste. Il s’agit de la reproduction d’un bureau d’ordinateur des années 90 sur lequel nous pouvons lancer les clips de l’interrogatoire via un logiciel intitulé L.O.G.I.C Database.

### Pour aller plus loin
Her Story a beaucoup fait parler de lui en 2015. Il a obtenu de nombreux prix, dont celui du [meilleur jeu narratif](http://www.polygon.com/2015/12/3/9846760/the-game-awards-2015-winners) aux Game Awards (en anglais). Vous pouvez en lire des critiques [ici](http://www.lemonde.fr/pixels/article/2015/12/30/les-10-jeux-video-qu-il-faut-retenir-de-l-annee-2015_4839384_4408996.html), [là](http://www.lesinrocks.com/2015/07/11/jeux-video/meurtre-mensonges-et-jeu-video-her-story-revolutionne-la-fiction-interactive-11760157/), [ici](http://next.liberation.fr/culture/2015/07/29/her-story-interro-surprise_1355878), [là](http://www.gamergen.com/tests/test-note-avis-review-her-story-experience-interactive-fmv-sam-barlow-enquete-viva-seifret-263849-1) et [encore là](http://www.polygon.com/a/game-of-the-year-2015/her-story-game-of-the-year-2015-polygon) (en anglais).


## *[Tentative d’épuisement de Tentative d’épuisement d’un lieu parisien de Georges Pérec](http://desordre.net/textes/bibliotheque/auteurs/perec/saint-sulpice.html)* (2002)
de Philippe De Jonckheere

Philippe De Jonckheere est un artiste multicarte : passé par les Arts déco, photographe, auteur, vidéaste, plasticien, son site accumule depuis 2001 dans un fouillis créatif et labyrinthique ses recherches, créations, réflexions. À chacun d’y trouver ce qu’il est venu y chercher, ou pas. Ici, il reprend le bien connu texte de Georges Pérec datant d’octobre 1974, sans y changer une virgule.

### Principe d’interaction
Je lis le texte de Pérec. Au survol de certains mots (en gras), des liens apparaissent, que je peux suivre ou non, à charge pour moi de ne pas dériver trop loin (et quand bien même, c’est tout le plaisir de la découverte). C’est tout !

### Un peu de technique
Du texte html, des hyperliens qui mènent un peu partout (et certains plus nulle part, liens morts inopérants), on ne peut pas dire que la technique soit reine ici. Pourtant, quel voyage immobile on peut faire, du texte aux liens, des pages web au texte littéraire. Et puis, n’est-ce pas là le propre de la lecture numérique, que de pouvoir s’enrichir ?

### Pour aller plus loin
Dix ans après De Jonckheere, en 2012, France Inter a voulu retenter l’expérience #telp, toujours place Saint-Sulpice, à Paris, à l’occasion de la [dernière émission d’Antibuzz](http://www.franceinter.fr/evenement-antibuzz-tente-d-epuiser-un-lieu-parisien). Et cette année, des élèves ont tenté d’[épuiser l’usine Lepoutre, à Tourcoing](http://www.cafepedagogique.net/lexpresso/Pages/2015/11/24112015Article635839338487829845.aspx), à l’aide, notamment, de [Thinglink](https://www.thinglink.com/), qui permet d’ajouter des liens à des images ou des vidéos.


## *[Circa 1948](http://circa1948.nfb.ca/)* (2014)
de Stan Douglas, production NFB Canada

Cette expérience immersive pour tablette vous plongera dans une recréation 3D de la Vancouver de l’après-guerre, une ville aujourd’hui disparue qui renaît dans *Circa 1948* grâce aux histoires de ceux qui y vécurent.

### Principe d’interaction

Je découvre les enregistrements audio des histoires des habitants de la Vancouver des années 40 en me déplaçant dans une recréation 3D de deux lieux emblématiques de la ville.

### Un peu de technique

*Circa 1948* utilise les fonctions d’OpenGL, “un ensemble normalisé de fonctions”, qui permet de dessiner des objets directement dans la fenêtre de l’application à partir des coordonnées des points et formes géométriques simples qui les composent. L’intérêt de cette solution est qu’elle permet à l’interacteur d’agir sur l’environnement graphique et qu’elle améliore les performances d’affichage.

### Pour aller plus loin
il existe également une version web d’[OpenGL](https://fr.wikipedia.org/wiki/OpenGL), qui permet de dessiner directement dans la fenêtre du navigateur, [WebGL](https://fr.wikipedia.org/wiki/WebGL), voici quelques exemples de [ses usages possibles](http://www.awwwards.com/22-experimental-webgl-demo-examples.html) (mention spéciale pour Rome, clip interactif de Chris Milk, où je peux altérer l’image grâce aux mouvements de ma souris).

En prime : Le NFB, c’est le pendant anglophone de l’ONF (Office National du Film) canadien, c’est la production d’œuvres et programmes interactifs la plus diversifiée, créative et abondante qui soit, [ça vaut carrément le détour](https://www.onf.ca/interactif/).


## *[Jeu d’influences](http://jeu-d-influences.france5.fr/)* (2014)
**de Julien Goetz et Florent Maurin, production Premières Lignes et France Télévisions Nouvelles Ecritures**

Dans *Jeu d’influences*, vous incarnez Louis Esmont, PDG d’une entreprise de BTP qui se trouve soudain confronté à une grave crise interne. Conseillé par un spin-doctor, vous ferez tout pour sortir votre entreprise et votre réputation intactes de cette crise, au prix parfois de dilemmes cornéliens…

### Principe d’interaction
Dans ce jeu documentaire, j’influe sur le récit grâce à mes choix. Trois indices, varient au gré de mes arbitrages et déterminent l’issue. Qu’un indice chute trop bas et je perds la partie.

### Un peu de technique
L’ensemble de l’architecture du jeu a été conçue sur… Excel. Le développement web est construit en HTML et JavaScript, avec une gestion de base de données pour les réponses données par les internautes lors des quiz intermédiaires.

### Pour aller plus loin 
[Le carnet de bord des auteurs](http://www.ulyces.co/baptiste-peyron/carnet-de-bord-jeu-influences-julien-goetz-florent-maurin/), pour mieux comprendre ce qui se joue lors de la conception du gameplay ; *[The Walking Dead](https://www.youtube.com/watch?v=JuxotWssdPY)*, qui a inspiré *Jeu d’influences* ; ainsi que *[Spent](http://playspent.org/html/)*, un serious-game qui vous met dans la peau d’un Américain moyen sommé de vivre avec 1000$ par mois.

