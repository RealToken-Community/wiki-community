---
description: le jeton et pré-jeton de gouvernance
---

# REG / SOON / USDREG

## Le jeton SOON, puis le droit USDREG

Le jeton SOON est la première étape vers un jeton de Gouvernance (REG).\
&#x20;         [Community call](https://www.youtube.com/watch?v=YJGj2JcSu6c\&t=632s) de présentation et des mécanismes du token SOON.\
Ce jeton a été remplacé par des droits en USDREG (droit en $, convertible uniquement en REG) à partir du 18 mars 2025. \
La quantité de ses droits sont visibles sur l'application pour les convertir en REG : [https://claim.realtoken.network/reg](https://claim.realtoken.network/reg)

## Distribution des SOON / USDREG

Ils sont attribués lors de la première [réévaluation](reevaluation.md) d'une propriété, ils sont bloqués (donc non transférables). Les Soon distribuées ont été remplacés par des droit en USDREG : avec une parité d'1 SOON pour un 1$ de jeton de Gouvernance (1 USDREG).

Le montant total des REG (figurant dans l'[onglet Valuation](reevaluation.md) de la propriété) est attribué aux wallets détenant le RealToken (au moment de la première réévaluation) et au prorata du montant détenu par chacun.

<figure><img src="../.gitbook/assets/image (263).png" alt="" width="563"><figcaption></figcaption></figure>

Les SOON était un token (adresse : \
[https://gnosisscan.io/token/0xaa2c0cf54cb418eb24e7e09053b82c875c68bb88#balances](https://gnosisscan.io/token/0xaa2c0cf54cb418eb24e7e09053b82c875c68bb88#balances)\
L'USDREG est un droit stocké dans un fichier (merkle tree) : [https://github.com/real-token/vault-merkle-data/tree/main/dao/usdreg\_convertion/2025](https://github.com/real-token/vault-merkle-data/tree/main/dao/usdreg_convertion/2025).

## Liste de distribution

RealT met à disposition des fichiers CSV, avec l'ensemble des SOON / USDREG distribués : [https://drive.google.com/drive/folders/1dw5DfJo6R1zVXC6b\_Rjw1988X\_yBfpfv](https://drive.google.com/drive/folders/1dw5DfJo6R1zVXC6b_Rjw1988X_yBfpfv)

## Conversion en REG

La conversion des USDREG en REG se fait avec l'application : [ttps://claim.realtoken.network/reg](https://claim.realtoken.network/reg)

Comme mentionné précédemment, à partir du 18 mars 2025 :&#x20;

* l'ensemble des token SOON que vous avez pu obtenir (sur différents wallets) ont été convertis en droit USDREG et attribué au wallet qui est déclaré comme recevant vos propriétés sur le site realt.co (à cette date),\
  Les tokens SOON ont ensuite été détruits (burn),
* lors des premières réévaluations qui suivent, ce ne seront plus des SOON mais des USDREG qui seront attribués,&#x20;

La conversion (claim) converti vos droit USDREG en REG, en fonction de la parité du REG (via un service d'Oracle, qui lisse le cours du jour précédent pour éviter toute manipulation du marché). \
La parité du REG étant variable, vous pourrez donc choisir le moment (et donc la parité) de la conversion. (pour un montant USDREG donné, vous aurez d'autant plus de REG que la parité du REG sera faible...et inversement).\
Tant que vous n'avez pas converti vos USDREG en REG, ils ne sont pas créé et vous n'avez donc pas le pouvoir de vote qui est associé.\
Si besoin (par ex wallet corrompu), les REG peuvent être réclamé vers un autre wallet (délégué).

Pour plus d'informations : [https://wiki.realtoken.community/fr/DAO/Life/ClaimREG](https://wiki.realtoken.community/fr/DAO/Life/ClaimREG)
