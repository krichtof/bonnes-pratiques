Ce que les startuppeurs ont appris.

Comment parler de l'Incubateur
------------------------------

Par exemple, pas comme ça :

> Le titre
> ##### Méthode « startup d’État », la nouvelle manière de construire les projets de l’administration
> me pose vraiment problème. Plutôt que de simplement le réécrire, je vais détailler pourquoi en espérant que ça guide de futurs points rédactionnels.
>
> 1. Ce n’est pas la nouvelle manière de construire mais une manière, qui ne doit surtout pas être perçue par des acteurs publics comme le moyen d’être hype sans se remettre en question. Ce n’est pas une évolution naturelle de tous les projets administratifs avec une part de numérique, mais une possibilité de construire de manière exploratoire un service encore inconnu. On reçoit déjà assez de demandes mal qualifiées comme ça, il faut limiter notre exposition.
> 2. Ce ne sont pas des projets mais des produits, ou éventuellement des services numériques. C’est très important : un projet a un début et une fin connues, un produit vivra et évoluera en permanence. On est sur un changement de pensée majeur pour l’administration. La notion de service est encore plus lointaine, et c’est peut-être même un peu tôt pour l’introduire, mais on peut faire le lien avec service public numérique.
> 3. Je ne suis vraiment pas convaincu par l’appellation de « méthode ». On a des principes, des valeurs, des exemples et des éléments de méthode, mais il ne me semble pas qu’une « Startup d’État » soit une méthode.
>
> « Produire rapidement et durablement des outils numériques qui améliorent le service public », c’est très bien  ;)
> Ou, pour rester plus proche de ton titre, « Les Startups d’État, un moyen de construire des produits numériques qui améliorent le service public ».
>
> Et s’il vous plaît, j’insiste sur la majuscule à Startup d’État. Ça signifie qu’on introduit un concept entier, par opposition à startup d’État, qui laisse entendre que c’est une startup de l’État, avec toutes les questions de statut moral. C’est comme les guillemets, mais sans l’aspect dépréciatif.


Identité visuelle
-----------------

Nous n'avons pas de charte graphique commune spécifique à l'Incubateur.

### Références

- [Charte graphique du SGMAP](http://www.modernisation.gouv.fr/fileadmin/nl_infos-301115/img/CharteGraphiqueSGMAP_novembre2015.pdf).

### Ressources

Ces images ne sont pas soumises à la licence CC0 appliquée à ce texte.

#### Logo SGMAP

Attention, il y en a eu plusieurs versions, la plupart encore trouvables par Google. Les précédentes sont dépréciées, n'utiliser que celles référencées ici.

Stocké dans le dossier [`images`](https://github.com/sgmap/bonnes-pratiques/blob/master/images).

Ce logo peut également être [hotlinké](http://www.modernisation.gouv.fr/sites/default/files/bloc-sgmap-2.jpg), avec l'avantage d'être mis à jour en autonomie par le service communication du SGMAP (exemple : bandeau noir en deuil national) et l'inconvénient de ne pas avoir de stabilité URL garantie à 100%.

#### Marianne

Stocké dans le dossier [`images`](https://github.com/sgmap/bonnes-pratiques/blob/master/images).

Attention, la Marianne appartient au [SIG](http://www.gouvernement.fr/service-d-information-du-gouvernement-sig). Ne pas l'utiliser sans discussion interne.

#### Logo « éprouvette » de l'Incubateur

Stocké dans le dossier [`images`](https://github.com/sgmap/bonnes-pratiques/blob/master/images).

Ce logo n'a pas aujourd'hui de reconnaissance officielle. Le privilégier pour les prototypes.

#### Logo OpenFisca

Stocké dans [`openfisca/openfisca-web-site`](https://github.com/openfisca/openfisca-web-site/tree/master/openfisca_web_site/static/hotlinks).

Ce logo peut également être [hotlinké](http://www.openfisca.fr/hotlinks/). La stabilité de ces URLs est garantie par l'équipe OpenFisca, contacter [**@cbenz**](https://github.com/cbenz) en cas de problème.

### Protips

Lorsque votre produit est en phase d'investigation ou en début de construction, ne vous préoccupez pas de son apparence.


Langue
------

Par souci de lisibilité pour les partenaires, notamment administratifs, la langue utilisée pour la description et le suivi de fonctionnalités est le français.

En revanche, pour éviter le coût du changement de contexte, les discussions techniques, notamment par le biais de commentaires ou d'échanges par des logiciels spécialisés, peuvent se faire en anglais, la langue la plus utilisée dans le cadre du développement logiciel.

> Attention à ne pas rédiger un `README` _intégralement_ en anglais, par exemple. Un simple résumé en français _([exemple](https://github.com/sgmap/paie-api#readme))_ vous permettra de [respecter la loi](https://www.legifrance.gouv.fr/affichTexte.do?cidTexte=LEGITEXT000005616341&dateTexte=vig#LEGIARTI000006421216).


Licence
-------

Sauf demande expresse justifiée et discutée en interne, notre code est publié sous licence libre. Une licence [AGPL-3.0](http://www.gnu.org/licenses/agpl-3.0.fr.html) est une bonne valeur par défaut.

### Compatibilité

Attention, si vous incluez du code externe dans le vôtre (pas du lien, mais bien de la copie), à n'inclure que du code sous une licence compatible avec la licence AGPL.

Si vous utilisez des bibliothèques non compatibles AGPL, pensez à le [préciser dans la licence](http://www.gnu.org/licenses/gpl-faq.html#GPLIncompatibleLibs) avant la phase de passation.

### Appliquer une licence

Inclure le fichier de licence [au format texte brut](http://www.gnu.org/licenses/agpl-3.0.txt) à la racine du dépôt concerné, sous le titre `LICENSE.AGPL.txt`.

> Ce nom en améliore la découvrabilité.

Si vous travaillez sur un module NPM, pensez à ajouter la prioriété `"license": "AGPL-3.0"` dans votre `package.json`.


Vocabulaire
-----------

### Handicap

On parle de personne « en situation de [handicap](http://www.legifrance.gouv.fr/affichCodeArticle.do?cidTexte=LEGITEXT000006074069&idArticle=LEGIARTI000006796446) » et non de personne « handicapée ».

> Je la classais volontiers parmi la foule des expressions issues du politiquement correct, pensant qu’elle voulait parler des handicapés mais en arrondissant les angles. Je n’ai pas tout de suite compris qu’elle ne désignait pas uniquement les personnes atteintes d’un handicap permanent, mais élargissait la notion de handicap à tout individu pouvant éprouver une difficulté à accomplir une tâche dans un contexte donné.

[Source](http://tanguyreve.unblog.fr/2012/05/03/personne-handicapee-ou-personne-en-situation-de-handicap/).


Syntaxe
-------

### Féminin ou masculin ?

Nos outils s'adressent à tou·te·s les citoyen·ne·s, mais la langue française impose de faire des choix de genre (féminin ou masculin), avec une préférence pour le masculin « qui l'emporte » dans un groupe.

Pour éviter de genrer les outils et ainsi faire du design inclusif, construisez des phrases **neutres en genre**.

Vous pouvez par exemple expliciter le sujet, en utilisant des termes génériques tels que « personne ».

En désespoir de cause, faites apparaître les formulations masculines et féminines dans la même phrase, comme le classique « né(e) en ».
Cependant, pour fluidifier la lecture, plutôt que des parenthèses, utilisez le [point médian](https://fr.wikipedia.org/wiki/Point_médian#Utilisation_dans_le_langage_non_sexiste) : `·` (`U+00B7`).


Typographie
-----------

### Guillemets

Les guillemets français sont [`«`](http://unicode-table.com/fr/00AB/) et [`»`](http://unicode-table.com/fr/00BB/), avec des espaces insécables [` `](http://unicode-table.com/fr/00A0/) respectivement après et avant le guillemet.

[Plus d'informations](https://www.noslangues-ourlanguages.gc.ca/bien-well/fra-eng/ponctuation-punctuation/guillemets-quotation-fra.html).

### Points de suspension

Les points de suspension sont [`…`](http://unicode-table.com/fr/2026/) et non `...` (trois points). Cette distinction est importante pour les sauts de ligne, les lecteurs d'écran et le copier-coller.


Analytics
---------

Toutes les statistiques d'usage des produits web sont disponibles sur l'instance [Piwik](https://piwik.org) publique [`stats.data.gouv.fr`](https://stats.data.gouv.fr). Cette transparence est importante pour incarner notre démarche d'ouverture et de collaboration avec les citoyens.

> Pour ne pas gonfler artificiellement ces statistiques, les IP suivantes peuvent être exclues dans Piwik :
>
> - `46.218.59.235` (ADSL Sully)
> - `89.225.241.174` (fibre Sully)
> - `46.218.46.150` (Mutinerie)
