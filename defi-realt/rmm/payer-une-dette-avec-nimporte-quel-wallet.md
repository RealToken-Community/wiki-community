# Payer une dette, avec n'importe quel wallet

Vous pouvez rembourser les fonds empruntés sur le RMM de n'importe quelle adresse Gnosis. L´interface du RMM ne le permet pas pour l´instant et il suffit juste d' interagir avec le Smart contract sur la blockchain.\


Sur RMM v2, la procédure était décrite sur le [FAQ RealT](https://faq.realt.co/fr/articles/7974754-payer-sa-dette-du-rmm-a-partir-de-n-importe-quelle-adresse).

Avec RMM v3, la procédure est différente car :&#x20;

* le smart contract RMM v3 est différent,
* il y a plusieurs Stablecoins d'emprunt (WXDAI et USDC),
* il faut au préalable, avoir autorisé le smart contract RMM à accéder aux Stablecoins que vous allez rembourser.

## Autorisation d'accès préalable

Pour que le smart contract du RMM v3 soit autorisé à agir sur vos Stablecoins, il suffit que le wallet (qui va faire le remboursement) ait fait au préalable un dépôt d'un tout petit montant mais avec un plafond un peu supérieur au remboursement que vous souhaitez faire.\
Dans l'exemple ci-après, au préalable d'un remboursement en USDC : nous avons fait un dépôt d'1 USDC avec un plafond illimité (en laissant le montant en rouge par défaut) :

<figure><img src="../../.gitbook/assets/image (259).png" alt="" width="375"><figcaption></figcaption></figure>

Nota : Vous pouvez vérifier sur l'application [Revoke.cash](https://revoke.cash/), l'existence de cette autorisation et pourrez par la suite la révoker.

<figure><img src="../../.gitbook/assets/image (262).png" alt="" width="563"><figcaption></figcaption></figure>

## Connexion au smart contract RMM v3

Vous accédez, via l'explorateur Gnosis, directement au smart contract par ce [lien](https://gnosisscan.io/address/0xfb9b496519fca8473fba1af0850b6b8f476bfdb3#writeProxyContract).&#x20;

<figure><img src="../../.gitbook/assets/image (260).png" alt=""><figcaption></figcaption></figure>

Cet page permet d´interagir directement avec le Smart Contract et comme toute interaction sur la blockchain, il faut connecter votre wallet (Cliquez sur Connect to Web3). L'explorateur Gnosis accepte Wallet Connect et les Wallets de navigateur.

Il se peut que votre wallet ne se connecte pas à la première tentative, il faut refaire la manipulation pour que votre adresse Gnosis apparaisse en vert sur le site.

## Interagir avec le Smart Contract <a href="#h_efd1cb9531" id="h_efd1cb9531"></a>

C´est la fonction 15 qui sert à rembourser les emprunts sur le Smart Contract du RMM v3, "repay (0x573ade81". Dans l'exemple ci-après, nous allons rembourser 0,1 XDAI ou USDC d'un autre wallet.

<figure><img src="../../.gitbook/assets/image (261).png" alt="" width="530"><figcaption></figcaption></figure>

* Le champ Asset, doit contenir l'adresse du Stablecoin qui sera remboursé\
  (Ces adresses sont disponibles sur la fiche du stablecoin sur le RMM)
* Le montant à rembourser doit être exprimé dans le format spécifique à chaque Stablecoin :
  * pour le WXDAI votre chiffre décimal doit être multiplié par 10 puissance 18. \
    Donc pour 0,1 WXDAI, il faut inscrire 100000000000000000 (1 et 17 zéro),
  * pour l'USDC votre chiffre décimal doit être multiplié par 10 puissance 6. \
    Donc pour 0,1 USDC, il faut inscrire 100000 (1 et 5 zéro)
* L'interstRateMode doit être 2 (remboursement d'un emprunt à taux variable),
* Et enfin le champ onBehalf0f doit contenir l'adresse du wallet qui a fait l'emprunt et que vous souhaitez rembourser. \


Il suffira de valider l´opération sur votre wallet et la transaction sera normalement effectuée.

