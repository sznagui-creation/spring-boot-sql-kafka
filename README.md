# spring-boot-sql-kafka

Dans le cadre de la modernisation du SI d'une entreprise de jeux d'argent vers une architecture événementielle, Nous développons un nouveau microservice responsable du cycle de vie d’une course de chevaux et de ses partants (chevaux).

Les contraintes métier sont les suivantes : 

• Une course a lieu un jour donné et possède un nom et un numéro unique pour ce jour ; 

• Une course possède au moins 3 partants ; 

• Chaque partant possède un nom et un numéro ; 

• Les partants d’une course sont numérotés à partir de 1, sans doublon ni trou. 

V1.0 :

• Création d'une API permettant de créer des courses et leurs partants, de stocker les informations en base de données et de les exposer au reste du SI par un message publié sur un bus. 
 
