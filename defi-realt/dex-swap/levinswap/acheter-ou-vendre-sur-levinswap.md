# Acheter ou vendre sur Levinswap

{% hint style="info" %}
En préalable (comme sur Yam) : il vous faut être whitelisté, avant toute acquisition d’un RealToken que vous ne possédez pas.
{% endhint %}

Pour échanger (swaper) un RealToken, vous devez connecter votre wallet sur l’application suivante (en étant sur la Gnosis Chain) : \
&#x20;                                   [https://app.levinswap.realt.community/#/swap](https://app.levinswap.realt.community/#/swap)

### Vente de Realtokens

{% embed url="https://youtu.be/CUm4wQAPK_4" %}

Dans la vidéo, vous voyez comment faire un swap, mais aussi comment évolue le prix de vente de votre RealToken en fonction de la quantité que vous souhaitez vendre :

* sa parité initiale dans le pool est de 48,67 USDC / RealToken (cf exemple de la page précédente),
* La video test en premier, la vente d'1 RealToken : le prix est de 47,19 USDC, soit une décote « _Price Impact_ » de 2,73 % (affichée en bas de l'écran) par rapport à la parité initiale de la pool,
* puis on teste la vente de 2 RealTokens, le prix continue à décroître à 45,93 USDC / RealToken, avec un P_rice Impact_ qui passe alors en rouge : au dessus de 5 % de décote,
* puis enfin 4 Realtokens , le montant passe à 43,6 USDC / Realtoken et le P_rice Impac_t à 10 % !

Ce comportement est lié au mécanisme utilisé par l’application pour préserver sa liquidité. Ainsi, on évite que la pool se vide complètement.\
Le _Price Impact_ est d’autant plus pénalisant, que la proportion de la transaction est grande au regard de la liquidité disponible (par ex, quand on retire 2 tokens, alors qu’il n'y en a que 35 de disponible...)

A ce prix (inférieur au prix RealT) vous vous dite, qu’il serait préférable d’acheter : à la fin de la précédente vidéo, vous voyez qu’il suffit juste de cliquer sur la flèche centrale pour passer à l’échange inverse : USDC contre des Realtokens.

### Achat de Realtokens

Vous allez voir que là aussi, le même phénomène se produit : le prix du token que vous souhaitez acheter augmente très vite avec la quantité demandée.

D’où la recommandation initiale, de n’utiliser Levinswap que pour des achats ou vente inférieur à 1 RealToken (des fractions de token, pour avoir des comptes ronds, par exemple :wink: )

{% embed url="https://youtu.be/q_ADrI-pR2Y" %}

### Slippage

La parité d’un échange se dégrade à cause du P_rice Impact_, mais cette dégradation peut être accrue par du « S_lippage_ ». Cela se produit si : juste avant l’approbation de votre échange, un autre échange venait à modifier la parité.\
Le mécanisme de protection, pour limiter le _Slippage_ est présenté dans la vidéo suivante :

{% embed url="https://youtu.be/uFFpYES4gWE" %}

Le champ « _Minimum received_ » (en bas de l'écran), indique la valeur limite au-delà de laquelle la transaction sera annulée.

Dans les _Settings_, vous pouvez modifier la limite de _Slippage_ (0,5 % par défaut), et vous voyez le _Minimum received_ s’actualiser en conséquence.

### Frais

L’échangeur prélève 0,3 %, du montant apporté lors d’un swap, dont l’essentiel sert à récompenser les apporteurs de liquidités.

### Combinaison de paires

Si vous demandez un échange dont la paire n’existe pas, Lewinswap va essayer de vous faire une proposition en combinant plusieurs paires.

Ci–après l’exemple, d’une combinaison RealToken > Levin > USDC (le prince impact est particulièrement sévère, car vous cumulez le manque de liquidité des deux pools !)

<figure><img src="../../../.gitbook/assets/image (249).png" alt="" width="291"><figcaption></figcaption></figure>
