# Option "RealToken Wallet" (Account Abstraction)

La blockchain présente de nombreux avantages pour les nouvelles applications, comme RealT, mais nécessite de se former aux techniques de la blockchain (création d’un wallet, sauvegarde de sa clé privée, achat de crypto, actions de sécurité,..)

A partir de Septembre 2022, les nouveaux utilisateurs de RealT ont pu choisir l’option « Walletless », simplifiant ces taches préalables. Avec cette option, RealT crée, gère et sécurise le wallet du client, sur lequel sont transférés les Realtokens et les loyers.\
\
La contrainte de cette solution, développée par RealT, est qu’elle n’est utilisable que sur le site [Realt.co](https://realt.co/) (et pas sur d'autres sites, comme YAM ou RMM).\
Depuis, les standards blockchain ont progressés et offrent maintenant ce niveau de simplification pour toutes les applications qui respectent une norme : celle de « l’Account Abstraction, AA».

Pour étendre les possibilités offertes à ses clients, RealT a engagé une transition progressive vers ce standard :

* depuis le 19 Juin 2024, les nouveaux utilisateurs peuvent opter pour cette solution (nommée "_RealToken Wallet_") en remplacement de l'option _Walletless_,
* depuis fin juillet 2024, les clients _Walletless_ peuvent migrer vers le _Realtoken Wallet_, sur lequel seront transférés les Realtokens et Stablecoin qui étaient précédemment sur leur Walletless,
* et plus tard, cette solution sera aussi disponible pour les détenteurs de wallet classique.

Cette transition sera aussi progressive, en terme de fonctionnalité :

* Dans un premier temps, le _RealToken Wallet_ ne sera utilisable qu'à partir du site Web [Realt.co](https://realt.co/), les fonctions disponibles étant assez semblables à celles du _Walletless_,
* dans un second temps, le _RealToken Wallet_ sera utilisable à partir d'une application Web (développée par RealT). De nouvelles fonctions deviendront alors disponibles pour ce wallet, comme la connexion aux applications ne supportant pas le standard _Abstract Account_ via WalletConnect 2 (déjà utilisé pour les connexion sur mobile)
* puis progressivement, au fur et à mesure que les applications supporteront le standard Abstract Account, il sera possible de s'y connecter directement (sans passer par WC2).

{% hint style="danger" %}
Le _Realtoken Wallet_ n'est actuellement disponible que sur la blockchain Gnosis. \
Ne faite donc aucun envoi de fond à cette adresse sur d'autres chaines, **sous peine qu'ils soient inaccessibles voir perdus.**
{% endhint %}

Les prochains chapitres détaillent :

* Comment créer ce nouveau "_RealToken Wallet_" lors de l'ouverture d'un compte RealT,
* Comment migrer un compte Walletless vers le _Realtoken Wallet_,
* Les usages possibles du _Realtoken Wallet dans sa première version,_
* l'évolution vers une nouvelle version (3) du RealToken Wallet,
* l'application pour le _RealToken Wallet_,
* Un schéma synthétisant la transition fonctionnelle,
* Un tableau comparatif des différents wallets, associés au compte Realt.co (_Walletless_ ,  _RealToken wallet_ et _Private wallet_ ),
