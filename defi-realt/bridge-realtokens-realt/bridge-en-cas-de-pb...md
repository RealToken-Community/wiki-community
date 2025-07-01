# Bridge, en cas de Pb..

Le bridge est une opération qui se déroule en 2 temps :

1. Une première transaction d'envoi (sur la chaine source), de vos RealTokens vers le Bridge,
2. Après validation par le Bridge : Une seconde transaction de réception (sur la chaine cible), de vos RealTokens vers votre wallet.

Si la première transaction échoue, c'est pas trop grave car vos tokens n'ont pas été transmis au Bridge.\
Par contre, si vous rencontrez des problèmes lors de la seconde transaction, vous êtes dans une situation plus délicate car vos RealTokens ont été transmis au Bridge !....

Une procédure pour annuler totalement le bridge et vous faire restituer vos RealTokens sur la chaine source, est alors mise à disposition dans l'historique via le statut "Help".\\

<figure><img src="../../.gitbook/assets/image (8) (1).png" alt="" width="563"><figcaption></figcaption></figure>

Une fois réalisée, le statut de l'opération de Bridge sera "Recovered"

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

La restitution est un peu plus complexe dans le cas d'un brige de Gnosis vers Ethereum, qui nécessite un Claim :

* Soit vous n'arrivez pas à lancer le claim depuis l'application : la solution est alors de le faire à partir de l'explorateur directement sur le smartcontract. L'adresse du contrat mediator, qui gère la logique du Bridge, est : ....(à compléter suite au déploiement)
*   Soit le claim a été lancé, mais n'aboutie pas :

    <figure><img src="../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="218"><figcaption></figcaption></figure>
