TP 1 - Commentaire 

J'ai lancé mon premier conteneur. Il s'est exécuté, et Docker a affiché un message de bienvenue confirmant que l'installation fonctionne correctement. Je vois avec docker ps – a 3 conteneurs hello-world donc chaque docker run crée un nouveau conteneur avec un nom aléatoire. Ils ont tous le statut Exited (0) et en comparant leurs dates de création et leurs status je remarque qu'ils se sont arrêtés automatiquement après exécution.  

TP 2 - Commentaire 

Déjà il y avait des fautes sur une des commandes. J'ai lancé nginx et accédé à la page d'accueil. Les logs montrent que tout fonctionne bien. J'ai compris que 8080:80 relie mon navigateur au port du conteneur. 

TP 3 - Commentaire 

Je suis entré dans le conteneur . J'ai utilisé bash à la place de sh car sh ne reconnaissait pas cd. J'ai pu explorer les fichiers nginx de l'intérieur.  

TP 4 - Commentaire 

J'ai créé ma propre image avec un Dockerfile. J'ai personnalisé nginx pour afficher ma page HTML.  

TP 5 - Commentaire 

Avec un seul fichier docker-compose.yml et une commande, j'ai lancé nginx sans taper d'options. docker compose down supprime tout proprement.  

TP Initiation à Git et GitHub 

J’avais déjà Git.