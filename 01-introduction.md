<br />
<div align="center">
  <a href="https://github.com/sqqyqqh/eloquentjs-md">
    <span style="font-size: 100px">🦚<span>
  </a>
<br/>
<br/>

<h1 align="center">Eloquent JavaScript - Édition Formation</h1>

  <p align="center">
    Chapitre 1: Introduction
    <br />
    <a href="https://github.com/sqqyqqh/eloquentjs-md/issues">Reporter un bug</a>
    —
    <a href="https://github.com/sqqyqqh/eloquentjs-md/issues">Demander une amélioration</a>
  </p>
</div>

<br/>

Lorsque les premiers ordinateurs personnels sont apparus, la plupart d'entre eux étaient fournis avec un langage de programmation simple, généralement une variante de BASIC. Les interactions avec l'ordinateur étaient fortement liées à ce langage, et tout utilisateur d'un ordinateur devait dès lors y goûter, qu'il le veuille ou non. À présent que les ordinateurs sont devenus nombreux et bon marché, les utilisateurs moyens se contentent la plupart du temps de ce qu'ils peuvent faire en cliquant avec la souris. Pour nombre d'entre eux, cela fonctionne très bien. Mais pour ceux d'entre nous qui ont une inclination naturelle au bricolage technique, la disparition de la programmation dans l'usage quotidien d'un ordinateur représente une forme de barrière.

Heureusement, avec l'évolution du World Wide Web, il se trouve que chaque ordinateur équipé d'un navigateur web moderne a également un environnement pour programmer en JavaScript. Il est gardé bien caché car il est dans l'air du temps de ne pas ennuyer l'utilisateur avec des détails techniques, mais une page web peut le rendre accessible et l'utiliser comme une plateforme pour apprendre à programmer.

C'est ce que ce livre (ou hyper-livre) essaie de faire.

> Je n'ai pas pour but d'éclairer ceux qui ne sont pas désireux d'apprendre, ni éveiller ceux qui ne sont pas soucieux de donner une explication eux-mêmes. Si je leur ai montré un angle du carré et qu'ils ne peuvent pas revenir à moi avec les trois autres, je ne devrais pas revenir sur le premier angle.
> 
> ― Confucius

Au-delà des explications qu'il donne sur le JavaScript, ce livre s'efforce d'initier aux principes fondamentaux de la programmation. Programmer s'avère être un exercice difficile. Les règles de base sont la plupart du temps simples et claires. Cependant, même des programmes construits suivant ces règles de base tendent à devenir suffisamment élaborés pour générer leurs propres règles et leur propre complexité. Voilà pourquoi la programmation est rarement simple et prévisible. Comme le dit Donald Knuth, que l'on peut considérer comme un des pères fondateurs dans ce domaine, c'est un art.

Pour tirer quelque chose de ce livre, il est indispensable de faire plus que de le lire passivement. Essayez de garder l'esprit affûté, efforcez-vous de résoudre les exercices, et n'allez plus loin que lorsque vous êtes certain d'avoir bien assimilé les étapes précédentes.

> Le programmeur en informatique est un créateur d'univers dont il est seul responsable. Des univers d'une complexité potentiellement illimitée peuvent être créés sous forme de programmes informatiques.
> 
> ― Joseph Weizenbaum, La puissance de l'ordinateur et la raison humaine

Un programme, c'est beaucoup de choses. C'est un bout de texte tapé par un programmeur, c'est la force directrice qui indique à l'ordinateur ce qu'il doit faire, c'est un ensemble de données dans la mémoire de l'ordinateur, et pourtant il contrôle les actions accomplies dans cette même mémoire. Les analog

ies qui comparent les programmes à des objets qui nous sont familiers ont tendance à tourner court alors que l'image d'une machine est, de manière superficielle, mieux adaptée. Les roues et les engrenages d'une montre mécanique sont ingénieusement agencés et coordonnés, et si l'horloger connaît son affaire, la montre donnera l'heure pendant des années. Les parties d'un programme sont de même étroitement solidaires et si le programmeur sait ce qu'il fait, son programme fonctionnera sans plantage.

Un ordinateur est une machine conçue pour héberger ce genre de machines immatérielles. Les ordinateurs eux-mêmes ne peuvent qu'exécuter stupidement des choses simples. S'ils sont très utiles, c'est parce qu'ils peuvent faire ces choses à une vitesse incroyable. Un programme peut, en combinant un grand nombre de ces actions simples, accomplir des tâches très complexes.

Pour beaucoup d'entre nous, écrire des programmes informatiques est un jeu fascinant. Un programme est une construction de l'esprit. Il ne coûte rien à élaborer, il ne pèse rien et se développe facilement sous nos mains. Si nous nous laissons aller, sa taille et sa complexité vont prendre des proportions démesurées, au point d'échapper au contrôle même de celui qui l'a créé. C'est le principal problème de la programmation. C'est la raison pour laquelle beaucoup de logiciels aujourd'hui finissent par planter, échouer et tout saloper.

Quand un programme fonctionne, c'est beau. L'art de la programmation est l'art de contrôler la complexité. Un programme de grande qualité est discret et apparaît simple malgré sa complexité.

Aujourd'hui, beaucoup de programmeurs croient que cette complexité est plus facile à gérer en utilisant seulement un petit jeu de techniques bien comprises dans leurs programmes. Ils ont élaboré des règles strictes concernant la forme que devraient adopter les programmes, et les plus zélés d'entre eux dénonceront ceux qui enfreignent ces règles comme de mauvais programmeurs.

> Quelle hostilité envers la richesse de la programmation ! Essayer de la réduire à quelque chose de direct et de prévisible, jeter l'opprobre sur tous les programmes bizarres et magnifiques... Le champ des techniques de programmation est gigantesque, fascinant par sa diversité et encore largement inexploré. Il est certainement bourré de chausse-trappes et de pièges à loups, menaçant de faire commettre au programmeur inexpérimenté toutes sortes d'affreuses erreurs. Cela signifie seulement que vous devez procéder avec prudence et garder votre sang-froid. En apprenant, vous rencontrerez toujours de nouveaux défis, de nouveaux territoires à explorer. Le programmeur qui refuse l'exploration va sûrement végéter, ne plus trouver ça drôle, perdre le désir de programmer (et devenir chef de projet).

En ce qui me concerne, le critère décisif pour évaluer un programme est : "Est-il correct ?". L'efficacité, la clarté et la taille sont également importantes, mais pouvoir mesurer avec exactitude le poids de l'un et le poids de l'autre est

 toujours une question d'opinion, une opinion que doit se faire chaque programmeur. Les règles générales sont utiles, mais on ne devrait jamais avoir peur de les transgresser.

Au début de l'informatique, lorsqu'elle venait de naître, il n'existait pas de langage de programmation. Les programmes ressemblaient à ceci :

```
00110001 00000000 00000000
00110001 00000001 00000001
00110011 00000001 00000010
01010001 00001011 00000010
00100010 00000010 00001000
01000011 00000001 00000000
01000001 00000001 00000001
00010000 00000010 00000000
01100010 00000000 00000000
```

Il s'agit d'un programme qui fait la somme des nombres de 1 à 10 et donne le résultat (1 + 2 + ... + 10 = 55). Il pourrait tourner sur l'ordinateur le plus simple. Pour programmer les premiers ordinateurs, il était nécessaire de disposer de grandes séries d'interrupteurs dans la bonne position, ou de perforer des trous dans des cartes que l'on faisait avaler à la machine. Vous imaginez facilement à quel point la procédure était fastidieuse et sujette à erreurs. Écrire ne serait-ce qu'un programme simple exigeait beaucoup d'intelligence et de discipline, les programmes complexes étaient carrément hors d'atteinte.

Bien entendu, saisir à la main des masques de bits (c'est ainsi qu'on appelle en général les suites de 1 et de 0 ci-dessus) donnait au programmeur l'impression d'être un puissant sorcier. Cela ne peut pas compter pour du beurre en ce qui concerne la satisfaction professionnelle.

Chaque ligne de programme contient une instruction unique. On pourrait l'exprimer en français sous cette forme :

- Stocker le nombre 0 à l'adresse mémoire 0
- Stocker le nombre 1 à l'adresse mémoire 1
- Stocker la valeur de l'adresse mémoire 1 dans l'adresse mémoire 2
- Soustraire 11 de la valeur stockée à l'adresse mémoire 2
- Si la valeur à l'adresse mémoire 2 est le nombre 0, continuer à l'instruction 9
- Ajouter la valeur de l'adresse mémoire 1 à la valeur de l'adresse mémoire 0
- Ajouter le nombre 1 à la valeur de l'adresse mémoire 1
- Continuer avec l'instruction 3
- Donner la valeur de l'adresse mémoire 0

Alors que c'est déjà plus lisible que la soupe binaire, cela reste assez désagréable. Il pourrait être utile d'utiliser des noms au lieu de nombres pour les instructions et les adresses mémoire :

```
Mettre 0 à 'total'
Mettre 1 à 'compteur'
[boucle]
Mettre 'compteur' à 'comparaison'
Soustraire 11 à 'comparaison'
Si 'comparaison' est zéro, continuer à [fin]
Ajouter 'compteur' à 'total'
Ajouter 1 à 'compteur'
Continuer à [boucle]
[fin]


Afficher 'total'
```

À partir de là, il n'est pas trop difficile de deviner comment fonctionne le programme. Qu'en dites-vous ? Les deux premières lignes donnent leur valeur initiale aux adresses mémoire : total sera utilisé pour calculer le résultat du programme et compteur conserve le nombre courant. Les lignes qui utilisent comparaison sont probablement les plus bizarres. Ce que le programme cherche à savoir, c'est si compteur est égal à 11, de manière à savoir s'il doit interrompre le calcul. Comme la machine est très rudimentaire, il peut seulement tester si un nombre est zéro, et prend une décision (sauter) basée sur ce critère. Il utilise donc l'adresse mémoire nommée comparaison pour calculer la valeur de compteur - 11, et décide suivant la valeur obtenue. Les deux lignes suivantes ajoutent la valeur de compteur au résultat et l'incrémentent de une à chaque fois que le programme a décidé qu'il n'avait pas encore atteint 11.

Voici maintenant le même programme en JavaScript :

```javascript
var total = 0, compteur = 1;
while (compteur <= 10) {
  total += compteur;
  compteur += 1;
}
print(total);
```

C’est encore un peu mieux pour nous. Le plus important c’est qu’il n’est plus nécessaire de préciser la façon dont nous voulons que le programme fasse un bond par-ci par-là. Le mot magique `while` s’en occupe. Le programme continue à exécuter les lignes ci-dessous tant que la condition qu’on lui a donnée est satisfaite : `compteur <= 10`, ce qui veut dire tant que « compteur est inférieur ou égal à 10 ». Apparemment, il n’y a plus besoin de créer une valeur temporaire et de la comparer à zéro. C’était un petit détail stupide, et le pouvoir des langages de programmation est justement qu’ils règlent pour nous ce genre de choses accessoires.

Finalement, voici à quoi pourrait ressembler le programme si nous nous étions arrangés pour que les opérations `serie` et `somme` soient disponibles, la première créant une collection de nombres dans une série tandis que la seconde calcule la somme d’une série de nombres :

```javascript
print(somme(serie(1, 10)));
```


La morale de cette histoire est donc que le même programme peut être exprimé de façon brève ou longue, lisible ou illisible. La première version du programme était extrêmement obscure, tandis que la dernière est quasiment du français : `print` (afficher) la somme de la série des nombres de 1 à 10. Nous verrons par la suite dans d’autres chapitres comment construire des choses telles que `somme` et `serie`.

Un bon langage de programmation aide le programmeur en lui fournissant une manière plus abstraite de s’exprimer. Il masque les détails inintéressants, procure des composants de base pratiques (comme la construction `while`) et, la plupart du temps, permet au programmeur d’ajouter lui-même de telles briques (comme les opérations `somme` et `serie`).

JavaScript est le langage qui est, actuellement, le plus utilisé pour faire toutes sortes de choses géniales et horribles avec des pages sur le World Wide Web. Certains prétendent que la prochaine version de JavaScript en fera un langage de référence pour d’autres tâches également. J’ignore si cela va se produire, mais si vous êtes intéressé par la programmation, JavaScript est sans aucun doute un langage utile à apprendre. Même si en fin de compte vous ne faites pas tellement de programmation web, les programmes hallucinants que je vais vous montrer dans cet ouvrage resteront toujours en vous, à vous hanter et à influencer les programmes que vous écrirez dans d’autres langages.

Certains vous diront des choses terribles à propos de JavaScript. Beaucoup de ces reproches sont fondés. La première fois que j’ai dû écrire quelque chose en JavaScript, j’ai rapidement méprisé ce langage. Il acceptait à peu près tout ce que je tapais, mais l’interprétait d’une façon complètement différente de celle que je voulais. Cela venait surtout du fait que je n’avais aucune idée de ce que je faisais, mais il y a aussi un véritable problème ici : JavaScript est absurdement laxiste dans ce qu’il permet.

Toutefois, la souplesse de ce langage est aussi un avantage. Elle laisse la place à de nombreuses techniques que les langages de programmation plus rigides ne permettent pas, et on peut l’utiliser pour compenser certains défauts de JavaScript. Après l’avoir étudié correctement et avoir travaillé avec un certain temps, j’ai vraiment appris à aimer ce langage.

Contrairement à ce que son nom suggère, JavaScript a très peu à voir avec le langage de programmation nommé Java. Le nom similaire a été inspiré par des considérations commerciales plutôt que rationnelles. En 1995, quand le JavaScript a été lancé par Netscape, le langage Java était promu partout et gagnait en popularité. Apparemment, quelqu’un a dû penser que c’était une bonne idée d’essayer de surfer sur la mode du moment. Nous voilà aujourd’hui coincés avec ce nom.

Il existe un langage associé au JavaScript et qui s’appelle ECMAScript. Quand les navigateurs autres que Netscape ont commencé à prendre en charge le JavaScript, ou quelque chose du même genre, on a écrit une documentation pour décrire avec précision comment le langage en question devait fonctionner. On l’a appelé ECMAScript, d’après le nom de l’organisation qui l’a standardisé.

ECMAScript décrit un langage de programmation à usage général, mais ne dit rien sur l’intégration de ce langage dans un navigateur internet. Le JavaScript c’est ECMAScript plus des outils supplémentaires pour gérer les pages web et les fenêtres de navigation.

Quelques autres logiciels utilisent le langage décrit dans le document ECMAScript. Plus important, le langage ActionScript utilisé par Flash est basé sur ECMAScript (bien qu’il ne suive pas précisément le standard). Flash est un système utilisé pour ajouter des trucs qui bougent et font du bruit sur les pages web. Ça ne vous fera pas de mal de connaître JavaScript si vous devez un jour apprendre à faire des animations en Flash.

JavaScript continue d’évoluer. Depuis la sortie de cet ouvrage, ECMAScript 5 est sorti, il est compatible avec la version décrite ici, mais y ajoute, en tant que méthodes natives, quelques fonctionnalités que nous écrirons nous-même. La dernière génération de navigateurs fournit cette version augmentée de JavaScript. En 2011, « ECMAScript harmony », une extension plus radicale du langage, était en cours de standardisation. Vous ne devriez pas trop craindre que ces nouvelles versions rendent obsolètes ce que vous apprenez dans ce livre. Il ne s’agira que d’une extension du langage dont nous disposons actuellement, donc pratiquement tout ce qui est écrit dans ce livre restera valide.

La plupart des chapitres de ce livre contiennent une quantité non négligeable de code2. D’après mon expérience, lire et écrire du code est une part importante de l’apprentissage de la programmation. Essayez de ne pas seulement jeter un œil sur ces exemples mais lisez-les vraiment attentivement et comprenez-les. Cela peut être long et déroutant au début, mais vous prendrez rapidement le coup. Il en va de même concernant les exercices. N’estimez pas les comprendre avant d’avoir effectivement écrit une solution qui fonctionne.

Le fonctionnement même du Web fait qu’il est toujours possible d’examiner les programmes JavaScript que les gens utilisent dans leurs pages web. Cela peut être un bon moyen d’apprendre comment certaines choses sont réalisées. Étant donné que la plupart des programmeurs web ne sont pas des programmeurs « professionnels », ou qu’ils ne considèrent pas la programmation JavaScript comme suffisamment intéressante pour en faire convenablement l’apprentissage, beaucoup du code que vous pourrez trouver ainsi sera de très mauvaise qualité. Quand vous apprenez à partir de code laid et incorrect, la laideur et la confusion se propagent dans votre propre code ; faites donc très attention de qui vous prenez vos leçons.

Pour vous permettre d’essayer les programmes, aussi bien les exemples que le code que vous écrirez vous-même, ce livre utilise ce que l’on appelle une console. Si vous utilisez un navigateur graphique moderne (*Internet Explorer* version 6 ou supérieur, *Firefox* 1.5 ou supérieur, *Opera* 9 ou supérieur, *Safari* 3 ou supérieur, Chrome), les pages de ce livre vont afficher une barre bleuâtre en bas de votre écran. Vous pouvez ouvrir la console en cliquant sur la petite flèche à l’extrémité droite de cette barre (notez qu’il ne s’agit pas de la console intégrée de votre navigateur).

La console contient trois éléments importants. Il y a une fenêtre de sortie, qui est utilisée pour montrer les messages d’erreurs et les choses qu’affichent les programmes. Sous celle-ci se trouve une ligne où vous pouvez saisir un bout de JavaScript. Essayez de saisir un nombre et appuyez sur la touche Entrée pour lancer ce que vous avez tapé. Si le texte que vous avez saisi a produit quelque chose de sensé, cela sera affiché dans la fenêtre de sortie. Maintenant, essayez de taper `mauvais!`, et appuyez à nouveau sur Entrée. La fenêtre de sortie va afficher un message d’erreur. Vous pouvez utiliser les touches flèche vers le haut et flèche vers le bas pour revenir aux commandes que vous avez saisies précédemment.

Pour les bouts de code plus importants, ceux qui s’étendent sur plusieurs lignes et que vous voulez conserver un peu, la zone de droite peut être utilisée. Le bouton « Lancer » est utilisé pour exécuter les programmes écrits dans cette zone. Il est possible d’avoir plusieurs programmes ouverts en même temps. Utilisez le bouton « Nouveau » pour ouvrir un nouveau tampon vide. Quand il y a plus d’un programme ouvert, le menu après le bouton « Lancer » peut être utilisé pour choisir lequel est affiché. Le bouton « Fermer », comme vous pouvez vous en douter, ferme un programme.

Il y a toujours un petit bouton avec une flèche dans le coin supérieur droit des programmes d’exemple de ce livre, qui peut être utilisé pour les lancer. L’exemple que nous avons vu auparavant ressemblait à ceci :

```javascript
var total = 0, compteur = 1;
while (compteur <= 10) {
  total += compteur;
  compteur += 1;
}
print(total);
```

Lancez-le en cliquant sur la flèche. Il y a aussi un autre bouton qui sert à charger le programme dans la console. N’hésitez pas à le modifier et à essayer le résultat. Le pire qu’il puisse arriver est que vous créiez une boucle sans fin. Une boucle infinie est ce que vous obtenez lorsque la condition d’un while ne devient jamais fausse, par exemple si vous choisissez d’ajouter 0 au lieu de 1 à la variable compteur. Alors le programme va tourner pour toujours.

Heureusement, les navigateurs gardent un œil sur les programmes qu’ils font tourner. Lorsque l’un d’eux prend un délai démesuré pour se terminer, ils vous demandent si vous voulez l’interrompre.

Dans certains chapitres à venir, nous créerons des programmes d’exemple qui seront constitués de multiples blocs de code. Souvent, vous devrez lancer chacun d’eux pour faire fonctionner le programme. Comme vous l’avez peut-être remarqué, la flèche d’un bloc de code devient violette lorsque le bloc a été exécuté. Lorsque vous lisez un chapitre, essayez de lancer chaque bloc de code que vous rencontrez, particulièrement ceux qui « définissent » quelque chose de nouveau (vous verrez ce que cela signifie dans le prochain chapitre).

Il est évidemment possible que vous ne puissiez pas lire un chapitre d’une seule traite. Ça veut dire que vous devrez commencer à mi-chemin quand vous reprendrez votre lecture, mais si vous ne lancez pas tout le code en commençant du haut du chapitre, certaines choses peuvent ne pas fonctionner. En maintenant la touche majuscule pendant que vous appuyez sur la flèche « Lancer » d’un bloc de code, tous les blocs précédant celui-ci seront également exécutés, ainsi lorsque vous commencez au milieu d’un chapitre, maintenez la touche majuscule enfoncée la première fois que vous faites tourner un morceau de code, et tout devrait fonctionner comme prévu.