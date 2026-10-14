<div align="center">

# 夕凪 Yunagi

**Le wiki collaboratif francophone de l'anime, du manga et du webtoon.**

Cataloguer, suivre, noter, savoir quand sort la suite — et enrichir le wiki avec la communauté.
100 % en français, pensé d'abord pour le mobile.

[![Site](https://img.shields.io/badge/site-yunagi.app-7c3aed)](https://yunagi.app/)
[![Présentation](https://img.shields.io/badge/présentation-presentation.yunagi.app-a78bfa)](https://presentation.yunagi.app/)
![Langue](https://img.shields.io/badge/langue-français-1f2937)
![Plateformes](https://img.shields.io/badge/plateformes-Web%20·%20PWA%20·%20iOS%20·%20Android-1f2937)
![Discord](https://img.shields.io/badge/Discord-YunaBot-5865F2)

[**Ouvrir Yunagi**](https://yunagi.app/) · [**Présentation**](https://presentation.yunagi.app/) · [Catalogue](https://yunagi.app/catalogue) · [Agenda](https://yunagi.app/agenda/semaine) · [Jeux](https://yunagi.app/jeux) · [Aide](https://yunagi.app/aide)

</div>

---

## Sommaire

1. [Yunagi en bref](#yunagi-en-bref)
2. [Galerie](#galerie)
3. [Catalogue et découverte](#catalogue-et-découverte)
4. [Bibliothèque et suivi personnel](#bibliothèque-et-suivi-personnel)
5. [Agenda des sorties](#agenda-des-sorties)
6. [Tops et jeux de classement](#tops-et-jeux-de-classement)
7. [Communauté](#communauté)
8. [Contribuer au wiki](#contribuer-au-wiki)
9. [Comptes, profils et confidentialité](#comptes-profils-et-confidentialité)
10. [Notifications](#notifications)
11. [Actualités](#actualités)
12. [Mobile, application et hors-ligne](#mobile-application-et-hors-ligne)
13. [YunaBot, le compagnon Discord](#yunabot-le-compagnon-discord)
14. [Autres fonctionnalités](#autres-fonctionnalités)
15. [État actuel et évolutions](#état-actuel-et-évolutions)
16. [Principes du produit](#principes-du-produit)
17. [Sources de données et crédits](#sources-de-données-et-crédits)

> **Légende des états** utilisée dans tout le document
> ✅ disponible · 🟡 partiel ou en cours · 🔜 prévu (chantier ouvert) · 💡 idée, non commencée

---

## Yunagi en bref

Yunagi est un **wiki de fans** consacré à l'anime, au manga, au webtoon et au light novel. Il s'adresse aux fans francophones lassés de jongler avec des références anglophones (AniList, MyAnimeList) et frustrés par leur expérience sur téléphone.

Ce qui le distingue :

| | |
|---|---|
| 🇫🇷 **Entièrement en français** | Interface, fiches, genres, statuts : tout est pensé pour un public francophone. |
| 🤝 **Un wiki modéré par la communauté** | N'importe quel membre peut enrichir une fiche. Chaque proposition est relue avant publication et rapporte des points. |
| 📱 **Mobile d'abord** | Site installable, utilisable hors connexion, et application publiée sur iOS et Android. |
| 📅 **Un agenda des sorties** | Les épisodes d'anime de la semaine et les parutions de tomes du mois, au même endroit. |
| 📚 **Le suivi au grain fin** | Progression, note et avis **par épisode, par chapitre et par tome**, mangathèque physique comprise. |
| 🎮 **Des tops qui se jouent** | Classer ses œuvres en duels, à l'aveugle, par élimination ou en tournoi. |
| 💬 **Une vraie communauté** | Profils, abonnements, critiques, espace discussion avec débats par camp, et un bot Discord. |

Yunagi est construit **d'abord pour son auteur et ses proches** : une application de fan, faite par un fan, utilisée au quotidien. Les choix de produit en découlent (voir [Principes du produit](#principes-du-produit)).

---

## Galerie

> 📸 **Les captures d'écran ne sont pas encore intégrées à ce README.**
> Elles n'ont pas pu être réalisées lors de sa rédaction : l'application et le site de présentation n'étaient pas joignables depuis l'environnement de travail, et aucune capture exploitable n'était archivée dans les sources consultées. Plutôt que d'illustrer avec de fausses images, la galerie reste vide pour l'instant.
>
> La liste des captures prévues (écran, URL, nom de fichier attendu) est tenue dans [`docs/assets/readme/`](docs/assets/readme/README.md). Une fois les images déposées dans ce dossier, elles prendront place ici et en tête de chaque section.

En attendant, le plus simple pour voir Yunagi est de l'ouvrir : [yunagi.app](https://yunagi.app/) ou la [présentation](https://presentation.yunagi.app/).

---

## Catalogue et découverte

### Recherche ✅

La barre de recherche, présente dans l'en-tête de chaque page, propose des **suggestions au fil de la frappe**.

- **Tolérante aux fautes** : la recherche est approximative, une coquille dans le titre suffit à retrouver l'œuvre.
- **Tous les titres comptent** : titre principal, titre anglais, titre japonais, synonymes et alias communautaires. Chercher « L'Attaque des Titans », « Attack on Titan » ou « Shingeki no Kyojin » mène à la même fiche.
- **Recherche par morceau de titre**, pas seulement par début de titre.
- **Recherche de membres** : les profils privés et les membres que vous avez bloqués n'y apparaissent pas.
- **Recherche dans l'espace discussion** : recherche plein texte dans les sujets.

### Catalogue ✅

La page [`/catalogue`](https://yunagi.app/catalogue) parcourt l'ensemble des œuvres, avec un bloc de tri et de filtres repensé pour rester compact sur mobile. Les œuvres d'une même licence y sont regroupées.

- Types couverts : **anime, manga, webtoon, light novel** (et web novel).
- La position de défilement est conservée quand on revient d'une fiche.
- *Limite* : des filtres par genre et par année ont été demandés par des utilisateurs et ne sont pas encore traités. 🔜

### Fiche d'œuvre ✅

C'est le cœur du wiki. Une fiche réunit :

- **Informations générales** : titres (principal, anglais, natif, synonymes), synopsis avec bouton « Voir + », format, type, dates, statut de diffusion ou de publication, genres, studios ou éditeurs.
- **Score** : la moyenne brute des membres, à côté d'un score pondéré qui évite qu'une œuvre notée par deux personnes passe en tête. La fiche distingue **« Ma note »** du **score communautaire**.
- **Personnages** du casting, avec un **sélecteur de langue** pour l'affichage de leurs noms.
- **Staff**.
- **Musiques** : openings, endings et bandes originales (OST).
- **Relations** entre œuvres : suite, préquelle, adaptation, etc.
- **Où regarder** : la disponibilité de l'œuvre en streaming.
- **Épisodes, chapitres et tomes**, avec leur propre page (voir ci-dessous).
- **Critiques** des membres, la liste des **contributeurs** de la fiche, commentaires.
- **« Résumé foireux »** : si le synopsis est mauvais, chacun peut proposer une description alternative, relue par la modération.
- La **saison projetée** de l'œuvre, issue de l'agenda.

### Franchises et licences ✅

Les œuvres d'un même univers sont rattachées à une **licence** (franchise). Une page de franchise agrège toutes ses œuvres — séries, films, mangas, spin-offs — et permet d'ajouter l'une d'elles à une liste.
Les doublons peuvent être **fusionnés**, et les relations restent cohérentes après fusion.

*Limite* : le rangement des licences est en cours ; certaines séries n'ont pas encore de licence ou ont une licence vide. 🟡

### Pages épisode, chapitre et tome ✅

Chaque épisode, chapitre ou tome a sa **propre page** : résumé, image de couverture (pour les tomes), commentaires dédiés, et note et avis des membres.

- Les **numéros décimaux** sont gérés (un « tome 7.5 », ça existe vraiment).
- Un chapitre peut être rattaché à son tome.
- **Statut canon** des épisodes : *canon*, *mixte* ou *filler*. Un épisode non renseigné n'est jamais présenté comme canon. Le filtre « parcours canon » (voir ce qu'on peut sauter) est en cours. 🟡

### Personnages et doubleurs ✅

- **Fiche personnage** : nom, nom japonais, rôle dans chaque œuvre, statut, image, description et **citations** marquantes.
- **Fiche doubleur** (et membres du staff) : les rôles tenus d'une œuvre à l'autre, VO et VF.
- Ces fiches sont contribuables, images comprises.

### Accueil et premiers pas ✅

- **Accueil visiteur** : présentation, statistiques vivantes du site, comparatif « Yunagi vs AniList / MAL ».
- **Accueil connecté** : carrousels, meilleurs contributeurs du moment, carte « Soutenir Yunagi ».
- **Parcours de bienvenue** en trois étapes au premier login, **checklist « premiers pas »** et bulles de découverte affichées une seule fois.
- **Page d'aide** [`/aide`](https://yunagi.app/aide) : toutes les fonctionnalités expliquées, avec des liens contextuels depuis les pages concernées.

---

## Bibliothèque et suivi personnel

### Ma collection ✅

Ajoutez une œuvre depuis sa fiche ou depuis le catalogue, puis suivez-la. La collection est séparée en trois listes — **Anime**, **Manga**, **Webtoon** — avec chacune sa page.

Les statuts proposés dépendent du type d'œuvre :

| Statut | Anime | Manga | Webtoon |
|---|:-:|:-:|:-:|
| En cours | ✅ | | ✅ |
| En cours de lecture | | ✅ | ✅ |
| À regarder | ✅ | | |
| À lire | | ✅ | ✅ |
| Terminé · En pause · Abandonné · En cours de revisionnage | ✅ | ✅ | ✅ |

Chaque entrée peut porter une **note sur 10**, une **progression**, un **nombre de revisionnages**, des **notes personnelles**, des **dates de début et de fin**, un marqueur **favori** et un réglage **public / privé**.

### Progression épisode par épisode ✅

- **Cases à cocher** directement dans la liste des épisodes de la fiche, avec un marqueur visuel « vu ».
- Une **fenêtre de progression** pour avancer d'un coup (« j'en suis au chapitre 112 »).
- La fiche et la fenêtre partagent la même source : le compteur et les cases vues restent cohérents.
- Si vous avez vu plus d'épisodes que la fiche n'en recense, vous pouvez **proposer d'ajouter les épisodes manquants** au wiki.

### Noter chaque épisode, chapitre et tome ✅

Au moment où vous cochez un épisode, la fenêtre de progression permet de lui donner **une note et un avis**. Même chose pour un chapitre ou un tome. Les avis d'items s'affichent sur la page de l'épisode et peuvent être supprimés.

### Mangathèque physique ✅

Pour les collectionneurs de tomes papier :

- Marquer chaque tome comme **possédé** ou **désiré**.
- Noter le **prix**, la **devise**, l'**état**, la **date d'achat** et des remarques.
- Visualiser d'un coup d'œil les **tomes manquants** (bande sur la carte de l'œuvre, détail au toucher).
- Statistiques de la mangathèque et **partage public**.
- *Prévu* : gérer plusieurs **éditions** d'un même tome (collector, coffret, réédition). 🔜

### Listes personnalisées ✅

Créez autant de listes que vous voulez (« À montrer à ma sœur », « Mes isekai préférés »…), ajoutez-y des œuvres depuis une fiche ou une page de franchise, et retrouvez-les sur votre profil. Les listes servent aussi de base aux [tops](#tops-et-jeux-de-classement).

### Statistiques ✅

Le profil affiche un résumé par type (œuvres terminées, épisodes, temps, note moyenne). La page **statistiques détaillées** (`/profile/<pseudo>/stats`) va plus loin :

- entrées, **temps de visionnage** estimé (jours + heures), note moyenne, épisodes et chapitres, favoris, œuvres critiquées, revisionnages ;
- répartition par statut et histogramme des notes ;
- **« Vos goûts vs la communauté »** : les œuvres que vous surnotez et sous-notez le plus ;
- top genres, répartition par décennie, par format, top studios.

*Limite connue* : pendant un revisionnage, le temps du premier visionnage n'est pas toujours compté. 🟡

### Importer sa bibliothèque ✅

Inutile de tout ressaisir : Yunagi reprend votre bibliothèque depuis trois sources.

| Source | Ce qui est repris |
|---|---|
| **MyAnimeList** | votre liste anime / manga exportée |
| **Tachimanga** | votre bibliothèque de lecture (sauvegarde Tachimanga, qui nécessite l'offre Premium de l'application) |
| **TV Time** | votre historique de séries, avec les instructions d'export expliquées dans l'écran |

L'import se fait en quatre temps : dépôt du fichier, **prévisualisation**, confirmation, résultat. Les titres sont rapprochés automatiquement du catalogue ; les œuvres introuvables sont signalées à l'équipe pour être ajoutées.

---

## Agenda des sorties

Une **fonctionnalité signature** : savoir quand sort la suite, sans dépendre d'un site tiers.

### Deux pages, deux rythmes ✅

| Page | Contenu | Présentation |
|---|---|---|
| [`/agenda/semaine`](https://yunagi.app/agenda/semaine) | les **épisodes d'anime** de la semaine | grille façon guide TV |
| [`/agenda/parutions`](https://yunagi.app/agenda/parutions) | les **parutions de tomes** de manga | liste chronologique par mois |

Le découpage suit le **rythme de sortie** plutôt que le type d'œuvre : l'anime sort chaque semaine, le manga chaque mois. Les œuvres de votre collection sont mises en avant.

### Comment l'agenda est tenu ✅

- Pour un anime, l'équipe saisit une **règle de diffusion** (jour, heure, date de début) et l'agenda en déduit tous les épisodes à venir. Les **exceptions** (pause, décalage) se posent à la main.
- Les tomes se saisissent **un par un** : les éditeurs français n'ont pas de rythme prévisible.
- Seuls les modérateurs, journalistes et administrateurs posent une date. C'est la seule exception assumée à la règle « tout passe par la modération ».

### Être prévenu d'une sortie 🟡

Une notification **« nouvel épisode »** (dans l'application et en push) est envoyée pour les œuvres suivies. Reste à traiter : annuler proprement une annonce quand un épisode est décalé après coup.

### Prévu ou envisagé

- 🔜 Agenda consultable par le bot Discord.
- 💡 Export vers Google Agenda / Apple Calendrier (iCal).
- *Exclu volontairement* : l'e-mail à chaque épisode (jugé trop intrusif) et le recalage automatique par une source externe.

---

## Tops et jeux de classement

La page [`/jeux`](https://yunagi.app/jeux) et l'éditeur de tops transforment le classement de ses œuvres en jeu. Un top est une liste classée ordinaire : chaque mode de jeu ne fait que la remplir.

### Créer un top ✅

- Glisser-déposer avec une carte qui suit le doigt ou la souris, et une **corbeille** qui apparaît en bas.
- **Podium** en tête du top et défilement infini (plus de limite à 100 entrées).
- **Vue liste en colonnes**.
- **Filtrer un top par tag** (par exemple : ne voir que le sport dans son top de tous les temps).
- **Image de partage** au format story.
- 🟡 En cours : créer un top en quelques clics et piocher dans sa collection directement depuis l'éditeur.

### Les modes de jeu

| Mode | Principe | État |
|---|---|---|
| **Classer en duels** | deux œuvres à la fois, vous choisissez, jusqu'à ce que la liste soit triée | ✅ |
| **Top 10 à l'aveugle** | les œuvres arrivent au hasard, vous les placez sans connaître la suite | ✅ (l'enregistrement de l'image de résultat bloque sur Android) |
| **Élimination** | dix œuvres, on les retire une à une jusqu'à la dernière | ✅ v1 · 🟡 v2 |
| **Ceci ou cela** | choisir entre deux propositions | ✅ |
| **Tournoi** | un tableau à élimination directe | ✅ |
| **Personnages** | listes de jeu composées de personnages | ✅ |
| **Musiques** | listes de musiques importées depuis une playlist YouTube | ✅ |
| **« Une œuvre »** | jouer avec les personnages d'une franchise | ✅ |
| **Tier list** | ranger en paliers, façon TierMaker | 💡 |

### Idées documentées 💡

Comparer son top avec celui d'un ami, top communautaire agrégé, défis thématiques avec date limite, historique d'un top, suggestions d'oublis (« Tu n'as pas oublié… ? »), un mot par entrée pour justifier le rang, top à taille fixe.

---

## Communauté

### Profils publics et abonnements ✅

- Profil avec avatar, bannière, description, aperçu de la collection par type, statistiques, listes et tops.
- **Suivre** d'autres membres, consulter ses abonnés et abonnements.
- **Favoris en commun** : sur le profil de quelqu'un d'autre, une bande montre les œuvres favorites que vous partagez (uniquement parmi ses favoris publics).
- **Duels de goût** : la page `/vs/<membre1>/<membre2>` compare deux profils.
- Badge de **niveau** affiché à côté du pseudo dans les commentaires et les discussions.

### Fil d'activité ✅

Le fil montre l'activité des membres que vous suivez : ajouts à la collection, critiques, contributions… Un filtre « Suivis » isole leurs sujets dans l'espace discussion.

### Critiques ✅

Écrivez une **critique d'œuvre** (en markdown, avec réglage de visibilité) ou un avis court sur un épisode, un chapitre ou un tome. La note d'œuvre est unique : la même note sert à la collection et à la critique, et noter ne nécessite pas d'ajouter l'œuvre à sa collection.

### Commentaires ✅

Sous les fiches, les épisodes, les chapitres, les tomes et les actualités :

- **fils imbriqués** « à la Reddit », tri, réponse à une personne précise ;
- **markdown** et **balises spoiler** ;
- **modification** pendant 10 minutes, tant que personne n'a répondu ;
- suppression qui laisse « [supprimé] » pour garder le fil lisible ;
- « charger plus de réponses » sur les gros fils.

### Espace discussion ✅

[`/discussions`](https://yunagi.app/discussions) est le forum de Yunagi :

- **Sujets** rattachés ou non à une œuvre, avec liens modifiables après création.
- **Débats par camp** : chacun choisit son camp et argumente ; un débat peut être clos.
- **Sondages**.
- **Avertissement spoiler basé sur votre progression** : si le sujet dépasse l'endroit où vous en êtes, vous êtes prévenu.
- Sujets **épinglés** par la modération, signalements, recherche plein texte.
- **Partage** d'une discussion en image ou sur Discord.
- 🔜 Découverte (tendances, pages par tag) et outils de modération avancés.

### Classement saisonnier ✅

[`/classement`](https://yunagi.app/classement) présente les **meilleurs contributeurs** (par points gagnés) et les **meilleurs collectionneurs** de la saison en cours. Le classement repart à zéro à chaque saison et les saisons passées sont archivées.

---

## Contribuer au wiki

Yunagi est un wiki : **tout membre connecté peut l'enrichir**.

### Ce que l'on peut proposer ✅

- Corriger ou compléter un champ d'une fiche d'œuvre, de personnage ou de doubleur.
- Ajouter des **épisodes**, des chapitres ou des tomes, avec leur résumé.
- Proposer une **image** (couverture, bannière, portrait), par envoi de fichier ou par lien.
- Proposer des **titres alternatifs**, un **résumé alternatif**, des **citations** de personnages.
- Signaler un problème ou envoyer un retour.

### Comment une contribution est traitée ✅

1. Vous proposez une modification.
2. Elle part dans la **file de relecture** de la modération. Les images restent privées jusqu'à leur approbation.
3. Un modérateur l'**approuve** ou la **refuse avec un motif**.
4. Si elle est approuvée, elle est publiée et vous **gagnez des points**.

Quelques règles garantissent la fiabilité du wiki : un champ déjà en attente de relecture ne peut pas être proposé une deuxième fois, on ne valide jamais sa propre contribution, et même les imports automatiques passent par ce circuit.

### Points et niveaux ✅

Chaque contribution approuvée rapporte des points selon un barème. Les points font progresser à travers **12 niveaux**, chacun avec son titre et son badge, et alimentent le [classement saisonnier](#classement-saisonnier-). Envoyer un retour depuis l'application rapporte aussi un point.

Les points ne s'achètent pas, et ne s'achèteront jamais : c'est le seul mécanisme de mérite du produit.

- 💡 Badges thématiques (par exemple, contribuer sur dix œuvres d'un même genre) et récompenses du classement : prévus, mais leurs critères ne sont pas encore définis.

### Espace d'administration ✅

Pour l'équipe : file de modération (avec approbation et refus groupés), signalements, gestion des images et des GIFs, suivi des œuvres manquantes repérées par les imports, et saisie de l'agenda.

---

## Comptes, profils et confidentialité

### Compte ✅

- Inscription par e-mail, avec **vérification de l'adresse**.
- **Mot de passe oublié** par lien à usage unique.
- Sessions révocables : se déconnecter déconnecte vraiment. Un membre actif reste connecté.
- Retour automatique à la page d'origine après connexion.
- **Liaison du compte Discord** avec le compte Yunagi.
- 🟡 **Connexion avec Google et Apple** : développée, en attente de mise en production et de vérification sur le web, iOS et Android.

### Rôles

Membre, journaliste, modérateur et administrateur. Chaque rôle débloque ses outils (rédaction d'actualités, relecture, administration).

### Confidentialité ✅

- **Profil public ou privé** : un profil privé n'est ni consultable ni trouvable par la recherche.
- Visibilité réglable **entrée par entrée** dans la collection.
- **Bloquer un membre** et gérer ses blocages ; les membres bloqués disparaissent de vos résultats de recherche.
- **Signaler** un contenu publié par un membre.
- **Supprimer son compte** directement depuis l'application, sans passer par le support.
- Pages légales : mentions, conditions d'utilisation, confidentialité, crédits.

### Personnalisation ✅

- Avatar (photo ou prise de vue) et bannière, description avec retours à la ligne.
- **Thème sombre** (par défaut) et **thème clair**.

---

## Notifications

| Canal | État | Ce qu'il couvre |
|---|---|---|
| **Dans l'application** | ✅ | la cloche et la page [`/notifications`](https://yunagi.app/notifications), regroupées par type et par jour |
| **Push** sur l'application mobile | ✅ | avec une invite d'activation au premier lancement |
| **E-mail** | 🔜 | réservé aux événements survenus en votre absence (nouvel abonné, mention, résumé) |

Exemples de notifications : réponse à un commentaire, mention, nouvel abonné, contribution acceptée, nouveau sujet d'une personne suivie, réponse dans une discussion à laquelle vous avez participé, **sortie d'un épisode** d'une œuvre suivie. Un clic mène directement à l'œuvre ou au contenu concerné.

Yunagi n'envoie jamais d'e-mail pour une action que vous venez de faire vous-même.

---

## Actualités

La rubrique [`/news`](https://yunagi.app/news) publie l'actualité anime et manga en français.

- Deux formats : la **brève** (flash) et l'**article** de fond.
- Image de couverture et bannière.
- **Catégories** et filtres par pastilles.
- Rédigées par les membres ayant le rôle **journaliste**, relues avant publication (refus motivé possible), commentables.
- Les billets du blog Yunagi sont repris automatiquement.

---

## Mobile, application et hors-ligne

### Application iOS et Android ✅

Yunagi est publié sur l'**App Store** et sur **Google Play**. L'application reprend tout le site, avec :

- les **notifications push** natives ;
- l'ouverture directe dans l'application des liens `yunagi.app` ;
- un confort tactile travaillé (geste de retour natif, barre de navigation basse, défilement fluide) ;
- un comportement gracieux sans réseau.

### Site installable (PWA) ✅

Sur navigateur, Yunagi s'installe comme une application : bouton « Installer » quand le navigateur le permet, instructions dédiées sur iPhone, **raccourcis** depuis l'icône, page hors-ligne et invitation à recharger lorsqu'une nouvelle version est disponible.

### Navigation rapide ✅

Les pages s'enchaînent sans rechargement complet, avec des transitions (la couverture « s'envole » vers la fiche), un cache des pages déjà vues et des **nouvelles tentatives automatiques** quand le réseau flanche — pratique dans les transports.

---

## YunaBot, le compagnon Discord

YunaBot apporte Yunagi sur les serveurs Discord.

| Commande | Ce qu'elle fait | État |
|---|---|---|
| `/search` | chercher une fiche | ✅ |
| `/catalogue` | parcourir le catalogue, avec tri et pagination | ✅ |
| `/profile` | afficher le profil Yunagi d'un membre | ✅ |
| `/stats` | afficher les statistiques d'un membre | ✅ |
| `/gif` | envoyer un GIF anime par catégorie | ✅ |
| `/addgif` | proposer un GIF au fonds communautaire (modéré) | ✅ |
| `/interact` | interagir avec un autre membre en GIF | ✅ |
| `/login` | lier son compte Discord à Yunagi | ✅ |
| Classements | top contributeurs et collectionneurs | ✅ |
| Notifications d'épisodes, quiz et mini-jeux | | 💡 |

---

## Autres fonctionnalités

- **Envoyer un retour** ✅ — un bouton présent sur toutes les pages ouvre un formulaire. Le contexte utile (page, appareil, navigateur, taille d'écran) est joint automatiquement, pour que le problème soit reproductible sans relancer son auteur.
- **Partage en image** ✅ — discussions, tops et résultats de jeux se partagent en image, et les liens Yunagi s'affichent proprement sur Discord et les réseaux sociaux.
- **Soutenir Yunagi** ✅ — une carte Ko-fi (accueil connecté et profil) affiche l'objectif mensuel des dons. Elle est masquée dans l'application iOS.
- **Programme bêta** ✅ — un accès anticipé pour les testeurs.

---

## État actuel et évolutions

### Vue d'ensemble

| Domaine | État |
|---|---|
| Catalogue, fiches, personnages, doubleurs, franchises | ✅ |
| Recherche | ✅ |
| Collection, progression par item, mangathèque, listes, statistiques | ✅ |
| Imports MyAnimeList, Tachimanga, TV Time | ✅ |
| Agenda anime et manga | ✅ |
| Notification de sortie d'épisode | 🟡 |
| Tops et jeux de classement | ✅ (enrichissements en cours) |
| Profils, abonnements, activité, critiques, commentaires, discussions | ✅ |
| Contributions, modération, points, 12 niveaux, classement saisonnier | ✅ |
| Actualités | ✅ |
| Application iOS / Android, PWA, hors-ligne | ✅ |
| YunaBot | ✅ |
| Connexion Google et Apple | 🟡 |
| E-mails de notification | 🔜 |

### Chantiers en cours

- 🟡 **Fiches enrichies** — parcours canon (voir quels épisodes sauter), puis épisodes essentiels, ordre de visionnage des films, relations entre personnages et anecdotes « Le saviez-vous ? ».
- 🟡 **Tops et jeux** — création express, collection dans l'éditeur, mode aveugle, Élimination v2.
- 🟡 **Qualité du catalogue** — rangement des licences, complément automatique des fiches incomplètes (toujours soumis à relecture), dédoublonnage des personnages.
- 🟡 **Connexion Google et Apple**.

### Évolutions documentées

- 🔜 **Éditions multiples de tome** : collector, coffret, rééditions — et les posséder séparément dans sa mangathèque.
- 🔜 **Apparitions** : qui apparaît dans quel épisode ou chapitre, avec quel rôle (sans spoiler), et quel épisode adapte quels chapitres.
- 💡 **Recommandations personnalisées**, explicables (« parce que tu as aimé X »).
- 💡 **« Ton année anime »** : un bilan annuel partageable en image.
- 💡 **Badges thématiques** et récompenses du classement.
- 💡 **Offre supporter** strictement cosmétique (thèmes, cadre de profil…), conditionnée à une décision prise après plusieurs mois de mesure des dons.

### Idées en réserve 💡

« Ce soir je regarde quoi ? », lecteur d'openings et d'endings, glossaire otaku francophone, pages studio et auteur enrichies, notes sur les personnages, listes collaboratives avec vote, clubs thématiques, recherche d'un anime à partir d'une capture, mode « apprendre le japonais », widget mobile.

---

## Principes du produit

- **Pas de fonctionnalité sans usage réel** : on répond à des besoins constatés.
- **Rien d'écrit dans le wiki sans relecture** : la règle vaut aussi pour les imports automatiques.
- **On ne vend jamais le mérite** : aucun avantage payant ne touchera aux points, aux niveaux ni au classement. Un éventuel premium restera cosmétique ou de confort.
- **Pas d'e-mail superflu** : uniquement pour ce qui arrive en votre absence.
- **Pas de dépendance subie** : l'agenda fonctionne sans site tiers ; une source externe peut proposer, jamais écrire seule.

---

## Sources de données et crédits

Le catalogue a été amorcé à partir de données **factuelles** issues de sources ouvertes, puis normalisé (genres traduits et dédoublonnés, éditeurs et studios en vocabulaire contrôlé) et enrichi par la communauté :

- **[AniList](https://anilist.co/)** — données factuelles sur les œuvres et les personnages.
- **[Wikidata](https://www.wikidata.org/)** — données publiées sous licence CC0.
- **[BnF](https://www.bnf.fr/)** — données bibliographiques, sous Licence ouverte.
- **[otakugifs.xyz](https://otakugifs.xyz/)** — source du fonds de GIFs de YunaBot.

Les synopsis, résumés alternatifs, citations, critiques et dates d'agenda sont rédigés ou vérifiés par les membres et l'équipe de Yunagi.

Les noms d'œuvres, de personnages et les visuels associés appartiennent à leurs ayants droit respectifs.

---

<div align="center">

**夕凪** — *le calme du soir, quand le vent tombe.*

[yunagi.app](https://yunagi.app/) · [presentation.yunagi.app](https://presentation.yunagi.app/)

</div>
