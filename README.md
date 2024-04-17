# Guacamole Docker

Guacamole Docker est un projet qui installe Guacamole 🚀

## Description

Ce projet vise à installer automatiquement Guacamole sur Docker sous certaines conditions

## Installation

Pour installer Guacamole Docker, suivez ces étapes :

1. Clonez ce dépôt sur votre machine locale :

    ```bash
    git clone https://github.com/PzPr0T0N/Guacamole-Docker.git
    ```

2. Renommez le répertoire cloné :

    ```bash
    mv Guacamole-Docker/ guacamole/
    ```

3. Accédez au répertoire guacamole :

    ```bash
    cd guacamole
    ```

4. Exécutez le script de préparation :

    ```bash
    sh prepare.sh
    ```

5. Démarrez les conteneurs Docker :

    ```bash
    docker-compose up -d
    ```

En bref :

```bash
git clone "https://github.com/PzPr0T0N/Guacamole-Docker.git"
mv Guacamole-Docker/ guacamole/
cd guacamole
sh prepare.sh
docker-compose up -d
```
