---
description: si vous ne disposez pas de votre ordinateur, lors d'une vente par exemple ..
---

# Achat/Paiement avec Smartphone

La procédure est moins simple que sur votre ordinateur, mais parfois on n'a pas le choix !

Il faut, dans ce cas, avoir une version de votre wallet sur un mobile. Suivant le wallet choisi, la procédure est différente.

## Avec MetaMask

MetaMask est disponible sur votre ordinateur, mais aussi sur mobile : [Android](https://play.google.com/store/apps/details?id=io.metamask) , [IOS](https://apps.apple.com/fr/app/metamask-blockchain-wallet).

A l'inverse de la version sur ordinateur (où Metamask est une extension de votre navigateur), sur mobile c'est l'application Metamask qui intègre un navigateur ! Ce n'est pas un navigateur aussi complet que ce que vous connaissez, mais ce sera suffisant et bien plus simple (cf solution suivante [avec un wallet mobile autre que MetaMask](achat-paiement-avec-smartphone.md#avec-un-wallet-mobile-autre-que-metamask)).

Parmi les 3 [modes de paiement](mode-de-paiement-realt.md), prenons la première option par [Request Finance](paiement-avec-request-finance.md).\
(Pour un paiement via [Coinbase Commerce](paiement-avec-coinbase-commerce.md), c'est très simple puisque la page Coinbase vous donne le montant et le wallet vers lequel vous devez faire votre paiement)

Pour un paiement Request Finance, avec votre smartphone et MetaMask (mobile), les étapes sont les suivantes :

1. Sur votre messagerie mobile, dans le mail de Request Finance : cliquer pour accéder à votre facture,
2. Le navigateur de votre mobile va alors s'ouvrir sur le site de Request Finance (en précisant que l'application n'est pas "optimisée" sur mobile !),
3. Ouvrir votre MetaMask mobile et le passer en mode navigateur (ce navigateur intégré est différent de votre navigateur habituel sur mobile),
4. Copier l'adresse (URL) du site Request Finance, qui s'est ouvert dans votre navigateur mobile habituel, et coller cette adresse dans le navigateur MetaMask,
5. La même page s'ouvre alors dans le navigateur intégré MetaMask, appuyer sur Pay Now, et une fois le montant affiché à nouveau Pay Now,
6. MetaMask va alors basculer automatiquement en mode Portefeuille, afin que vous puissiez signer la transaction (pour mémoire, nous sommes sur Gnosis il vous faut donc un peu de xDai pour les frais de transactions),
7. MetaMask repasse en mode Navigateur et vous pouvez voir la confirmation de paiement du site Request Finance.

<details>

<summary>Parcours en image (Paiment Request Finance avec MetaMask mobile)</summary>

<img src="../../.gitbook/assets/image (68).png" alt="" data-size="original"> <img src="../../.gitbook/assets/image (152).png" alt="" data-size="original"> <img src="../../.gitbook/assets/image (157).png" alt="" data-size="original">

</details>

## Avec un wallet mobile autre que MetaMask

Prenons l'exemple du [RealT Wallet](../../portefeuille/realt-wallet.md) ou de son "grand frère" [Bridge Wallet](https://www.mtpelerin.com/fr/bridge-wallet).

Dans ce cas, il n'y a pas de navigateur intégré (comme avec [MetaMask](achat-paiement-avec-smartphone.md#avec-metamask)), vous allez donc devoir vous servir de votre navigateur mobile habituel et passer manuellement du navigateur au wallet (rien d'automatisé, comme dans la solution précédente).\
Pour faire le lien entre votre wallet et l'application web 3 (Request Finance) dans votre navigateur, il faut par ailleurs passer par un composant qui se nomme WalletConnect.

Sur votre smartphone, pour un paiement Request Finance avec [RealT Wallet](../../portefeuille/realt-wallet.md) (ou[Bridge Wallet](https://www.mtpelerin.com/fr/bridge-wallet)) , les étapes sont les suivantes :

1. Sur votre messagerie mobile, dans le mail de Request Finance : cliquer pour accéder à votre facture,
2. Le navigateur de votre mobile va alors s'ouvrir sur le site de Request Finance (en précisant que l'application n'est pas "optimisée" sur mobile !),
3. Faire "Pay Now" sur la facture affichée,
4. Dans le menu qui s'est ouvert, prendre l'option WalletConnect,
5. Une nouvelle page apparaît avec un QR code, faire un copier (avec la fonction "copier" sous le QR),
6. Passer sur RealT Wallet (sans fermer le navigateur), et sélectionner le mode Réglages,
7. Puis sélectionner WalletConnect, puis coller le QR code,
8. Rebasculer sur le navigateur (et l'application Request Finance), le lien WalletConnect ayant été établi le montant de votre facture apparaît pour paiement, faire Pay Now,
9. Revenir sur RealT Wallet, une demande d'approbation est apparue, que vous devez confirmer,
10. Repasser sur le navigateur : le paiement ayant été effectué la facture apparaît en mode "Paid".

<details>

<summary>Parcours en image (Paiement Request Finance avec RealT Wallet)</summary>

<img src="../../.gitbook/assets/image (176).png" alt="" data-size="original"> <img src="../../.gitbook/assets/image (60).png" alt="" data-size="original"> <img src="../../.gitbook/assets/image (64).png" alt="" data-size="original"> <img src="../../.gitbook/assets/image (80).png" alt="" data-size="original">

</details>
