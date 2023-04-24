
# SA5. Véhicule autonome : Gestion automatique de la traversée d’une intersection intelligente

## Description
Domaine Intelligence Artificielle Langage (proposé) C++, java Responsable du sujet Samir AKNINE Les récentes évolutions technologiques des dernières années ont permis d’améliorer le niveau d’équipement des véhicules rendus de plus en plus connectés, voire autonomes, ce qui permet de proposer de nouvelles réponses aux problèmes du trafic urbain. Les véhicules sont, à présent, capables de communiquer et de se coordonner. Avec notre projet, nous proposons une approche de régulation du trafic s’appuyant sur des méthodes distribuées pour améliorer les conditions de mobilité des véhicules. Dans le cadre ce travail, nous implémenterons la méthode de régulation que nous avons définie à l’échelle de l’intersection tirant parti des capacités de communication des véhicules, et dans laquelle les véhicules autonomes négocient leur droit de passage dans chaque intersection. Cette négociation s’effectue en utilisant des mécanismes prédéfinis en s’appuyant sur les données de mobilité de chaque véhicule et en permettant ainsi de prendre en compte différents critères pour la prise de décision locale, comme l’état général du trafic, la localisation d’éventuelles congestions, ou encore la circulation des bus, les trajets programmés par les véhicules, etc

## Contributeurs
Voici notre équipe, vous pouvez nous contacter via notre LinkedIn :
- [Salah Eddine Ait Allaoua](https://www.linkedin.com/in/salah-eddine-ait-allaoua-b62249153/).
- [Thibault Stanislas]().
- [Tran Anh Duy NGUYEN](https://www.linkedin.com/in/nguyentrananhduy/).
- [Minh Quang CAO](https://www.linkedin.com/in/minh-quang-cao-5a3270257/).


## Diagramme
![Diagramme V0 drawio](https://user-images.githubusercontent.com/84486806/233907006-69eea20f-2cbb-4f57-a14a-4e42a2ae8ff5.png)


## Stack technique

**Langage de programmation:** Java.

**Frameworks:** Java Swing.


## Fonctionnalités
- L'utilisateur peut entrer le nombre d'intersection avant d'exécuter l'application.
- L'utilisateur peut entrer le nombre de voiture avant d'exécuter l'application.
- L'utilisateur peut choisir la vitesse d'exécution du programme.
- Il existe de nombreux types de véhicules différents tels que: voiture normale, camion de pompiers, ambulance, voiture de police. Ils ont des priorités et des vitesses différentes.
- La priorité des véhicules sera d'autant plus élevée s'il y a plus de véhicules de même direction derrière lui sur la même route.
- Les véhicules sont classés par ordre de priorité pour circuler à travers les intersections afin d'éviter les bouchons.
- Les véhicules autonomes choisiront automatiquement les itinéraires les plus efficaces pour éviter les bouchons ou une surabondance de voitures à une intersection.


## Exécution de l'application

```bash
$ chmod u+x ./exe.sh
$ ./exe.sh
```
## Vidéo Démo
