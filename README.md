

    ***Auteur: JLASSI Imen

    ***Description: IL s'agit un todoList (liste de taches) ou chaque client poura ajouter et supprimer des tâches 
       et ça sera affiché pour les autres clients en temps réel.

    ***Langague utilisé: -HTML5
                         -JAVASCRIPT
                         -JSON
    ***Environnement: Node.js 10.15.3

    ***Fichiers: 
         -Package.json: contient la description du projet avec la liste de ses dépendances.
         -todo.ejs: est le template de la page qui sera retourner au client 
         -app.js: contient la déclaration  module express qui permet a travers .GET et .POST de récupérer les routes(URL) 
         pour aoujter ou suprimer une tache et le module socket pour transmetre les modifications au différents clients en temps réel à travers broadcast.

Pour démarrer le projet il faut exécuter les commandes:
- npm install pour installer les dépendances 
- node app.js lancer le projet