# initiation-python
exos de python

Ressource : Découvrir Python
  
Découvrir Python
C'est le moment de faire tes gammes en Python. Accroche-toi bien car dans la data, Python est indispensable !

1. Introduction
Sans transition aucune, on se lance ! Comment ça marche Python ? Est-ce que c'est si intuitif que ça ? Quels objets vais-je utiliser en Python ?

Allons découvrir tout cela 🐣 🐣 ☕️☕️

📌 Utilité pour le projet : 5/5
📊 Utilité pour être Data Analyst : 4/5
💡 Pourquoi cette ressource ? : Se familiariser avec les notebooks et découvrir la syntaxe générale de Python.

2. La ressource
Pour bien comprendre les bases de Python, nous te demandons de suivre le cours OpenClassrooms Initiez-vous à Python pour l'analyse de données.
Ce cours est très bien fait et il est adapté au niveau débutant.

Force-toi à prendre deux heures entières pour faire les 3 premiers chapitres (en réalisant les exercices sur ton Notebook et les quizz). Tu peux t'arrêter avant Prenez en main les modules et librairies Python car c'est le programme de la journée de demain.

2.1. Jupyter Notebook et Anaconda
Pour ton environnement de développement, nous te recommandons fortement de suivre ce que préconise le cours, c'est-à-dire télécharger Anaconda et utiliser Jupyter Notebook.

Plusieurs outils différents permettent de coder en Python, notamment les IDE populaires comme Pycharm, Spyder, ou encore Visual Studio.

Un IDE (ou environnement intégré de développement) est un ensemble d'outils pour augmenter la productivité des programmeurs qui développent des logiciels.

Mais pour débuter et avoir un environnement Python complet et prêt à l’emploi, l’idéal est d’installer la distribution Anaconda.

Anaconda Individual Edition est une plateforme de distribution Python recensant plus de 20 millions d’utilisateurs dans le monde, basée sur un écosystème totalement open-source.

En téléchargeant Anaconda, tu bénéficieras à la fois de :

une installation de Python
les packages de data science tels que NumPy, Pandas, Scikit-learn …
des IDE de dernière génération tels que Jupyter (JupyterLab et Jupyter Notebooks) ou Spyder
l’outil Conda pour gérer les environnements et les répertoires de packages.
Quant à Jupyter, de quoi s'agit-il ?

Créé à partir de Python en 2014, Jupyter est un notebook de calcul (computational notebook) open-source, gratuit et interactif.
Avec cet outil, il est possible de visualiser le code et de l’exécuter depuis la même interface utilisateur. On peut même apporter des changements au code et vérifier les résultats de ces modifications instantanément.
Enfin, cet outil permet de combiner du code, des équations, des visualisations ou du texte. Pour cette raison, il s’agit d’un outil idéal et très utile pour les Data Analysts et les Data Scientists.

✌️✌️ BONNE ASTUCE ✌️✌️

C'est assez facile de prendre en main Jupyter Notebook mais si tu veux intégrer les fonctionnalités principales, je t'invite à lire ce guide rapide d'utilisation.

N'hésite pas, dès le début, à documenter tes notebooks en utilisant les commentaires ou le format Markdown. Cela te permettra d'y retourner plus tard et de comprendre ce que tu voulais faire à l'époque. Par ailleurs, tu pourras plus facilement les partager à la communauté.

3.2. Types de variables et fonctions
Cf. chapitre 2 du cours OpenClassrooms

Un type est une information sur le contenu de la variable qui indique à l'interpréteur Python la manière de manipuler cette information.

Il existe plusieurs types de variables pour stocker les éléments en Python :

les types numériques : qui peuvent être des nombres entiers int ou des nombres réels float. Ex : x = 3 ou y = 3.5 ;
les booléens boolean : sont le résultat d'opérations logiques et ont deux valeurs possibles : True ou False. Ex : x = 4 < 5 ;
les chaînes de caractères string : qui permettent de stocker du texte. Ex : x = "Hello world" ;
les listes list : un tableau ordonné, où chaque élément est associé à un indice. Ex : x = [4,5] ;
les tuples tuple : un tableau d'objets qui peut être de tout type. Ex : x = (4,5) ;
les dictionnaires dictionary : un tableau non ordonné, où chaque élément est associé à une clé. Ex : symboles = {"H" : "hydrogen", "He" : "helium", "Li" : "lithium"}
les sets ou ensembles set : une collection d'objets non ordonnée et contenant des éléments uniques. Ex : s = {1,2,3}.
Tu as dû remarquer que chaque type a une syntaxe particulière : les crochets pour la liste, les parenthèses pour le tuple etc.

Le type d'une variable peut changer, il correspond toujours au type de la dernière affectation.
La fonction type() détermine le type d'une variable.

Enfin, il y a des variables immuables, c'est-à-dire qu'elles ne peuvent pas être modifiées. Les nombres sont des types immuables, tout comme les chaînes de caractères et les tuples.
Ex :

  x = (3,2)
  x[0] = 1
  TypeError: 'tuple' object does not support item assignment.
3.3. Boucles et conditions
Cf. chapitre 3 du cours OpenClassrooms

3.4. Gestion des fichiers
La ressource est disponible ici. Tu peux réaliser les activités si ça te dit, ou au moins comprendre les codes en solution (pour cela, tu dois d'abord envoyer un code).

4. Points importants à retenir
Comprendre les différents types et comment on les reconnaît (parenthèses, crochets etc).
Les types sous Python

Se familiariser avec les méthodes les plus utilisées sur ces types (accéder à un élément, ajouter un élément, supprimer un élément, modifier un élément, compter le nombre d’éléments stockés etc.)

Comprendre la gestion des fichiers avec Python

5. Pour aller plus loin
La documentation Python disponible ici. Quand tu commenceras à être à l'aise avec Python, tu pourras trouver des renseignements sur tous les packages et méthodes existants en Python. N'oublie pas de RTFM.

Par ailleurs, il existe énormément de ressources en ligne pour apprendre à maîtriser Python. On a décidé d'arrêter de les partager car ça inquiétait plus les moussaillons qu'autre chose. Si tu as envie d'en faire plus et de découvrir certains aspects précis de Python, à toi d'aller chercher les sites qui te correspondent le mieux ✌️✌️

Projets : Petits programmes en Python
  
Petits programmes en Python
C'est parti, tu vas créer ton premier Jupyter Notebook et tes premiers programmes Python. Good luck my friend 🚀

1. Introduction
Pour ton premier jour de développeur Python 😎 rien de mieux que de te faire la main avec une série de programmes ... dont certains que tu as déjà faits en Ruby !

2. A toi de jouer !
La difficulté des exercices est croissante alors pas d'inquiétude si tu as du mal vers la fin du projet.

2.1. Rapide exerice de chauffe : manipulation de chaînes de caractères ⛓
créer et afficher la variable bonjour qui contient une chaîne de caractères hello world !
afficher le premier caractère de bonjour
afficher le dernier caractère de bonjour
afficher les caractères de bonjour de la position 1 à la position 3
afficher les caractères de bonjour de la position 3 jusqu'à la fin
vérifier que bonjour commence par hel
2.2. Manipulation de fonctions 🔗
créer une fonction qui prend en paramètre une variable intitulée name et qui affiche Hello suivi du prénom choisi
écrire un programme qui demande à l'utilisateur son prénom et lui retourne un message lui disant Hello suivi de son prénom
2.3. Manipulation des conditions ↙️
écrire un programme qui demande à l'utilisateur de saisir son âge et affiche vous êtes majeur ! si l'âge est supérieur ou égal à 18 et vous êtes mineur sinon
écrire un programme qui demande à l'utilisateur de saisir un nombre et affiche a est pair si la valeur de a est paire et a est impair sinon
👾👾 ALERTE 👾👾

On arrête les exercices de chauffe ici. Retour à nos chers exercices de mardi dernier.

Le fait de reprendre les mêmes programmes que mardi de la semaine dernière va t'aider à bien comprendre les différences entre Ruby et Python. D'ailleurs, on te déconseille de chercher à traduire ton programme Ruby en Python mais cherche plutôt, pour chaque programme, à reprendre la logique de décomposition que tu as apprise la fois dernière. Puis à voir comment tu écrirais le morceau en Python avec ce que tu as appris ce matin dans les ressources et ton nouvel oeil de Data Analyst en herbe !

2.4. Multiples de 3 et 5 🎲🎲
2.4.1. L'énoncé
Cédric Villani a besoin d'aide pour enfin décrocher le prix Nobel de Mathématiques. Il a besoin de résoudre le problème suivant :

Si on liste tous les entiers naturels strictement inférieurs à 11 et qui sont multiples de 3 ou 5, on obtient 3, 5, 6, 9 et 10. La somme de ces nombres est égale à 33.
=> Trouve la somme des entiers naturels strictement inférieurs à 1000 et qui sont multiples de 3 ou 5.

Pour t'aider sur ce premier exercice, on va décomposer des étapes qui vont nous permettre de le résoudre.

2.4.2. Mise en oeuvre de l'approche analytique
Comme on l'a appris, pour résoudre ce problème compliqué, on va le découper en plein de petits problèmes simples. Ici, on doit écrire un programme qui prend un nombre, et qui ressort la somme des multiples de 3 ou 5 inférieurs à ce nombre.

Moi, quand je lis ça, je me dis "ok, mon programme va aller de zéro jusqu'à 1000 (par exemple) et à chaque chiffre va tester s'il est multiple de 3 ou 5. Si c'est le cas, il met le chiffre de côté, dans une boite, pour faire une somme à la fin. Si le chiffre n'est pas multiple, on l'oublie et on passe au suivant".

Hum, en écrivant ça sur papier, j'ai identifié 2 choses qui vont composer mon programme final :

"mon programme va aller de zéro jusqu'à 1000 (par exemple)" => Il va y avoir une boucle !
"à chaque chiffre [mon programme] va tester s'il est multiple de 3 ou 5" => voilà un problème simple et bien défini : être capable d'identifier si un nombre est multiple de 3 ou 5 !

Allez c'est parti, tu peux te lancer maintenant !

2.4.3. La solution
Tu peux voir à la suite deux solutions pour ce programme. Essaye d'abord de faire ta version avant de les regarder.
On te montre la solution pour que tu voies qu'on n'est plus exactement dans la même démarche qu'avec Ruby (écrire des méthodes qu'on imbrique entre elles). A partir de maintenant et car précisément tu souhaites te spécialiser dans la donnée, tu peux aller au plus vite et au plus efficace. L'objectif dans l'analyse de données, c'est d'utiliser le code pour obtenir le bon résultat.

Une des solutions peut s'écrire ainsi :

resultat = 0
for i in range(1, 1000):
    if i%3 == 0 or i%5 == 0:
        resultat += i
print(resultat)
Ou, en version plus condensée, ainsi :

print(sum(i for i in range(1, 1000) if i%3 == 0 or i%5 == 0))
2.5. Cryptofolies 💳💳
Après ce petit tour de chauffe, voici un autre exercice sous forme d'initiation à la cybersécurité, avec un algorithme de chiffrement hyper secure (lol) : le chiffrement par décalage. En effet, la NSA a besoin de chiffrer ses e-mails et veut faire appel à toi pour implémenter cette méthode indéchiffrable par un enfant de 5 ans.

En cryptographie, le chiffrement par décalage, aussi connu comme le chiffre de César ou le code de César, est une méthode de chiffrement très simple utilisée par Jules César dans ses correspondances secrètes.
Le texte chiffré s'obtient en remplaçant chaque lettre du texte clair original par une lettre à distance fixe, toujours du même côté, dans l'ordre de l'alphabet. Si jamais on dépasse la dernière lettre de l'alphabet, on continue à compter depuis le début. Par exemple avec un décalage de 3 vers la droite, A est remplacé par D, B devient E, W devient Z, X devient A, Y devient B, etc.
Il s'agit d'une permutation circulaire de l'alphabet. La longueur du décalage, 3 dans l'exemple évoqué, constitue la clé du chiffrement qu'il suffit de transmettre au destinataire — s'il sait déjà qu'il s'agit d'un chiffrement de César — pour que celui-ci puisse déchiffrer le message. Dans le cas de l'alphabet latin, le chiffre de César n'a que 26 clés possibles (plus la clé nulle, qui ne modifie pas le texte).

Ta mission : créer une fonction caesar_cipher qui prend en paramètres un string et une clé de chiffrement (nombre de lettres à décaler) pour en sortir le string modifié.

> caesar_cipher("What a string!", 5)
=> "Bmfy f xywnsl!"
2.6 Jean-Michel Trader 💸💸
Si tu es arrivé à bout des deux premiers exercices, bien joué ! On continue sur notre lancée.

Après la cybersécurité à la NSA, Lehman Brothers veut te débaucher pour faire de la finance. Hyper cool. Ils te demandent cette fois de coder un programme qui permet, à partir d'une liste de prix, de connaître le meilleur jour d'achat et le meilleur jour de revente pour faire le maximum de bénéfices.

Si l'on considère la liste de prix suivante : [17, 3, 6, 9, 15, 8, 6, 1, 10], la fonction day_trader doit renvoyer qu'il s'agit du deuxième jour à l'achat et du cinquième jour à la revente.

> day_trader([17, 3, 6, 9, 15, 8, 6, 1, 10])
=> [1,4]  # $15 - $3 == $12
2.7 Compter les mots
2.7.1. La première version
Après Lehman Brothers, Google a besoin de toi pour faire de la Data Science. Quelle star ! Écris une fonction intitulée word_counter qui prend en paramètres 2 éléments :

le corpus, string dans lequel tu devras checker le nombre d'occurrences de différents strings
la référence, une liste de mots (strings) qui seront recherchés dans le corpus La fonction devra renvoyer le nombre d'occurrences de chaque mot de la référence dans le corpus sous la forme d'un dictionnaire. Ainsi :
> reference = ["below", "down", "go", "going", "horn", "how", "howdy", "it", "i", "low", "own", "part", "partner", "sit"]
> word_counter("below", reference)
=> {"below" : 1, "low" : 1}
> word_counter("Howdy partner, sit down! How's it going?", reference)
=> {"down" : 1, "how" : 2, "howdy" : 1, "go" : 1, "going" : 1, "it" : 2, "i" : 3, "own" : 1, "part" : 1, "partner" : 1, "sit" : 1}
2.7.2. Compter chez Shakespeare 🤓🤓
Google veut savoir combien de fois l'on peut trouver dans l'œuvre intégrale de Shakespeare les mots suivants :

reference = ["the", "of", "and", "to", "a", "in", "for", "is", "on", "that", "by", "this", "with", "i", "you", "it", "not", "or", "be", "are"]
Crée un fichier shakespeare.txt qui reprend le corpus intégral de l'oeuvre de l'écrivain anglais. Ton programme appellera le fichier shakespeare.txt (indice : c'est plus facile s'ils sont dans le même dossier) pour s'en servir comme corpus, pour ensuite compter les occurrences du dictionnaire.

3. Rendu attendu
Un fichier .ipynb qui comprend l'ensemble des scripts demandés. Ou plusieurs fichiers .py.
