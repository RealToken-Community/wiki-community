# Les différents wallets et évolution progressive du "RealToken Wallet"

<figure><img src="../../.gitbook/assets/image (303).png" alt=""><figcaption><p><a href="https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing">https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing</a></p></figcaption></figure>

A partir de la gauche du schéma ci-dessus : Le site web [Realt.co](https://realt.co/) est une application Web2 qui s’accède de façon classique avec un identifiant et un mot de passe (auquel, en option, vous pouvez ajouter une sécurité d'accès supplémentaire avec un second code : fonction 2FA).\
Pour autant, les RealTokens que vous achetez et les loyers que vous percevez ne sont pas détenus par RealT (ou sur l’application Realt.co), mais sont stockés sur un wallet (même dans le cas de l’option « _WalletLess_ » !).

Les applications qui fonctionnent sur la blockchain (qualifiées de DApp : Application décentralisée ou Web3), ne s’accèdent qu’avec une clé privée (stokée dans Metamask, ou Ledger,..).\
C’est par exemple le cas des deux DApp : YAM (pour acheter et vendre des Realtokens) et RMM (pour déposer et emprunter avec des Realtokens). Ces deux applications peuvent faire des transactions sur votre wallet (avec votre approbation). D’autres applications communautaires (Dashboard, Crypt’Alloc, Pit’swap, ..) vous demandent juste votre clé publique, pour lire l’état de votre wallet (pour l'execution de  transactions, elles renvoient à YAM ou Swapcat).

La fonction Walletless, ne permet pas d'accéder aux DApp, ce que le nouveau _Realtoken wallet_ (basé sur le standart d'Account Abstraction) permettra progressivement :&#x20;

* Etape 1 : Tout se fait à partir du site [Realt.co](https://realt.co/). \
  La création du _Realtoken Wallet_ (AA), avec une authentification par Gmail ou un Social Login (compte existants : Facebook, Discord ou  Twitchh) sans vous soucier de sa clé privée, sera répartie sur plusieurs adresses et sécurisée par RealT (ou par la suite, par l'utilisateur lui même si il le souhaite),
* Etape 2 : Une application spécifique pour le _Realtoken Wallet_  sera développée pour accéder aux DApp qui ne supporteraient pas le standard AA, et cela au travers de la solution WalletConnect 2 (comme cela se fait actuellement sur mobile),
* Etape 3 : Les DApp de l'écosystème (YAM,..) seront progressivement mis à niveau pour accepter le standard AA. Il sera alors possible pour le _RealToken Wallet_ de ne plus passer par le site [Realt.co](https://realt.co/) et d'accéder à des fonctions supplémentaires (tel que l'emprunt RMM par ex.)

A terme, vous aurez donc deux moyens de vous servir de votre _Realtoken Wallet_ :&#x20;

* soit au travers du site Realt.co ( pour les comptes qui sont dans ce mode), qui exécutera automatiquement la connexion au _Realtoken Wallet_ (avec le social login et éventuellement le 2FA, qu'il aura mémorisé),
* soit sur les DApp, supportant le standard _Account Abstraction_, en utilisant le social login associé au _Realtoken Wallet_ lors de sa création. C'est à ce stade que le 2FA prendra toute son importance, pour compléter la sécurité d'accès d'un simple social login.

La clé privée associé au _Realtoken Wallet_ est complètement masquée, seul le social login (voire son 2FA) est a connaitre. Si jamais vous le perdez, vous pourrez :&#x20;

* Soit demander à Realt de restaurer le lien entre votre _Realtoken Wallet_ et votre nouveau social login,
* Soit changer vous même le social login associé à votre _Realtoken Wallet_, ce qui nécessitera l'approbation de plusieurs wallets (guardian), que vous aurez du préalablement substitués aux wallets définis par défaut à la création et détenus par RealT.

Ainsi, grâce aux possibilités de l'Abstract Account, malgré une perte des moyens de connexion à votre _Realtoken wallet_, vous ne perdez pas son contenu.

