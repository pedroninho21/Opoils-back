# Opoils-back

## 🔧 INSTALLATION

### Pré-requis
- Un compte [SendInblue](https://fr.sendinblue.com/) ou tout fournisseur d'accès a un relai SMTP pour l'envoi de mail
- Un compte [AWS](https://aws.amazon.com/) pour utiliser le service de stockage de fichier [AWS S3](https://aws.amazon.com/fr/s3/)
- Une base de données PostgreSQL (par exemple [Render](https://render.com/)) ou un serveur postgresql en local

### Installation
- Clonez ce repo
- Créez et configurez un fichier **.env** à la racine du projet, un example est disponible dans le fichier __.env.exemple__
- Installez les dépendances avec la commande ``yarn``
- Installez la base de données avec la commande ``npx prisma migrate deploy``
- Générez les fonctions de Prisma avec la commande ``npx prisma generate``
- Lancez le serveur back-end avec la commande ``yarn start``. 
Vous pouvez également utiliser la commande ``yarn run start:dev`` pour relancer le serveur
a chaque changement de fichier.
