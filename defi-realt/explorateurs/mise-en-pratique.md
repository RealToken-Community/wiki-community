---
description: de l'usage de l'explorateur (GnosisScan)
---

# Mise en pratique

{% hint style="info" %}
Un conseil, avant de commencer : Entraînez vous avec votre propre wallet...\
Vous savez quelles actions vous avez effectuées, donc si vous ne savez pas à quoi correspondent certains termes, le fait que ce soit votre wallet vous comprendrez mieux :wink:
{% endhint %}

## Analyse d'un wallet

Pour l'exemple, nous allons prendre un des[ gros wallet RealT](../../la-communaute-realt/analyse-des-investisseurs.md).

<figure><img src="../../.gitbook/assets/image (80).png" alt=""><figcaption></figcaption></figure>

1. Zone de recherche, dans laquelle vous allez copier l'adresse du wallet,
2. après recherche, l'explorateur confirme l'addresse analysée,
3. nous sommes sur la blockchaine Gnosis, mais ce wallet a des actif sur 10 autres blockchain,
4. Solde du portefeuille,
5. liste des tokens dans le portefeuille,
6. Identifiant unique pour chacune des transactions,
7. action qui a été réalisée (méthode du smart-contrat utilisé),
8. adresse de l'origine de la transaction (ici l'adresse du portefeuille),
9. adresse de destination de la transaction,
10. montant de la transaction,
11. frais de la transaction,
12. pour avoir l'ensemble des transactions du wallet (sous forme de tableur csv).

## Analyse d'une transaction

En cliquant sur le Transaction Hash, apparait le niveau de détail suivant pour une transaction (qui est ici un achat de RealToken sur  [YAM](../dex-swap/yam.md)) :&#x20;

<figure><img src="../../.gitbook/assets/image (174).png" alt=""><figcaption></figcaption></figure>

1. Transaction Hash,
2. Statut de la transaction,
3. Adresse du portefeuille émetteur de la transaction,
4. Adresse du smart-contrat qui a traité la transaction (YAM),
5. Détail des transferts, ici deux :&#x20;
   * retrait de 51,5 USDC du portefeuille,
   * ajout d'un RealToken vers le portefeuille.
6. Frais de la transaction.

<details>

<summary>Détails complémentaires </summary>

![](<../../.gitbook/assets/image (237).png>)

1. Accessible en ouvrant la flèche en bas de la page,
2. Fonction (Méthode) invoquée, lors de la transaction, sur le smart-contrat (YAM : BuywithPermit)
3. Données d'entrée vers le smart-contrat, en format décodé
4. ID de l'offre YAM,
5. Montant en USDC du RealToken (à multiplier par 10^6, pour l'obtenir en décimal)
6. Quantité de RealToken acheté (à multiplier par 10^18 pour l'obtenir en décimal)

</details>

## Analyse d'un smart-contrat

Prenons comme exemple le smart-contrat de la propriété, évoquée dans le chapitre précédent.

<figure><img src="../../.gitbook/assets/image (171).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/image (74).png" alt=""><figcaption></figcaption></figure>

1. Adresse du smart-contrat qui gère les RelaToken de la propriété,
2. Onglet pour accéder au détail du contrat,
3. Sélection pour lire les informations du contrat,
4. Informations du contrat interrogeable (en lecture),\
   Par exemple, la quantité de ce token dans un\
   &#x20;wallet (celui du chapitre précédent) : \
   ![](<../../.gitbook/assets/image (180).png>)
5. Sélection pour modifier le contrat,\
   Il faudra alors vous connecter avec un wallet, pour approuver les modifications.
6. Adresse des RealTokens correspondants à cette propriété

Concernant le smart-contrat du Realtoken :&#x20;

<figure><img src="../../.gitbook/assets/image (193).png" alt=""><figcaption></figcaption></figure>

1. Nombre de RealToken pour cette propriété,
2. Onglet pour accéder aux informations sur les wallets qui possèdent ce RealToken,
3. Nombre de wallet qui détiennent ce RealToken,
4. Adresse des wallets qui détiennent ce RealToken avec la quantité.

## Analyse d'un Token

Par exemple, pour le token SOON : pour voir [l'historique de vos versements](broken-reference).
