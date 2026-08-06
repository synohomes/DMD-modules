# DMD-modules
Modules pour Domydesk.


# Modules DoMyDesk 1.2

Ce dépôt regroupe les **nouveaux modules développés et adaptés pour DoMyDesk 1.2**.

Il accompagne l'évolution de DoMyDesk vers une plateforme plus homogène, modulaire et mieux intégrée, avec un fonctionnement commun entre les différents modules.

Les modules publiés pour **DoMyDesk 1.2** suivent progressivement un fonctionnement commun afin de mieux s’intégrer à l’environnement général de DoMyDesk, quel que soit leur domaine d’utilisation.

DoMyDesk n’est pas limité aux outils informatiques ou à l’administration de serveurs. Un module peut aussi bien servir à gérer une infrastructure qu’à utiliser un bloc-notes, lancer un minuteur, suivre un compte à rebours, consulter une carte, organiser des informations sur des plantes ou des animaux, utiliser des outils pratiques ou encore proposer des fonctions plus orientées loisirs.

Les mécanismes de DoMyDesk 1.2 sont donc pensés pour être utilisables par des modules très différents.

* **Intégration ActionHub** *(ActionHub permet à un module de déclarer les actions qu’il peut proposer et de les rendre accessibles depuis un système commun à DoMyDesk. Une action n’est pas forcément une opération informatique : il peut s’agir de démarrer un minuteur, créer une note, ouvrir un emplacement sur une carte, ajouter une plante à une collection, modifier une fiche d’animal, lancer une tâche, exporter une information ou effectuer une action sur un équipement. ActionHub permet ainsi aux modules de parler le même langage tout en conservant leur propre fonctionnement.)* ;

* **Prise en charge de Quick-Session** *(Quick-Session permet de créer temporairement un contexte de travail dans DoMyDesk. Une session peut servir pendant une intervention technique, mais aussi pendant une préparation, une recherche, une organisation ou toute activité nécessitant de regrouper plusieurs actions. Par exemple, une session peut contenir la consultation d’une carte, plusieurs notes, une liste de tâches, un timer et différentes informations provenant de plusieurs modules. Les actions réalisées peuvent être associées à cette session jusqu’à sa clôture afin de conserver un historique cohérent de ce qui a été fait.)* ;

* **Système complet de notifications** *(les modules peuvent informer les utilisateurs lorsqu’un événement mérite leur attention. Cela peut être un partage, un nouveau message, une modification de donnée, l’échéance prochaine d’un compte à rebours, une tâche attribuée, une modification de droits, une information provenant d’un autre utilisateur ou tout autre événement pertinent pour le module. Le principe est que les notifications correspondent réellement à des événements utiles et ne soient pas limitées aux fonctions techniques de DoMyDesk.)* ;

* **Gestion des droits et permissions fines** *(DoMyDesk 1.2 permet d’aller plus loin qu’un simple droit “module autorisé” ou “module interdit”. Un utilisateur peut disposer uniquement des fonctions dont il a besoin. Selon le module, les permissions peuvent concerner la lecture, la création, la modification, la suppression, le partage, l’exportation ou certaines actions spécifiques. Cela peut servir pour un serveur ou une imprimante, mais également pour une collection botanique, des fiches animales, des notes partagées, une carte ou n’importe quelle ressource proposée par un module.)* ;

* **Journalisation des actions et événements** *(les modules peuvent conserver un historique des événements importants : création, modification, suppression, partage, exportation, lancement d’une action, changement de configuration, erreur ou autre opération significative. Les journaux ne servent donc pas uniquement à surveiller des serveurs. Ils permettent également de savoir qui a modifié une information, quand un élément a été partagé ou quelle action a été effectuée dans un module collaboratif.)* ;

* **Partage de données ou de ressources entre utilisateurs lorsque le module le permet** *(les modules compatibles peuvent permettre à un utilisateur de partager une donnée ou une ressource avec une autre personne présente sur la même instance DoMyDesk. Il peut s’agir d’un contact, d’une tâche, d’un document, d’une note, d’un emplacement, d’une fiche botanique, d’une fiche animale, d’un inventaire ou de toute autre donnée prévue par le module. Le partage peut prendre différentes formes : accès à une donnée commune, copie dans l’espace du destinataire, transmission d’un élément ou attribution de droits spécifiques.)* ;

* **Interface adaptée au fonctionnement du dashboard DoMyDesk** *(un module est pensé comme un véritable élément du bureau DoMyDesk et non comme une simple page web indépendante. Les modules peuvent être organisés librement dans l’espace de travail et déplacés selon les besoins de l’utilisateur. Lorsqu’un module utilise des fenêtres complémentaires, celles-ci peuvent s’intégrer directement au dashboard afin de conserver une logique de bureau : fiche détaillée, aperçu, impression, PDF, carte, information complémentaire ou configuration peuvent ainsi rester dans l’environnement DoMyDesk.)* ;

* **Compatibilité bureau et mobile** *(DoMyDesk peut être utilisé sur plusieurs types d’appareils. Les modules sont donc progressivement adaptés à une utilisation sur ordinateur, tablette et smartphone. L’objectif n’est pas uniquement de réduire la taille de l’interface, mais également de conserver des actions accessibles au tactile et un affichage utilisable lorsque l’espace disponible devient plus petit.)* ;

* **Intégration avec les thèmes DoMyDesk** *(les modules n’imposent pas leur propre identité graphique au détriment du reste du bureau. Ils utilisent autant que possible les variables et paramètres du thème actif de DoMyDesk. Un module de gestion de serveurs, un bloc-notes, un timer, une carte ou un module botanique peuvent ainsi conserver une identité visuelle cohérente au sein du même environnement.)* ;

* **Stockage persistant séparé du code des modules afin de faciliter les mises à jour** *(les informations créées par les utilisateurs ne doivent pas disparaître lorsqu’un module est remplacé ou mis à jour. Les données persistantes sont donc séparées du code du module. Cela concerne aussi bien une configuration technique que des notes personnelles, des tâches, des collections, des fiches, des historiques ou toute autre donnée enregistrée par un module.)* ;

* **Structure et politique de nommage harmonisées pour les nouveaux modules** *(les modules destinés à DoMyDesk 1.2 suivent progressivement une structure commune et une politique de nommage identifiable, notamment avec la convention `DMD-...`. Cette harmonisation facilite l’installation, les mises à jour, la maintenance et les échanges avec les fonctions communes de DoMyDesk, sans obliger tous les modules à proposer les mêmes fonctions.)*.

Cette nouvelle organisation permet à DoMyDesk de conserver une base commune tout en accueillant des modules extrêmement différents.

Un même dashboard peut par exemple contenir des outils d’administration informatique, un **Timer**, un **Countdown**, un **Bloc-notes**, une **Map**, une liste de tâches, des outils consacrés à la **botanique**, aux **animaux**, à l’impression 3D, aux contacts, aux documents, à l’organisation personnelle ou même à des **jeux**.

C’est justement l’un des principes de DoMyDesk : le bureau n’impose pas un usage précis.

Chaque utilisateur peut construire son environnement avec les modules qui correspondent à ses besoins, qu’ils soient **professionnels, techniques, personnels, pratiques ou liés aux loisirs**.

---

**DoMyDesk — Votre environnement. Vos outils. Votre infrastructure.**
