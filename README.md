# tp-wik-dps-tp01

# Express Ping Server

Ce projet est une application Node.js utilisant Express pour créer un serveur HTTP simple qui répond à une route `/ping`. Lorsqu'un client effectue une requête GET sur `/ping`, le serveur renvoie les en-têtes de la requête dans une réponse JSON. Si une requête est effectuée sur une route autre que `/ping`, le serveur renverra une réponse 404 (Not Found).

## Prérequis

Avant de pouvoir exécuter cette application, assurez-vous d'avoir Node.js et npm (Node Package Manager) installés sur votre système. Vous pouvez les télécharger à partir du site officiel de Node.js : https://nodejs.org/

## Installation

1. Clonez ce référentiel sur votre machine locale en utilisant la commande suivante :

   ```bash
   git clone <URL du référentiel>
   ```

2. Accédez au répertoire du projet :

   ```bash
   cd express-ping-server
   ```

3. Installez les dépendances en exécutant la commande suivante :

   ```bash
   npm install
   ```

## Configuration

L'application est configurée pour écouter sur le port 8080 par défaut. Vous pouvez également définir un port personnalisé en définissant la variable d'environnement `PING_LISTEN_PORT`. Si `PING_LISTEN_PORT` n'est pas définie, le serveur utilisera le port 8080.

## Utilisation

Pour lancer le serveur, exécutez la commande suivante à partir du répertoire du projet :

```bash
npm start
```

Une fois le serveur en cours d'exécution, vous pouvez effectuer une requête GET vers `http://localhost:8080/ping` pour obtenir les en-têtes de la requête dans une réponse JSON.

Pour tester la gestion des routes inexistantes, vous pouvez effectuer une requête vers n'importe quelle autre route que `/ping`, par exemple `http://localhost:8080/anything`, et vous recevrez une réponse 404 (Not Found).

## Contribution

Si vous souhaitez contribuer à ce projet, vous pouvez ouvrir une nouvelle issue ou soumettre une demande d'extraction (pull request) avec vos modifications. Nous serions ravis d'examiner et de fusionner vos contributions.

## Licence

Ce projet est sous licence MIT. Veuillez consulter le fichier LICENSE pour plus de détails.

---

N'hésitez pas à personnaliser ce README en fonction de vos besoins et des informations spécifiques à votre projet. Assurez-vous également de remplacer `<URL du référentiel>` par l'URL réelle de votre référentiel GitHub.