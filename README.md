# Fiction-Interactive-SA22

Projet publié sur Itch.io 
https://maryloug.itch.io/lescycles

<b>Présentation du projet</b> : <br>
"Les Cycles" est une fiction interactive codée sur Twine en format SugarCube2.36.1. Elle a été réalisée dans le cadre du cours "Fiction interactive" d'Isaac Pante à l'Université de Lausanne (SLI, Lettres, UNIL) au semestre d'automne 2022. 
La première version (Abus) a été créée avec Harlowe sur Twine avant de passer sur SugarCube pour la V2 pour profiter de l'interface plus modulable, notamment l'ajout facile de "sidebar". 
Cette FI a plusieurs fonctionnalités : le coeur est les choix qui mènent à chaque fois vers un passage différent (pas de faux choix menant au même passage). Par contre, il faut débloquer certains codes pour que certains passages importants se débloquent. Le début de la FI se construit autour d'un "cycle" qu'il faudra briser sous peine de "mourir". Pour débloquer de nouveaux passages, plusieurs mécanismes ont été utilisés : cliquer sur certains mots pour faire apparaître un texte important ou pour débloquer un passage, remplir un textbox avec le bon mot-clé... 
Une fois ces passages débloqués, le véritable combat commence : le joueur peut faire des choix qui auront un impact important sur la suite de l'histoire. Mais malgré tous ces choix, ces passages débloqués et les "achievements" qui peuvent être débloqués dans le jeu, dans certains passages, le/la joueur/euse sera sujet/te au hasard total de la violence : certains passages (en bleu) sont totalement hors de son contrôle, et iel aura pu tout faire correctement et échouer tout de même... 
![image](https://user-images.githubusercontent.com/114563068/214649285-a0883d02-14da-4bf5-b69a-559bd5b5a4d7.png)
J'ai ajouté un premier lien cliquable au tout début du texte pour que le joueur comprenne qu'il doit cliquer sur les bouts de texte en surbrillance pour faire apparaître la suite / passer au passage suivant.
<br><br>Le jeu a deux issues : l'échec et la fin. Il existe une voie royale pour réussir du premier coup le jeu, en brisant le cycle dès le premier tour et en n'ayant aucun élément de hasard.
<br><br>L'interface dispose de deux barres latérales : à gauche, pour suivre sa progression (les informations et achievements débloqués), et à droite, des informations pour sensibiliser sur le sujet de la violence conjugale. 
<br><br>Les "textbox" jaunes sont interactives. Il est possible d'entrer du texte dedans. Le premier textbox à remplir est celui du nom de l'abuseur. A ce propos, je sais que les victimes de violences conjugales ne sont pas toujours des femmes. Dans une version ultérieure du projet, il serait intéressant de permettre au joueur de choisir son genre, et celui de l'abuseur, de la même manière qu'il est possible de choisir le nom de l'abuseur. Ce premier textbox permettant de choisir le nom de l'abuseur me paraissait crucial afin que le/la joueur/euse établisse dès le début une sorte de "lien" avec l'abuseur, avant de savoir qu'iel en est la victime. Quelqu'un qui joue au jeu pourrait choisir de mettre dans la case le nom d'une personne aimée ou appréciée... et devoir ensuite jouer jusqu'au bout du jeu avec le nom d'une personne aimée qui, potentiellement, le/la tue. C'était une manière de souligner que les victimes et les auteur-e-s de victimes conjugales sont des couples "lambda". Ils peuvent être littéralement n'importe qui. Y compris - et surtout - des gens qu'on aime .
Il y a aussi des "faux" textbox, qui sont juste une imitation CSS de la fonction textbox. Ces encarts-là ne sont pas interactifs, il s'agit simplement de "notifications" envoyées/reçues qui ne peuvent pas être changées, d'où leur aspect gris. J'ai décidé d'avoir ces deux "encarts" afin d'harmoniser l'aspect du jeu tout en ayant une mécanique interactif (jaune) vs obligatoire (grisé) 
<br>![image](https://user-images.githubusercontent.com/114563068/215530830-635474ea-44b0-4b7d-8f89-62df6c38ef77.png)
<br>vs
<br>![image](https://user-images.githubusercontent.com/114563068/215530961-b303da61-1a43-42e6-9c42-6052f999b7fd.png)
<br><br>De la même manière, le jeu a été édité afin que les choix "normaux" vers les passages soient affichés en brillant (blanc). 
Lorsqu'un choix a été débloqué, le nouveau passage s'affiche en brillant jaune : 
<br><br>![image](https://user-images.githubusercontent.com/114563068/214645720-91989aeb-997e-48c8-a663-5a1473c2ff0b.png)
<br><br>Ces options n'apparaissent pas tant qu'elles n'ont pas été débloquées. 
Le jeu a donc été harmonisé afin que "jaune = interactif" et "blanc = base de la structure du jeu"
<br><br>Le jeu a été lancé en décembre 2022 en mode prototype sur itch.io en mode privé avec un mdp : FIUNIL
https://maryloug.itch.io/lescycles
Remis à jour en février 2023 et republié à la place de l'ancienne version. 
<b>copyright</b> : 
N'ayant absolument aucune connaissance en code au-delà du HTML basique pour faire de la maintenance de site internet, j'ai pêché mes codes dans <i>beaucoup</i> d'endroits. Liste des sites/projets/vidéos visités/es: 
  <br><br> 
 https://qjzhvmqlzvoo5lqnrvuhmg.on.drv.tw/UInv/Sample_Code.html#Music
 https://www.google.com/search?q=how+to+add+audio+to+sugarcube&oq=how+to+add+audio+to+sugarcube&aqs=chrome.0.69i59.5093j0j7&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:65f5eab7,vid:N_CRN9mLbUs
  https://intfiction.org/t/how-do-i-change-the-color-of-a-passage-link-in-sugarcube-2-31-1/46669/23
  https://www.reddit.com/r/twinegames/comments/ajrqo5/sugarcube_2x_twine_2_background_image_with_text/
  https://github.com/ChapelR/custom-macros-for-sugarcube-2/blob/master/scripts/speech.js
  https://www.w3schools.com/howto/howto_css_image_text.asp
  https://intfiction.org/t/twine-sugarcube-background-image-with-link/55486
  http://twinery.org/questions/7298/how-to-link-audio-files-in-sugarcube-2-21-0
  <br><br>
  Code utilisé pour la couleur de tous les textes/passages par l'utilisateur greyelf en 2016 : <br>
  https://twinery.org/forum/discussion/5625/any-dynamic-text-effect-macros-for-sugarcube-2-x <br>
  Lorsque j'ai découvert à mi-chemin qu'il valait mieux passer de Harlowe à SugarCube, le github ChapelR/harlowe-to-sugarcube.md m'a beaucoup aidée : <br>
  https://gist.github.com/ChapelR/9b5ddb9d97a87700b2d5ec1b305312ea <br>
  Code utilisé et repris tel quel pour créer le RightSideBar par l'utilisateur HiEv en 2018 : <br>
  http://twinery.org/questions/25976/how-to-create-a-right-sidebar <br>
  Code utilisé et repris quasi tel quel pour le style des textbox par fjolt : <br>
  https://fjolt.com/article/css-ios-crystalline-effect-backdrop-filter <br>
  Code utilisé pour pouvoir valider le texte entré dans les textbox par l'utilisateur HiEv en 2020 : <br>
  https://intfiction.org/t/text-box-and-the-enter-key-query/45281/2 <br>
