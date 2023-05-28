# Quai-Antique
Mon ECF pour le titre graduate dev web fullstack

Quai Antique est un site de réservation pour un restaurant qui permet aux utilisateurs de réserver une table, de consulter les réservations existantes, de publier des images de plats du restaurant et de gérer le contenu des menus.

Instructions d'installation

Clonez ce dépôt sur votre machine locale : git clone https://github.com/votre-utilisateur/quai-antique.git

Rendez-vous dans le répertoire du projet : cd quai-antique

Installez les dépendances du projet à l'aide de Composer : composer install

Configurez les paramètres de l'application en copiant le fichier .env et en le renommant en .env.local. Modifiez les variables d'environnement selon vos besoins, notamment les informations de connexion à la base de données.

#Créez la base de données et exécutez les migrations :

php bin/console doctrine:database:create php bin/console doctrine:migrations:migrate

Démarrez le serveur local de Symfony :
symfony server:start

Accédez à l'application dans votre navigateur à l'adresse http://localhost:8000.
Création d'un administrateur pour le back-office

#Pour créer un compte administrateur, suivez les étapes ci-dessous :

Ouvrez une console dans le répertoire du projet.

Exécutez la commande suivante pour créer un nouvel utilisateur administrateur : php bin/console app:create-admin-user

Suivez les instructions à l'écran pour fournir les informations nécessaires, telles que le nom d'utilisateur, l'adresse e-mail et le mot de passe.

Une fois l'utilisateur créé, vous pourrez vous connecter au back-office de l'application en utilisant les informations d'identification de l'administrateur.
