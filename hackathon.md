Retours d'expérience organisation de hackathons
===============================================

_Contenu originalement consolidé par [Étalab](https://semestriel.framapad.org/p/Retours_XP_Hackathons)_

Préparation
-----------

### Équipe

- Constituer une vraie équipe-projet dès le debut : un·e responsable salle et matériel, un·e responsable data, un·e responsable accès aux données, un·e responsable com'/participants, un·e responsable déroulé de l'évenement.

### Logistique / matériel

#### Constitution d'un kit Hackathon/Barcamp

- Points d'accès WiFi + routeur/switches
- Des câbles RJ45 (dont quelques longs et/ou prises CPL)
- Une clé USB pour 4 participants (pour qu'ils puissent se les passer rapidement)
- Un ou deux disques durs externes pour les données volumineuses
- Tous les adaptateurs pour vidéoprojecteur
  - USB → HDMI
  - VGA → DVI
  - Mini DisplayPort → VGA
  - Mini DisplayPort → HDMI
- Un poste minimaliste dédié au vidéoprojecteur (type netbook premier prix avec les connectiques qu'il faut).
- Télécommande / pointeur.

### Données

- Obtenir les données ouvertes pour l'occasion au moins 2 semaines avant l’événement.
- Vérifier leur état d'anonymisation si besoin.
- Documenter les principaux jeux de données avant l’événement.

### Communauté

- Communiquer sur l'événement (blog d'Étalab, Twitter…).
- Ouvrir systématiquement un pad pour que les gens puissent se préparer avant sur certains sujets.
- Vérifier qu'il n'y a pas de collision avec un autre événement sur le même créneau pour la même communauté.


Déroulement
-----------

- Inviter les participants à publier leurs réutilisations sur data.gouv.fr dès le début de l'événement et leur rappeler à la fin.
- Inviter les participants à publier leur slides dès le début de l’événement et leur rappeler à la fin.
- (Re)tweeter les moments forts de l'événement.
- Limiter la durée des interventions/pitchs pour un démarrage rapide.

### Lieu

- Facilement accessible.
- Donner le maximum d'informations pratiques pour s'y rendre.

### Format et distribution des données

- Base relationnelle : ce choix s'était révélé concluant lors de l'ouverture du DAMIR, il devient plus difficile de ne retenir que cette solution lorsque les données proposées sont volumineuses et hétérogènes.
- Un serveur distant est un moyen simple de travailler sur les données sans récupérer trop de choses. Bien tester les performances en amont pour déterminer si cette solution est viable avec tous les participants.
- Fournir égalemetn des dumps dans un format exploitable (CSV/JSON) en deux versions : complets et échantillons sous la forme de fichiers plats type `.csv.tgz` (`csv.tar.xz` a un excellent taux de compression, dans le cas des grosses bases la différence est notable).
- Si possible, exposer les datasets sur `data.gouv.fr`.
- Clés USB.
- Torrent, à privilégier pour la distribution en local.

Suivi
-----

- Publier un article de récap' sur le blog avec des liens vers les réutilisations et vers les présentations.
- Faire un débrief sur les retours des participants sur les données, les outils, l'événement, le lieu…
