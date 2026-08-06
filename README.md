# DMD-modules
Modules pour Domydesk.


# Modules DoMyDesk 1.2

Ce dépôt regroupe les **nouveaux modules développés et adaptés pour DoMyDesk 1.2**.

Il accompagne l'évolution de DoMyDesk vers une plateforme plus homogène, modulaire et mieux intégrée, avec un fonctionnement commun entre les différents modules.

Les modules publiés ici sont progressivement adaptés au standard **DoMyDesk 1.2**, avec notamment :

* **Intégration ActionHub** *(permet aux modules d’envoyer leurs actions importantes vers un point central de DoMyDesk ; l’utilisateur peut ainsi retrouver plus facilement les actions disponibles ou liées à un élément sans devoir naviguer dans plusieurs écrans)* ;

* **Prise en charge de Quick-Session** *(permet d’ouvrir une session de travail temporaire autour d’une intervention ou d’une tâche ; les actions réalisées par les modules compatibles peuvent être rattachées à cette session afin de conserver un historique cohérent jusqu’à sa clôture)* ;

* **Système complet de notifications** *(les modules peuvent prévenir les utilisateurs lorsqu’un événement les concerne : partage d’un élément, nouveau message, modification, changement de droits, action effectuée, erreur, information importante, etc. ; les notifications sont centralisées dans DoMyDesk et accessibles depuis la cloche de notification)* ;

* **Gestion des droits et permissions fines** *(il ne s’agit plus uniquement d’autoriser ou non l’accès à un module ; les administrateurs peuvent définir précisément les actions autorisées pour un utilisateur ou un groupe, par exemple consulter, modifier, supprimer, partager, démarrer ou arrêter une ressource selon les possibilités du module)* ;

* **Journalisation des actions et événements** *(les opérations importantes effectuées dans un module sont enregistrées dans des journaux dédiés avec les informations utiles comme la date, l’utilisateur, l’action réalisée, son résultat et éventuellement des détails supplémentaires ; cela permet de suivre l’activité et de comprendre ce qui a été fait)* ;

* **Partage de données ou de ressources entre utilisateurs lorsque le module le permet** *(un élément créé ou géré par un utilisateur peut être transmis ou partagé avec un autre utilisateur DoMyDesk ; selon le module, le destinataire peut recevoir une copie, un accès partagé ou des droits spécifiques sur la ressource concernée)* ;

* **Interface adaptée au fonctionnement du dashboard DoMyDesk** *(les modules sont conçus pour fonctionner directement dans l’espace de travail DoMyDesk et respecter son comportement : déplacement des modules sur le dashboard, organisation libre de l’espace, fenêtres et popups intégrées au bureau plutôt qu’ouverture systématique de nouvelles pages ou de nouveaux onglets)* ;

* **Compatibilité bureau et mobile** *(l’affichage des modules s’adapte à la taille de l’écran afin qu’ils puissent être utilisés aussi bien sur ordinateur que sur smartphone ou tablette, avec une interface responsive et des contrôles utilisables au tactile)* ;

* **Intégration avec les thèmes DoMyDesk** *(les modules utilisent les couleurs, textes, arrière-plans et styles définis par le thème actif de DoMyDesk au lieu d’imposer leurs propres couleurs ; changer de thème permet donc de conserver une interface cohérente dans l’ensemble du bureau)* ;

* **Stockage persistant séparé du code des modules afin de faciliter les mises à jour** *(les données importantes des utilisateurs et des modules ne sont pas enregistrées directement dans le dossier contenant le code du module ; une mise à jour ou un remplacement du module peut ainsi être effectué sans écraser les données existantes)* ;

* **Structure et politique de nommage harmonisées pour les nouveaux modules** *(les modules DoMyDesk 1.2 suivent une organisation commune pour leurs fichiers, leur identification et leur nommage, notamment avec la convention `DMD-...` ; cela facilite leur maintenance, leur installation, les mises à jour et leur intégration avec le cœur de DoMyDesk)*.


L'objectif est de conserver la philosophie de DoMyDesk : permettre à chacun de construire un environnement adapté à ses besoins en ajoutant uniquement les outils qui lui sont utiles.

DoMyDesk ne se limite pas à l'administration informatique. Selon les modules installés, il peut servir à gérer une infrastructure, des contacts, des tâches, des tickets, des documents, des équipements, des inventaires, des imprimantes 3D et bien d'autres usages.

## Installation

Chaque module possède sa propre structure et ses éventuelles instructions d'installation ou de configuration.

Les modules sont destinés à être installés sur une instance compatible de **DoMyDesk 1.2**.

## Évolution

Ce dépôt évoluera au fur et à mesure de la migration des anciens modules et de la création de nouveaux outils.

Certains modules pourront également recevoir de nouvelles fonctionnalités indépendamment des mises à jour du cœur de DoMyDesk.

---

**DoMyDesk — Votre environnement. Vos outils. Votre infrastructure.**
