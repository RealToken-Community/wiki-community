---
description: Service de prêt et d'emprunt sur la blockchain Gnosis
---

# RMM (RealT)

## Introduction

L’application [RMM](https://rmm.realtoken.network/markets) (RealT Market Maker), a été mise en place en Avril 2022 par RealT (à partir du [Protocole AAVE v2](rmm-v2-avril-2022.md)) afin de fournir un service de dépôt et prêts de Stablecoins, en échange de RealTokens mis en garantie, sur la blockchain Gnosis.

En Avril 2023, le mode de présentation de l'application a été modifé, en cohérence avec l'application AAVE et afin de préparer la transition vers la version 3.

Le 8 Février 2024, la version 3 du RMM a été déployée en production.

<figure><img src="../../.gitbook/assets/image (1).png" alt="" width="189"><figcaption></figcaption></figure>

## Guide utilisateur

Tuto, réalisé par un membre de la communauté : \


{% file src="../../.gitbook/assets/Tuto RMM v3 9 Fev.pdf" %}

<figure><img src="../../.gitbook/assets/image (256).png" alt="" width="431"><figcaption></figcaption></figure>

## Comment ça marche

En complément du guide utilisateur, un document plus technique sur comment fonctionne la solution.

{% file src="../../.gitbook/assets/RMM CCM 11 Fev.pdf" %}

## Mesures de transition v2 > v3

Afin de faciliter la transition :&#x20;

* La liste des Realtokens "collatéralisables" sera, dans un premier temps, identique en v2 et v3 (pour ne pas augmenter la demande de liquidité). De nouveaux Realtokens collatéralisables seront ajoutés progressivement en v3 par la suite.
* L'usage du RMM v2 a été limité : il n'est plus possible de déposer, ni d'emprunter. Les retraits et remboursements demeurent eux actifs (afin de pouvoir quitter cette version),
* Les loyers, payés en armmWXDAI, le seront sur le RMM v3 et plus sur la v2,
* Les loyers déjà payables en armmXDAI, seront aussi payables en armmUSDC,
* Augmentation de la LTV des RealTokens sur le RMM v2 et envoi d'un mail&#x20;

{% file src="../../.gitbook/assets/Mail RealT 16 Février 2024.png" %}

* Le Facteur de Réserve, des WXDAI sur RMM v2, a été progressivement augmenté de 10% à 25 puis 50%, afin de limiter le taux des dépôts de WXDAI sur RMM v2.
