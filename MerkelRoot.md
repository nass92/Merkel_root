## question 1: 
Si, dans le Merkel Root,  le nombre de transactions dans le Block à valider est impair alors on combine la dernière derniere transaction avec elle-même. 

ex : on a 6 transaction=> 


txA   -> hA
              ==> hAB
txB   -> hB
                        ==> hABCD
txC   -> hC
              ==> hCD
txD   -> hD                             ===> hABCDEFEF = racine de Merkel

txE   -> hE
              ==> hEF   ==> hEFEF
txF   ->hF


## question 2: 

Un nœud Bitcoin est en fait un simple dispositif de stockage, comme un ordinateur portable ou un PC avec accès à Internet, qui a la capacité de stocker la blockchain Bitcoin. Ces nœuds relaient les informations des utilisateurs aux mineurs. Ils conservent également la blockchain Bitcoin.

Les nœuds sont synchronisés les uns avec les autres. Même si un nœud est hors ligne pendant un certain temps, il téléchargera les dernières données des autres nœuds dès qu'il se connectera à nouveau à Internet.

## question 3 : 

Edward Snowden est un génie de l'informatique. il est aussi un adepte de la cryptographie. Etant un programmeur de la CIA et de la NSA pendant la creation de bitcoin, ce qui lui permettait de voir la réalité du monde dans lequel nous vivions. Avec son talent informatique et ses connaissances du monde réel, je pense qu'il a put influer sur de façon indirect voir meme direct sur le projet bitcoin. 

## question 4 : 

Un bloc est un ensemble organisé de transactions, qui contient un horodatage (l'heure et la date de validation) et une preuve (de travail, d'enjeu, d'autorité) inclus par le validateur. Les blocs sont liés entre eux à partir d'un premier bloc de référence, de sorte à former une chaîne, la chaîne de blocs.

## question 5 :

## question 6 :

Pour modifier  le contenu d'une transaction, il faut la modifier dans le block ou elle est inscrit. Si cela arrive, alors le Merkle root inscrit dans le block header ne sera plus valide. Pour reussir a faire ce genre d'operation, il faudrait détenir au moins 51% du hash du réseau. Aujourd'huit sur le réseau bitcoin, il est impossible de detenir 51% du hashrate, à moins de créer un cartel de pool de minage afin de controler le réseaux. 
Sur d'autre blockchain, par contre, il est possible de reussir une tel attaque (attaque des 51%). 
