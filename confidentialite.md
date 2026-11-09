# Politique de confidentialité de Rythmo

*Dernière mise à jour : 9 novembre 2026*

Rythmo est une application Android qui crée des plans d'entraînement de course à pied (et de triathlon) et les adapte
à vos séances. Elle est développée par un développeur indépendant (compte GitHub **Martinouse05**).

**En résumé : vos données restent sur votre téléphone.** Rythmo n'a pas de serveur, pas de compte utilisateur,
pas de publicité, pas de statistiques d'utilisation, pas de traceur. Le développeur ne reçoit aucune de vos données.

## 1. Les données que vous saisissez

Pour construire votre plan, Rythmo vous demande : votre objectif (course, date, chrono visé), votre expérience et
votre volume actuel, vos jours disponibles, vos chaussures, et, si vous le souhaitez, votre sexe, votre âge, votre
poids, votre taille, vos chronos récents, votre VMA et vos autres sports. Vous notez ensuite vos séances dans le
journal (séance faite, ressenti, douleur éventuelle, notes) et vous pouvez écrire au coach intégré.

**Où ces données sont gardées :** uniquement sur votre téléphone, dans la mémoire de l'application, avec une copie
de secours dans le stockage privé de l'application sur Android (pour les retrouver si la mémoire de la page est
vidée). Le coach fonctionne entièrement sur le téléphone : vos messages ne sont envoyés à personne.

**À quoi elles servent :** uniquement à calculer votre plan, vos allures et vos statistiques, et à adapter les
semaines suivantes.

## 2. Health Connect (facultatif)

Si vous l'activez, Rythmo **lit** dans Health Connect les données suivantes, et rien d'autre :

| Donnée Health Connect | Utilisation dans Rythmo |
|---|---|
| Exercices (séances enregistrées par votre montre ou une autre appli) | Retrouver les sorties faites, cocher les séances du plan et adapter les semaines suivantes |
| Fréquence cardiaque | Afficher la fréquence cardiaque moyenne et maximale de la séance et sa courbe, estimer l'intensité réelle |
| Distance | Comparer la distance courue au plan et calculer le volume de la semaine |
| Calories actives | Afficher les calories dépensées dans le détail de la séance |

Rythmo n'écrit rien dans Health Connect. Les données lues restent sur votre téléphone : elles ne sont **jamais**
envoyées au développeur, à intervals.icu ni à aucun tiers, jamais vendues, et jamais utilisées pour de la publicité.
Vous pouvez retirer l'accès à tout moment dans les réglages de Health Connect.

L'utilisation par Rythmo des informations reçues de Health Connect respecte la politique d'autorisations de
Health Connect, y compris les exigences d'utilisation limitée (*Limited Use*).

## 3. intervals.icu (facultatif)

Si vous connectez votre compte intervals.icu (pour envoyer les séances à votre montre et récupérer vos sorties) :

- la clé d'accès (clé API) que vous collez dans Rythmo reste **uniquement sur votre téléphone** ; elle n'est jamais
  incluse dans les sauvegardes ;
- Rythmo **envoie** à votre calendrier intervals.icu les séances prévues de votre plan (date, nom, durée, structure
  et allures ou zones visées), et supprime celles qu'il avait envoyées et qui ne font plus partie du plan ;
- Rythmo **lit** vos activités récentes (date, type, durée, distance, fréquence cardiaque, cadence, tours, courbes de
  vitesse et de fréquence cardiaque) pour remplir votre journal.

Ces échanges se font directement entre votre téléphone et intervals.icu, de façon chiffrée (HTTPS). Le développeur de
Rythmo n'y a pas accès. Les données présentes sur intervals.icu relèvent de la
[politique de confidentialité d'intervals.icu](https://www.intervals.icu/privacy-policy/).

## 4. Sauvegarde

Le bouton « Sauvegarder » crée un fichier contenant vos données Rythmo (sans la clé intervals.icu) et ouvre le menu de
partage d'Android : c'est **vous** qui choisissez où le garder (Google Drive, e-mail, fichiers du téléphone…).
Rythmo ne l'envoie nulle part de lui-même.

## 5. Autres connexions

- **Recherche de mise à jour :** Rythmo lit un petit fichier public sur GitHub (`version.json`) pour savoir si une
  nouvelle version existe. Aucune donnée personnelle n'est envoyée ; comme pour tout site web, GitHub reçoit les
  informations techniques de connexion (adresse IP).
- **Voix pendant les séances guidées :** elle utilise le moteur de synthèse vocale installé sur votre téléphone.

## 6. Conservation et suppression

Vos données restent sur le téléphone tant que vous gardez l'application. Pour tout effacer : **Réglages → Mes données
→ Effacer et recommencer**, ou désinstallez l'application. Les séances envoyées à intervals.icu se suppriment depuis votre
compte intervals.icu. Les fichiers de sauvegarde que vous avez créés se suppriment là où vous les avez rangés.

## 7. Sécurité

Les échanges avec intervals.icu et GitHub sont chiffrés (HTTPS). Les données sont gardées dans l'espace privé de
l'application, inaccessible aux autres applications.

## 8. Enfants

Rythmo ne s'adresse pas aux enfants de moins de 13 ans et ne collecte sciemment aucune donnée les concernant.

## 9. Modifications et contact

En cas de changement, cette page est mise à jour et sa date modifiée. Pour toute question :
[ouvrir une demande sur GitHub](https://github.com/Martinouse05/rythmo-releases/issues).

---

# Rythmo privacy policy (English)

*Last updated: 9 November 2026*

**Your data stays on your phone.** Rythmo has no server, no user account, no ads, no analytics and no trackers.
The developer receives none of your data.

- **Data you enter** (goal, race date, target time, experience, weekly volume, available days, shoes, and optionally
  sex, age, weight, height, recent race times, VO2max speed, other sports; training log, feelings, notes, coach
  messages) is stored only on your device, with a backup copy in the app's private Android storage, and is used only
  to build and adapt your plan. The built-in coach runs entirely on the device.
- **Health Connect (optional, read-only):** exercise sessions, heart rate, distance and active calories, used to mark
  completed sessions, show heart rate and calories in the session details and adapt the plan. This data never leaves
  the device, is never sent to the developer, intervals.icu or any third party, never sold and never used for ads.
  Rythmo's use of information received from Health Connect adheres to the Health Connect Permissions policy,
  including the Limited Use requirements. Access can be revoked at any time in Health Connect.
- **intervals.icu (optional):** your API key stays on your device (never included in backups). Rythmo sends your
  planned sessions to your intervals.icu calendar and reads your recent activities, directly between your phone and
  intervals.icu over HTTPS. See [intervals.icu's privacy policy](https://www.intervals.icu/privacy-policy/).
- **Backup:** created only when you tap the button; you choose where to keep the file.
- **Update check:** Rythmo reads a public `version.json` file on GitHub; no personal data is sent.
- **Deletion:** Settings → My data → Delete and start over, or uninstall the app.
- **Children:** Rythmo is not directed at children under 13.
- **Contact:** [open an issue on GitHub](https://github.com/Martinouse05/rythmo-releases/issues).
