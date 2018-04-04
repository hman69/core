Änderungsprotokoll 
=========

3.2.2
=====

-   Possibilité d'afficher les graphiques sous forme de tableau ou d'exporter ceux-ci en csv ou xls

-   Les utilisateurs peuvent maintenant ajouter leur propre fonction php pour les scénarios. Voir documentation des scénarios pour la mise en place

-   JEED-417 : ajout d'une fonction time_diff dans les scénarios

-   Ajout d'un délai configurable avant réponse sur les intéractions (permet d'attendre que le retour d'état se fasse par exemple)

-   JEED-365 : Löschen des "Benutzerinformationsbefehls", der durch Nachrichtenaktionen ersetzt werden soll. Das ermöglicht Ihnen, mehrere verschiedene Befehle zu starten, um ein Szenario zu starten ... Achtung, wenn Sie einen "Benutzerinformationsbefehls" haben, muss er neu konfiguriert werden.

-   Option hinzugefügt, um den Zugang zum Support zu erleichtern (auf der Benutzerseite und beim Öffnen eines Tickets)

-   Es wurde ein Fehler der Rechte nach einer Wiederherstellung einer Sicherung behoben

-   Aktualisierte Übersetzungen

-   Bibliotheken aktualisiert (jquery und highcharts)

-   Die Möglichkeit, einen Befehl in den automatischen Interaktionen
    zu verbieten

-   Verbesserte automatische Interaktionen

-   Fehler bei der Verwaltung von Interaktionen Synonyme behoben

-   Ein Benutzersuchfelds für LDAP/AD-Verbindungen hinzugefügt
    (ermöglicht Jeedom AD kompatibel zu machen)

-   Rechtschreibkorrekturen (Dank an dab0u für seine enorme Arbeit)

-   JEED-290 : Sie können sich nicht mehr mit den Standard Anmeldedaten 
    (admin/admin) aus der Entfernung verbinden, nur das lokale Netzwerk ist erlaubt

-   JEED-186 : Man kann jetzt die Grundfarbe in den Designs
    wählen

-   Für Block A, die Möglichkeit, eine Zeit zwischen 00:01 und 00:59 
    einzustellen, indem man einfach die Minuten eingibt (ex 30 für 00:30)

-   Hinzufügen aktiver Sitzungen und Geräte, die auf der Profilseite 
    des Benutzers und der Benutzerverwaltungsseite
    registriert sind

-   JEED-284 : Die permanente Verbindung hängt nun von einem eindeutigen 
    Benutzer und einem peripheren Schlüssel ab (und nicht nur vom Benutzer)

-   JEED-283 : Hinzufügen eines Rettungsmodus zu Jeedom durch Hinzufügen 
    von &rescue=1 in der URL

-   JEED-8: Hinzufügen des Namens des Szenarios zum Titel der Seite während der Ausgabe
    der Ausgabe

-   Optimierung organisatorischer Änderungen (Widgets-Größe, Geräteposition, 
    Befehlsposition) auf dem Armaturenbrett und den Ansichten.
    Achtung, Änderungen werden nur gespeichert, wenn Sie den 
    Bearbeitungsmodus verlassen.

-   JEED-18 : Hinzufügen von Protokollen beim Öffnen eines zu unterstützenden Tickets

-   JEED-181 : Hinzufügen eines Namensbefehls in den Szenarien, um den 
    Namen des Befehls oder des Geräts oder Objekts abzurufen

-   JEED-15 :  Batterie und Warnung auf der Webapp hinzugefügt

-   Fehler im Firefox Behoben, beim Verschieben von Objekten im Design 

-   JEED-19 : Bei einem Update ist es jetzt möglich, das Update Skript vor 
    der Aktualisierung auf den neuesten Stand zu bringen

-   JEED-125 : einen Link zur Dokumentation, zum Zurücksetzen 
    des Passworts, hinzugefügt

-   JEED-2 : Verbesserte Zeitverwaltung während eines Neustarts

-   JEED-77 :  Verwaltung der Variablen in der http-API hinzugefügt

-   JEED-78 : Hinzufügen der Tag-Funktion für die Szenarien. Beachten Sie, 
    dass es in den Szenarien mit den Tags notwendig ist, von *Montag* zu 
    Tag (Montag) zu wechseln

-   JEED-124 : Die Verwaltung der Timeouts in den Szenarien korrigiert

-   Fehlerkorrekturen

-   Möglichkeit, eine Interaktion zu deaktivieren

-   Einen Dateieditors hinzugefügt (nur für 
    erfahrene Benutzer)

-   Die Generischen Typen "Licht Zustand" (Binär), "Licht 
    Farbtemperatur" (Info), "Licht Licht Farbtemperatur" (Aktion) hinzugefügt

-    Die Möglichkeit obligatorische Wörter in einer Interaktion zurückzugeben

3.1.7 
=====

-   Fehler Korrekturen (besonders bei historischen und 
    statistischen Funktionen)

-   Verbesserung des Updatesystems mit einer Seite mit Versionshinweisen (die Sie vor jedem Update selbst überprüfen müssen !!!!)
     (die Sie vor jedem Update selbst überprüfen 
    müssen !!!!)

-   Es wurde ein Fehler behoben, durch den Protokolle während der Wiederherstellung wiederhergestellt wurden

3.1 
===

-   Fehlerkorrekturen

-   globale Jeedom Optimierung (beim Laden von Plugin Klassen, 
    Zeit fast durch 3 geteilt)

-   Support für Debian 9

-   Modus eine Seite (Seitenwechsel, ohne die gesamte Seite neu zu laden, nur 
    der Teil, der sich ändert)

-   Es wurde eine Option hinzugefügt, um die Objekte im Armaturenbrett 
    auszublenden, sie aber immer in der Liste zu haben

-   Un double-clic sur un noeud sur le graphique de lien (sauf pour
    les variables) amène sur sa page de configuration

-   Possibilité de mettre le texte à gauche/droit/au centre sur les
    designs pour les élements de type texte/vue/design

-   Ajout des résumés d’objets sur le dashboard (liste des objets
    à gauche)

-   Ajout des interactions de type "previens-moi-si"

-   Revue de la page d’acceuil des scénarios

-   Ajout d’un historique de commandes pour les commandes SQL ou système
    dans l’interface de Jeedom

-   Possibilité d’avoir les graphiques d’historiques des commandes en
    webapp (par appui long sur la commande)

-   Ajout de l’avancement de l’update de la webapp

-   Reprise en cas d’erreur de mise à jour de la webapp

-   Suppression des scénarios "simples" (redondant avec la configuration
    avancée des commandes)

-   Ajout de hachurage sur les graphs pour distinguer les jours

-   Refonte de la page des interactions

-   Refonte de la page profils

-   Refonte de la page d’administration

-   Ajout d’une "santé" sur les objets

-   Correction de bug sur le niveau de batterie des équipements

-   Ajout de méthode dans le core pour la gestion des commandes mortes
    (doit être ensuite implementée dans le plugin)

-   Possibilité d’historiser des commandes de type texte

-   Sur la page historique vous pouvez maintenant faire le graphique
    d’un calcul

-   Ajout d’une gestion de formule de calcul pour les historiques

-   Remise à jour de toute la documentation :

    -   Toute les docs ont été revues

    -   Suppression des images pour faciliter la mise à jour et le
        multilingue

-   Plus de choix possibles sur les réglage des tailles de zone dans les
    vues

-   Possibilité de choisir la couleur du texte du résumé d’objet

-   Ajout d’une action remove\_inat dans les scénarios permettant
    d’annuler toutes les programmations des bloc DANS/A

-   Possibilité dans les designs pour les widgets au survol de choisir
    la position du widget

-   Ajout d’un parametre reply\_cmd sur les interactions pour spécifier
    l’id de la commande à utiliser pour répondre

-   Ajout d’une timeline sur la page historique (attention doit etre
    activée sur chaque commande et/ou scénario que vous voulez
    voir apparaitre)

-   Possibilité de vider les évènements de la timeline

-   Possibilité de vider les IPs bannies

-   Correction/amélioration de la gestion des comptes utilisateurs

    -   Possibilité de supprimer le compte admin de base

    -   Prévention du passage en normal du derniere administrateur

    -   Ajout d’une sécurité pour éviter la suppression du compte avec
        lequel on est connecté

-   Possibilité dans la configuration avancé des équipements de mettre
    la disposition des commandes dans le widgets en mode table en
    choissisant pour chaque commande la case ou la mettre

-   Possibilité de reorganiser les widgets des équipements depuis le
    dashboard (en mode edition clic droit sur le widget)

-   Changement du pas des widgets (de 40\*80 à 10\*10). Attention cela
    va impacter la disposition sur votre dashboard/vue/design

-   Possibilité de donner une taille de 1 à 12 aux objets sur le
    dashboard

-   Possibilité de lancer independament les actions des scénarios (et
    plugin type mode/alarm si compatible) en parallèle des autres

-   Possibilité d’ajouter un code d’accès à un design

-   Ajout d’un watchdog independant de Jeedom pour verifier le status de
    MySql et Apache

3.0.11 
======

-   Correction de bugs sur les demandes "ask" en timeout

3.0.10 
======

-   Correction de bugs sur l’interface de configuration des interactions

3.0 
===

-   Suppression du mode esclave

-   Possibilité de déclencher un scénario sur un changement d’une
    variable

-   Les mises à jour de variables déclenchent maintenant la mise à jour
    des commandes d’un équipement virtuel (il faut la dernière version
    du plugin)

-   Possibilité d’avoir une icone sur les commandes de type info

-   Possibilité sur les commandes d’afficher le nom et l’icone

-   Ajout d’une action "alert" sur les scénarios : message en haut dans
    jeedom

-   Ajout d’une action "popup" sur les scénarios : message à valider

-   Les widgets des commandes peuvent maintenant avoir une méthode
    d’update ce qui évite un appel ajax à Jeedom

-   Les widgets des scénarios sont maintenant mis à jour sans appel ajax
    pour avoir le widget

-   Le résumé global et des pièces sont maintenant mis à jour sans appel
    ajax

-   Un clic sur un élément d’un résumé domotique vous amène sur une vue
    détaillée de celui-ci

-   Vous pouvez maintenant mettre dans les résumés des commandes de type
    texte

-   Changement des bootstraps slider en slider (correction du bug du
    double événement des sliders)

-   Sauvegarde automatique des vues lors du clic sur le bouton "voir le
    résultat"

-   Possibilité d’avoir les docs en local

-   Les développeurs tiers peuvent ajouter leur propre système de
    gestion de tickets

-   Refonte de la configuration des droits utilisateurs (tout est sur la
    page de gestion des utilisateurs)

-   Mise à jour des libs : jquery (en 3.0) , jquery mobile, hightstock
    et table sorter, font-awesome

-   Grosse amélioration des designs:

    -   Toutes les actions sont maintenant accessibles à partir d’un
        clic droit

    -   Possibilité d’ajouter une commande seule

    -   Possibilité d’ajouter une image ou un flux vidéo

    -   Possibilité d’ajouter des zones (emplacement cliquable) :

        -   Zone de type macro : lance une série d’actions lors d’un
            clic dessus

        -   Zone de type binaire : lance une série d’actions lors d’un
            clic dessus en fonction de l’état d’une commande

        -   Zone de type widget : affiche un widget au clic ou au survol
            de la zone

    -   Optimisation générale du code

    -   Possibilité de faire apparaître une grille et de choisir sa
        taille (10x10,15x15 ou 30x30)

    -   Possibilité d’activer une aimantation des widgets sur la grille

    -   Possibilité d’activer une aimantation des widgets entre eux

    -   Certains types de widgets peuvent maintenant être dupliqués

    -   Possibilité de verrouiller un élément

-   Les plugins peuvent maintenant utiliser une clef api qui leur est
    propre

-   Ajout d’interactions automatiques, Jeedom va essayer de comprendre
    la phrase, d’exécuter l’action et de répondre

-   Ajout de la gestion des démons en version mobile

-   Ajout de la gestion des crons en version mobile

-   Ajout de certaines informations de santé en version mobile

-   Ajout sur la page batterie des modules en alerte

-   Les objets sans widget sont automatiquement masqués sur le dashboard

-   Ajout d’un bouton dans la configuration avancée d’un
    équipement/d’une commande pour voir les événements de
    celui-ci/celle-ci

-   Les déclencheurs d’un scénario peuvent maintenant être des
    conditions

-   Un double clic sur la ligne d’une commande (sur la page
    de configuration) ouvre maintenant la configuration avancée de
    celle-ci

-   Possibilité d’interdire certaines valeurs pour une commande (dans la
    configuration avancée de celle-ci)

-   Ajout des champs de configuration sur le retour d’état automatique
    (ex revenir à 0 au bout de 4min) dans la configuration avancée d’une
    commande

-   Ajout d’une fonction valueDate dans les scénarios (voir
    documentation des scénarios)

-   Possibilité dans les scénarios de modifier la valeur d’une commande
    avec l’action "event"

-   Ajout d’un champ commentaire sur la configuration avancée d’un
    équipement

-   Ajout d’un système d’alerte sur les commandes avec 2 niveaux :
    alerte et danger. La configuration se trouve dans la configuration
    avancée des commandes (de type info seulement bien sûr). Vous pouvez
    voir les modules en alerte sur la page Analyse → Equipements. Vous
    pouvez configurer les actions sur alerte sur la page de
    configuration générale de Jeedom

-   Ajout d’une zone "tableau" sur les vues qui permet d’afficher une ou
    plusieurs colonnes par case. Les cases supportent aussi le code HTML

-   Jeedom peut maintenant tourner sans les droits root (expérimental).
    Attention car sans les droits root vous devrez manuellement lancer
    les scripts pour les dépendances des plugins

-   Optimisation du calcul des expressions (calcul des tags uniquement
    si présents dans l’expression)

-   Ajout dans l’API de fonction pour avoir accès au résumé (global
    et d’objet)

-   Possibilité de restreindre l’accès de chaque clef api en fonction de
    l’IP

-   Possibilité sur l’historique de faire des regroupements par heure ou
    année

-   Le timeout sur la commande wait peut maintenant être un calcul

-   Correction d’un bug s’il y a des " dans les paramètres d’une action

-   Passage au sha512 pour le hash des mots de passe (le sha1
    étant compromis)

-   Correction d’un bug dans la gestion du cache qui le faisait grossir
    indéfiniment

-   Correction de l’accès à la doc des plugins tiers si ceux-ci n’ont
    pas de doc en local

-   Les interactions peuvent prendre en compte la notion de contexte (en
    fonction de la demande précédente ainsi que celle d’avant)

-   Possibilité de pondérer les mots en fonction de leur taille pour
    l’analyse de la compréhension

-   Les plugins peuvent maintenant ajouter des interactions

-   Les interactions peuvent maintenant renvoyer des fichiers en plus de
    la réponse

-   Possibilité de voir sur la page de configuration des plugins les
    fonctionalités de ceux-ci (interact, cron…​) et de les désactiver
    unitairement

-   Les interactions automatiques peuvent renvoyer les valeurs des
    résumés

-   Possibilité de définir des synomymes pour les objets, équipements,
    commandes et résumés qui seront utilisés dans les réponses
    contextuelles et résumés

-   Jeedom sait gérer plusieurs interactions liées (contextuellement)
    en une. Elles doivent être séparées par un mot clef (par défaut et).
    Exemple : "Combien fait-il dans la chambre et dans le salon ?" ou
    "Allume la lumière de la cuisine et de la chambre."

-   Le statut des scénarios sur la page d’édition est maintenant mis à
    jour dynamiquement

-   Possibilité d’exporter une vue en PDF, PNG, SVG ou JPEG avec la
    commande "report" dans un scénario

-   Possibilité d’exporter un design en PDF, PNG, SVG ou JPEG avec la
    commande "report" dans un scénario

-   Possibilité d’exporter un panel d’un plugin en PDF, PNG, SVG ou JPEG
    avec la commande "report" dans un scénario

-   Ajout d’une page de gestion de rapport (pour les retélécharger ou
    les supprimer)

-   Correction d’un bug sur la date de dernière remontée d’un événement
    pour certains plugins (alarme)

-   Correction d’un bug d’affichage avec Chrome 55

-   Optimisation du backup (sur un RPi2 le temps est divisé par 2)

-   Optimisation de la restauration

-   Optimisation du processus de mise à jour

-   Uniformisation du tmp jeedom, maintenant tout est dans /tmp/jeedom

-   Possibilité d’avoir un graph des différentes liaisons d’un scénario,
    équipement, objet, commande ou variable

-   Possibilité de régler la profondeur des graphiques de lien en
    fonction de l’objet d’origine

-   Possibilité d’avoir les logs des scénarios en temps réel (ralentit
    l’exécution des scénarios)

-   Possibilité de passer des tags lors du lancement d’un scénario

-   Optimisation du chargement des scénarios et pages utilisant des
    actions avec option (type configuration du plugin alarme ou mode)

2.4.6 
=====

-   Amélioration de la gestion de la répétition des valeurs des
    commandes

2.4.5 
=====

-   Correction de bugs

-   Optimierung der Überprüfung von updates

2.4 
---

-   Allgemeine Optimierung

    -   Gruppierung von SQL-Abfragen

    -   Entfernung von unnötigen Abfragen

    -   Passage en cache du pid, état et dernier lancement des scénarios

    -   Passage en cache du pid, état et dernier lancement des crons

    -   Dans 99% des cas plus de requête d’écriture sur la base en
        fonctionnement nominal (donc hors configuration de Jeedom,
        modifications, installation, mise à jour…​)

-   Suppression du fail2ban (car facilement contournable en envoyant une
    fausse adresse ip), cela permet d’accélérer Jeedom

-   Ajout dans les interactions d’une option sans catégorie pour que
    l’on puisse générer des interactions sur des équipements sans
    catégorie

-   Ajout dans les scénarios d’un bouton de choix d’équipement sur les
    commandes de type slider

-   Bootstrap-Update in 2.3.7

-   Ajout de la notion de résumé domotique (permet de connaitre d’un
    seul coup le nombre de lumières à ON, les porte ouvertes, les
    volets, les fenêtres, la puissance, les détections de mouvement…​).
    Tout cela se configure sur la page de gestion des objets

-   Ajout de pre et post commande sur une commande. Permet de déclencher
    tout le temps une action avant ou après une autre action. Peut aussi
    permettre de synchroniser des équipements pour, par exemple, que 2
    lumières s’allument toujours ensemble avec la même intensité.

-   Optimisation des listenner

-   Ajout de modal pour afficher les informations brutes (attribut de
    l’objet en base) d’un équipement ou d’une commande

-   Possibilité de copier l’historique d’une commande sur une autre
    commande

-   Possibilité de remplacer une commande par une autre dans tout Jeedom
    (même si la commande à remplacer n’existe plus)

2.3 
---

-   Korrektur der Filter auf dem Markt

-   Correction des checkbox sur la page d’édition des vues (sur une
    zone graphique)

-   Correction des checkbox historiser, visible et inverser dans le
    tableau des commandes

-   Correction d’un soucis sur la traduction des javascripts

-   Ajout d’une catégorie de plugin : objet communiquant

-   GENERIC_TYPE hinzugefügt

-   Suppression des filtres nouveau et top sur le parcours des plugins
    du market

-   Renommage de la catégorie par defaut sur le parcours des plugins du
    market en "Top et nouveauté"

-   Correction des filtres gratuit et payant sur le parcours des plugins
    du market

-   Correction d’un bug qui pouvait amener à une duplication des courbes
    sur la page d’historique

-   Correction d’un bug sur la valeur de timeout des scénarios

-   correction d’un bug sur l’affichage des widgets dans les vues qui
    prenait la version dashboard

-   Correction d’un bug sur les designs qui pouvait utiliser la
    configuration des widgets du dashboard au lieu des designs

-   Correction de bugs de la sauvegarde/restauration si le nom du jeedom
    contient des caractères spéciaux

-   Optimisation de l’organisation de la liste des generic type

-   Amélioration de l’affichage de la configuration avancée des
    équipements

-   Correction de l’interface d’accès au backup depuis

-   Sauvegarde de la configuration lors du test du market

-   Préparation à la suppression des bootstrapswtich dans les plugins

-   Correction d’un bug sur le type de widget demandé pour les designs
    (dashboard au lieu de dplan)

-   correction de bug sur le gestionnaire d’événements

-   passage en aléatoire du backup la nuit (entre 2h10 et 3h59) pour
    éviter les soucis de surcharge du market

-   Correction du market de widget

-   Correction d’un bug sur l’accès au market (timeout)

-   Correction d’un bug sur l’ouverture des tickets

-   Correction d’un bug de page blanche lors de la mise à jour si le
    /tmp est trop petit (attention la correction prend effet à
    l’update n+1)

-   Ajout d’un tag *jeedom\_name* dans les scénarios (donne le nom
    du jeedom)

-   Correction de bugs

-   Déplacement de tous les fichiers temporaire dans /tmp

-   Amélioration de l’envoi des plugins (dos2unix automatique sur les
    fichiers \*.sh)

-   Refonte de la page de log

-   Ajout d’un thème darksobre pour mobile

-   Possibilité pour les developpeurs d’ajouter des options de
    configuration des widget sur les widgets spécifique (type sonos,
    koubachi et autre)

-   Optimisation des logs (merci @kwizer15)

-   Possibilité de choisir le format des logs

-   Optimisation diverse du code (merci @kwizer15)

-   Passage en module de la connexion avec le market (permettra d’avoir
    un jeedom sans aucun lien au market)

-   Ajout d’un "repo" (module de connexion type la connexion avec
    le market) fichier (permet d’envoi un zip contenant le plugin)

-   Ajout d’un "repo" github (permet d’utiliser github comme source de
    plugin, avec systeme de gestion de mise à jour)

-   Ajout d’un "repo" URL (permet d’utiliser URL comme source de plugin)

-   Ajout d’un "repo" Samba (utilisable pour pousser des backups sur un
    serveur samba et récupérer des plugins)

-   Ajout d’un "repo" FTP (utilisable pour pousser des backups sur un
    serveur FTP et récupérer des plugins)

-   Ajout pour certain "repo" de la possibilité de recuperer le core de
    jeedom

-   Ajout de tests automatique du code (merci @kwizer15)

-   Possibilité d’afficher/masquer les panels des plugins sur mobile et
    ou desktop (attention maintenant par défaut les panels sont masqués)

-   Possibilité de désactiver les mises à jour d’un plugin (ainsi que
    la vérification)

-   Possibilité de forcé la verification des mises à jour d’un plugin

-   Légère refonte du centre de mise à jour

-   Possibilité de désactiver la vérification automatique des mises à
    jour

-   Correction d’un bug qui remettait toute les données à 0 suite à un
    redémarrage

-   Possibilité de configurer le niveau de log d’un plugin directement
    sur la page de configuration de celui-ci

-   Possibilité de consulter les logs d’un plugin directement sur la
    page de configuration de celui-ci

-   Suppression du démarrage en debug des démons, maintenant le niveau
    de logs du démon est le même que celui du plugin

-   Nettoyage de lib tierce

-   Suppression de responsive voice (fonction dit dans les scénarios qui
    marchait de moins en moins bien)

-   Correction de plusieurs faille de sécurité

-   Ajout d’un mode synchrone sur les scénarios (anciennement
    mode rapide)

-   Possibilité de rentrer manuellement la position des widgets en % sur
    les design

-   Refonte de la page de configuration des plugins

-   Possibilité de configurer la transparence des widgets

-   Ajout de l’action jeedom\_poweroff dans les scénarios pour arrêter
    jeedom

-   Retour de l’action scenario\_return pour faire un retour à une
    intéraction (ou autre) à partir d’un scénario

-   Passage en long polling pour la mise à jour de l’interface en temps
    réel

-   Correction d’un bug lors de refresh multiple de widget

-   Optimisation de la mise à jour des widgets commandes et équipements

-   Ajout d’un tag *begin\_backup*, *end\_backup*, *begin\_update*,
    *end\_update*, *begin\_restore*, *end\_restore* dans les scénarios

2.2 
---

-   Correction de bugs

-   Simplification de l’accès aux configurations des plugins à partir de
    la page santé

-   Ajout d’une icône indiquant si le démon est démarré en debug ou non

-   Ajout d’une page de configuration globale des historiques
    (accessible à partir de la page historique)

-   Correction de bugs pour docker

-   Possibilité d’autoriser un utilisateur à se connecter uniquement à
    partir d’un poste sur le réseau local

-   Refonte de la configuration des widgets (attention il faudra
    sûrement reprendre la configuration de certains widgets)

-   Renforcement de la gestion des erreurs sur les widgets

-   Possibilité de réordonner les vues

-   Refonte de la gestion des thèmes

2.1 
---

-   Refonte du système de cache de Jeedom (utilisation de
    doctrine cache). Cela permet par exemple de connecter Jeedom à un
    serveur redis ou memcached. Par défaut Jeedom utilise un système de
    fichiers (et non plus la BDD MySQL ce qui permet de la décharger un
    peu), celui-ci se trouve dans /tmp il est donc conseillé si vous
    avez plus de 512 Mo de RAM de monter le /tmp en tmpfs (en RAM pour
    plus de rapidité et une diminution de l’usure de la carte SD, je
    recommande une taille de 64mo). Attention lors du redémarrage de
    Jeedom le cache est vidé il faut donc attendre pour avoir la
    remontée de toutes les infos

-   Refonte du système de log (utilisation de monolog) qui permet une
    intégration à des systèmes de logs (type syslog(d))

-   Optimisation du chargement du dashboard

-   Correction de nombreux warning

-   Possibilité lors d’un appel api à un scénario de passer des tags
    dans l’url

-   Support d’apache

-   Optimisation pour docker avec support officiel de docker

-   Optimisation pour les synology

-   Support + optimisation pour php7

-   Refonte des menus Jeedom

-   Suppression de toute la partie gestion réseau : wifi, ip fixe…
    (reviendra sûrement sous forme de plugin). ATTENTION ce n’est pas le
    mode maître/esclave de jeedom qui est supprimé

-   Suppression de l’indication de batterie sur les widgets

-   Ajout d’une page qui résume le statut de tous les équipements sur
    batterie

-   Refonte du DNS Jeedom, utilisation d’openvpn (et donc du
    plugin openvpn)

-   Mise à jour de toutes les libs

-   Interaction : ajout d’un système d’analyse syntaxique (permet de
    supprimer les interactions avec de grosses erreurs de syntaxe type «
    le chambre »)

-   Suppression de la mise à jour de l’interface par nodejs (passage en
    pulling toutes les secondes sur la liste des événements)

-   Possibilité pour les applications tierces de demander par l’api les
    événements

-   Refonte du système « d’action sur valeur » avec possibilité de faire
    plusieurs actions et aussi l’ajout de toutes les actions possibles
    dans les scénarios (attention il faudra peut-être toutes les
    reconfigurer suite à la mise à jour)

-   Possibilité de désactiver un bloc dans un scénario

-   Ajout pour les développeurs d’un système d’aide tooltips. Il faut
    sur un label mettre la classe « help » et mettre un attribut
    data-help avec le message d’aide souhaité. Cela permet à Jeedom
    d’ajouter automatiquement à la fin de votre label une icône « ? » et
    au survol d’afficher le texte d’aide

-   Changement du processus de mise à jour du core, on ne demande plus
    l’archive au Market mais directement à Github maintenant

-   Ajout d’un système centralisé d’installation des dépendances sur les
    plugins

-   Refonte de la page de gestion des plugins

-   Ajout des adresses mac des différentes interfaces

-   Ajout de la connexion en double authentification

-   Suppression de la connexion par hash (pour des raisons de sécurité)

-   Ajout d’un système d’administration OS

-   Ajout de widgets standards Jeedom

-   Ajout d’un système en beta pour trouver l’IP de Jeedom sur le réseau
    (il faut connecter Jeedom sur le réseau, puis aller sur le market et
    cliquer sur « Mes Jeedoms » dans votre profil)

-   Ajout sur la page des scénarios d’un testeur d’expression

-   Revue du système de partage de scénario

2.0 
---

-   Refonte du système de cache de Jeedom (utilisation de
    doctrine cache). Cela permet par exemple de connecter Jeedom à un
    serveur redis ou memcached. Par défaut Jeedom utilise un système de
    fichiers (et non plus la BDD MySQL ce qui permet de la décharger un
    peu), celui-ci se trouve dans /tmp il est donc conseillé si vous
    avez plus de 512 Mo de RAM de monter le /tmp en tmpfs (en RAM pour
    plus de rapidité et une diminution de l’usure de la carte SD, je
    recommande une taille de 64mo). Attention lors du redémarrage de
    Jeedom le cache est vidé il faut donc attendre pour avoir la
    remontée de toutes les infos

-   Refonte du système de log (utilisation de monolog) qui permet une
    intégration à des systèmes de logs (type syslog(d))

-   Optimisation du chargement du dashboard

-   Correction de nombreux warning

-   Possibilité lors d’un appel api à un scénario de passer des tags
    dans l’url

-   Support für Apache

-   Optimisation pour docker avec support officiel de docker

-   Optimisation pour les synology

-   Unterstützung + Optimierung für php7

-   Refonte des menus Jeedom

-   Suppression de toute la partie gestion réseau : wifi, ip fixe…
    (reviendra sûrement sous forme de plugin). ATTENTION ce n’est pas le
    mode maître/esclave de jeedom qui est supprimé

-   Suppression de l’indication de batterie sur les widgets

-   Ajout d’une page qui résume le statut de tous les équipements sur
    batterie

-   Refonte du DNS Jeedom, utilisation d’openvpn (et donc du
    plugin openvpn)

-   Mise à jour de toutes les libs

-   Interaction : ajout d’un système d’analyse syntaxique (permet de
    supprimer les interactions avec de grosses erreurs de syntaxe type «
    le chambre »)

-   Suppression de la mise à jour de l’interface par nodejs (passage en
    pulling toutes les secondes sur la liste des événements)

-   Possibilité pour les applications tierces de demander par l’api les
    événements

-   Refonte du système « d’action sur valeur » avec possibilité de faire
    plusieurs actions et aussi l’ajout de toutes les actions possibles
    dans les scénarios (attention il faudra peut-être toutes les
    reconfigurer suite à la mise à jour)

-   Possibilité de désactiver un bloc dans un scénario

-   Ajout pour les développeurs d’un système d’aide tooltips. Il faut
    sur un label mettre la classe « help » et mettre un attribut
    data-help avec le message d’aide souhaité. Cela permet à Jeedom
    d’ajouter automatiquement à la fin de votre label une icône « ? » et
    au survol d’afficher le texte d’aide

-   Changement du processus de mise à jour du core, on ne demande plus
    l’archive au Market mais directement à Github maintenant

-   Ajout d’un système centralisé d’installation des dépendances sur les
    plugins

-   Refonte de la page de gestion des plugins

-   Ajout des adresses mac des différentes interfaces

-   Ajout de la connexion en double authentification

-   Suppression de la connexion par hash (pour des raisons de sécurité)

-   Ajout d’un système d’administration OS

-   Ajout de widgets standards Jeedom

-   Ajout d’un système en beta pour trouver l’IP de Jeedom sur le réseau
    (il faut connecter Jeedom sur le réseau, puis aller sur le market et
    cliquer sur « Mes Jeedoms » dans votre profil)

-   Ajout sur la page des scénarios d’un testeur d’expression

-   Revue du système de partage de scénario

