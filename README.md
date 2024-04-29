# AGLprojectSpécifications du projet :
a) Notions de base et contraintes du projet :
Les systèmes domotiques se basent sur l'utilisation de capteurs, d'actionneurs et de
contrôleurs pour surveiller l'environnement domestique et prendre des décisions en fonction
des données collectées.

Par exemple, un capteur de mouvement peut détecter la présence de personnes dans une
pièce et réguler automatiquement l'éclairage.
La domotique permet un contrôle à distance via des appareils tels que les smartphones,
tablettes ou ordinateurs, offrant ainsi aux utilisateurs la possibilité de gérer leurs
équipements même lorsqu'ils sont absents.

Les contraintes peuvent être des obstacles à ces notions de ce système, tels que :
![438083339_392355316958846_3219458332132396786_n](https://github.com/nouhabennasr/AGLproject/assets/168307999/1d36b64e-5135-4ef1-9030-1fe005588f32)

● L’intégration étroite de capteurs (par exemple, capteurs de mouvement,
détecteurs de fumée) et d'une variété d’actionneurs (comme les lumières, les
serrures intelligentes).

● La nécessité de télécharger un programme informatique pour établir la
communication avec le système domotique et contrôler les appareils
connectés.

● La réactivité en temps réel du système pour garantir un contrôle et une
surveillance efficaces des équipements connectés, incluant des critères tels
que le temps de réponse, la gestion énergétique..

3
● La communication avec les dispositifs de manière cohérente et fiable, en
prenant en compte les protocoles de communication spécifiques à chaque
dispositif.

● La collecte, le traitement et l’analyse efficaces de grandes quantités de
données afin de fournir des fonctionnalités telles que l'automatisation des
tâches, la détection d'anomalies..

● La mise en œuvre des protocoles de sécurité robustes pour protéger les
données sensibles sur la vie privée et la sécurité des utilisateurs en transit et
au repos, ainsi que pour sécuriser l'accès aux appareils connectés.

● Le fonctionnement de manière fiable, même dans des conditions imprévues
ou en cas de défaillance d'un composant.

● Considération des besoins et des préférences des utilisateurs dans la
conception des interfaces utilisateur pour qu’elles soient conviviales, faciles à
utiliser et intuitives .

b) Description des acteurs et fonctionnalités attendues du projet :
Notre système domotique va offrir une gamme variée de fonctionnalités répondant aux
besoins et aux préférences individuels des utilisateurs.

Notre projet possède un seul type d’acteur qui est l’utilisateur


L’utilisateur : cet acteur a le droit de se servir de notre plateforme domotique à distance ou
localement en utilisant son téléphone portable ou bien son ordinateur. Il interagit avec le
logiciel via une interface utilisateur graphique (IHM).

Voici une description détaillée des fonctionnalités présentées :

● Contrôle de l'éclairage : possibilité d'allumer/éteindre des lumières.

● Gestion de l’économie de l'énergie : optimisation de la consommation énergétique en
régulant les équipements selon les besoins réels et en détectant les gaspillages.

● Surveillance de la maison, en temps réel et à distance : détection des intrusions, des
fuites d'eau, des incendies, etc., grâce à des capteurs et des caméras de surveillance
avec stockage des enregistrements ( dans le cloud ou sur un support local ) et
réception des alertes lors des scénarios anormaux ( via des appareils connectés sur
smartphone ou ordinateur par exemple ).

● Automatisation des tâches : la possibilité d’ouvrir/ fermer les portes et les volets, à
distance pour les visiteurs autorisés.
Test	1	2	3	4
Precondition				
Have an account	F	T	T	T
Internet connection	F	T	T	
Platform installed	F	T		
Postcondition				
Access to CasaControl control interface	F	F	F	T
Number of tests	1	1	1	1

![CAP][Uploading 438083339_392355316958846_3219458332132396786_n.jpg…]()


[domotique AGL Spécifications.pdf](https://github.com/nouhabennasr/AGLproject/files/15146254/domotique.AGL.Specifications.pdf)
[domotique-AGL-conception-préliminaire.pdf](https://github.com/nouhabennasr/AGLproject/files/15146264/domotique-AGL-conception-preliminaire.pdf)
[domotique-AGL-conception-détaillée.pdf](https://github.com/nouhabennasr/AGLproject/files/15146265/domotique-AGL-conception-detaillee.pdf)
[domotique AGL suite conception détaillée et préparation de tests unitaires.pdf](https://github.com/nouhabennasr/AGLproject/files/15146268/domotique.AGL.suite.conception.detaillee.et.preparation.de.tests.unitaires.pdf)
