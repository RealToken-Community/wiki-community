---
description: >-
  comment contrôler les autorisations que vous avez accordées  à des smart
  contrats sur vos jetons.
---

# Autorisations de dépense sur vos jetons

Lors de vos transactions, vous donnez des autorisations à des smart contrats pour accéder et déplacer vos jetons.&#x20;

Pour avoir la liste de ces autorisations (Allowance) vous pouvez utiliser l'application : [https://revoke.cash/](https://revoke.cash/)

<figure><img src="../.gitbook/assets/image (126).png" alt=""><figcaption></figcaption></figure>

Connecter votre Wallet, choisissez le bon réseau.&#x20;

La liste des Jetons, sur ce wallet et sur ce réseau apparaitra avec:  les autorisations qui ont été données, pour quel montant, pour quel smart contrat et quand.

Il vous est possible d'annuler cette autorisation (bouton Revoke en bout de ligne), ou de réduire celle-ci (crayon au milieu de la ligne).&#x20;

Ces modifications sont enregistrées sur la blockchain, donc supportent des frais de réseau (modiques pour Gnosis).

{% hint style="info" %}
L'usage d'un Cold wallet ne vous protège pas contre une autorisation donnée à un smart contrat corrompu. Limiter ces autorisations, complète donc votre protection.
{% endhint %}

Le choix des allocations à révoquer est un compromis entre sécurité et commodité. Car lorsque le smart contrat aura à nouveau besoin d'accéder à votre jeton il devra à nouveau obtenir l'autorisation de votre part (avec les frais de réseau associé).
