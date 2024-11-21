# DApp "RealToken Wallet"

RealT a développé la première DApp, à laquelle vous pouvez vous connecter avec votre _RealToken Wallet :_ [_https://wallet.realtoken.network/_](https://wallet.realtoken.network/)

<figure><img src="../../.gitbook/assets/image (3).png" alt="" width="375"><figcaption></figcaption></figure>

Dans cette première version, trois fonctions sont disponibles : le transfert de tokens, la connexion via WalletConnect (uniquement en V3) et le vote DAO.

<figure><img src="../../.gitbook/assets/image (304).png" alt="" width="386"><figcaption></figcaption></figure>

## Transfert de Token

Vous pouvez transférer vos tokens uniquement sur Gnosis (dans une première version) d'un _RealToken Wallet_ vers un autre wallet (_Realtoken Wallet_ ou _Private Wallet /_ Wallet "classique" _-_).

Les tokens transférables sont des Stablecoin (USDC, WXDAI), les REG, les tokens de dépôts sur RMM (armmv3USDC et armmv3WXDAI) et les RealTokens (pour lesquels l'adresse cible devra être whitelistée !..).

<figure><img src="../../.gitbook/assets/image (2) (1) (1).png" alt="" width="303"><figcaption></figcaption></figure>

RealT a fait la notice suivante, pour la migration des tokens sur les _RealToken Wallet_ anciennes versions vers la v3 _:_ [_https://drive.google.com/file/d/1z7mwO8t9x6FTz55wosxAanUjktte9nzk/view_](https://drive.google.com/file/d/1z7mwO8t9x6FTz55wosxAanUjktte9nzk/view)

Nota : ça peut être parfois assez long ...Soyez patient !

<figure><img src="../../.gitbook/assets/image (4) (1).png" alt=""><figcaption></figcaption></figure>

### Pour vérifier le transfert sur un explorateur

*   Sur[ l'explorateur](https://gnosisscan.io/)[ Gnosis](https://gnosisscan.io/), entrer votre adresse de _Realtoken wallet,_

    <figure><img src="../../.gitbook/assets/image (5).png" alt="" width="375"><figcaption></figcaption></figure>
*   Sélectionnez "Internal Transactions" , puis cliquer sur la dernière transaction&#x20;

    <figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
* Dans la fenêtre qui s'est ouverte, rechercher la partie "ERC20 Tokens transferred". Vous voyez alors l'adresse source (From) et cible (To) du transfert, ainsi que le token et sa quantité (For).

## Connexion WalletConnect

WalletConnect est un service qui permet de relier de façon sécurisée (cryptée)  un wallet à une DApp pour signer des transactions.\
Vous avez peut être déjà utilisé ce service pour connecter un wallet mobile à une DApp sur votre navigateur PC ou votre mobile.\
Dans notre cas, cela va permettre de relier votre _Realtoken Wallet_ à une DApp, qui ne supporte pas la connexion avec le _RealToken Wallet,_ afin d'opérer des transactions.

Prenons l'exemple de la DApp RMM (c'est semblable pour YAM, ou tout autre DApp proposant un accès WalletConnect v2).

Pour réaliser cette connexion :&#x20;

* vous avez besoin de deux instances de navigateur (soit deux onglets sur un même navigateur, soit deux navigateurs).
*   Sur une des instances vous lancer la [DApp _RealToken Wallet_](https://wallet.realtoken.network/)_,_ vous vous connectez avec votre Social Login et vous cliqué en haut sur WalletConnect : une fenêtre va apparaitre où vous devez entrer une URL WalletConnect...

    <figure><img src="../../.gitbook/assets/image (7).png" alt="" width="467"><figcaption></figcaption></figure>
* Sur la deuxième instance de navigateur, vous lancer [RMM](https://rmm.realtoken.network/markets/) (par ex), vous connectez votre portefeuille en choisissant WalletConnect : apparait alors une fenêtre avec un QRcode, vous copier le lien associé (dans votre presse papier) en cliquant sur "Connect Your Wallet"

<figure><img src="../../.gitbook/assets/image (9).png" alt="" width="294"><figcaption></figcaption></figure>

*   Vous retournez sur l'instance avec la DApp _RealToken Wallet_ et vous collez le lien (du presse papier) dans la fenêtre demandant l'URL&#x20;

    <figure><img src="../../.gitbook/assets/image (10).png" alt="" width="337"><figcaption></figcaption></figure>
*   Cliquez sur "Se connecter" et c'est gagné !&#x20;

    <figure><img src="../../.gitbook/assets/image (11).png" alt="" width="335"><figcaption></figcaption></figure>
* Retournez sur l'instance RMM et en haut à droite apparait bien, que vous êtes connecté avec l'adresse de votre _RealToken Wallet._

Vous pouvez maintenant, agir sur RMM comme un wallet classique (déposer, emprunter, rembourser, retirer du dépôt).\
A ceci près, que :&#x20;

* il faut jongler avec les deux instance de navigateurs, à chaque confirmation de transaction,
* que les instances doivent être actualisée manuellement (via PF5),
* que c'est lent ...\
  Attention : si vous tapez plusieurs fois sur une fonction RMM (pensant qu'elle n'a pas été prise en compte) ça fera plusieurs fois la transactions !...(certes, que vous pourrez ne pas la confirmer sur le wallet, et ainsi éviter les doublons..)

La DApp _RealToken wallet_ est une application Web et pas une extension de navigateur comme MetaMask ou Rabby. Les actions sont donc moins fluides, mais cela devrait s'améliorer avec le temps .. \
C'est la toute première version de cette DApp :wink:...

## Vote DAO

Si l'application WalletConnect venait à ne pas fonctionner, une fonction de vote a été rajouté directement sur le _Realtoken wallet._

Il vous suffira :&#x20;

* sur l'application de [vote DAO](https://www.tally.xyz/gov/realtoken-ecosystem-governance), de copier le Proposal ID du vote :&#x20;

<figure><img src="../../.gitbook/assets/image (305).png" alt="" width="443"><figcaption></figcaption></figure>

*   puis, de le copier dans le _Realtoken Wallet_ :&#x20;

    <figure><img src="../../.gitbook/assets/image (306).png" alt="" width="256"><figcaption></figcaption></figure>
* et enfin de voter.

## Utilisation du canal WalletConnect de Rabby

La solution WalletConnect est parfois un peu "capricieuse".  [Rabby](../../portefeuille/rabby.md) à mis en place une solution WalletConnect qui semble plus stable.\
Tuto pour utiliser ce moyen&#x20;

{% file src="../../.gitbook/assets/WC2 Rabby.pdf" %}
