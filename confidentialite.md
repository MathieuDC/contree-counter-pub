# Politique de confidentialité de Contrée

*Dernière mise à jour : 10 octobre 2026*

Cette politique vaut à partir de Contrée 2.0.0, la première version de l'app avec un compte. Les versions 1.x n'ont pas de compte : pour elles, seul vaut ce qui est dit sans compte.

## En résumé

- **Sans compte, rien ne quitte votre iPhone.** L'app ne se connecte pas à Internet : vos parties et vos réglages restent sur votre iPhone, comme avant.
- **Le compte est facultatif.** Il se crée avec « Se connecter avec Apple » et un pseudo, sans nom ni e-mail. Le créer, c'est accepter les [conditions d'utilisation](conditions.md).
- **Avec un compte**, le serveur de Contrée, hébergé en France chez Clever Cloud, garde votre pseudo, les parties terminées comptées avec le compte, vos amis, vos groupes et vos stats. Il s'en sert pour vous les rendre sur vos appareils, les montrer aux joueurs concernés et traiter les signalements : à rien d'autre.
- **Vos amis voient vos stats**, sans vos partenaires ni vos adversaires. Le détail d'une partie n'est vu que par celui qui l'a comptée, les joueurs placés à table et les membres des groupes où elle compte.
- **Les prénoms que vous tapez** pour les joueurs sans compte partent avec la partie : les joueurs placés à table les voient.
- **Vous pouvez supprimer votre compte** depuis l'app, sur la page Compte : tout ce qui est à lui disparaît du serveur.
- **Ni publicité, ni pistage, ni mesure d'audience, ni SDK tiers.** Rien n'est vendu ni partagé à des fins commerciales.

## Qui publie l'app

Contrée est une app iPhone qui compte les points de la belote contrée. Elle est publiée par **Mathieu de Campou**, développeur indépendant qui publie l'app à titre personnel. Dans cette page, il est appelé « l'éditeur ». Pour les données du compte, il est le responsable du traitement, au sens du Règlement général sur la protection des données (RGPD).

Contact : **[humbles-mansarde.9a@icloud.com](mailto:humbles-mansarde.9a@icloud.com)**

## Sans compte : rien ne quitte votre iPhone

Sans compte, Contrée fonctionne comme avant :

- elle **ne se connecte jamais à Internet** et ne contacte aucun serveur, pas même celui de l'éditeur ;
- la page « Un compte, si vous le souhaitez », montrée une seule fois à la première ouverture, n'appelle pas le réseau : « Ignorer » la ferme, et rien ne part ;
- seul le bouton « Se connecter avec Apple », sur la page Compte, crée un compte et commence à joindre le serveur.

Créer un compte plus tard n'envoie pas vos parties d'avant. Elles restent sur l'iPhone, avec le repère « Sans compte » dans l'historique, et ne comptent dans aucune stat.

## Les données enregistrées sur votre iPhone

Pour fonctionner, l'app enregistre sur votre iPhone :

- vos **réglages** : les noms par défaut des équipes, « Saisir la couleur », « Garder l'écran allumé pendant une partie », « Renseigner les prénoms », les **règles de la partie** choisies pour la prochaine partie (objectif, « Score révolu », méthode de comptage et ses options, contrats, belote et annonces), et une marque qui retient que la page « Un compte, si vous le souhaitez » a déjà été montrée, pour qu'elle ne revienne pas ;
- la **partie en cours** : sa date et son heure de début, ses règles, les noms des équipes, les **prénoms des joueurs**, leurs places, le sens du jeu et la partance, ce qui est sélectionné dans le compteur, et chaque **donne** jouée, avec sa date et son heure, son contrat (valeur, atout, contre), l'équipe qui attaque, les points marqués et, en points faits, ce que vous avez noté sur la **feuille de marque** (plis, belotes, annonces) ;
- l'**historique** des parties terminées ou abandonnées, avec les mêmes informations et la date et l'heure de leur fin.

Les points tapés sur la feuille de marque ne sont enregistrés qu'avec la donne, quand vous touchez « Valider ».

Avec un compte, s'y ajoutent :

- dans chaque partie lancée avec le compte, l'identifiant de ce compte et, pour chaque place liée à un compte, l'identifiant et le pseudo de ce compte ;
- un dossier à part, `compte/`, qui garde une copie de ce que le serveur envoie : votre compte (son identifiant, votre pseudo, l'état de l'envoi des parties), vos amis, vos demandes d'ami, les comptes que vous avez bloqués, vos stats, celles de vos amis et celles des membres de vos groupes, vos groupes et vos invitations, et les parties en ligne reçues du serveur (celles de vos autres appareils, et celles que d'autres ont comptées avec vous ou dans vos groupes). C'est une copie jetable : elle est effacée à la déconnexion et à la suppression du compte, et refaite depuis le serveur si elle manque ;
- dans le **Trousseau** d'iOS : l'identifiant de votre compte, l'identifiant que donne Apple et les jetons de connexion au serveur. Après la suppression d'un compte, si ses parties de cet iPhone n'ont pas encore pu redevenir des parties sans compte, l'identifiant du compte supprimé y reste jusqu'à ce que ce soit fait.

Ces données sont écrites dans l'espace privé de l'app, sur votre iPhone, chacune dans un fichier et sa copie de secours (et, si un fichier a été abîmé, dans quelques copies de la version abîmée, mises de côté). **L'éditeur n'a pas accès aux fichiers de votre iPhone.** Il ne reçoit que ce que l'app envoie au serveur avec un compte (voir plus bas).

### Sauvegardes et changement d'iPhone

Les parties et les réglages font partie des **sauvegardes de votre iPhone**, sur iCloud ou sur un ordinateur (Finder sur Mac, app Appareils Apple ou iTunes sur PC), y compris les parties comptées sur cet iPhone avec un compte. Ils sont restaurés avec la sauvegarde, par exemple quand vous passez à un nouvel iPhone. Ces sauvegardes sont gérées par Apple ou par votre ordinateur, selon vos propres réglages. L'éditeur n'y a pas accès.

Le dossier `compte/` est exclu des sauvegardes. Les informations de connexion du Trousseau restent propres à cet iPhone : elles ne passent ni par le trousseau iCloud, ni sur un autre iPhone. Après une restauration sur un nouvel iPhone, on se reconnecte, et ce qui est à votre compte revient du serveur.

Sans compte, l'app **ne synchronise rien** : pas d'iCloud Drive, pas de partage entre vos appareils. Avec un compte, vos parties terminées passent d'un appareil à l'autre par le serveur de Contrée, pas par iCloud. Les réglages et la partie en cours restent propres à chaque appareil.

## Avec un compte

### Se connecter avec Apple

- Le compte se crée par « Se connecter avec Apple », sur la page Compte. Contrée ne demande à Apple ni votre nom ni votre e-mail : Apple ne les transmet pas.
- Apple donne à l'app un identifiant opaque, propre à l'éditeur, et un jeton signé. Le serveur vérifie ce jeton avec les clés publiques d'Apple, puis échange le code de connexion contre un jeton d'Apple, qu'il garde chiffré : il ne sert qu'à révoquer l'accès quand vous supprimez le compte, comme Apple l'exige.
- Le compte n'a pas de mot de passe. L'identifiant Apple n'est jamais montré aux autres joueurs.
- Vous choisissez ensuite un **pseudo**, de 3 à 12 caractères, unique et filtré par une liste de mots interdits. Tant qu'il n'est pas choisi, le compte n'est visible de personne et aucune partie ne s'y rattache. Vous pouvez le changer à tout moment, sur la page Compte (« Pseudo »). Une partie garde le pseudo du jour où elle a été jouée.

Apple sait que vous utilisez « Se connecter avec Apple » avec Contrée, et le gère selon sa propre politique de confidentialité.

### Ce que garde le serveur

- **Votre compte** : un identifiant tiré au hasard par le serveur, l'identifiant que donne Apple, le jeton d'Apple chiffré, la date de création du compte et votre pseudo.
- **Les connexions de vos appareils** : pour chaque appareil connecté, une session, faite d'une empreinte de son jeton (pas le jeton lui-même) et de sa date d'expiration. Ni le nom ni le modèle de l'appareil, ni son adresse IP.
- **Les parties terminées** que vous avez comptées avec le compte, gagnées ou abandonnées, telles que votre iPhone les a enregistrées : leurs dates et heures, leurs règles, les noms des équipes, les prénoms tapés, les comptes placés à table avec leur pseudo, les places, le sens du jeu et la partance, et chaque donne (date et heure, contrat, atout, contre, équipe qui attaque, points marqués, feuille de marque), avec leur date de réception. Pour chaque compte placé à table, sa place, son équipe et ce que la partie apporte à ses stats. Pour la synchronisation, le serveur tient aussi, pour chaque compte, la liste des parties qu'il voit.
- **Vos amis** : vos amis (et depuis quand), les demandes d'ami reçues et envoyées, les comptes que vous avez bloqués et les signalements que vous avez faits. Le serveur garde aussi, sans vous les montrer, les blocages et les signalements dont votre compte fait l'objet, ainsi que les demandes d'ami d'un compte que vous avez bloqué et ses invitations dans un groupe d'avant le blocage.
- **Vos groupes** : leur nom, leur créateur, leur date de création, leurs membres et leurs invités, avec la date de leur entrée ou de leur invitation, et, pour une invitation en attente, qui l'a faite.
- **Vos stats**, calculées par le serveur à partir des parties terminées où votre compte est placé à table (une partie abandonnée ne compte pas) : les Résultats, les Contrats de votre équipe, les Points, et vos Partenaires et Adversaires (leur pseudo, et vos parties et victoires avec chacun ou contre chacun). Au total, et dans chacun de vos groupes.

Une partie part sur le serveur quand elle se termine : jusque-là, elle reste sur l'iPhone qui la compte. Si vous rouvrez une partie déjà envoyée (« Annuler la dernière donne »), sa nouvelle fin remplace la version du serveur. Le serveur relit chaque partie reçue et recalcule ses points pour vérifier qu'ils sont justes. Il ne garde à table que vous-même et vos amis : tout autre compte placé perd son lien et n'y reste que par son pseudo, devenu un simple prénom ; un compte qui n'existe plus devient « Compte supprimé ».

Ne partent jamais : la partie en cours, vos réglages et les parties sans compte. Le serveur ne reçoit ni votre nom, ni votre e-mail, ni votre numéro de téléphone, ni vos contacts, ni votre position.

L'éditeur, qui exploite le serveur, peut techniquement accéder à ces données. Il ne les consulte que pour faire fonctionner le service, traiter un signalement ou répondre à une demande de votre part. Elles ne sont ni vendues, ni louées, ni transmises à quiconque, sauf obligation légale.

### Les prénoms des autres joueurs

Aux places sans compte, vous tapez un prénom, ou un surnom. Avec un compte, ce prénom part avec la partie : celui qui l'a comptée et les joueurs placés à table le voient dans son détail. Il ne sert à rien d'autre et ne compte dans aucune stat. Tapez des prénoms ou des surnoms que les joueurs acceptent de voir ainsi. Une personne qui ne veut pas figurer dans une partie peut écrire à l'éditeur. Sans compte, ces prénoms restent sur votre iPhone.

### Qui voit quoi

- **Vous** : tout ce qui est à votre compte, sur chacun de vos appareils connectés.
- **Vos amis** : votre pseudo et vos stats globales (Résultats, Contrats de votre équipe, Points), **sans vos partenaires ni vos adversaires**. Ils ne voient ni la liste de vos parties, ni vos autres amis, ni les groupes dont ils ne sont pas membres. Seuls vos amis peuvent vous placer à table : la partie arrive alors dans votre historique et, sauf si elle est abandonnée, dans vos stats.
- **Les joueurs d'une partie** (celui qui l'a comptée et les joueurs placés à table) : tout le détail de cette partie, avec les noms des équipes, les prénoms tapés, les pseudos des joueurs placés et celui de la personne qui l'a comptée.
- **Les membres d'un groupe** : les pseudos de ses membres et de ses invités, le classement, les parties qui comptent dans le groupe (celles dont les 4 joueurs en sont membres) en détail, et les stats de chaque membre dans ce groupe, **partenaires et adversaires du groupe compris**. Une partie compte dans le groupe dès que ses 4 joueurs en sont membres, même une partie jouée avant la création du groupe ou avant l'arrivée de l'un d'eux. Quitter un groupe en fait sortir, pour tous, les parties où vous avez joué.
- **Un compte invité dans un groupe** : tant qu'il ne l'a pas rejoint, seulement le nom du groupe et le pseudo de celui qui l'a invité.
- **Un compte à qui vous demandez d'être ami** : votre pseudo, avec votre demande.
- **Tous les autres** : rien. Il n'y a ni annuaire ni recherche : on ne trouve un compte que par son pseudo exact, ou en scannant son QR code.

Vos stats de partenaires et d'adversaires ne sont donc visibles que par vous et, pour les parties d'un groupe, par les membres de ce groupe.

### Ajouter un ami, et l'appareil photo

- **« Ajouter par pseudo »** : votre ami reçoit une demande, qu'il accepte ou refuse.
- **« Mon QR code »** montre un code qui change toutes les 10 minutes et ne s'affiche qu'avec le réseau. Celui qui le scanne dans Contrée devient votre ami tout de suite, sans demande : ne le montrez qu'à quelqu'un que vous voulez ajouter.
- **« Scanner un QR code »** utilise l'appareil photo, et seulement pour cela. iOS vous demande l'autorisation une fois ; vous pouvez la retirer dans les Réglages de l'iPhone. L'image est analysée sur l'iPhone, n'est ni enregistrée ni envoyée : seul le code lu part au serveur.

Retirer un ami (« Retirer de mes amis ») arrête de partager vos stats l'un avec l'autre ; vos parties communes restent.

### Bloquer et signaler

- **« Bloquer »**, sur la page d'un ami, en balayant une demande reçue vers la gauche, ou pour un membre d'un de vos groupes, ami ou non (dans l'onglet « Membres », le bouton ⋯ de sa ligne, ou en bas de sa fiche), coupe le contact : l'amitié et les demandes en cours disparaissent, et ce compte ne peut plus vous demander en ami, vous inviter dans un groupe ni vous placer à table. Il n'en est pas prévenu. Vos groupes communs restent : un membre bloqué reste dans le groupe, y voit encore vos stats et vos parties, et vous les siennes ; vous pouvez quitter le groupe (« Quitter le groupe »). Vous débloquez un compte depuis « Comptes bloqués », sur la page Amis (« Débloquer »).
- **« Signaler le pseudo »**, sur la page d'un ami ou pour un membre d'un de vos groupes (le bouton ⋯ de sa ligne, ou sa fiche), **« Signaler »**, en balayant une demande reçue vers la gauche, et **« Signaler »**, pour le nom d'un groupe, à côté de ce nom dans son onglet « Membres » (pour ses membres, sauf son créateur) ou sur une invitation reçue, avant de la rejoindre, envoient un signalement à l'éditeur. Le serveur garde votre compte, le compte ou le groupe visé, la date et, une fois le signalement traité, la date de son traitement, sans message. Il n'est montré à personne d'autre, et le compte signalé n'en est pas prévenu.
- L'éditeur examine les signalements avec un outil du serveur qui ne montre pas qui a signalé. Un pseudo inacceptable est remplacé par un pseudo neutre (« Joueur » suivi d'un nombre), un nom de groupe par « Groupe ».
- Les règles de conduite, le délai de traitement des signalements et ce que fait l'éditeur d'un contenu inacceptable sont dans les [conditions d'utilisation](conditions.md).

### Quand l'app joint le serveur

Avec un compte, l'app joint le serveur au lancement, au retour au premier plan, à la fin d'une partie, au retour du réseau, quand vous tirez une page du compte vers le bas, et à chaque action (choisir son pseudo, ajouter un ami, rejoindre un groupe…). Chaque requête porte la version de l'app, pour qu'une version trop ancienne soit avertie. Au lancement, l'app demande aussi à Apple si votre identifiant Apple autorise toujours Contrée. Rien ne part en arrière-plan, et l'app n'envoie pas de notifications. Hors ligne, on joue comme d'habitude : ce qui doit partir part au retour du réseau.

### Où sont les données : Clever Cloud, en France

Le serveur de Contrée et sa base de données sont hébergés en France, dans la région de Paris, par **Clever Cloud**, société française. Clever Cloud les héberge pour le compte de l'éditeur, comme sous-traitant au sens du RGPD : il ne peut s'en servir que pour cet hébergement, et doit les protéger au moins comme le dit cette page.

Le serveur ne s'adresse qu'à Apple, et ne lui envoie que ce qu'Apple a lui-même délivré : à la connexion, le code reçu d'Apple par l'app, pour vérifier la connexion et obtenir le jeton d'Apple ; à la suppression d'un compte, ce jeton, pour le révoquer.

- **Journaux techniques** : le serveur note chaque requête reçue (l'action demandée, et parfois l'identifiant technique du compte, du groupe ou de la partie qu'elle vise) et ses erreurs, sans pseudo ni contenu de partie. Ces journaux sont gardés 7 jours.
- **Adresse IP** : comme tout hébergeur, Clever Cloud reçoit l'adresse IP de l'appareil qui se connecte, pour lui répondre. Le serveur de Contrée ne l'enregistre pas ; Clever Cloud peut en garder une trace dans ses propres journaux techniques.
- **Sauvegardes** : la base du serveur de l'App Store est sauvegardée chaque jour, et ces sauvegardes sont gardées au plus 30 jours.
- **La version de test** de l'app (TestFlight) joint un serveur de test à part, lui aussi chez Clever Cloud, en France, avec ses propres comptes : rien n'y passe du serveur de l'App Store, ni l'inverse. Ce serveur ne reçoit pas les avis d'Apple décrits plus bas : un compte de test se supprime par « Supprimer le compte », dans la version de test.

## Combien de temps les données sont gardées

- **Le compte et ce qui est à lui** (pseudo, amis, demandes, blocages, signalements faits, groupes, invitations, stats, parties comptées) : tant que le compte existe. Un compte inutilisé n'est pas supprimé de lui-même : c'est vous qui le supprimez.
- **Une partie** : tant qu'existe le compte de celui qui l'a comptée. Si vous y étiez placé et que vous supprimez votre compte, elle reste à ses autres joueurs, avec « Compte supprimé » à votre place.
- **Les sessions de vos appareils** : une session ne vaut plus 90 jours après sa dernière utilisation. Elle est effacée à la déconnexion de l'appareil, avec le compte, ou, une fois expirée, à la connexion suivante du compte.
- **Les journaux techniques du serveur** : 7 jours.
- **Les sauvegardes de la base** : au plus 30 jours. Une donnée supprimée en disparaît donc au plus tard 30 jours après.

## Se déconnecter

Sur la page Compte, touchez « Se déconnecter » (tant que vous n'avez pas choisi de pseudo, sur la page Pseudo, sous le champ). Les informations de connexion et le dossier `compte/` sont effacés de cet iPhone, et, si le réseau le permet, sa session est fermée sur le serveur ; sinon, elle expire d'elle-même. Rien d'autre n'est supprimé du serveur : vous retrouvez tout en vous reconnectant.

Les parties comptées sur cet iPhone avec ce compte y restent, cachées jusqu'à votre prochaine connexion avec ce compte ; celles qui n'ont pas encore été envoyées partiront à ce moment-là. La partie en cours lancée avec le compte continue sur cet iPhone, sans compte ni joueurs liés, et ne sera pas envoyée. La confirmation le dit.

## Supprimer vos données

### Sur l'iPhone

- **Une partie de l'historique** : touchez Compte (en haut à gauche), puis « Historique » ; balayez la partie vers la gauche, puis touchez « Supprimer ». Seules les parties sans compte se suppriment ainsi : une partie en ligne disparaît avec le compte qui l'a comptée.
- **La partie en cours** : touchez « Nouvelle partie ». Une partie qui compte au moins une donne jouée est rangée dans l'Historique, après confirmation ; une partie lancée avec un compte part alors sur ce compte, comme abandonnée. Sans donne jouée, « Nouvelle partie » ramène à l'écran de début sans rien ranger dans l'Historique.
- **Les prénoms des joueurs** : ils passent d'une partie à la suivante. Pour les effacer, videz leurs places sur l'écran « Nouvelle partie », ou désactivez « Renseigner les prénoms » avant de commencer la partie.
- **Les noms par défaut des équipes** : videz-les dans Réglages > Noms par défaut.
- **Toutes les données de l'iPhone** : supprimez l'app (appui long sur son icône, puis « Supprimer l'app »). Les fichiers de l'app sont alors effacés de l'iPhone. Une copie peut rester dans vos anciennes sauvegardes d'iPhone jusqu'à ce qu'elles soient remplacées ou supprimées (sur iPhone : Réglages > votre nom > iCloud > Gérer le stockage > Sauvegardes). Supprimer l'app ne supprime pas le compte, et le Trousseau d'iOS peut garder la connexion : touchez « Se déconnecter » avant, si vous ne voulez rien laisser sur l'iPhone.

### Supprimer votre compte

Sur la page Compte, touchez « Supprimer le compte », puis confirmez deux fois (« Supprimer le compte », puis « Supprimer »). Il faut être connecté et en ligne : si la page demande de vous reconnecter, faites-le d'abord. Tant que vous n'avez pas choisi de pseudo, la page Compte est la page Pseudo : touchez « Supprimer le compte », sous le champ, avec les mêmes confirmations. Le serveur révoque d'abord les jetons d'Apple ; s'il n'y parvient pas, rien n'est supprimé, et l'app le dit.

Sont alors supprimés du serveur, définitivement : votre compte et votre pseudo, vos sessions, vos amitiés et vos demandes d'ami, les blocages faits par vous ou contre vous, les signalements faits par vous ou sur vous, votre place dans vos groupes, vos invitations reçues ou faites, vos stats et les parties que vous avez comptées.

Chez les autres joueurs, à leur prochaine synchronisation :

- les parties que vous avez comptées disparaissent pour tout le monde : de l'historique et des stats des joueurs placés, et des groupes ;
- dans les parties comptées par d'autres, votre place perd votre compte et votre pseudo, et affiche « Compte supprimé ». Ces parties leur restent et comptent toujours dans leurs stats, mais sortent des groupes. Sur l'iPhone de celui qui a compté la partie, son fichier garde le pseudo que la partie avait, mais l'app affiche « Compte supprimé » ;
- une partie où le serveur n'avait pas gardé votre compte à table (vous n'étiez pas, ou plus, ami avec celui qui l'a comptée) garde votre pseudo comme un simple prénom ;
- vous quittez la liste d'amis de vos amis, et vos stats avec vous ;
- vos groupes restent à leurs autres membres. Si vous en étiez le créateur, le membre le plus ancien prend votre place ; un groupe dont vous étiez le dernier membre disparaît.

Sur votre iPhone, les informations de connexion et le dossier `compte/` sont effacés. Les parties comptées sur cet iPhone avec ce compte y restent, comme des parties sans compte : vous pouvez alors les supprimer de l'historique. Vos autres appareils font de même à leur prochain contact avec le serveur.

Il peut rester une copie de ces données dans les sauvegardes du serveur, au plus 30 jours.

### Si vous arrêtez « Se connecter avec Apple » pour Contrée

- Si vous retirez Contrée des apps qui utilisent « Se connecter avec Apple », dans les réglages de votre identifiant Apple, Apple en prévient le serveur, qui déconnecte tous vos appareils ; chaque iPhone se déconnecte aussi de lui-même, au lancement suivant de l'app. Le compte n'est pas supprimé : vous le retrouvez à votre prochaine connexion. Pour le supprimer, utilisez « Supprimer le compte ».
- Si vous supprimez votre identifiant Apple, Apple en prévient le serveur de l'App Store, qui supprime aussi votre compte Contrée, comme « Supprimer le compte ».

## Obtenir une copie de vos données

Vos parties et vos stats se consultent dans l'app (« Historique », « Mes stats »). L'app n'a pas de bouton pour exporter vos données : pour en obtenir une copie, écrivez à l'éditeur, en donnant votre pseudo. Il vous envoie ce que le serveur garde de votre compte, dans un format courant et lisible par une machine (JSON). Pour s'assurer que le compte est le vôtre, il peut vous demander de changer un moment votre pseudo pour un mot qu'il vous indique.

## Sécurité

- Les échanges entre l'app et le serveur passent toujours par HTTPS, chiffrés.
- Les jetons de connexion sont rangés dans le Trousseau d'iOS, sur cet iPhone seulement. Un jeton d'accès ne vaut qu'une heure.
- Le serveur ne garde qu'une empreinte des jetons qu'il délivre, et chiffre le jeton d'Apple. La connexion du serveur à sa base est chiffrée. Les clés secrètes restent dans les réglages de l'hébergeur, jamais dans le code.
- Le serveur vérifie à un seul endroit qui a le droit de voir quoi.
- Les changements de pseudo, les demandes d'ami, les QR codes scannés, les signalements, les créations de groupes et les invitations sont limités par heure, contre les abus.
- En cas de violation de données, l'éditeur la signale à la CNIL dans les 72 heures, comme le RGPD le demande, et en informe les joueurs sur cette page.

## Ce que l'app ne fait pas

Avec ou sans compte :

- elle ne fait **aucun suivi** (« tracking ») : pas d'identifiant publicitaire, pas de publicité, pas de mesure d'audience, pas de statistiques d'usage. Les stats de Contrée sont celles de vos parties, et seulement avec un compte ;
- elle n'intègre **aucun SDK ni service tiers** (analyse, publicité, rapports de plantage, réseaux sociaux) ;
- elle ne vend et ne partage **aucune donnée** à des fins commerciales ;
- elle n'accède ni à votre position, ni aux contacts de l'iPhone, ni à vos photos, ni au micro, et n'envoie pas de notifications. La liste d'amis est celle de Contrée, pas vos contacts. L'appareil photo ne sert qu'à scanner le QR code d'un ami.

## Ce qui relève d'Apple et de GitHub

- **App Store** : le téléchargement, les mises à jour, les notes et les avis passent par Apple, selon sa propre politique de confidentialité.
- **TestFlight** : la version de test passe par l'app TestFlight d'Apple, selon sa propre politique de confidentialité ; les retours que vous y envoyez parviennent à l'éditeur.
- **Se connecter avec Apple** : Apple gère votre identifiant Apple et la connexion, selon sa propre politique (voir plus haut).
- **Demande de note** : après quelques parties gagnées, l'app peut afficher la fenêtre d'Apple qui propose de noter l'app. C'est Apple qui gère cette fenêtre et votre réponse. L'éditeur ne voit que les notes et avis publics de l'App Store.
- **Partage avec les développeurs** : si vous avez activé ce partage (Réglages > Confidentialité et sécurité > Analyse et améliorations), Apple peut transmettre à l'éditeur des rapports de plantage et des statistiques anonymes et agrégées. Ces informations sont recueillies par iOS, pas par l'app. Vous pouvez désactiver ce partage à tout moment.
- **Liens vers ce site** : les liens « Politique de confidentialité », « Conditions d'utilisation » et « Assistance » des Réglages, et le lien des conditions d'utilisation sous « Se connecter avec Apple », ouvrent ces pages dans Safari. Elles sont hébergées par GitHub (GitHub Pages), qui peut conserver des journaux techniques de leur consultation (adresse IP, par exemple) selon sa propre politique de confidentialité.

## Pourquoi ces données sont traitées (base légale)

Sans compte, l'éditeur ne traite aucune donnée. Avec un compte :

- **le compte et ce qu'il permet** (pseudo, parties en ligne, amis, groupes, stats) : c'est le service que vous demandez en créant le compte, qui ne peut pas fonctionner sans ces données (exécution du service, article 6.1.b du RGPD) ;
- **la sécurité, les journaux techniques, le filtre des pseudos et des noms de groupe, le blocage et les signalements** : l'intérêt légitime de l'éditeur à protéger le service et ses joueurs (article 6.1.f), et les règles de l'App Store, qui les demandent pour tout contenu créé par les utilisateurs ;
- **les prénoms tapés aux places sans compte** : l'intérêt légitime des joueurs à garder le détail de leurs parties et à le partager avec ceux qui les ont jouées (article 6.1.f).

## Vos droits

Le RGPD vous donne un droit d'accès, de rectification, d'effacement, de portabilité, d'opposition et de limitation sur vos données personnelles. Avec Contrée :

- **accès et portabilité** : écrivez à l'éditeur, qui vous envoie une copie de vos données (voir plus haut) ;
- **rectification** : changez votre pseudo sur la page Compte ; pour le reste, écrivez à l'éditeur ;
- **effacement** : « Supprimer le compte », dans l'app ; si vous ne pouvez plus ouvrir l'app, écrivez à l'éditeur, avec votre pseudo ;
- **opposition et limitation** : écrivez à l'éditeur. Vous pouvez aussi vous déconnecter ou supprimer votre compte à tout moment.

Ces droits valent aussi pour une personne dont le prénom a été tapé dans une partie. L'éditeur répond dans un délai d'un mois. Sans compte, vos données sont sur votre iPhone, sous votre seul contrôle.

Pour toute question, écrivez à l'adresse ci-dessous. Si vous estimez que vos droits ne sont pas respectés, vous pouvez adresser une réclamation à la CNIL ([www.cnil.fr](https://www.cnil.fr)).

## Enfants

Contrée ne demande jamais l'âge. Sans compte, elle ne collecte rien, auprès de personne. Si vous avez moins de 15 ans, demandez l'accord d'un parent avant de créer un compte. Un parent peut supprimer le compte depuis l'app (« Supprimer le compte »), ou écrire à l'éditeur.

## Modifications de cette politique

Si cette politique change, cette page est mise à jour, et sa date aussi. Une nouvelle version de l'app ne commencera jamais à collecter de nouvelles données sans que cette page le dise d'abord, et sans que la fiche App Store soit mise à jour en conséquence.

La politique de Contrée 1.0 disait que l'app ne collectait aucune donnée : c'est toujours vrai sans compte. Le compte de la 2.0.0, facultatif, est la seule raison de cette nouvelle politique.

## Contact

**Mathieu de Campou**<br>
**[humbles-mansarde.9a@icloud.com](mailto:humbles-mansarde.9a@icloud.com)**
