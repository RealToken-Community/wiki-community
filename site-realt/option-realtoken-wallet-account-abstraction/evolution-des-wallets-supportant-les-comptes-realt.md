# Evolution des wallets supportant les comptes RealT"

<figure><img src="../../.gitbook/assets/image (303).png" alt=""><figcaption><p><a href="https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing">https://drive.google.com/file/d/1y0P_e2qKy7Rnll8P3psmwT0DBPAd3CcR/view?usp=sharing</a></p></figcaption></figure>

Quelques explications, concernant ce schéma qui peut paraitre compliqué ..;-)

Tout d'abord, la partie haute concerne les applications de type Web2, celles que vous connaissez de façon classique et auxquelles on se connecte avec un identifiant et un mot de passe. Celle qui figure ici est celle du site  [Realt.co](https://realt.co/)

Sur la partie basse du schéma, ce sont les application de type Web3 (ou DApp), celles qui sont apparues avec l'avènement des Blockchains et auxquelles on se connecte avec un wallet.

Un compte RealT (sur le site Relat.co), dispose obligatoirement d'un wallet pour stocker vos RealTokens et vos loyers (même quand vous étiez avec un compte _Walletless_ !)

Regardons maintenant ce schéma de la gauche vers la droite :&#x20;

* Le wallet "classique", auquel on accède avec sa clé privée stockée dans une DApp (MetaMask, Rabby) ou dans un matériel (Ledger,..), est le wallet utilisé dès l'origine de RealT. Il permet d'accéder aux autres DApp comme YAM, RMM, Communautaire,..
* En 2022, RealT a introduit le compte _Walletless_ pour simplifier la gestion du wallet par l'utilisateur. Le wallet est un Safe Wallet, créé et géré en totalité par RealT. Ainsi pas besoin pour l'utilisateur RealT de se former aux beautés de la technologies blockchain...\
  La contre partie de cette simplification, c'est que le holder ne peut se connecter aux DApp (puisqu'il ne possède ni l'adresse du Safe wallet, ni les clés d'accès).
* En juin 2024 est apparu le _RealToken Wallet (_basé sur le standard d'A_ccount Abstraction, AA)._\
  Dans cette première étape_,_ les fonctions sont assez semblables au _Walletless_ : Création et gestion par RealT, accès uniquement par le site Realt.co, non accès aux DApp (en écriture)..\
  A la différence du _Walletless,_ l'utilisateur dispose de l'adresse de son _RealToken wallet_ et du moyen d'y accéder (accès via un S_ocial Login_, cad l'utilisation d'un compte existant sur les réseaux sociaux : gmail, facebook, discord ou twitch). Cela permet quelques premières nouveautés par rapport au _Walletless :_ Réception de token (uniquement sur Gnosis), whitelist du wallet sur des propriété, accès en lecture aux DApp,..\
  A la différence du _Private Wallet,_ si vous perdez votre moyen d'accès au _RealToken wallet,_ vous ne perdez pas les fonds qui y résident. ReaT (voir vous à l'avenir) serez capable de réinitialiser votre Social Login.
* En Septembre 2024 est apparu la DApp "_RealToken Wallet_". Il s'agit de la première DApp à laquelle vous pouvez vous connecter avec votre _Realtoken wallet_ (et votre Social Login). Développée par RealT, elle permet dans sa premières version de faire des transferts de tokens et la connexion à d'autre DApp (qui ne supporte pas le standard AA) au moyen du service WalletConnect 2 (service déjà utilisé lorsqu'on se connecte avec un mobile).\
  Ainsi vous pouvez, avec ce DApp wallet, vous connecter en mode écriture aux DApp YAM, RMM et faire des transactions !...
* Dans une troisième étape d'évolution du _RealToken Wallet,_ lorsque d'autres DApp (comme YAM et RMM) supporteront l'accès avec le _RealToken Wallet,_ vous n'aurez même plus besoin de passer par le DApp Wallet et WC2.

Ces trois principales étapes d'évolution du _RealToken Wallet_ seront complétées d'un enrichissement progressif des fonctions disponibles pour ce wallet : sur le site Realt.co ainsi que sur le DApp wallet.\
Le _RealToken Wallet_ présente l'avantage par rapport au _Private Wallet_ (wallet classique) d'être "programmable" (via son smart contrat associé). Ainsi de nouvelles fonctions comme des paiements sous condition : de montant, de date, de ..seront possibles.

[Un tableau synthétise et compare](comparatif-entre-les-types-de-wallet.md), les fonctions disponibles pour chacun des wallets. \
\
Le standard d'Account Abstraction est la base de nombreuses évolutions, ce qui explique la nécessité de mises à jour régulières de la solution utilisée par RealT : [V3 du _Realtoken Wallet_ ](v3-du-realtoken-wallet.md)
