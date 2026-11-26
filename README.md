# Dethrone
Ce site présente la faisabilité d'un *concept d'expérience multimédia* présenté dans le cours *582-501MO Conception d'une expérience multimédia* au collège Montmorency enseigné par Thomas O Fredericks.

> « Inquiète est la tête qui porte la couronne. »
> — William Shakespeare, *Henri IV*

## Équipe

- Ben Fradj, Adam : rôle : Tech
- Sadki, Mohamed Ali : rôle : Esthétique
- Jayden Ferdinand : rôle : Prog

## Résumé du projet

**Dethrône** est une installation interactive où le visiteur s'assoit sur un vrai trône pour devenir roi, et où n'importe qui peut venir le défier en duel devant la foule pour lui prendre sa place.

Tout passe par le **téléphone** des joueurs. Le roi scanne le code QR du trône, le challenger scanne celui du piédestal. Avant le duel, chacun choisit en secret ses **3 gestes** (un par manche) parmi **Attaque**, **Parade** et **Feinte**. Ensuite, les deux joueurs prennent une **épée en mousse** et exécutent leurs 3 gestes en même temps, au rythme des tambours. L'écran annonce le gagnant de chaque manche, puis le verdict.

Comme les choix arrivent directement des téléphones, le système sait toujours qui est le roi et combien de **victoires de suite** il a.

Autour du duel, les spectateurs se placent sur deux tapis pour montrer leur camp : les **Fidèles** soutiennent le roi, les **Rebelles** veulent le faire tomber. Les tapis n'ont aucun effet sur le jeu : ils servent à rassembler la foule et à créer l'ambiance.

Quand un roi perd sa place, le système génère un **blason unique** à partir de son règne. Ce blason rejoint la **Galerie des Règnes**, projetée sur un mur, et apparaît sur le téléphone de l'ex-roi, qui peut le garder en souvenir.

| | |
| -- | -- |
| **Médium** | Installation interactive |
| **Public cible** | Les tueurs (taxonomie de Bartle) : agir sur les autres joueurs, attaquer, battre, dominer |
| **Thème** | La communauté : la foule choisit son camp et vit le duel ensemble |
| **Types d'interaction** | Agir sur un objet central (le trône) · Étendre son corps par un objet (le téléphone, l'épée) · Laisser une trace (la Galerie) |
| **Continuum** | Entre le milieu (*modifier l'œuvre*) et la droite (*faire émerger de nouvelles situations*) |
| **Artéfact** | Un blason génératif par roi, dans la Galerie des Règnes et sur le téléphone de l'ex-roi |

## Le parcours de l'interacteur

1. **Il entre et observe.** Il voit un trône éclairé au fond de la salle. Si le trône est vide, l'écran affiche « Le trône est libre ». Sinon, il voit le nom du roi, ses victoires de suite et la file des challengers.
2. **Il prend le trône (s'il est libre).** Il s'assoit, scanne le code QR du trône avec son téléphone et entre son pseudo. Il devient roi. Si deux personnes arrivent en même temps, **la plus âgée a la priorité**.
3. **Ou il défie le roi.** Il scanne le code QR du piédestal et entre son pseudo. Il est ajouté à la file d'attente ; son téléphone lui indique sa place.
4. **Il prépare son duel en secret.** Quand c'est son tour, il choisit sur son téléphone ses 3 gestes, un par manche (par exemple : Feinte, Attaque, Parade), puis il valide. Le roi fait la même chose de son côté.
5. **Il se bat à l'épée.** Les deux joueurs prennent une épée en mousse. Pour chaque manche, l'écran compte « 3, 2, 1, FRAPPEZ ! » et les deux joueurs font en même temps le geste choisi. L'écran annonce ensuite qui gagne la manche.
6. **Il gagne ou il perd.** Après les 3 manches, celui qui en a gagné le plus remporte le duel. En cas d'égalité, le roi garde son trône.
   - Si le challenger gagne, le roi se lève et le challenger s'assoit : il devient le nouveau roi.
   - Si le roi gagne, il ajoute une victoire à sa série et le challenger suivant s'avance.
7. **Il règne.** Après 3 victoires de suite, le roi peut imposer un **décret** depuis son téléphone : interdire un geste à son prochain adversaire.
8. **Il tombe, et il laisse une trace.** Quand il perd, son **blason** est généré, ajouté à la **Galerie des Règnes** et envoyé sur son téléphone.

## Comment le projet s'adapte pour un à plusieurs interacteurs

| Nombre de personnes | Ce qui se passe |
| -- | -- |
| **1 personne** | Elle s'assoit, scanne le code du trône et devient roi. Elle règne en attendant un challenger, et son nom reste affiché à l'écran. |
| **2 personnes** | Un roi sur le trône, un challenger sur le piédestal : c'est le duel de base. Si le trône est vide et que les deux arrivent en même temps, la plus âgée s'assoit en premier. |
| **3 personnes et plus** | Les challengers s'ajoutent à la **file d'attente** en scannant le code du piédestal ; l'écran et leur téléphone affichent l'ordre de passage. Les autres se placent sur le tapis des Fidèles ou des Rebelles pour encourager leur camp. |
| **Grande foule** | Le duel devient un spectacle : la foule entoure les duellistes et réagit à chaque coup d'épée. |

Le seul outil nécessaire est un téléphone. Un téléphone de prêt est disponible à l'entrée pour les visiteurs qui n'en ont pas.

## Pourquoi ce projet est original ?

- **Le pouvoir devient visible.** Dans un groupe, on ne voit jamais comment quelqu'un prend le pouvoir ni comment il le perd. Dans Dethrône, tout se passe devant tout le monde.
- **Un duel joué avec le corps.** Les gestes sont choisis en secret sur le téléphone, mais ils sont exécutés pour vrai, à l'épée, devant la foule. Personne ne sait ce que l'autre va faire avant le coup.
- **Le bluff avant le combat.** Choisir ses 3 gestes d'avance oblige à anticiper l'adversaire : va-t-il commencer par attaquer ? Va-t-il répéter le même geste ?
- **Un objet réel au centre.** Le trône est un vrai siège : s'asseoir dessus, c'est déjà un geste fort, et devoir s'en lever devant tout le monde l'est encore plus.
- **Une mémoire collective.** Avec la Galerie des Règnes, chaque roi laisse un blason généré à partir de son règne. Plus l'installation vit, plus son histoire grandit.
