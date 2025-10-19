# Application "Realtoken Wallet"

Avec votre _Realtoken Wallet,_ les actions possibles sur le site Realt.co sont limités (achat de nouveaux Realtoken, vente à RealT et transfert de vos fonds vers votre banque). \
Pour utiliser toutes les applications du Web3 (qui s'accèdent avec un wallet), comme YAM RMM, .. , l'adresse de votre compte ne suffit pas (car votre _Realtoken wallet_ est un peu particulier, c'est un Abstract Account). \
Un application Web a été créé par RealT pour cela  : [_https://wallet.realtoken.network/_](https://wallet.realtoken.network/)\
_(_&#x63;ette application est un peu l'équivalent de Metamask ou Rabby, pour un wallet classique).

## Connexion avec un "social login"

Pour vous connecter, à l'application _Realtoken wallet,_ vous devez utiliser le social login (Compte : Google, Facebook, Twitch ou Discord) que vous avez indiqué lors de la création de votre _Realtoken wallet_.&#x20;

<figure><img src="../../.gitbook/assets/image (1) (1) (2).png" alt="" width="375"><figcaption></figcaption></figure>

{% hint style="warning" %}
Ne pas utiliser la fonction "Connexions avancées", qui ne sert que dans des cas très particuliers. Sinon vous risquez d'avoir ce genre de message d'erreur :&#x20;
{% endhint %}

<figure><img src="../../.gitbook/assets/image (315).png" alt="" width="330"><figcaption></figcaption></figure>

Cette application est réservée au _Realtoken Wallet_, vous ne pouvez pas (simplement) vous y connecter avec un portefeuille "classique" (dont vous détenez la seed phrase).

Exemple de connexion, avec un compte Google :&#x20;

<figure><img src="../../.gitbook/assets/image (1) (1) (2) (1).png" alt="" width="563"><figcaption></figcaption></figure>

Si vous avez perdu le social login de votre _Realtoken Wallet_, vous devez passer par le support de RealT (la bulle orange sur le site realt.co), afin que vous puissiez le réinitialiser.

Si vous avez activé le MFA/2FA et que vous rencontrez des soucis : [page spécifique](des-soucis-avec-le-mfa-ou-2fa-...md)

## Principales fonctions de l'application

Dans sa première version (Sept 2024), l'application ne disposait que de trois fonctions : le transfert de tokens, la connexion via WalletConnect et le vote DAO.\
En mars 2025, une nouvelle version de l'application a été  déployée, que nous allons détailler dans les chapitres suivants. &#x20;

<figure><img src="../../.gitbook/assets/image (3) (2).png" alt="" width="563"><figcaption></figcaption></figure>

### Portefeuille

Le premier onglet (en haut à droite) donne une vue globale de votre wallet (image ci-dessus)\
Le second onglet, apporte une vue plus détaillée du contenu de votre _Realtoken Wallet (image ci-dessous)_&#x20;

<figure><img src="../../.gitbook/assets/image (5) (2).png" alt="" width="563"><figcaption></figcaption></figure>

La liste de vos tokens sur Gnosis est répartie en plusieurs catégories, qui se suivent : Actif, Realtoken, RMM et YAM.

{% hint style="warning" %}
Le _Realtoken Wallet_ n'est disponible que sur Gnosis : N'envoyez pas de fonds à son adresse, sur une autre blockchain, ils seraient perdus !
{% endhint %}

Les tokens les plus classiques (et notamment les Realtokens) s'affichent automatiquement. Nous verrons le cas de ceux qui n'apparaissent, pas dans le chapitre "Paramètres".

En bout de ligne à droite, vous disposez d'une flèche sélectable pour agir sur vos Actifs ou Realtoken (exemple pour l'USDC sur l'image ci-dessus). Ainsi vous pouvez transférer le token vers une autre adresse.

Nota : ça peut être parfois un peu long ...Soyez patient !

<figure><img src="../../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Si vous souhaitez vérifier le transfert sur un explorateur

*   Sur[ l'explorateur](https://gnosisscan.io/)[ Gnosis](https://gnosisscan.io/), entrer votre adresse de _Realtoken wallet,_

    <figure><img src="../../.gitbook/assets/image (5) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>
*   Sélectionnez "Internal Transactions" , puis cliquer sur la dernière transaction&#x20;

    <figure><img src="../../.gitbook/assets/image (6) (1) (1).png" alt=""><figcaption></figcaption></figure>
* Dans la fenêtre qui s'est ouverte, rechercher la partie "ERC20 Tokens transferred". Vous voyez alors l'adresse source (From) et cible (To) du transfert, ainsi que le token et sa quantité (For).

### Connexion WalletConnect

WalletConnect est un service qui permet de relier de façon sécurisée (cryptée)  un wallet à une DApp (Application Décentralisée, sur une blockchain) pour signer des transactions.\
Vous avez peut être déjà utilisé ce service pour connecter un wallet mobile à une DApp sur votre navigateur PC ou votre mobile.\
Dans notre cas, cela va permettre de relier votre _Realtoken Wallet_ à une DApp, qui ne supporte pas la connexion avec le _RealToken Wallet,_ afin d'opérer des transactions.

Prenons l'exemple de la DApp RMM (c'est semblable pour YAM, ou tout autre DApp proposant un accès WalletConnect v2).

Pour réaliser cette connexion :&#x20;

* vous avez besoin de deux instances de navigateur (soit deux onglets sur un même navigateur, soit deux navigateurs).
*   Sur une des instances vous lancer la [DApp _RealToken Wallet_](https://wallet.realtoken.network/)_,_ vous vous connectez avec votre Social Login et vous cliqué en haut sur WalletConnect : une fenêtre va apparaitre où vous devez entrer une URL WalletConnect...

    <figure><img src="../../.gitbook/assets/image (7) (1) (1).png" alt="" width="467"><figcaption></figcaption></figure>
* Sur la deuxième instance de navigateur, vous lancer [RMM](https://rmm.realtoken.network/markets/) (par ex), vous connectez votre portefeuille en choisissant WalletConnect : apparait alors une fenêtre avec un QRcode, vous copier le lien associé (dans votre presse papier) en cliquant sur "Connect Your Wallet"

<figure><img src="../../.gitbook/assets/image (9) (1).png" alt="" width="294"><figcaption></figcaption></figure>

*   Vous retournez sur l'instance avec la DApp _RealToken Wallet_ et vous collez le lien (du presse papier) dans la fenêtre demandant l'URL&#x20;

    <figure><img src="../../.gitbook/assets/image (10).png" alt="" width="337"><figcaption></figcaption></figure>
*   Cliquez sur "Se connecter" et c'est gagné !&#x20;

    <figure><img src="../../.gitbook/assets/image (11).png" alt="" width="335"><figcaption></figcaption></figure>
* Retournez sur l'instance RMM et en haut à droite apparait bien, que vous êtes connecté avec l'adresse de votre _RealToken Wallet._

Vous pouvez maintenant, agir sur RMM comme un wallet classique (déposer, emprunter, rembourser, retirer du dépôt).\
A ceci près, que :&#x20;

* il faut jongler avec les deux instance de navigateurs, à chaque confirmation de transaction,
* que les instances peuvent parfois devoir être actualisées manuellement (via PF5),
* que c'est lent ...\
  Attention : si vous tapez plusieurs fois sur une fonction RMM (pensant qu'elle n'a pas été prise en compte) ça fera plusieurs fois la transactions !...(certes, que vous pourrez ne pas la confirmer sur le wallet, et ainsi éviter les doublons..)

La DApp _RealToken wallet_ est une application Web et pas une extension de navigateur comme MetaMask ou Rabby. Les actions sont donc moins fluides, mais cela devrait s'améliorer avec le temps ..&#x20;

\
L'apport important de la **nouvelle version**, sur ce sujet, est le niveau de détail des fenêtres d'approbation lors d'une transaction. \
Exemple lors d'un dépôt sur RMM :

<figure><img src="../../.gitbook/assets/image (6) (2).png" alt="" width="563"><figcaption></figcaption></figure>

#### Premier dépôt d'USDC sur RMM

Lorsque vous déposer pour la première fois des USDC sur RMM, veiller a être en mode Transaction et non Message signé :&#x20;

<figure><img src="../../.gitbook/assets/image (327).png" alt="" width="563"><figcaption></figcaption></figure>

La version actuelle de WalletConnect du Realtoken Wallet ne supporte pas les transactions en [mode permit](../../securite/controle-des-autorisations.md) (avec signature). \
\
Le problème ne se produit pas : \


* avec un dépot en XDAI, car le XDAI ne supporte pas le mode Permit (l'option "Signed message" ne sera alors pas proposée)
* lors des dépôts d'USDC suivants, car lors du premier dépôt vous donnez un accès "illimited" du RMM à vos USDC.

#### Utilisation du canal WalletConnect de Rabby

La solution WalletConnect est parfois un peu "capricieuse".  [Rabby](../../portefeuille/rabby.md) à mis en place une solution WalletConnect qui semble plus stable.\
Tuto pour utiliser ce moyen&#x20;

{% file src="../../.gitbook/assets/WC2 Rabby.pdf" %}

## Vote DAO

Comme toute DApp l'application de vote (Tally) est accessible par WalletConnect.\
Si l'application WalletConnect venait à ne pas fonctionner, une fonction de vote a été rajouté directement sur le _Realtoken wallet._

Il vous suffira :&#x20;

* sur l'application de [vote DAO](https://www.tally.xyz/gov/realtoken-ecosystem-governance), de copier le Proposal ID du vote :&#x20;

<figure><img src="../../.gitbook/assets/image (305).png" alt="" width="443"><figcaption></figcaption></figure>

*   puis, de le copier dans le _Realtoken Wallet_ :&#x20;

    <figure><img src="../../.gitbook/assets/image (306).png" alt="" width="256"><figcaption></figcaption></figure>
* et enfin de voter.

## Paramètres

Le troisième onglet (en haut à gauche), permet l'activations de certaines options.

#### Tokens personnalisés

Lorsqu'un token ne s'affiche pas dans votre liste, vous pouvez l'ajouter manuellement

<figure><img src="../../.gitbook/assets/image (318).png" alt="" width="563"><figcaption></figcaption></figure>

#### Carnet d'adresses

Si vous souhaitez mémoriser une adresse de wallet destinataire, qui sera sélectable lors d'un envoi :&#x20;

<figure><img src="../../.gitbook/assets/image (2) (2).png" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="info" %}
Les tokens et adresses personnalisés sont stockés sur votre appareil/navigateur. Vous ne les retrouverez donc pas, si vous changer d'appareil/navigateur.
{% endhint %}
