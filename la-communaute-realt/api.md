# API

Les informations, concernant les propriétés tokenisés par RealT, sont fournies à l’origine (off-chain) : soit sur le site web Realt.co, soit au travers d’une Interface (API).

RealT fourni les données et la Communauté à mis en en place une application API pour les distribuer.

Ainsi, d’autres applications développées par la Communauté, peuvent utiliser à ces informations au travers de requêtes sur l’API.

## L’application API

L’application est constituée de son code ainsi que d’une application web de documentation, basée sur la solution _NelmioApiDocBundle._ Elle est disponible à l’adresse suivante : [https://api.realt.community/](https://api.realt.community/)\


<figure><img src="../.gitbook/assets/image (1).png" alt="" width="563"><figcaption></figcaption></figure>

Lorsque l’information recherchée est simple, par exemple la date de la dernière mise à jour, il suffit de cliquer sur le « GET » correspondant, puis « Try it out », puis « Execute » , le résultat s’affiche dans la partie « Response body »

<figure><img src="../.gitbook/assets/image (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

Par contre quand le résultat est une liste d’informations bien plus conséquente, comme la liste de tous les Realtokens émis, la présentation du résultat au format JSON, est bien moins lisible... sauf pour une application.

## Niveau de détail

L’API fournie de base, un nombre d’informations limité :

Par exemple pour /v1/token (une dizaine d’info. par RealToken)

<figure><img src="../.gitbook/assets/image (2).png" alt="" width="461"><figcaption></figcaption></figure>

Si vous souhaitez obtenir bien plus d’informations (> 150 par Realtoken), vous devez obtenir et utiliser une API-key :

<figure><img src="../.gitbook/assets/image (3).png" alt="" width="563"><figcaption></figcaption></figure>

Le google sheet suivant, vous donne un exemple de l’ensemble des informations disponibles pour un RealToken si vous utilisez l’API-Key : [https://docs.google.com/spreadsheets/d/1B\_5sPNW6sVDnYDQmAaTfaakN3aG6e1WZa5-VAx3LDsY](https://docs.google.com/spreadsheets/d/1B\_5sPNW6sVDnYDQmAaTfaakN3aG6e1WZa5-VAx3LDsY/edit?usp=sharing)

## API-Key

Pour l’obtenir, vous devez remplir le formulaire suivant :[https://docs.google.com/forms/d/e/1FAIpQLSf20z9fooLlq7tJTrUM4ESRlGRaqXun1wHLz5UscsF2xkdhfg/viewform](https://docs.google.com/forms/d/e/1FAIpQLSf20z9fooLlq7tJTrUM4ESRlGRaqXun1wHLz5UscsF2xkdhfg/viewform)

* Email et Username : servent à vous joindre, si nécessaire par mail ou Telegram,
* Ethereum Address : servira pour accéder à l’Application en mode Web3 (fonction prochainement disponible),
* Application name : juste pour information (et détecter d'éventuels doublons)
* Referer / Source IP : Information optionnelle pour sécuriser l’usage de l’API-Key (pour le cas où la clé serait visible dans votre application). Si une adresse est mentionnée, la requête API devra être envoyée depuis cette adresse.

## Seuils et DAO

L’usage de l’API-Key permet actuellement, de simplement donner accès à plus d’informations.\
Son usage pourra à l’avenir être étendu : par exemple via un seuil d’activité (quota), au-delà duquel l’usage de l’API serait payant.

L’application API fera partie du patrimoine de la DAO.\
Ainsi , la facturation au-delà de certains seuils (nombre de requêtes, niveau d’information, ..) sera une décision de la DAO pour lui apporter une source complémentaire de financement.

## Formats des requêtes

Elles sont visible dans cette partie de l’application :

*   Sans API-Key&#x20;

    <figure><img src="../.gitbook/assets/image (4).png" alt="" width="340"><figcaption></figcaption></figure>
*   Avec API-Key\
    Après l’avoir saisie dans la partie Authorize de l’application (le cadenas apparaîtra alors en position fermée)

    <figure><img src="../.gitbook/assets/image (5).png" alt="" width="231"><figcaption></figcaption></figure>

    Le format de la requête inclus votre APY-Key :

    <figure><img src="../.gitbook/assets/image (6).png" alt="" width="450"><figcaption></figcaption></figure>
