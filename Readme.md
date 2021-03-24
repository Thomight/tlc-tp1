Pour l'étape 2, il suffit de lancer `docker-compose up`



Pour l'étape 3, je n'ai pas réussi à trouver la lib libjasper1 pour alpine.

J'ai donc utiliser ubuntu:16.04 pour fait mon image minimal ce qui n'est pas très optimiser.

Deux lignes de commandes sont nécessaire pour cette étape :

1. `docker build -f Dockerfile.ubuntu -t tlc/tp1_e3_ubu .`
2. `docker run -p 8080:8080 -it tlc/tp1_e3_ubu`
