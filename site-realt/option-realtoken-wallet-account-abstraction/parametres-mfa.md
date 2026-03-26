# Paramètres MFA

En mars 2026, une nouvelle possibilité est apparue sur l'application Realtoken Wallet : celle de gérer les paramètres du MFA via l'accès au dashboard Web3Auth :

<figure><img src="../../.gitbook/assets/image.png" alt="" width="563"><figcaption></figcaption></figure>

Le tableau de bord n'apparait que si vous avez activé l'option MFA :

<figure><img src="../../.gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure>

Vous y trouverez les informations / possibilités suivantes :&#x20;

1. Le Social login que vous utilisez pour vous connecter à votre Realtoken Wallet (ici un compte Google),\
   Avec le niveau de sécurité associé, suivant le nombre de moyens de récupération activés. Pour être au maximum, il faut en avoir deux.
2. Le Social login de récupération, activé lors de l'initialisation du MFA (ici un compte Discord), que vous pouvez modifier.
3.  Facteur supplémentaire de récupération, via une Phrase de récupération.\
    Cette phrase est générée automatiquement par web3auth. Vous pouvez vous la copier, vous la faire envoyer à un mail ou la télécharger.\
    Une fois activée, le dashboard se présentera comme suit :&#x20;

    <figure><img src="../../.gitbook/assets/image (2).png" alt="" width="328"><figcaption></figcaption></figure>

    et vous pourrez l'utiliser lors d'une connexion sur un nouvel environnement.
4. Liste des appareils sur lesquels vous avez sauvegardé votre connexion.\
   La suppression d'un appareil vous empêchera d'utiliser cet appareil pour vous authentifier et accéder à votre compte. Vous devrez alors utiliser un facteur de récupération.
5.  Facteur supplémentaire de récupération, via un mot de passe.\
    Une fois activé, lors d'une connexion sur un nouvel environnement la fenêtre "New device detected" fera apparaitre cette nouvelle possibilité<br>

    <figure><img src="../../.gitbook/assets/image (4).png" alt="" width="199"><figcaption></figcaption></figure>
6. Facteur supplémentaire de récupération, via une Passkey\
   Vous pourrez utiliser soit une clé de sécurité (sur un PC) soit un smartphone, comme clé de récupération.\
   Comme pour le mot de passe, cette nouvelle possibilité apparaitra dans le menu "New device detected"
7. Facteur supplémentaire de récupération, via une application d'authentification.\
   Vous utiliserez alors un moyen semblable à ce que vous utilisez pour vous connecter en [2FA sur le site Realt.co](../acces-en-2fa-a-votre-compte.md)\
   Comme pour le mot de passe, cette nouvelle possibilité apparaitra dans le menu "New device detected"

{% hint style="warning" %}
Pour améliorer la sécurité d'accès à votre Realtoken wallet, il est donc souhaitable d'ajouter au Social login de récupération (de base), un autre facteur de récupération parmi les différents possibles.
{% endhint %}

En résumé, avec un second facteur de récupération, l'authentification d'accès à votre Realtoken wallet est répartie à 4 endroits :&#x20;

* Social login de connexion (exemple compte google),
* Appareil (dans le navigateur),
* Social login de récupération (exemple compte discord),
* Second facteur de récupération (exemple phrase de récupération).

L'accès à votre Realtoken Wallet necessite :  la première information plus une des trois autres.<br>

A l'avenir RealT, pourrait ne plus supporter certain facteur de récupération (il suffira alors de les remplacer).
