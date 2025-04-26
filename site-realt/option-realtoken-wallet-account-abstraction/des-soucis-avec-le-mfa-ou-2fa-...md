# des soucis avec le MFA (ou 2FA)..

## C'est quoi, ca m'apporte quoi ?

Le MFA, multiple facteurs d'authentification (ou 2FA, second facteur d'authentification) est un dispositif de sécurité pour protéger l'accès à votre Realtoken Wallet. Comme souvent avec les dispositifs de sécurité, il nous protège mais au prix de contraintes supplémentaires....\
\
Le MFA vous est proposé lors de la[ création de votre Realtoken Wallet](creation-du-realtoken-wallet-a-la-creation-dun-compte-realt.md), il est optionnel (en cliquant sur "Skip for now"), et vous ait reproposé à chaque connexion à votre wallet.

<figure><img src="../../.gitbook/assets/image (322).png" alt="" width="238"><figcaption></figcaption></figure>

* Sans cette protection :  votre authentification est stockée chez un prestataire (Web3 Auth), certes de façon sécurisé mais vous êtes dépendant du prestataire.
* Avec cette protection : votre authentification est répartie entre le prestataire, votre équipement et un moyen de récupération.\
  Ainsi les informations chez le prestataire ne suffisent pas pour une connexion à votre wallet, il faut en plus celle de votre équipement ou de récupération.\
  Le social login de récupération, vous protégeant contre la perte de votre équipement.

Les informations MFA stockées sur votre équipement sont en fait stockées sous forme de cookies sur votre navigateur. **Si vous changer d'équipement, de navigateur ou que vous effacer vos cookies, vous devrez vous servir du social login de récupération**.\
Souvenez vous, lors de la création du 2FA, vous avez du cocher ce message :&#x20;

<figure><img src="../../.gitbook/assets/image (321).png" alt="" width="322"><figcaption></figcaption></figure>

## Connexion avec le MFA

Si vous avez activé le MFA et que l'application ne trouve pas le cookie correspondant sur votre navigateur, elle va vous afficher l'ecran suivant "New device detected" :

<figure><img src="../../.gitbook/assets/image (323).png" alt="" width="221"><figcaption></figcaption></figure>

Vous devez alors cliquer sur "Social Factor", pour vous connecter avec le social login de récupération (différent ce celui indiqué après "Social login" sur l'image ci-dessus),  que vous avez indiqué lors de la création du MFA.\
Une fois l'authentification avec le second facteur réussit, il vous sera proposé de sauvegarder cette authentification sur votre équipement  (ce qui évitera d'avoir a réutiliser le MFA, lors de la prochaine connexion avec cet équipement).

<figure><img src="../../.gitbook/assets/image (324).png" alt="" width="201"><figcaption></figcaption></figure>

Si vous avez perdu votre second login de récupération ou qu'il ne fonctionne pas, vous devrez alors demander au support RealT (bulle orange sur realt.co) une réinitialisation de votre accès à votre Realtoken Wallet.
