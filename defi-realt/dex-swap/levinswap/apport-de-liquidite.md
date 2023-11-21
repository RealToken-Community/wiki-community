# Apport de liquidité

Pour apporter de la liquidité à une paire, vous devez lui transférer les deux tokens avec la parité en cours sur la paire. Vous recevrez en échange un token LP (Liquidity Provider), qui sera votre preuve de dépôt et qui vous permettra de toucher une quote-part des frais de swap.

{% embed url="https://youtu.be/nRphv86nDjI" %}

La vidéo montre, comment apporter de la liquidité : vous indiquez une quantité pour l'un des tokens et l'autre s'ajuste automatiquement avec la parité de la pool.\
Ici la parité reste constante, quelque soit les montants apportés. Par contre, le pourcentage que vous posséderez de la pool, lui évolue.\
En ajoutant de la liquidité, vous gagnez 0,25 % des transactions sur la paire, proportionnellement à votre part dans le pool. Les frais de swap s'accumulent  dans le pool et peuvent être réclamés en retirant vos liquidités.\
Nota : La différence avec les 0,3% (évoqué dans la page précédente), sert a financer le protocole.

### Traitement des loyers des Realtokens dans une pool

RealT distribue le loyer de l'ensemble des RealTokens d'une paire, aux apporteurs de liquidité, à l'exclusion de RealT lui même. Ce dernier point constitue pour RealT, une façon de rémunérer les apporteurs de liquidité, en complément des frais (très faibles) sur les swap.

Analysons, à partir d’un exemple, l’impact financier pour un apporteur de liquidité.\
Il faut au préalable, trouver la répartition de la paire entre holders :&#x20;

{% embed url="https://youtu.be/QIK4zV7NLF4" %}

Dans la vidéo, la paire contient 29 RealTokens.\
Imaginons que vous soyez le wallet qui se termine par f4b2 : vous possédez alors 5 % de la pool et donc des 29 RealTokens (ainsi que du montant USDC de la pool).\
RealT (qui initialise les pools avec 20 Realtokens et les USDC correspondants) possède actuellement 69 % de la pool.

Comme évoqué précédmemment, lorsque RealT va distribuer les loyers aux holders de cette pool, le wallet f4b2 touchera les loyers de 16 % (= 5 % / (1- 66%)) des Realtokens de la pool (puisque RealT ne se verse pas de loyer à lui même).

Il faut minorer ce surplus de loyer, par le fait que vous avez aussi apporté des USDC avec vos RealTokens et ces USDC auraient pu rapporter des loyers....

Vous trouverez, dans le tableur ci-après, une synthèse financière comparant un investissement en apport de liquidité à un investissement avec le même montant mais uniquement en Realtokens.

<figure><img src="../../../.gitbook/assets/image (248).png" alt=""><figcaption><p><a href="https://docs.google.com/spreadsheets/d/1L3ogld67t3-G9J9Lb9rMwVI4JqUIRLD3TDpQ55dUNeo/edit?usp=sharing">https://docs.google.com/spreadsheets/d/1L3ogld67t3-G9J9Lb9rMwVI4JqUIRLD3TDpQ55dUNeo/edit?usp=sharing</a></p></figcaption></figure>

Le surplus de loyer dépend de nombreux facteurs. Vous pouvez télécharger le tableur et le personnaliser à votre cas.\
Les loyers des RealTokens, déposés sur des pool Levinswap, apparaitront sur des lignes à part dans votre mail hebdomadaire de loyer.
