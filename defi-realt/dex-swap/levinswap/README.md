# Levinswap

LevinSwap est un échangeur décentralisé (DEX). Il permet l’échange de tokens à partir de réserves (pool/paire), pourvues au préalable par des apporteurs de liquidité.

Sur YAM (ou Swapcat) : vous publiez une offre et devez attendre un acheteur...\
Avec Levinswap, l’échange se fait instantanément, mais avec un prix qui peut varier suivant la liquidité (quantité de token) de la pool.

<figure><img src="../../../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

LewinSwap, est une copie (fork) de l’application Uniswap Version 2 sur la Gnosis Chain.\
RealT utilise Levinswap depuis mars 2021. Malheureusement, le principal développeur de Levinswap a quitté le projet en 2022. \
Fin 2022, l’exploitation de l’application a été reprise par la communauté RealT. RealT étudie une solution de remplacement et continue à utiliser Levinswap en attendant.

A chaque création de RealTokens, RealT crée la paire correspondante sur Levinswap et alloue une liquidité initiale (\*), afin que les propriétaires (holder) de RealToken puissent échanger leurs RealTokens contre un autre token.

Le second token de la paire, a évolué avec le temps :

* jusqu’à mai 2021, c’était LEVIN (token de la DAO du projet Lewinswap),
* après, et jusqu’à mai 2022, c’était WETH,
* et depuis, c’est le stablecoin USDC.

La valeur du LEVIN est proche de 0, ses pools quasi vide : ces paires sont donc à éviter.\
Les pools en WETH et USDC ont une liquidité assez faible (1000 à 2000 $) : il est donc préférable de les utiliser pour acheter ou vendre des fractions de RealTokens.

Les pages suivantes, vont détailler :

* la liste des paires d’échange disponibles avec des RealTokens,
* comment faire un achat ou une vente de RealTokens sur Levinswap,
* comment apporter de la liquidité à une paire.

(\*) : A chaque nouveau Realtoken, RealT crée une paire Levinswap avec : 20 Realtokens et l’équivalent en USDC.
