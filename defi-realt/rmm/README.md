---
description: Service de prêt et d'emprunt sur la blockchain Gnosis
---

# RMM (RealT)

## Introduction

L’application [RMM](https://rmm.realtoken.network/markets) (RealToken Money Market), a été mise en place en Avril 2022 par RealT (à partir du [Protocole AAVE v2](rmm-v2-avril-2022.md)) afin de fournir un service de dépôt et prêts de Stablecoins, en échange de RealTokens mis en garantie, sur la blockchain Gnosis.

En Avril 2023, le mode de présentation de l'application a été modifé, en cohérence avec l'application AAVE et afin de préparer la transition vers la version 3.

Le 8 Février 2024, la version 3 du RMM a été déployée en production.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="189"><figcaption></figcaption></figure>

## Guide utilisateur

Tuto, réalisé par un membre de la communauté : \


{% file src="../../.gitbook/assets/Tuto RMM v5.pdf" %}

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

## Comment ça marche

En complément du guide utilisateur, un document (un peu) plus technique sur comment fonctionne la solution et comment agir directement sur les smart contrats.

{% file src="../../.gitbook/assets/RMM CCM v3 - 31 Juillet.pdf" %}

## Transition v2 > v3

<details>

<summary>Etapes de transition : </summary>

* La liste des Realtokens "collatéralisables" est, dans un premier temps, identique en v2 et v3 (pour ne pas augmenter la demande de liquidité). De nouveaux Realtokens collatéralisables seront ajoutés progressivement en v3 par la suite.
* L'usage du RMM v2 a été limité : il n'est plus possible de déposer, ni d'emprunter. Les retraits et remboursements demeurent eux actifs (afin de pouvoir quitter cette version),Les loyers, payés en armmWXDAI, le seront sur le RMM v3 et plus sur la v2,
* Les loyers déjà payables en armmXDAI, seront aussi payables en armmUSDC,
* Augmentation de la LTV des RealTokens sur le RMM v2 et envoi d'un mail par RealT,
* Le Facteur de Réserve, des WXDAI sur RMM v2, a été progressivement augmenté de 10% à 25, puis 50%, puis 75% !..afin de limiter le taux des dépôts de WXDAI sur RMM v2 (et favoriser la migration),
* 28 Février : Une première série de 16 nouvelles propriétés, a été ajoutée au RMM v3. La LTV des propriétés sur RMM v3 a été porté de 50 à 60%,&#x20;
* 6 Avril : 158 Propriétés sont collatéralisables (vs 54 à l'origine),
* 4 Mai : 290 Propriétés sont maintenant collatéralisables !\
  Le facteur de réserve de la v2 a été porté à 100% (donc plus aucun intérêt, n'est versé sur les dépôts de XDAI).\
  98 K ont été ajoutés par RealT sur la v2, afin de permettre à ceux qui ne pouvaient retirer leurs dépôts de XDAI par manque de liquidité, de pouvoir le faire.
* Le 6 Juin : 142 nouvelles propriétés ont été ajoutées au RMM v3. Ce qui fait au total 432 sur plus de 520 propriétés, disponibles comme collatéral.&#x20;
* 23 Juillet : 35 propriétés ont été ajoutées au RMM.
* ...

</details>

## Evolution du Wrapper

Dans certains cas, des RealTokens doivent être détruits (détokenisation, perte d'accès au wallet, ..), ce qui peut engendrer des dysfonctionnement sur RMM (si ces Realtoken garantisent des emprunts). De nouvelles fonctions ont été ajoutés au contrat Wrapper, que la DAO sera en charge d'exécuter.\
\
[https://wiki.realtoken.community/fr/dapp-ecosystem/rmm](https://wiki.realtoken.community/fr/dapp-ecosystem/rmm)

## Usage des frais du RMM v3

{% file src="../../.gitbook/assets/Rev DAO RMM.pdf" %}
