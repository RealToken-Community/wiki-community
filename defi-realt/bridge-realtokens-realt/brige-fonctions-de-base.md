# Brige, fonctions de base

Transférer vos RealTokens d'une chaine à une autre, avec ce Bridge, est assez simple.

Document publié par RealT, lors de la mise en production : [https://rebrandly.realt.co/bia](https://rebrandly.realt.co/bia)

Mode opératoire (élaboré lors des tests) :&#x20;

{% hint style="info" %}
Si l'adresse cible n'est pas identique à l'adresse source, vous devez demander au préalable son whitelisting.
{% endhint %}

1.  Se connecter avec son wallet, en étant sur la chaine source (Ethereum, par ex),

    <figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="211"><figcaption></figcaption></figure>
2.  Sélectionner la propriété de votre wallet que vous souhaitez transférer :\
    (vous pouvez en sélectionner plusieurs, dans la limite de 6, en cochant les cases en tête de liste)

    <figure><img src="../../.gitbook/assets/image (3) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="168"><figcaption></figcaption></figure>
3.  Indiquer la quantité des RealTokens sélectionnés, à transférer :

    <figure><img src="../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="290"><figcaption></figcaption></figure>
4. Si vous souhaitez bridger vers un autre wallet (qui doit etre whitelisté) : indiquer son adresse ("reception personnalisée"),
5.  Transférer, en validant la transaction avec les frais correspondants (à votre charge).

    <figure><img src="../../.gitbook/assets/image (7) (1) (1) (1) (1).png" alt="" width="327"><figcaption></figcaption></figure>
6.  Un message confirme l'envoi sur la chaine source (avec les coordonnées de la transaction correspondante) :

    <figure><img src="../../.gitbook/assets/image (26).png" alt="" width="216"><figcaption></figcaption></figure>
7.  Actualiser votre navigateur, puis aller dans "Historique",\
    Vous constatez que vous êtes "En attente de confirmations" (mécanisme interne du Bridge, qui peut prendre un moment..) :

    <figure><img src="../../.gitbook/assets/image (9) (1).png" alt="" width="563"><figcaption></figcaption></figure>
8. La suite dépend de la chaine cible :

*   Dans le **sens Ethereum vers GnosisChain** : une transaction transferera automatiquement le RealToken sur votre wallet (dans History, le statut passera à "Complété")

    <figure><img src="../../.gitbook/assets/image (10) (1).png" alt="" width="563"><figcaption></figcaption></figure>
*   Dans le **sens GnosisChain vers Ethereum** : à cause des frais de réseau, la livraison sur Ethereum ne sera pas automatique et necessitera une opération de claim (dans Historique, le statut sera à "Réclamer")

    <figure><img src="../../.gitbook/assets/image (29).png" alt="" width="563"><figcaption></figcaption></figure>

    * Pour transférer le Realtoken vers votre wallet sur Ethereum (Claim),
      * vous devez au préalable vous mettre sur Ethereum,
      * vous devez valider la transaction avec les frais correspondants (à votre charge),
      *   la transaction apparaitra dans l'historique avec le statut "Réclamé"

          <figure><img src="../../.gitbook/assets/image (30).png" alt="" width="563"><figcaption></figcaption></figure>

## Exemples en vidéo :

* Bridge de RealTokens dans le **sens Ethereum vers Gnosis :**

{% embed url="https://youtu.be/v90YyqqXWGg" %}

* Bridge de RealTokens dans le **sens Gnosis vers Ethereum** :

{% embed url="https://youtu.be/HN91aCaL-LQ" %}
