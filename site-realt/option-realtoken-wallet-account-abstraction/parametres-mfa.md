# Paramètres MFA

En mars 2026, une nouvelle possibilité est apparue sur l'application Realtoken Wallet, celle de gérer les paramètres du MFA via l'accès au dashboard Web3Auth :

<figure><img src="../../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

Le tableau de bord n'apparait que si vous avez activé l'option MFA :

<figure><img src="../../.gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure>

Vous y trouverez les informations / possibilités suivantes :&#x20;

1. Le Social login que vous utilisez pour vous connecter à votre Realtoken Wallet (ici un compte Google),\
   Avec le niveau de sécurité associé, suivant le nombre de moyen de récupération activés. Pour être au maximum, il faut en avoir deux)
2. Le social login de récupération, activé lors de l'initialisation du MFA (ici un compte Discord),
3.  Facteur supplémentaire de récupération, via une Phrase de récupération.\
    Cette phrase est générée automatiquement par web3auth. Vous pouvez vous la copier, vous la faire envoyer à un mail ou la télécharger.\
    Une fois activée, le dashboard se présentera comme suit :&#x20;

    <figure><img src="../../.gitbook/assets/image (2).png" alt="" width="328"><figcaption></figcaption></figure>

    et vous pourrez l'utiliser lors d'une connexion sur un nouvel environnement.
4. Liste des appareils sur lesquels vous avez sauvegardé votre connexion.\
   La suppression d'un appareil vous empêchera d'utiliser cet appareil pour vous authentifier et accéder à votre compte. Vous devrez alors utiliser un facteur de récupération.
5.  Facteur supplémentaire de récupération, via un mot de passe.\
    Une fois activé, lors d'une connexion sur un nouvel environnement la fenètre "New device detected" fera apparaitre cette nouvelle possibilité<br>

    <figure><img src="../../.gitbook/assets/image (4).png" alt="" width="199"><figcaption></figcaption></figure>
6. Facteur supplémentaire de récupération, via une Passkey\
   Vous pourrez utiliser soit une clé de sécurité (sur un PC) soit un smartphone, comme clé de récupération.
7. Facteur supplémentaire de récupération, via une application d'authentification.\
   Vous utiliserez alors un moyen semblable à ce que vous utilisez pour vous connecter en [2FA sur le site Realt.co](../acces-en-2fa-a-votre-compte.md)
