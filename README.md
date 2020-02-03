# tp1-coquard-thomas

#B3 DevOps - TP 1

## Info
mail: thomas.coquard@ynov.com
github_username: ThomasYnov-gif


## Résumé TP

Le but de ce TP est de provisionner une VM avec Vagrant. Il faut savoir que Vagrant est un logiciel libre et open-source pour la création et la configuration des environnements de développement virtuel.

Dans notre cas, on souhaite créer une VM donc l'OS est ubuntu dans lequel les paquets nodejs@12, openssh-server et nginx sont installés.
De plus, dans notre configuration, nous devons avoir un bootstrap.sh dans lequel chacune de nos commandes devront y être inscrites dans le but de séparer notre fichier de configuration principale qui est "Vagrantfile" avec les commandes qui sont elles, secondaires à la création de VM.

Pour lancer le vagrant, la commande a utilisé est : vagrant up

Pour le stopper : vagrant destroy

Pour lancer le ssh : ssh vagrant@127.0.0.1 -p 2220 

Pour vérifier notre page html, on se rend dans un navigateur puis on se rend à l'adresse : http://127.0.0.1:8080.

