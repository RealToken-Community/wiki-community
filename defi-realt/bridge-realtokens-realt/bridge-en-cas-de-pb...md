# Bridge, en cas de Pb..

Le bridge est une opération qui se déroule en 2 temps :&#x20;

1. Une première transaction (sur la chaine source) d'envoi de vos RealTokens vers le Bridge,&#x20;
2. Après validation par le Bridge : Une seconde transaction (sur la chaine cible) de reception de vos RealTokens vers votre wallet.

Si la première transaction échoue, c'est pas trop grave car vos tokens n'ont pas été transmis au Bridge.\
Par contre, si vous rencontrez des problèmes lors de la seconde transaction, vous etes dans la situation plus délicate car vos RealTokens sont coincés dans le Bridge !....

Le cas le plus complexe, est celui d'un brige de Gnosis vers Ethereum, qui nécessite un Claim :&#x20;

* Soit vous n'arrivez pas à lancer le claim depuis l'application : la solution est alors de le faire à partir de l'explorateur directement sur le smartcontract.\
  L'adresse du contrat mediator, qui gère la logique du Bridge, est : ....(à compléter suite au déploiement) ...
*   Soit le claim a été lancé, mais n'aboutie pas :

    <figure><img src="../../.gitbook/assets/image (21).png" alt="" width="218"><figcaption></figcaption></figure>

    Une procédure pour annuler totalement le bridge et vous faire restituer vos RealTokens sur la chaine source, est alors a mis à disposition dans l'historique via le statut "Help".\


    <figure><img src="../../.gitbook/assets/image (15).png" alt="" width="563"><figcaption></figcaption></figure>

    Une fois réalisée, le statut de l'opération de Bridge sera "Recovered"

    <figure><img src="../../.gitbook/assets/image (22).png" alt="" width="563"><figcaption></figcaption></figure>
