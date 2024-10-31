# Betty Bet

Betty Bet est un bot Discord conçu pour gérer des paris et des jeux au sein de votre serveur. Il offre une variété de commandes pour parier, consulter des statistiques, organiser des tournois, et bien plus encore.

## Fonctionnalités

- **/register** : Inscrivez-vous pour obtenir des GearPoints initiaux et commencer à parier.
- **/points** : Consultez vos GearPoints actuels et votre statut.
- **/inventory** : Consultez les GearPoints dans votre inventaire.
- **/claim** : Réclamez des GearPoints depuis votre inventaire pour les ajouter à votre solde.
- **/leaderboard** : Affichez le classement des meilleurs parieurs.
- **/bethistory** : Affichez votre historique de paris.
- **/stats** : Affichez vos statistiques détaillées.
- **/globalstats** : Affichez les statistiques globales des paris.
- **/togglenotifications** : Activez ou désactivez les notifications pour les GearPoints d'inventaire.
- **/clearmessages** : Effacez tous les messages privés envoyés par le bot.
- **/presentation** : Présente Betty Bet et ses fonctionnalités.
- **/guess** : Jouez à un jeu de devinettes ! Devinez un nombre entre 1 et 10000. Gagnez 5 GearPoints si vous devinez correctement, perdez 10 GearPoints sinon.

### Commandes réservées aux rôles **BetManager** :

- **/placeyourbets** : Lancez une période de paris entre deux joueurs.
  - **Options** :
    - `player1name` : Nom du joueur 1
    - `player2name` : Nom du joueur 2
- **/addpoints** : Ajoutez des GearPoints à un utilisateur spécifique.
  - **Options** :
    - `user` : Utilisateur à qui ajouter des GearPoints
    - `points` : Nombre de GearPoints à ajouter
- **/clearbets** : Effacez tous les paris en cas de problème et remboursez les GearPoints.
- **/win** : Déclarez le gagnant et redistribuez les GearPoints.
  - **Options** :
    - `winner` : Le joueur gagnant (1 ou 2)
- **/betslist** : Consultez la liste des paris placés sur chaque joueur.
- **/deleteuser** : Supprimez un utilisateur enregistré.
  - **Options** :
    - `userid` : ID de l'utilisateur à supprimer
- **/backup** : Chiffrez et sauvegardez les données depuis la sauvegarde déchiffrée.
- **/sendbackup** : Envoyez le fichier de sauvegarde déchiffré.
- **/addtournamentparticipant** : Ajoutez un utilisateur à la liste des participants au tournoi.
  - **Options** :
    - `user` : Utilisateur à ajouter
- **/removetournamentparticipant** : Retirez un utilisateur de la liste des participants au tournoi.
  - **Options** :
    - `user` : Utilisateur à retirer
- **/listtournamentparticipants** : Listez tous les participants au tournoi.
- **/cleartournamentparticipants** : Effacez la liste des participants au tournoi.
- **/transferdebilus** : Transférez tous les GearPoints du debilus closet à un utilisateur spécifique et videz le closet.
  - **Options** :
    - `user` : Utilisateur à qui transférer les GearPoints

## Installation

1. Clonez ce dépôt sur votre machine locale.
```sh
   git clone https://github.com/valentinpoupier/betty-bet.git
   cd betty-bet
```
2. Installer les dépendances.
```sh
   npm install
```
4. Configurez les variables d'environnement en créant un fichier .env à la racine du projet et en y ajoutant les valeurs suivantes :
```sh
   DISCORD_TOKEN=your-discord-bot-token
   ALGO=your-encryption-algorithm
   KEY=your-secret-key
```
5. Lancer le bot.
```sh
   npm start
```

## Utilisation

Une fois le bot lancé, invitez-le sur votre serveur Discord et utilisez les commandes pour commencer à parier et à jouer. Assurez-vous d'avoir les rôles appropriés pour utiliser les commandes réservées aux BetManagers.

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus d'informations.


### Conclusion

Ce fichier README donne un aperçu complet de Betty Bet, ses fonctionnalités, comment l'installer et l'utiliser. Si vous avez besoin de plus de détails ou de modifications supplémentaires, faites-le moi savoir !
