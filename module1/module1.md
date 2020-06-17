TITLE: Internet: technologies, usages, société
MENUTITLE: Internet
AUTHOR: Culture Numérique Squad
LANGUAGE: fr
CSS: http://culturenumerique.univ-lille.fr/css/base.css

# Informatique et numérique

[Informatique et numérique](https://vimeo.com/122104210){: .cours_video }

À l'origine, au début, les ordinateurs étaient réservés aux informaticiens, ou
plutôt comme cette discipline naissait à peine, aux mathématiciens et
électroniciens qui les créaient. En anglais un ordinateur se nomme
*computer*, dont la traduction exacte est *calculateur*.

![Alan Turing](media/alanturing.jpg)

Fondamentalement les ordinateurs ne font que des calculs, ils ne
savent pas manipuler autre chose que des nombres, qui plus est des
nombres représentés sous forme binaire c'est-à-dire avec des 0 et
des 1. En effet, comme toutes les machines électriques la seule
information qu'ils "comprennent" est de la forme, "y'a du courant" ou
"y'a pas de courant".

Or, aujourd'hui, nous utilisons des ordinateurs tous les jours, non
pas pour faire des calculs, mais pour réaliser de nombreuses activités
diverses et variées qu'elles soient professionnelles, liées à nos
loisirs ou à notre vie quotidienne. Et pourtant, ces ordinateurs ne
sont toujours que des machines qui font des calculs. Il a donc fallu
trouver des techniques pour traduire/coder le texte, le son, les
images avec des nombres. C'est ce qu'on appelle la *numérisation*. On
dit souvent que notre monde est analogique (ou continu) et que le
monde des machines est numérique (ou digital). Les scanners, appareils
photo numériques, enregistreurs mp3 par exemple sont des dispositifs
qui permettent de passer du monde analogique des hommes au monde
numérique des machines, c'est-à-dire de numériser les informations
sous forme de nombres que les ordinateurs vont pouvoir manipuler.

Nous vivons dans un monde où le numérique a pris beaucoup de place :
internet, la radio, la télévision, la téléphonie, la photographie et
bien d'autres choses que nous ne soupçonnons pas sont entièrement
numériques et donc manipulables par des ordinateurs au sens large, par
exemple, des tablettes, des smartphones, les box adsl, ... en fait toutes
les machines qui fonctionnent avec des processeurs, (nous reviendrons
sur ce terme).

Cela représente des enjeux de société très importants. Le numérique a
ouvert des possibilités gigantesques en terme de gain de temps, de
facilité de traitement, de nouvelles fonctionnalités, d'accès aux
informations, aux archives, ... Mais en même temps de nouvelles
questions sont apparues : où sont stockées les données ? Qui y a accès ?
Sont-elles en sécurité ? Sommes-nous dépendants de machines, de
logiciels, de sociétés commerciales ?

Pour que ces questions ne restent pas dans les mains des
informaticiens, il est nécessaire que chacun fasse l'effort de
comprendre les bases, les fondements des technologies numériques qui
nous entourent. Le citoyen du XXIème siècle a besoin d'une véritable
culture numérique qui ne se limite pas à l'utilisation d'un traitement
de texte ou la participation à un réseau. C'est ce que nous allons
développer dans ces cours.

```comprehension
::Pourquoi représenter avec des nombres ?::
[html]<p>Pourquoi faut-il représenter les textes, images, sons,
etc, par des nombres dans un ordinateur ?</p>
{
~<p>C'est un choix industriel.</p>#<p>Non, les industriels n'avaient pas le choix.</p>
~<p>Les ordinateurs ont été inventés par des mathématiciens.</p>#<p>Non, les mathématiciens savent manipuler autre chose que des nombres, et les ordinateurs sont le fruit de l'interaction entre de nombreuses sciences.</p>
=<p>Tout ordinateur est fondamentalement une machine qui calcule avec des
nombres.</p>#<p>Oui, comme un ordinateur ne manipule que des nombres,
tout doit être représenté sous forme de nombres être manipulé par un ordinateur.</p>
####<p>Un ordinateur ne manipule que des nombres, tout doit donc être représenté sous forme de nombres pour qu'il puisse le manipuler.</p> }

::Numérisation::
[html]<p>Que signifie <em>numérisation</em> ?</p>{
=<p>L'opération qui consiste à représenter sous forme de nombres une
information quelle qu'elle soit.</p>#<p>Oui !</p>
~<p>L'opération qui consiste à citer tous les nombres (1, 2, 3, 4, ….).</p>#<p>Non, citer tous les nombres c'est compter...</p>
####<p>La numérisation est l'opération qui consiste à représenter sous forme de nombres une information, quelle qu'elle soit.</p> }

::Où sont les processeurs ?::
[html]<p>Parmi ces objets, quels sont ceux équipés de
processeur(s) \:</p>{ ~%20%<p>tablettes</p>
~%20%<p>smartphones</p> ~%20%<p>box ADSL</p>
~%20%<p>lecteur mp3</p> ~%20%<p>ordinateur</p>
~<p>aucun</p>#<p>Tous !</p> ####<p>Tous
ces objets sont équipés de micro-processeurs !</p> }
```

```activité
::Le numérique concerne tout le monde::
[markdown]
**Quels étudiants sont concernés par le numérique ?**
\n
Le numérique concerne évidemment les étudiants en informatique et plus généralement les étudiants des filières scientifiques.  Mais vous qui êtes inscrits dans une université de sciences humaines et sociales, êtes-vous concernés ?
\n
Choisissez au moins 3 des domaines suivants et faites des recherches pour voir en quoi ils sont impactés par le numérique : les médias, la santé, l'histoire, la sociologie, la linguistique, les arts, la culture, l'enseignement, l'archéologie.
\n
Faites une synthèse en quelques lignes de vos recherches en précisant les domaines auxquels vous vous êtes intéressés. Indiquez les liens des sites sur lesquels vous avez trouvé ces informations. La liste est non exhaustive et vous pouvez vous intéresser à d'autres domaines.
{####
# Le numérique concerne tout le monde
Ces recherches ont dû vous convaincre, si c'était nécessaire, que le numérique **n'est pas réservé** aux informaticiens, il concerne tout le monde, toutes les disciplines.
S'agissant plus particulièrement des **sciences humaines**, la prise en compte du numérique a fait évoluer les champs disciplinaires pour faire apparaître ce qu'on appelle les **humanités numériques** ( *digital humanities* en anglais).
\n
Voici quelques exemples que nous vous proposons, n'hésitez pas à proposer d'autres exemples dans le forum de discussion :
\n
* Dans les **médias** : nouveau sous-métier de journalisme : les **data-journalistes**
	* [data-visualisation](http://www.lemonde.fr/data-visualisation/)
	* [journalisme de données](http://fr.wikipedia.org/wiki/Journalisme_de_données)
* Dans la **santé** : (imagerie, dossier numérique du patient, ...)
	* [simulation](https://interstices.info/jcms/c_21525/simulation-de-loperation-de-la-cataracte)
* En **histoire, sociologie, linguistique** : *fouille de données*
	* [fouille de données](http://www.youtube.com/watch?feature=player_embedded&v=tp4y-_VoXdA)
* En **art et culture** :
	* [Le Fresnoy](http://www.lefresnoy.net/fr/Le-Fresnoy/presentation)
* Dans l'**enseignement** : (outils numérique d'accompagnement scolaire, MOOC,...):
	* [FUN](https://www.france-universite-numerique-mooc.fr/cours/)
* En fouille archéologique :  une réalisation prestigieuse réalisée à Lille :
	* [vase qui parle](http://bsa.biblio.univ-lille.fr/blog/2013/09/exposition-le-vase-qui-parle-au-palais-des-beaux-arts-de-lille/)
}
```

```activité-avancée
::Le numérique au quotidien::[markdown]Les microprocesseurs, les ordinateurs ont envahi notre quotidien. Pour chacun des domaines suivants, cherchez des exemples où le numérique a permis des évolutions notables :
\n
- Domotique
- Transports
- Vêtements
- Médical / paramédical
\n
Après avoir effectué vos recherches, copier dans la fenêtre de rendu 1 lien pour au moins 3 des 4 thèmes proposés (un lien par thème).
{####
# le numérique au quotidien
Quelques exemples que nous vous proposons au cas où vous n'auriez rien trouvé, ...
\n
La **domotique** est un domaine en pleine expansion qui vise à équiper numériquement notre maison :
\n
- [nest](https://nest.com/fr/)
- [domotique](http://fr.wikipedia.org/wiki/Domotique)
\n
Pour les **transports**, les ordinateurs de bord sont depuis longtemps présents dans les voitures, de plus en plus ils sont responsables de notre sécurité :
\n
- [electrostabilisateur]( http://fr.wikipedia.org/wiki/electrostabilisateur_programmé)
- [ordinateur de bord](http://fr.wikipedia.org/wiki/Ordinateur_de_bord)
\n
Les **chaussures** : gadget ou réelle innovation ? Ce genre d'objet est de plus en plus présents dans nos vies :
\n
 - [chaussures](http://www.linternaute.com/science/technologie/deja-demain/07/chaussure-intelligente/chaussure-intelligente.shtml)
Les **lentilles pour la vue** ?
 - [lentilles](http://www.zdnet.fr/actualites/google-apres-les-lunettes-connectees-les-lentilles-pour-le-diabete-39797148.htm)
}

::Le numérique dans la société::
[markdown]
**Le numérique, un enjeu pour les citoyens du XXIème siècle** ...
\n
Le numérique nous concerne tous en tant que citoyen. Il permet de nouvelles choses en automatisant des procédures et en donnant accès à des données jusqu'ici inexploitables. Mais numérique n'est évidemment pas systématiquement synonyme de progrès. Il faut toujours réfléchir aux **finalités des applications** développées. Nous vous invitons à vous documenter et à réfléchir aux questions suivantes :
\n
- Dans la **gestion de l‘énergie**: qu'est-ce que la troisième révolution industrielle et pourquoi le numérique y contribue-t-il ?
- En **politique et média** : Qu'est-ce que la vérification par les faits (fact-checking en anglais) ? En quoi le numérique l'a rendue possible / facile ?
- En **citoyenneté** : Que signifie vote électronique et en quoi cela pose-t-il des questions essentielles ? Trouver au moins un avantage et un inconvénient.
\n
Après avoir fait vos recherches, répondez aux questions posées en quelques lignes et en indiquant les liens où vous avez trouvé ces informations.
{####
Voici quelques liens que nous vous proposons mais que vous avez sûrement trouvés par vous-même :
\n
- À propos de la troisième révolution industrielle :
	- [Troisième révolution industrielle](http://fr.wikipedia.org/wiki/Troisième_révolution_industrielle)
	- [pasdecalais](http://www.latroisiemerevolutionindustrielleennordpasdecalais.fr)
- En politique et média : Qu'est-ce que la vérification par les faits (fact-checking en anglais) ? En quoi le numérique l'a rendue possible / facile ?
	- [vérification par les faits](http://fr.wikipedia.org/wiki/Vérification_par_les_faits)
- En citoyenneté : Que signifie vote électronique et en quoi cela pose-t-il des questions essentielles ? Trouver au moins un avantage et un inconvénient.
	- [arguments] (http://fr.wikipedia.org/wiki/Vote_électronique#Arguments_en_faveur)
}
```


# OUTILS INFORMATIQUES
## Impact du numérique sur le climat -exemple de la vidéo

1/ Utiliser le navigateur Firefox, s'il n'est pas encore installé sur votre machine, je vous conseille de le faire, c'est un des meilleurs navigateurs. Il est disponible sur toutes les machines de l'IUT.
- installer sur votre navigateur Firefox, l'extension [Carbonalyser](https://addons.mozilla.org/fr/firefox/addon/carbonalyser/) (cette extension n'existe que pour Firefox)
- cette extension va vous permettre de mesurer tout au long de vos navigations sur le web, l'impact climatique que vos activités génèrent.
Il est sécure, et ne piste pas vos données.

2/ À partir de cette page https://theshiftproject.org/article/climat-insoutenable-usage-video/

Lire et télécharger les documents (en particulier le rapport complet), et les étudier avec soin, puis répondez aux questions de l'activité suivante.

```activite
::part du numerique dans les ges::
Quelle est la part du numérique dans l'émission des GES (Gaz à effet de serre) au niveau mondial ?
À quelle autre domaine est-il comparé dans le document ?
Cette part est-elle stable, en diminution, ou en progression ?
{}

::part production vs usages::
Ces émissions de ges liées au numérique proviennent de 2 origines distinctes : la production des matériels et les usages (transferts de données). Quelle est la part de la consommation des données (usages) en regard de la production des matériels ?
{}

::part video en ligne::
Parmi les flux de données mondiaux, quelle part revient :
- à la vidéo en général ?
- à la vidéo dite "en ligne"
Dans les vidéos en ligne, quel est le secteur le plus important ?
Dans quel secteur se trouve Netflix ?
{}

::def sobriete numerique::
Reformuler avec vos propres mots ce que veut dire la "sobriété numérique". (rmq, recopier une définition n'a aucun intérêt, autant ne pas répondre, ...)
{}

::participation forum sobriete numerique::
Discutez sur le forum, dans la discussion prévue à cet effet de la sobriété numérique. Quelles propositions, quelles difficultés, quelles mises en oeuvre, donnez des exemples, ...
j'ai posté une contribution sur le forum et j'ai lu les contributions des autres {TRUE}

```

