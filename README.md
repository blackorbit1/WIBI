# WIBI : Will I Be Infected ?

<img src="https://desfichesdescartes.fr/projet/icon_localisation_rouge.png" alt="Logo de l'application WIBI" width="200"/>

## A quoi ça sert ?

Déterminer la probabilitée d'attrapper le covid en fonction de son comportement et des lieux que l'on souhaite visiter.

## Base technique

Cette application est codée en react native, ce qui permet une compatibilitée totale autant avec Android qu'avec iOS

La base technique de cette application provient du repos suivant : https://github.com/flatlogic/react-native-starter

## Se lancer

#### 1. Cloner le repos et installer

```bash
# Cloner le repo
git clone https://github.com/flatlogic/react-native-starter.git

# Aller dans le dossier du projet et installer les dépendances
cd react-native-starter && yarn install

# Installer Pods
cd ios && pod install
```

#### 2. Ouvrir RNS dans votre simulateur iOS

Executez cette commande pour démarrer le serveur de développement et démarrer votre application dans le simulateur iOS :
```
yarn run:ios
```

Ou sur Android :
```
yarn run:android
```

Et voilà !

## Documentation

Une documentation sur la structure utilisée pour l'application peut etre trouvée à l'adresse suivante : https://docs.reactnativestarter.com 


## License

[Mozilla Public License 2.0](LICENSE)
