# Bridge REG (RealT)

RealT met en place un autre Bridge dédié aux REG.

Ici la technologie utilisée est [CCIP de Chainlink](https://docs.chain.link/ccip) (vs Omnibridge pour le [Bridge de Realtoken](bridge-realtokens-realt/)).

<figure><img src="../.gitbook/assets/image (269).png" alt="" width="316"><figcaption></figcaption></figure>

## Mode opératoire

<figure><img src="../.gitbook/assets/image (271).png" alt="" width="563"><figcaption></figcaption></figure>

1. Sélectionner le réseau d'origine (ici Gnosis),
2. Sélectionner le réseau cible (ici Polygon),
3. Indiquer la quantité de REG à bridger,
4. Sélectionner le token de frais (celui du réseau d'origine ou du LINK, token de Chainlink)\
   Nota : les frais sont ceux de Chainlink et du réseau (ici 26 Cts, indépendant de la quantité à bridger)
5. Eventuellement, une adresse de réception différente de celle d'émission
6. Si vous n'êtes pas sur le bon réseau, il vous sera proposer d'en changer avant de lancer le transfert\


Après signature avec le wallet, un message apparait en haut à gauche vous indiquant que le bridge est en cours d'exécution et comment voir son avancement.
