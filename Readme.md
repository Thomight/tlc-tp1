Pour l'epape 2, il suffit de lancer `docker-compose up`



Pour l'étape 3, je n'ai pas reussi a trouver la lib libjasper1 pour alpine.

j'ai donc utiliser ubuntu:16.04 pour fait mon image minimal ce qui n'est pas tres optimiser.

deux ligne de commande son necessaire pour cette etape :

1. `docker build -f Dockerfile.ubuntu -t tlc/tp1_e3_ubu .`
2. `docker run -p 8080:8080 -it tlc/tp1_e3_ubu`
