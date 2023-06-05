**SGBD**:
De manière général :
    • Qu’est ce qu’un SGBD ? 
    Un système de gestion de base de données (SGBD) est un logiciel système permettant aux utilisateurs et programmeurs de créer et de gérer des bases de données.
    
    • Qu’est-ce qu’un système d’information ? 
    Le système d’information (SI) est un ensemble de ressources et de dispositifs permettant de collecter, stocker, traiter et diffuser les informations nécessaires au fonctionnement d’une organisation (administration, entreprise…).
    
    • Qu’est-ce qu’une base de données ? 
    Une base de données est un ensemble d'informations qui est organisé de manière à être facilement accessible, géré et mis à jour. Elle est utilisée par les organisations comme méthode de stockage, de gestion et de récupération de l’informations.
    
    • Citez les différences entre ces éléments. 
    SGBD créé et gere les bases de données
    SI collecte, stocke, traite et diffuse les informations 
    Base De Donnéés permet de gerer et de mettre a jour ces données et ces informations



Pour un MCD (Modèle Conceptuel de Données) :
    • Qu’est ce qu’un MCD et pourquoi est-ce que cela existe ?
    Un modèle conceptuel de données (MCD) pour une base de données permet d’identifier les principales entités à représenter, leurs relations et leurs attributs, et d’analyser la structure conceptuelle du    système d’information.
    
    • Comment représenter une entité ?
    Les classes d'entités sont représentées par un rectangle. Ce rectangle est séparé en deux champs 
    
    • Comment représenter une liaison entre des entités ?
    Par des traits qui les relie
    
    • Où mettre les données qui composent nos entités ?
    Dans les rectangles
    
    • Quels sont les différents types de cardinalité possibles ? Où les placer dans notre schéma ?
    Les cardinalités possibles sont :

    0,1 : au minimum 0, au maximum 1 seule valeur (CIF) ;
    1,1 : au minimum 1, au maximum 1 seule valeur (CIF) ;
    0,n : au minimum 0, au maximum plusieurs valeurs ;
    1,n : au minimum 1, au maximum plusieurs valeurs.
    On les places sur les ligne pour faire les liaisons

    • Citer quelques bonnes pratiques de normalisation.
    Critères de choix entité ou association
    Une entité a une existence propre et a un identifiant.
    Une association n’existe que si ces extrémités existent et n’a pas d’identifiant propre.
    Une entité peut être associée à d’autres entités , une association non.

    • A quoi servent les clés primaires ?
      La clé primaire est l’un des outils principaux des bases de données (BDD) relationnelles. Elle permet d’identifier de façon unique chaque enregistrement d’une table. De plus, les clés primaires mettent en r     relation les différentes tables dans la base de données.





Pour un MLD (Modèle Logique de Données) :
    • Comment passer d'un MCD au MLD ? 
    
    Règle numéro 1 : 
    a) Une entité du MCD devient une relation, c’est à dire une table.
    b) Son identifiant devient la clé primaire de la relation. 
    c) Les autres propriétés deviennent les attributs de la relation. 
    
    Règle numéro 2 :
Une association de type 1:N (c’est à dire qui a les cardinalités maximales positionnées à « 1 » d’une côté de l’association et à « n » de l’autre
côté) se traduit par la création d’une clé étrangère dans la relation correspondante à l’entité côté « 1 ».
Cette clé étrangère référence la clé primaire de la relation correspondant à l’autre entité. 
    
    Règle numéro 3 :
Une association de type N :N (c’est à dire qui a les cardinalités maximales positionnées à « N » des 2 côtés de l’association) se traduit par la
création d’une table dont la clé primaire est composée des clés étrangères référençant les relations correspondant aux entités liées par
l’association.
Les éventuelles propriétés de l’association deviennent des attributs de la relation. 
    
https://www-igm.univ-mlv.fr/~chochois/RessourcesCommunes/BDD/Modelisation/coursMLD.pdf



Que deviennent les associations ?
Elles sont traduite



