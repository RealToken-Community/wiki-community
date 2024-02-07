# La liquidation

Le mécanisme de Liquidation garantie le bon fonctionnement du RMM. \
Lorsque le collatéral d'un wallet n'est plus suffisant pour garantir ses emprunts, il passe automatiquement en mode liquidation (cf détail dans le [tuto](./)).\
Un liquidateur peut alors acheter, avec une décote, tout ou partie du collatéral du wallet en liquidation, le paiement servant à rembourser l'emprunt.

La liquidation est ouverte à tout les wallets whitelistés. Ce peut être une autre façon d'acquérir des RealTokens avec réduction.

La liste des Wallets proches de la liquidation, est accessible dans un des [onglets du RMM](https://liquidation.rmm.realt.community/). Lorsque vous voyez un Health Factor très proche de 1, il peut être intéressant d'évaluer le moment de la liquidation (si le wallet reste inactif!)

## Evaluation du moment de liquidation

Prenons l'exemple suivant :

<figure><img src="../../.gitbook/assets/image (182).png" alt=""><figcaption></figcaption></figure>

Pour calculer le délais avant liquidation, il faut disposer de deux informations sur le wallet :

* Le montant en collatéral : visible ci-dessus 7 717,038$
*   Le montant emprunté :

    Pour ce faire, deux approches sont possibles  :&#x20;

    * soit par calcul (approximatif) à partir des chiffres visible ci-dessus \
      &#x20;7 717,038$ \* 70% _(seuil de liquidation)_ / 1,013 _(Health Factor)_ = 5 332,60$
    * soit par interrogation de  l’explorateur (cf dernier paragraphe du [tuto RMM](./)), qui donne alors le chiffre : 5 330,56$                                                                         &#x20;

Si le wallet est inactif, l'évaluation du nombre de jours avant la liquidation, se calcul comme suit :&#x20;

* Le seuil de liquidation étant de 70 % (pour un collatéral avec que des RealToken) : le wallet deviendra liquidable lorsque le montant emprunté sera supérieur à : \
  7 717,04 \* 70 % = 5 401,93$,
* La différence avec le montant emprunté actuellement est : 5 401,93 – 5 330,56 = 71,53$,
* Avec un taux d’emprunt de 6 % / an, les frais journaliers de l’emprunt sont : 5 330,60$ \* 6 % / 365 jours = 0,876 $/j
* Pour simplifier, considérons que le montant des intérêts journaliers est constant (le calcul exact devrait tenir de la composition des intérêts…).\
  Le nombre de jour pour atteindre la liquidation est donc : 71,53 / 0,876 = 82 jours

Conclusion : Si le propriétaire de ce wallet ne fait rien, il deviendra liquidable dans 82 jours.

{% hint style="warning" %}
Avec un seul type de RealToken en collatéral, la liquidation pourrait aller jusqu’à 4244$ ! .. (soit 50 % du collatéral \* (1+ 10 % de pénalité de liquidation)).

Ce montant pourrait être bien moindre, si le collatéral avait été réparti sur de multiples types de RealTokens (la liquidation se faisant RealToken par RealToken, jusqu’à HF > 1)
{% endhint %}

## Liquidations effectuées

Liste des liquidations sur le RMM : \
\
[https://docs.google.com/spreadsheets/d/1ksmZyjVRWi4ART3yIWczOtFE-jucIxcRCULDRYkq1Bs/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1ksmZyjVRWi4ART3yIWczOtFE-jucIxcRCULDRYkq1Bs/edit?usp=sharing)

<figure><img src="../../.gitbook/assets/image (1) (1).png" alt=""><figcaption></figcaption></figure>
