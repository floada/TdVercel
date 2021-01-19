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
