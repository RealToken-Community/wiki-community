# Montant des autorisations avec MetaMask

MetaMask a modifié la façon dont il traite les demandes d’approbation (préalable à tout transaction avec un smart contrat), il demande désormais aux utilisateurs de spécifier eux mêmes, la quantité de jeton dont ils souhaitent approuver l’utilisation.

Là où la démarche, emprunte de transparence, peut perturber l’utilisateur ; c’est que le montant affiché par défaut par MetaMask est le montant proposé par l’application (avec laquelle vous êtes en train de faire la transaction).

Hors, pour simplifier le parcours utilisateur, certaines applications proposent que l’approbation soit pour une quantité "illimitée" !…

Prenons comme exemple un dépôt de WXDAI sur le RMM : l’approbation MetaMask qui apparaît maintenant est la suivante, avec un chiffre très élévé (en rouge) pour le plafond :\
(Ce comportement est identique avec d'autres applications, comme 1inch par exemple)

<figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="361"><figcaption><p>Exemple de plafond "illimité" par défaut</p></figcaption></figure>

Vous avez alors trois options :&#x20;

1.  **Approuver en l’état**, sans modification du montant.

    Vous acceptez alors que le contrat RMM puisse utiliser un montant "illimité" de vos WXDAI. \
    Ce qui simplifiera votre prochain dépôt, puisque vous n’aurez plus besoin de faire cette étape d’approbation préalable…

    Vous pouvez vérifier votre approbation en allant sur [Revoke.cash](https://revoke.cash/), \
    (et éventuellement la revoquer, ce qui vous coutera des frais de transaction, que vous auriez pu éviter avec l'option 3)

    <figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption><p>Autorisation du wallet via Revoke.cash</p></figcaption></figure>
2.  **Cliquer sur « Max »**,

    Votre approbation sera alors limitée au montant dont vous disposez sur votre wallet.\
    Dans l’exemple : l’approbation sera pour 96,38 WXDAI alors que la transaction de dépôt n’est que de 10 WXDAI.

    <figure><img src="../.gitbook/assets/image (3) (1) (1) (1) (1).png" alt="" width="138"><figcaption></figcaption></figure>
3.  **Indiquer le montant de la transaction** \
    Cette solution est la plus sécurisée, puisque votre accord est limité au montant de la transaction, mais vous devrez refaire cette étape préalable d’approbation à chaque transaction.

    <figure><img src="../.gitbook/assets/image (4) (1) (1) (1) (1).png" alt="" width="154"><figcaption></figcaption></figure>

Référence sur le site [MetaMask](https://support.metamask.io/hc/en-us/articles/6055177143579-How-to-customize-token-approvals-with-a-spending-cap).

## Approbation par signature (Permit)

Un nouveau mode d'approbation (EIP-2612 ou Permit) se déploie progressivement : il est déjà utilisé sur le YAM et le sera sur RMM v3.&#x20;

<figure><img src="../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="291"><figcaption></figcaption></figure>

L'approbation est remplacée par une signature qui ne nécessite pas de transaction (donc pas de frais !)

<figure><img src="../.gitbook/assets/image (6) (1) (1) (1).png" alt="" width="275"><figcaption></figcaption></figure>

Cette solution est par ailleurs plus sécurisée, car :

* le montant signé est limité à la transaction ("value"),
* numéro d'ordre change à chaque signature ("nonce"),
* sa durée de validité est limitée dans le temps ("deadline").

Ce mode d'approbation :

* n'est possible que pour les tokens (et les protefeuilles) qui le supporte : soit l'USDC, mais pas encore de WXDAI.
* ne sera pas proposé (/accessible), si vous avez déjà fait une approbation "illimitée" (cf option 1, du chapitre ci-dessus) pour cette dAPP et ce token.
