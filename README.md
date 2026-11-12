# Goalkeeper OS — Elouan

Application de suivi sportif pour gardien de but, déployable sur GitHub Pages. Version autonome sans base de données externe.

## Utiliser

Ouvrir https://elouanprg.github.io/goalkeeper-os/ après activation GitHub Pages (Settings → Pages → Deploy from a branch → main → root).

Sur mobile, ajouter le site à l'écran d'accueil. Le suivi se sauvegarde localement dans le navigateur de cet appareil. Exporter des sauvegardes régulièrement.

## Données d'emploi du temps

Le calendrier Satellys est **privé** et n'est pas inclus dans ce dépôt public. Importer le fichier iCalendar dans l'interface (Réglages / Planning). Le fichier exporté depuis le tableur de l'utilisateur est fourni séparément dans la conversation.

Jours de football : mardi et jeudi ; match dimanche. Alternance de 8h30 à 17h ; retour des cours vers 17h30.

## Notifications

GitHub Pages ne prend pas en charge l'envoi des Web Push en arrière-plan sans serveur. Utiliser l'export des rappels au format .ics pour le calendrier du téléphone. Les notifications de test dans l'application ne signifient pas que les notifications automatiques hors ligne sont activées.

## Confidentialité

Application et code publics, mais **pas** les emplois du temps individuels, bilans, données de santé, fichiers personnels, clés secrètes. Les données utilisateur sont stockées côté navigateur.

## Références

ACSM : https://pubmed.ncbi.nlm.nih.gov/41843416/
MDN Web Push : https://developer.mozilla.org/en-US/docs/Web/API/Push_API
