## Architecture

Le projet est structuré en deux modules principaux :

- **parser** : analyse la ligne de commande saisie par l’utilisateur et la transforme
  en une structure exploitable (commande, arguments).
- **executor** : exécute les commandes parsées en créant et en synchronisant
  les processus via les appels système UNIX (`fork`, `exec`, `wait`).
