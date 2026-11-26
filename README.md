# Dethrône

Ce site présente la faisabilité d'un *concept d'expérience multimédia* présenté dans le cours *582-501MO Conception d'une expérience multimédia* au collège Montmorency enseigné par Thomas O Fredericks.

> « Inquiète est la tête qui porte la couronne. »
> — William Shakespeare, *Henri IV*

## Équipe

- Adam Ben Fradj : tech, prog, esthétique

## Résumé du projet

**Dethrône** est une installation interactive où le visiteur s'assoit sur un vrai trône pour devenir roi, et où n'importe qui peut venir le défier en duel devant la foule pour lui prendre sa place.

Le duel est un roche-papier-ciseaux à trois gestes : **Attaque**, **Parade** et **Feinte**. Chaque joueur choisit en secret avec des boutons, puis le résultat est révélé lentement à l'écran, comme dans l'activité *Rock Paper Scissors+* vue en classe. Le premier à gagner deux manches remporte le duel.

Autour du duel, les spectateurs forment la **Cour** : ils choisissent leur camp en se plaçant sur un tapis au sol, les **Fidèles** pour soutenir le roi, les **Rebelles** pour le faire tomber. Le camp le plus nombreux donne un avantage à son joueur.

Quand un roi perd sa place, le système génère un **blason unique** à partir de son règne. Ce blason rejoint la **Galerie des Règnes**, projetée sur un mur, et l'ex-roi repart avec une version imprimée. La Galerie devient l'histoire de tous ceux qui sont passés.

| | |
| -- | -- |
| **Médium** | Installation interactive |
| **Public cible** | Les tueurs (taxonomie de Bartle) : agir sur les autres joueurs, attaquer, battre, dominer |
| **Thème** | La communauté : la foule choisit son camp et vit le duel ensemble |
| **Types d'interaction** | Agir sur un objet central · Agir sur son environnement · Collaborer à plusieurs · Laisser une trace |
| **Continuum** | Entre le milieu (*modifier l'œuvre*) et la droite (*faire émerger de nouvelles situations*) |
| **Artéfact** | Un blason génératif par roi, dans la Galerie des Règnes et sur un ticket imprimé |

## Le parcours de l'interacteur

1. **Il entre et observe.** En entrant, le visiteur voit un trône éclairé par un projecteur au fond de la salle. Si personne n'y est assis, c'est le **Roi Fantôme** (une IA) qui règne à l'écran. Sinon, il voit le roi en place, son nombre de victoires et la foule autour.
2. **Il choisit son camp.** En attendant son tour, il se place sur le tapis des **Fidèles** ou celui des **Rebelles**. Il peut changer de camp à tout moment.
3. **Il défie le roi.** Il monte sur le **piédestal** en face du trône. Le système détecte sa présence et lance le duel.
4. **Il choisit son geste en secret.** Pendant 5 secondes, lui et le roi appuient chacun sur un des trois boutons : Attaque, Parade ou Feinte.
5. **Il assiste à la révélation.** Les deux cartes se retournent au ralenti sur le grand écran pendant 3 secondes. La musique monte, le spot tremble, la foule réagit.
6. **Il gagne ou il perd.** Le premier à deux manches gagne le duel.
   - S'il gagne, le roi se lève et le challenger **s'assoit sur le trône** : il devient le nouveau roi. La caméra prend sa photo.
   - S'il perd, il quitte le piédestal et le roi gagne une pierre sur sa couronne.
7. **Il règne.** En tant que roi, il défend son trône contre chaque nouveau challenger. Après 3 victoires, il obtient un **décret royal** qui lui permet de changer une règle pour le prochain duel.
8. **Il tombe, et il laisse une trace.** Quand il est détrôné, son **blason** est généré, ajouté à la **Galerie des Règnes** et imprimé sur un ticket qu'il emporte à la sortie.

## Comment le projet s'adapte pour un à plusieurs interacteurs

| Nombre de personnes | Ce qui se passe |
| -- | -- |
| **1 personne** | Le trône est vide : le visiteur affronte le **Roi Fantôme**, une IA qui joue à l'écran. S'il gagne, il devient le premier roi. Il peut aussi s'asseoir directement sur le trône et attendre un challenger. |
| **2 personnes** | Un roi sur le trône, un challenger sur le piédestal : c'est le duel de base. |
| **3 personnes et plus** | Les autres visiteurs forment la **Cour**. Ils se placent sur le tapis des Fidèles ou des Rebelles, et le camp le plus nombreux donne un avantage à son joueur (une manche perdue est annulée). Ils font la file pour défier le roi. |
| **Grande foule** | Le duel devient un spectacle : les deux tapis peuvent accueillir jusqu'à environ 16 personnes chacun, et les autres regardent autour. |

Le système ne demande aucune inscription : il suffit de s'asseoir, de monter sur le piédestal ou de marcher sur un tapis.

## Pourquoi ce projet est original ?

- **Le pouvoir devient visible.** Dans un groupe, on ne voit jamais comment quelqu'un prend le pouvoir ni comment il le perd. Dans Dethrône, tout se passe devant tout le monde.
- **La foule fait partie du jeu.** Les spectateurs ne regardent pas seulement : en se déplaçant d'un tapis à l'autre, ils influencent le duel. Des inconnus forment des camps, se trahissent et créent leurs propres légendes.
- **Un objet réel au centre.** Le trône est un vrai siège : s'asseoir dessus, c'est déjà un geste fort, et devoir s'en lever devant tout le monde l'est encore plus.
- **La révélation lente.** Inspirée de *Rock Paper Scissors+*, elle transforme un simple choix en moment dramatique et fait réagir toute la salle.
- **Une mémoire collective.** Avec la Galerie des Règnes, chaque roi laisse un blason généré à partir de son règne. Plus l'installation vit, plus son histoire grandit.
