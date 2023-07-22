# public-idsa
Public readme for project IDSA (Intelligent Defences Schduling Application)

![Logo](https://drive.google.com/file/d/1kS3ygqJcn88AxLq4TQgGAT1CBMQoC9bl/view?usp=drive_link)

IDSA est une application web de planification des soutenances destinée à aider l’administration
d’IFRI à organiser au mieux les soutenances. Elle permet par exemple de détecter automatiquement
si un enseignant est programmé 2 fois à la même heure, de générer automatiquement le programme
des soutenances.

Pour la réalisation de l’application web, nous avons utilisé plusieurs technologies. Ces différentes
technologies sont organisées en trois catégories : le Front-end, le Back-end et le déploiement.

## En front-end
Nous avons utiliser le framework **Vuejs**

## En back-end
* les framework Django`et Django Rest`Framwork
* la librairie **OR-Tools** de Google
* le SGBDR **MariaDB**

## Pour le déploiement
Nous avons opté pour les services Cloud:
* AWS Lambda
* API Gateway

La valeur ajoutée d’une telle application est d’abord de planifier et de maintenir un suivi rigoureux
des soutenances. Il permet aussi de trouver les enseignants qui correspondent le mieux pour être
membre du jury sur un mémoire de soutenance. Pour cela, il se base sur les disponibilités des enseignants,
des salles, ainsi que les compétences respectives des enseignants.
