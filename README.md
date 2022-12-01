# SecuBD
___
## **1. Types d’attaques**
___
En informatique, l’on parle d’attaque lorsqu’une personne exploite une faille ou une limite dans un système informatique. Les attaques sont classées en type :   
*	L’interception : c’est un type d’attaque qui consiste à intercepter les données circulant sur un réseau. Ce type d’attaque rassemble une attaque comme le sniffing passif : c’est le fait qu’un utilisateur malveillant espionne un réseau dans lequel il est situé.

*	L’interruption : C’est un type d’attaque qui touche la disponibilité de sorte à rendre un système inaccessible. Ici, nous pouvons citer le déni de service qui est une attaque qui consiste à submerger un serveur de trafics inutiles afin de le rendre hors service.

*   La modification : C’est un type d’attaque qui consiste à modifier un message. Elle porte atteinte à l’intégrité. On peut citer, l’attaque de l’homme du milieu (Man in the middle), elle a pour but de s’insérer entre deux ordinateurs qui communiquent. Dans ce cas, le pirate se fait passer pour l’ordinateur qui devrait recevoir le message afin de l’intercepter. 

*	Modification : C’est n type d’attaque qui porte atteinte à l’authenticité. C’est le fait d’insérer un message dans un réseau.

___
## **2. Attaques touchant les bases de données**
___
Certaines attaques touchent plus les bases de données que d’autres. Par exemple :
*	Le déni de service : Il peut être obtenu en profitant de la vulnérabilité d'une plate-forme de bases de données pour faire tomber un serveur. D'autres techniques communes de déni de service incluent la corruption de données, l'engorgement du réseau, et la surcharge en ressources du serveur (mémoire, unité centrale, etc.). La surcharge des ressources est une technique très commune dans les environnements de bases de données.

*	Injection SQL : Dans une attaque par injection SQL, l'auteur insère généralement (ou « injecte ») des informations de bases de données non autorisées dans une chaîne de données SQL vulnérable. Généralement les chaînes de données visées incluent les procédures enregistrées et les paramètres d'entrée des applications Web. Ces informations injectées sont ensuite envoyées vers la base de données où elles sont exécutées. En utilisant l'injection SQL, les auteurs d'attaques peuvent obtenir l'accès illimité à l'ensemble d'une base de données.

*	Elévation de privilège : Les auteurs d'attaques peuvent profiter des vulnérabilités des logiciels plate-forme de bases de données pour transformer les privilèges d'accès d'un utilisateur ordinaire en ceux d'un administrateur. Les vulnérabilités peuvent se trouver dans les procédures enregistrées, les fonctions intégrées, les implémentations de protocoles, voire même dans les données SQL

* Abus de privilège excessif : Lorsque les utilisateurs (ou les applications) ont des privilèges d'accès à une base de données excédant les exigences de leur fonction professionnelle, ils peuvent abuser de ces privilèges à des fins malveillantes. Par exemple, un directeur d'université dont la fonction n'exige que la capacité à modifier les coordonnées des étudiants peut profiter de privilèges de mise à jour de bases de données excessifs pour modifier les notes. L'utilisateur d'une base de données peut se retrouver avec des privilèges excessifs pour la simple raison que les administrateurs de bases de données n'ont pas le temps de définir ni de mettre à jour des mécanismes de contrôle granulaire des privilèges d'accès pour chaque utilisateur. Par conséquent, tous les utilisateurs ou les grands groupes d'utilisateurs ont des privilèges d'accès génériques définis par défaut qui excèdent largement les exigences de leur fonction spécifique.
___
## **3. Extensions des fichiers de données**
___

*	MySQL :  .frm, .MYD, .MYI .

*   SQL Server :  .mdf

*	Oracle :  .dbf

___
## **4. Définition de la politique de sécurité de l'INTSEC**
___

Les ITSEC définissent la politique de sécurité comme l’ensemble des lois règles ou pratiques qui régissent la façon dont l’information sensible et les autres ressources sont gérées, protégées et distribuées à l’intérieur d’un système d’information.
