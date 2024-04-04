# Arbitrage, Impermanent Loss

### Arbitrage

La paire fonctionne de manière autonome : son protocole calcul la parité, sans aucune relation avec les prix de marché.\
Il peut alors se produire, un décalage : entre la parité de la paire et le prix de marché, induisant une opportunité d'arbitage.

Sur Levinswap, si la parité d'un RealTokens est très inférieure à sa valeur de marché (sur site RealT ou sur YAM), l'arbitrage consiste à acheter ce RealToken dans la pool et à le revendre à un montant plus élevé. L'arbitrageur fait ainsi, un bénéfice et fait remonter la parité de la pool.

Analysons cela, au travers d'exemples :

<figure><img src="../../../.gitbook/assets/image (284).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/19Ih_NMWgKtCl9ueTH6iBlsxEUjeY7XpcbmWs1URmkQA/edit?usp=sharing">https://docs.google.com/spreadsheets/d/19Ih_NMWgKtCl9ueTH6iBlsxEUjeY7XpcbmWs1URmkQA/edit?usp=sharing</a></p></figcaption></figure>

Dans l'exemple, après une réévaluation, le RealToken est passé de 50 à 60$. Alors que la parité du pool est restée à 50$.\
Un arbitreur à acheté 2,1 RealTokens à 54,79$ l'unité, pour les revendre à 60$ (voir plus ...). Faisant une plus value et remonter la parité de la pool à 60$.\
Inversement, si le RealToken avait baissé de 50 à 40$, l'arbitreur aurait vendu 2,83 RealTokens à 44,73$ l'unité (réduisant sa perte sur le Realtoken).

### Impermanent Loss (IL)

l'IL est un facteur de risque important, pour les apporteurs de liquidité en Defi. L'IL se produit, à l'occasion de variations significatives des prix des tokens déposés sur une pool. Il correspond à la différence entre le dépôt de fonds sur une pool et simplement garder ses fonds (qui se valorisent, suite à la variation de prix).

Reprenons l'exemple du tableur ci-dessus.

Le RealToken a augmenté de 20% (50 à 60$), le holder de la pool à fait 38,18$ de gain (400 - 438,18). Si maintenant on compare ce gain, à celui qu'aurait fait le holder sans faire d'apport de liquidité : 440$ (=4 \* 60 $ + 200$), l'_Impermanent Loss_ est 1,82$ (440 - 438,18) soit 0,41%.\
Dans le cas inverse, si le Relatoken avait perdu 20% (50 à 40$), l'_Impermanent Loss_ serait de 2,23 $ soit 0,62%.

Les variations des paires RealToken / USDC étant limités, le risque d'IL l'est par la même.

Le qualificatif _Impermanent,_ est lié au fait que cette "perte" n'est effective que lors du retrait de la liquidité apportée. En restant dans la pool, de nouvelles variations peuvent venir corriger cette perte potentielle.
