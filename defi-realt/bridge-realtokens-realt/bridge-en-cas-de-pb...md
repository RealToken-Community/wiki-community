# Bridge, en cas de Pb..

Le bridge est une opération qui se déroule en 2 temps :

1. Une première transaction d'envoi (sur la chaine source), de vos RealTokens vers le Bridge,
2. Après validation par le Bridge : Une seconde transaction de réception (sur la chaine cible), de vos RealTokens vers votre wallet.

Si la première transaction échoue, c'est pas trop grave car vos tokens n'ont pas été transmis au Bridge.\
Par contre, si vous rencontrez des problèmes lors de la seconde transaction, vous êtes dans une situation plus délicate car vos RealTokens ont été transmis au Bridge !....

Une procédure pour annuler totalement le bridge et vous faire restituer vos RealTokens sur la chaine source, est alors mise à disposition dans l'historique via le statut "Help".\\

<figure><img src="https://community-realt.gitbook.io/~gitbook/image?url=https%3A%2F%2F1959376943-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQcs2CVc1dLNx1s027s4H%252Fuploads%252Fx25wDzY1RArm1LUwcLu5%252Fimage.png%3Falt%3Dmedia%26token%3D76cc1fcc-ea3d-428d-bd03-efe8ba3e51fd&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=a34e9591&#x26;sv=1" alt="" width="563"><figcaption></figcaption></figure>

Une fois réalisée, le statut de l'opération de Bridge sera "Recovered"

<figure><img src="https://community-realt.gitbook.io/~gitbook/image?url=https%3A%2F%2F1959376943-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252FQcs2CVc1dLNx1s027s4H%252Fuploads%252Fg3ULq7LqhMGAMEh0muRz%252Fimage.png%3Falt%3Dmedia%26token%3D183cdc1e-10d0-4a0a-89b3-0dcea0d60012&#x26;width=768&#x26;dpr=4&#x26;quality=100&#x26;sign=15abd52&#x26;sv=1" alt="" width="563"><figcaption></figcaption></figure>

La restitution est un peu plus complexe dans le cas d'un brige de Gnosis vers Ethereum, qui nécessite un Claim :

* Soit vous n'arrivez pas à lancer le claim depuis l'application : la solution est alors de le faire à partir de l'explorateur directement sur le smartcontract. L'adresse du contrat mediator, qui gère la logique du Bridge, est : ....(à compléter suite au déploiement)
*   Soit le claim a été lancé, mais n'aboutie pas :

    <figure><img src="../../.gitbook/assets/image (2).png" alt="" width="326"><figcaption></figcaption></figure>
