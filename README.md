# mern-ecom
1. Préparer l’application MERN
Assurez-vous que l'application MERN (MongoDB, Express, React, Node.js) fonctionne correctement en local.
Configurez les variables d’environnement pour stocker les informations sensibles (comme la chaîne de connexion MongoDB).
2. Créer un compte Azure
Inscrivez-vous sur Microsoft Azure et créez un compte.
3. Configurer MongoDB Atlas
Créez un cluster sur MongoDB Atlas pour héberger votre base de données.
Récupérez la chaîne de connexion MongoDB pour l'utiliser dans votre backend Node.js.
4. Préparer votre application pour le déploiement
Construisez le frontend React avec npm run build pour générer le dossier build.
Intégrez la chaîne de connexion MongoDB et d'autres variables sensibles via des fichiers .env.
5. Créer une Web App sur Azure
Dans le portail Azure, créez une nouvelle ressource Web App.
Remplissez les informations nécessaires (nom, groupe de ressources, région, etc.).
6. Configurer la source de déploiement
Dans le Deployment Center de votre Web App Azure, choisissez la source de déploiement (GitHub, Local Git, Azure Repos).
Si vous utilisez GitHub, liez votre dépôt contenant l’application MERN à Azure.
7. Déployer l'application MERN
Si vous avez choisi GitHub, Azure déploiera automatiquement votre application.
Si vous utilisez Local Git, clonez votre dépôt Azure, ajoutez vos fichiers et poussez les changements via Git.
8. Configurer les variables d’environnement
Dans Configuration sur le portail Azure, ajoutez les variables d’environnement nécessaires, telles que la chaîne de connexion MongoDB.
9. Tester l'application
Accédez à l'URL fournie par Azure pour tester votre application MERN.
Vérifiez que le frontend React et le backend Node.js sont fonctionnels, avec une connectivité correcte à MongoDB.
Ces étapes permettent de déployer une application MERN sur Microsoft Azure en utilisant MongoDB Atlas pour la gestion de la base de données et Azure Web Apps pour héberger l’application.
