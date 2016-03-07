## XVM Updater v2.8 ##
Adaptations pour la nouvelle version d'XVM :
  * Suppression de l'option "afficher les chances de victoire".
  * Suppression de l'option "afficher les stats".

---

## XVM Updater v2.7.2 ##
  * L'extraction des archives est désormais réalisée par Abbrevia TAbUnzipper au lieu du ShellUnzip de Windows.
  * Correction du bug causant la mauvaise détection du répertoire d'installation de WoT.
  * Optimisation de l'icône de l'application et réduction de la taille de l'exécutable.

---

## XVM Updater v2.7.1 ##
  * Ajout de CONFIG\_RTC afin de permettre la compatibilité avec les anciens fichiers de démarrage de configuration.
  * Changements mineurs de l'interface.
  * Optimisations mineures du code.

---

## XVM Updater v2.7 ##
  * Suppression du code inutile.
  * Amlioration de la détection automatique du répertoire d'installation.
  * Ajout de l'affichage dynamique de la révision de la dernière nightly.
  * Correction de l'erreur de violation d'accès mémoire silencieuse causant une mauvaise détection de la version du jeu.
  * Correction de l'affichage de code HTML dans les menus déroulants dans de rares cas.
  * Ajout du Néerlandais.
  * Correction de la traduction russe.
  * Correction de la traduction polonaise.

---

## XVM Updater v2.6 ##
  * Correction d'un bug causant un mauvais fonctionnement de l'option 'Garder l'ancienne configuration'.
  * Ajout du Finlandais.
  * Correction de la traduction allemande.

---

## XVM Updater v2.5 ##
Adaptations pour la nouvelle version d'XVM :
  * Ajout d'une option pour activer l'affichage des stats des joueurs.
  * Suppression de l'option activant la minimap.
  * Suppression de l'option chargée de créer un raccourci sur le bureau.
  * Suppression de fonctions désormais inutiles dans le code.

---

## XVM Updater v2.4 ##
  * Optimisations du code.
  * Ajout de la vérification des librairies .NET Framework 3.5 et Visual C++ 2005 SP1, XVM Updater les installera si besoin.
  * Correction de la sélection du répertoire d'installation de WoT (cliquer sur 'Non' ne fermait pas la fenêtre).
  * Correction du téléchargement des configs pré-fournies des versions précédentes de WoT (les erreurs de téléchargement n’interrompront plus la mise à jour).
  * Correction de la variable %TEMP% causant l'erreur 'OS unsupported' lors de l'installation de Dokan sur Windows 8.
  * Correction d'un bug mineur dans l'affichage des traductions.
  * Amélioration de l'aspect visuel de la barre de progression lorsque l'installation d'une librairie ou l'extraction de fichiers est en cours.
  * XVM Updater est maintenant capable d'auto-élever ses privilèges afin de tourner correctement sur des comptes utilisateurs limités.
  * Vous pouvez désormais fermer le programme n'importe quand.

---

## XVM Updater v2.3 ##
  * Ajout du hongrois dans les traductions.
  * Optimisations mineures du code.
  * Correction d'un bug critique empêchant la fin du script d'installation (la création du raccourci et le nettoyage des fichiers temporaires) d'être exécutée.
  * Correction de la procédure d'activation de la minimap (ajout du support des commentaires dans le code).
  * Correction du traitement de l'UTF-8 dans toutes les procédures d'édition du fichier de configuration (les caractères UTF-8 étaient remplacés par des '?').

---

## XVM Updater v2.2 ##
  * Support multi-langage (actuellement Anglais, Français, Allemand, Polonais, Russe, Ukrainien).
  * Modifications mineures de l'interface afin de caser toutes les langues.
  * Correction d'un bug rare rendant impossible la création du raccourci sur le bureau.
  * Correction d'un bug d'encodage de caractères dans la procédure d'activation de la Minimap.

---

## XVM Updater v2.1.1 ##
  * Correction d'un bug inconnu générant une erreur de violation d'adresse mémoire silencieusement lors de la vérification de la version du jeu.
  * Correction d'un bug critique causant une exception "indice de liste hors limite" dans de rares cas.

---

## XVM Updater v2.1 ##
  * Correction de quelques bugs d'interface.
  * Correction définitive du mode compatibilité pour Windows 8.
  * Ajout de l'option 'Activer la fonctionnalité Minimap'.

---

## XVM Updater v2.0.1 ##
  * Optimisations mineures du code.
  * Correction du mode de compatibilité Win7 pour Windows 8.
  * Correction d'un message d'erreur incorrect.
  * Correction de quelques fonctions utilitaires.
  * Code retravaillé afin d'éviter les faux-positifs de certains antivirus.

---

## XVM Updater v2.0 ##
  * Optimisation du code.
  * Suppression du système de rapport d'installation.
  * Correction d'un bug d'affichage mineur dans la version francophone.
  * Correction d'un bug d'affichage de la barre de progression lorsque l'installation est terminée.
  * Modification de la sélection manuelle du dossier d'installation ("worldoftanks.exe" doit maintenant être obligatoirement présent).
  * Modification de l'interface : suppression de la section 'À propos' et changement de quelques contrôles.
  * Ajout du support des versions tests d'XVM (liste des versions compatibles dynamiquement téléchargée à l'exécution).
  * Ajout du choix du fichier de configuration à partir d'une sélection (sélection dynamiquement téléchargée à l'exécution).
  * Ajout du support de Windows 8 pour l'installation de Dokan (activation du mode compatibilité pour Windows 7).
  * Changement de l'icône du programme.
  * Le code source est maintenant disponible sous licence GPL.

---

## XVM Updater v1.1.1 ##
  * Modifications mineures de l'interface.
  * Optimisation et correction du code.
  * Correction de l'affichage des erreurs.
  * Correction de l'option 'Garder l'ancienne configuration d'XVM' :
    1. Une copie de sauvegarde de votre fichier de configuration actuel est désormais faite.
    1. Le fichier de config actuel est préservé même si un vieux fichier de config existe déjà.
  * Diminution considérable du poids de l'application (désormais ~450 ko).

---

## XVM Updater v1.1 ##
  * Amélioration considérable de la détection automatique du répertoire d'installation.
  * Amélioration de certaines traductions/boites de dialogue.
  * Amélioration de l'interface.
  * Amélioration de la procédure d’interprétation du script.
  * Correction d'une erreur apparaissant aléatoirement à la fin de l’interprétation.
  * Correction d'une erreur apparaissant si un disque/lecteur n'était pas prêt.
  * Ajout de l'option d'affichage des chances de victoire.
  * On peut désormais forcer l'origine du script depuis la ligne de commande (ex: "XVM\_Updater.exe TEST.script").
  * On peut désormais arrêter l'installation/mise à jour dès que l'action en cours est terminée.
  * Si un erreur survient lors du téléchargement, la raison de l'erreur est désormais affichée.

---

## XVM Updater v1.0.1 ##
  * Correction de l'erreur de violation mémoire.
  * Correction de la vérification des fichiers systèmes.
  * Amélioration de la détection automatique du répertoire d'installation de World of Tanks.

---

## XVM Updater v1.0 ##
  * Toutes les fonctions finales sont désormais implémentées.
  * Code retravaillé.
  * Ajout du support des rapports d'installation.
  * Ajout de la localisation (anglais/français).
  * Ajout des liens dans la section 'À propos'.
  * Ajout du support du téléchargement de fichiers redirigés.
  * La procédure d'installation/mise à jour prend désormais en compte la version du client (afin d'obtenir le bon script quand une nouvelle version du jeu est installée).
  * La procédure d'installation/mise à jour vérifie désormais si le client est fermé avant de procéder (sinon le programme peut se bloquer).
  * Correction de bug dans la fonction IF\_NEXISTS (le bloc d'instruction n'était jamais exécuté).
  * Correction de bug dans le remplacement de la variable %WINDOWS%.
  * Correction de bugs mineurs dans la procédure d’interprétation du script.
  * Correction de bug mineur en cas d'échec du téléchargement des fichiers.
  * Nouvelle icône.

---

## XVM Updater v1.0 RC1 ##
  * Première version de cet utilitaire, afin de tester si tout fonctionne bien.