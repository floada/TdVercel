# TDVercel -- Florian ADAM

4) vercel -v

5) npm i -g @angular/cli
   ng new TDVercel

6) cd TDVercel --> pour se placer dans le dossier
   vercel deploy

7) vercel list

8) vercel logs https://td-vercel-ruby.vercel.app

9) vercel inspect https://td-vercel-ruby.vercel.app --> récupération des informations sur la configuration du déploiment

10) Les variables d'environnement sont des variables extérieurs à l'application, elles sont liées à l'environnment.
Ces variables peuvent être utilisées dans le code.

11) vercel env add plain EnvVar0 production

12) vercel env ls

13) Les secrets sont des variables chiffrés pour les informations sensibles comme les mots de passe

14) 

15) vercel secrets add SecretVar2 UnAutreGrosSecret --> créer le secret
    vercel env add secret MySecretVar2              --> créer la variable d'environnement

16) Les trois environnements sont : Production,Preview et Development
    Permet de séparer les variables utiles au fonctionnement et au développement, ainsi on peut faire des test sans arréter le fonctionnement de l'appli

17) 

18) https://github.com/floada/TdVercel

19) La pull request permet de faire une demande pour récupérer les modifications effectuer sur 
le serveur. La requête va comparer le dépôt local avec le dépôt sur git pour récupérer les 
différences. 

git branch branche1
git checkout branche1
vercel env add plain EnvVar1 production

Quand on modifie le dépôt git, le nouveau dépôt git va être deployé en preview pour vérifier que tout fonctione

20) Apres le merge, c'est l'environnement production qui est déployer

21) Le déploiment en production correspond à la branche master de git.
Les pull request vont passer les modifications en preview puis une fois valider (par un merge) elles ont passer en production.
Les pull request permmetent de s'assurer que tout fonctionne
Pendant la dev, la feature est dans l'environnement developpement. Puis elle passe en preview avec une pull request et enfin en production quand la pull request est validée.

22)Serveless est l'utilisation d'un tier pour la réalisation de certaines tâches(cloud computing).
Le client peut exécuter l'application sans se soucier de la partie serveur.
Le client fournit le code et ensuite le fournisseur va se charger d'éxécuter le code sur un serveur.



