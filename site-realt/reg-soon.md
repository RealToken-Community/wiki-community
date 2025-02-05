---
description: le jeton et pré-jeton de gouvernance
---

# REG / SOON

## Le jeton SOON

Le jeton SOON est la première étape vers un jeton de Gouvernance (REG).

[Community call](https://www.youtube.com/watch?v=YJGj2JcSu6c\&t=632s) de présentation et des mécanismes du token SOON,

## Sa distribution

Il est émis lors de la première [réévaluation](reevaluation.md) d'une propriété, il est temporaire et bloqué (il n'est donc pas transférable). Il sera remplacé par le jeton de gouvernance avec une parité d'1 SOON pour un 1$ de jeton de Gouvernance.

Le montant total des SOON (figurant dans l'[onglet Valuation](reevaluation.md) de la propriété) est distribué aux wallets détenant le RealToken (au moment de la première réévaluation) et au prorata du montant détenu par chacun.

<figure><img src="../.gitbook/assets/image (263).png" alt="" width="563"><figcaption></figcaption></figure>

Vous pouvez vérifier en [ajoutant le token](../portefeuille/metamask/ajout-dun-token.md) SOON sur votre wallet (celui qui détient le RealToken au moment de la réévaluation), Son adresse est la suivante : 0xaA2C0cf54cB418eB24E7e09053B82C875C68bb88.

Schéma, fait par un membre de la communauté, pour comprendre (de façon simplifiée) la relation réévaluation vs distribution de SOON :

<figure><img src="../.gitbook/assets/image (116).png" alt="" width="456"><figcaption></figcaption></figure>

## Liste de distribution

RealT met à disposition les fichiers CSV avec l'ensemble des SOON distribués :

[https://drive.google.com/drive/folders/1dw5DfJo6R1zVXC6b\_Rjw1988X\_yBfpfv](https://drive.google.com/drive/folders/1dw5DfJo6R1zVXC6b_Rjw1988X_yBfpfv)

## Historique des SOON reçus

Vous pouvez retrouver l'ensemble des Soons qui vous ont été versés sur un wallet, en allant sur le smart contract SOON dans l'explorateur et en inscrivant l'adresse de votre vallet dans le champ de recherche des holders :\
\
[https://gnosisscan.io/token/0xaa2c0cf54cb418eb24e7e09053b82c875c68bb88#balances](https://gnosisscan.io/token/0xaa2c0cf54cb418eb24e7e09053b82c875c68bb88#balances)

<figure><img src="../.gitbook/assets/image (264).png" alt="" width="563"><figcaption></figcaption></figure>

## Conversion en REG

La conversion des SOON en REG va se faire en deux étapes :

* La première sera réalisée par RealT, qui va convertir vos tokens SOON en USDREG (1 pour 1). \
  Les USDREG sont un montant en $, qui vous est alloué et qui n'est convertible qu'en REG (qui seront créés à cette occasion).\
  A l'issue de cette étape, les tokens SOON seront détruits.
* La seconde étape sera réalisée par vous même, en choisissant le moment où vous souhaitez convertir vos USDREG en REG (opération de "claim").\
  La parité du REG étant variable, vous pourrez ainsi choisir le moment (et donc la parité) de la conversion. (pour un montant USDREG donné, vous aurez d'autant plus de REG que la parité du REG sera faible...et inversement).\
  Pour ce faire, une application de claim sera disponible (comme celle pour claimer les REG de l'[Airdrop Genesis](../defi-realt/la-dao-et-son-reg.md)). Un fois connecté à l'application, avec le wallet qui possédait les tokens SOON : vous verrez le montant de USDREG qui vous est alloué et vous pourrez les claimer (en totalité uniquement). Les REG correspondants seront alors transférés sur le wallet qui a claim (voir sur un autre, si besoin).

Par la suite, la conversion des frais RealT ne se fera plus en SOON mais directement en USDREG.&#x20;
