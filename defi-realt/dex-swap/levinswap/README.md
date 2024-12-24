# Levinswap

{% hint style="danger" %}
Début Février 2024, RealT a retiré 80 % des liquidités qu'ils avaient apporté sur Levinswap (réduisant de 20 à 4 Realtokens + contrepartie). Son apport est maintenant limité à 2 Realtokens + contrepartie USDC. Une nouvelle application est en cours de développement.
{% endhint %}

LevinSwap est un échangeur décentralisé (DEX). Il permet l’échange de tokens à partir de réserves (nommées ou pool ou paire), et pourvues de tokens au préalable par des apporteurs de liquidité.

Sur YAM (ou Swapcat) : vous publiez une offre et devez attendre un acheteur...\
Avec Levinswap, l’échange se fait instantanément, mais avec un prix qui peut varier suivant la liquidité de la pool (quantité de token disponible).

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

LewinSwap, est une copie (fork) de l’application Uniswap Version 2 sur la Gnosis Chain.\
RealT utilise Levinswap depuis mars 2021. Malheureusement, le principal développeur de Levinswap a quitté le projet en 2022. \
Fin 2022, l’exploitation de l’application a été reprise par la communauté RealT. RealT étudie une solution de remplacement et continue d'utiliser Levinswap en attendant.

A chaque création de RealTokens, RealT crée la paire correspondante sur Levinswap et alloue une liquidité initiale (\*), afin que les propriétaires de RealTokens puissent échanger leurs RealTokens contre un autre token.

Le second token de la paire, a évolué avec le temps :

* jusqu’à mai 2021, c’était LEVIN (token de la DAO du projet Lewinswap),
* après, et jusqu’à mai 2022, c’était wETH,
* et depuis, c’est le stablecoin USDC.

La valeur du LEVIN est proche de 0, ses pools quasi vide : ces paires sont donc à éviter.\
Les pools en wETH et USDC ont une liquidité assez faible (2500 à 3500 $) : il est donc préférable de les utiliser pour acheter ou vendre des fractions de RealTokens.

Les pages suivantes, vont détailler :

* la [liste des paires d’échange disponibles](liste-des-paires-avec-realtoken.md) avec des RealTokens,
* comment faire un [achat ou une vente de RealTokens sur Levinswap](acheter-ou-vendre-sur-levinswap.md),
* comment [apporter de la liquidité à une paire](apport-de-liquidite.md).

(\*) : A chaque nouveau Realtoken, RealT crée une paire Levinswap avec : 20 Realtokens (réduit à 2 depuis Février. 2024) et l’équivalent en USDC.
