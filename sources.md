Il semblerait que tu fasses référence à l'attaque majeure contre le protocole **Resolv**, qui a eu lieu hier, le **22 mars 2026**. C'est un cas d'école de ce que l'on appelle un "Infinite Mint Exploit" (exploitation d'impression infinie).

Voici les détails clés de cette affaire qui a secoué la DeFi ces dernières 24 heures :

### 1. Ce qui s'est passé (L'Exploit)

Le hacker a réussi à compromettre une clé privée privilégiée (appartenant au `SERVICE_ROLE`) stockée dans l'infrastructure cloud (AWS KMS) de Resolv.

* **Le "Mint" :** Avec cette clé, l'attaquant a pu contourner les vérifications normales de collatéral. Il a déposé seulement environ **200 000 $** en USDC, mais a utilisé la clé compromise pour autoriser la création de **80 millions de jetons USR** (le stablecoin de Resolv).
* **Le "Depeg" :** Le hacker a immédiatement déversé (dumpé) ces jetons non garantis dans les pools de liquidité (notamment sur Curve). Comme il y avait soudainement beaucoup trop de jetons USR par rapport aux réserves réelles, le prix s'est effondré, tombant jusqu'à **0,20 $** (soit une perte de 80 % de sa valeur).

### 2. L'impact sur les utilisateurs

Ce n'est pas seulement le prix qui a chuté. L'attaque a créé un effet domino :

* **Dilution massive :** Les détenteurs de USR ont vu la valeur de leurs actifs fondre instantanément.
* **Contagion DeFi :** Comme le USR était utilisé comme collatéral sur d'autres plateformes (comme Morpho), le depeg a forcé des liquidations en cascade. Certains opportunistes ont même acheté du USR à 0,20 $ pour essayer de rembourser des dettes comptabilisées à 1 $, drainant encore plus de liquidité.

### 3. Liens publics et sources

Tu peux suivre les analyses techniques et les mises à jour officielles via ces liens (ou en cherchant ces titres) :

* **Rapport de Chainalysis :** [The Resolv Hack: How One Compromised Key Printed $23 Million](https://www.chainalysis.com/blog/lessons-from-the-resolv-hack/) (Analyse détaillée du vol des clés).
* **Article de The Block :** [Resolv's USR stablecoin depegs after attacker mints 80 million tokens](https://www.theblock.co/post/394582/resolvs-usr-stablecoin-depegs-after-attacker-mints-80-million-unbacked-tokens-extracts-roughly-25-million).
* **X (ex-Twitter) :** Cherche les comptes de **ZachXBT** ou **PeckShieldAlert**, qui ont documenté les transactions on-chain en temps réel dès le début de l'attaque.

---

**As-tu des fonds bloqués sur ce protocole ou sur une plateforme liée ?** Si c'est le cas, je peux t'aider à vérifier si des formulaires de réclamation ou des plans de compensation ont été annoncés par l'équipe de Resolv Labs.
