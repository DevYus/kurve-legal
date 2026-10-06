---
title: Privacy Policy / Politique de confidentialité
---

[Français](#francais) · [English](#english)

# Kürve — Privacy Policy {#english}

[Passer au français](#francais)

*Effective date: 3 October 2026*

This policy applies to the Kürve app for Android and iOS.

## Summary

Kürve is a practice tool for musicians (A-B loop, time-stretch, pitch-shift). It collects no personal
data: there is no Kürve account and no Kürve server. What you import, save and configure is kept on
your device and never leaves it through Kürve; the only way it can leave is your phone's own system
backup, which you control (see "Device backups" below). Kürve also keeps a small error log on your
device (see "Error log" below); Kürve never sends it, and it leaves your device only if you choose to
share it. The only network activity is downloading an offline voice-recognition pack, and only after
you agree to it.

## What Kürve processes, and where

- **Audio tracks and practice sessions.** Kürve keeps its own copy of each track you import, and
  stores your practice sessions — session name, track title, category and length, the location of
  Kürve's copy of the track (which contains the original file name), loop points, bookmarks and
  their names, speed and pitch settings, the track's cover art, and when the session was created and
  last updated — in a database on your device. It also saves a waveform
  preview of each track, and your app settings (language, theme, screen and vibration preferences).
  None of this is ever uploaded or sent anywhere by Kürve; there is no Kürve backend that could
  receive it.
- **Error log.** When Kürve hits an unexpected error, it adds one line to a small log kept on your
  device, in the app's cache (not in the documents or settings storage). Each line holds the time
  (UTC, to the minute), the error's type name, a short label (a Flutter library name, a short fixed
  phrase naming the operation, stored with underscores, e.g. "Importing_a_track", or a platform
  error code; a label that looks like a file name is dropped, so it is never a file name), an
  operating-system error code if there is one, and the locations (file and line) in Kürve's own
  code. It never holds the error message, file paths, file or track names, session or bookmark
  names, audio, voice or transcripts, or any device identifier. The log is limited to about 128 KiB
  (two files, the older one discarded when the newer fills up) and is not part of Android's Auto
  Backup or an iPhone backup. Kürve never sends it. After an unexpected error, a popup asks whether
  you want to send the bug report to the developers; if you tap Yes, or tap "Export the error log"
  in Settings, your phone's share sheet opens with the log file, you choose the app and the
  recipient, and nothing is sent without that action. The text pre-filled in the share names the
  contact address below and the app version, but you choose the recipient. Whichever app you pick
  handles the file under its own policy. If you send a report, the developer uses it only to find
  and fix the bug and does not share it. "No" keeps the log on your device, and "Clear the log" in
  Settings deletes the log and every copy Kürve or the share sheet kept in the app's cache; a copy
  you already sent or saved elsewhere is outside Kürve's reach. To avoid repeated popups, Kürve stores one timestamp of the last time it asked, in the app's settings; it is
  not personal data.
- **Microphone.** With your permission, requested the first time you tap the microphone button in
  the player, the microphone is used only to recognize voice commands (e.g. to start or stop a loop),
  and only while it is listening: tapping the button starts listening, which stops after one command
  or when you tap the button again. If you switch on continuous listening, it keeps listening after
  each command until you tap the button again or close the player. Recognition runs entirely on your
  device, offline. What the microphone hears never leaves your device: it is not recorded to a file,
  not stored and not transmitted.
- **Network access.** The app uses the network for exactly one purpose: downloading the offline
  voice-recognition pack (about 40 MB) for the app's current language (English or French), the first
  time you tap the microphone in that language and agree to the download. The pack is downloaded
  over HTTPS directly from the Vosk speech-recognition project's server (alphacephei.com) and checked
  against a fixed fingerprint before it is used. That request sends no data about your use of the
  app. Like any download, it does reveal to the Vosk server your device's IP address, the standard
  technical information every download includes (Android version and phone model, in the request's
  "User-Agent"), and which language pack you downloaded. No other feature of Kürve uses the network: no analytics, crash-reporting, advertising or
  tracking SDKs are included (the error log above is kept on your device and never sent by Kürve), and fonts are bundled with the app rather than downloaded.
- **Device backups.** Kürve adds no backup of its own, but your phone's system backup can include
  its data:
  - On Android, when Backup is turned on in your system settings, Android's Auto Backup covers your
    practice sessions database and your app settings, and nothing else. It never covers the
    voice-recognition pack (Kürve downloads it again when you need it), the copies of your imported
    tracks or their waveform previews. So after restoring onto a new phone, your sessions come back
    but each track has to be re-linked. What Android does with the cloud backup depends on your
    version: on Android 9 to 11 it is only made when it is encrypted on your phone, and a direct
    phone-to-phone transfer probably copies nothing from Kürve; on Android 12 and later it is only
    made when your phone is able to encrypt it end to end (Android does not check that you turned
    that on), and a direct transfer copies the same data; on Android 7 and 8 it goes to your Google
    account without that condition. In every case the backup goes to your own Google account or new
    device; Kürve's developer has no access to it. You can turn backup off in your Android system
    settings at any time.
  - On iPhone, an iCloud or computer backup includes your practice sessions database and app
    settings, but not the copies of your imported tracks or their waveform previews, which are kept
    in temporary and cache storage that iOS does not back up.
  - The error log is not included in either backup.

## What Kürve does not do

- Kürve does not create user accounts and does not require sign-in.
- Kürve does not share, sell or transmit any data to third parties, because it does not collect any
  in the first place. The error log is never sent by Kürve; it is shared only if you choose to, as
  described above.
- Kürve does not use cookies, advertising identifiers or analytics SDKs.
- Kürve does not access contacts, location, camera or any data other than the microphone audio
  described above, and the files you explicitly import. On Android, Kürve uses two permissions you
  may see: the microphone and network access (only for the voice pack). You pick files through the
  system file picker, which needs no storage permission.

## Deleting your data

Everything Kürve keeps is on your device. Uninstalling the app, or clearing its storage in your
system settings, deletes all of it. On Android, clearing only the app's cache deletes the copies of
your imported tracks, their waveform previews and the error log, but keeps your sessions (each track
then has to be re-linked). "Clear the log" in Settings deletes the log and every copy Kürve or the
share sheet kept in the app's cache; a copy you already sent or saved elsewhere is outside Kürve's
reach. A copy of your data in your own system backup is managed from your Google or Apple account.

## Children's privacy

Kürve does not knowingly collect personal data from anyone, including children, because it does not
collect personal data from any user.

## Changes to this policy

If Kürve's data practices change, this document will be updated before the change ships, and the
"Effective date" above will be revised accordingly.

## Contact

For any question about this policy or your data, write to contact.kurveio@gmail.com. E-mails received there are used only to answer you.

---

# Kürve — Politique de confidentialité {#francais}

[Jump to English](#english)

*Date d'effet : 3 octobre 2026*

Cette politique s'applique à l'application Kürve pour Android et iOS.

## Résumé

Kürve est un outil de travail instrumental (boucle A-B, ralenti, transposition). L'application ne
collecte aucune donnée personnelle : il n'existe ni compte Kürve ni serveur Kürve. Ce que vous
importez, enregistrez et configurez est conservé sur votre appareil et n'en sort jamais par
l'intermédiaire de Kürve ; seule la sauvegarde système de votre téléphone, que vous contrôlez, peut
l'en faire sortir (voir « Sauvegardes de l'appareil » ci-dessous). Kürve conserve aussi un petit
journal d'erreurs sur votre appareil (voir « Journal d'erreurs » ci-dessous) ; Kürve ne l'envoie
jamais, et il ne quitte votre appareil que si vous choisissez de le partager. La seule activité
réseau est le téléchargement d'un pack de reconnaissance vocale hors ligne, et uniquement après votre
accord.

## Ce que Kürve traite, et où

- **Pistes audio et sessions de travail.** Kürve conserve sa propre copie de chaque piste importée,
  et enregistre vos sessions de travail — nom de la session, titre, catégorie et durée de la piste,
  emplacement de la copie de la piste faite par Kürve (qui contient le nom du fichier d'origine),
  points de boucle, signets et leurs noms, réglages de vitesse et de hauteur, pochette de la piste,
  dates de création et de dernière modification de la session — dans une base de données sur votre
  appareil. Il enregistre aussi un aperçu de la forme d'onde de chaque piste, ainsi que vos réglages
  (langue, thème, préférences d'écran et de vibration). Kürve n'envoie jamais rien de tout cela où que
  ce soit : il n'existe pas de serveur Kürve susceptible de le recevoir.
- **Journal d'erreurs.** Lorsque Kürve rencontre une erreur inattendue, il ajoute une ligne à un
  petit journal conservé sur votre appareil, dans le cache de l'application (et non dans le stockage
  des documents ou des réglages). Chaque ligne contient l'heure (UTC, à la minute), le nom du type de
  l'erreur, un court libellé (le nom d'une bibliothèque Flutter, une courte expression fixe désignant
  l'opération, enregistrée avec des tirets bas, par exemple « Importing_a_track », ou un code
  d'erreur de la plateforme ; un libellé qui ressemble à un nom de fichier est supprimé, il n'est
  donc jamais un nom de fichier), un code d'erreur du système d'exploitation s'il y en a un, et les
  emplacements (fichier et ligne) dans le code de Kürve lui-même. Il ne contient jamais le message de
  l'erreur, les chemins de fichiers, les noms de fichiers ou de pistes, les noms de sessions ou de
  signets, l'audio, la voix ou les transcriptions, ni aucun identifiant de l'appareil. Le journal est
  limité à environ 128 Kio (deux fichiers, le plus ancien étant supprimé quand le plus récent est
  plein) et ne fait partie ni de la sauvegarde automatique d'Android ni d'une sauvegarde iPhone.
  Kürve ne l'envoie jamais. Après une erreur inattendue, une fenêtre vous demande si vous voulez
  envoyer le rapport de bug aux développeurs ; si vous touchez Oui, ou « Exporter le journal des
  erreurs » dans les réglages, la feuille de partage de votre téléphone s'ouvre avec le fichier du
  journal, vous choisissez l'application et le destinataire, et rien n'est envoyé sans cette action.
  Le texte pré-rempli du partage mentionne l'adresse de contact ci-dessous et la version de
  l'application, mais c'est vous qui choisissez le destinataire. L'application que vous choisissez
  traite le fichier selon sa propre politique. Si vous envoyez un rapport, le développeur ne
  l'utilise que pour trouver et corriger le bug et ne le partage pas. « Non » conserve le journal sur
  votre appareil, et « Effacer le journal » dans les réglages supprime le journal et toute copie que
  Kürve ou la feuille de partage a conservée dans le cache de l'application ; une copie que vous avez
  déjà envoyée ou enregistrée ailleurs échappe à Kürve. Pour éviter
  les fenêtres répétées, Kürve enregistre dans les réglages de l'application un seul horodatage de la
  dernière fois qu'il a posé la question ; ce n'est pas une donnée personnelle.
- **Microphone.** Avec votre autorisation, demandée la première fois que vous touchez le bouton
  microphone du lecteur, le microphone sert uniquement à reconnaître les commandes vocales (par
  exemple démarrer ou arrêter une boucle), et seulement pendant l'écoute : toucher le bouton lance
  l'écoute, qui s'arrête après une commande ou quand vous touchez à nouveau le bouton. Si vous activez
  l'écoute continue, elle se poursuit après chaque commande jusqu'à ce que vous touchiez à nouveau le
  bouton ou fermiez le lecteur. La reconnaissance s'exécute entièrement sur votre appareil, hors
  ligne. Ce que le microphone entend ne quitte jamais votre appareil : ce n'est ni enregistré dans un
  fichier, ni conservé, ni transmis.
- **Accès réseau.** L'application n'utilise le réseau que dans un seul but : télécharger le pack de
  reconnaissance vocale hors ligne (environ 40 Mo) correspondant à la langue de l'application
  (anglais ou français), la première fois que vous touchez le microphone dans cette langue et
  acceptez le téléchargement. Le pack est téléchargé en HTTPS directement depuis le serveur du projet
  de reconnaissance vocale Vosk (alphacephei.com), et vérifié par une empreinte fixe avant d'être
  utilisé. Cette requête ne transmet aucune donnée sur votre utilisation de l'application. Comme tout
  téléchargement, elle révèle toutefois au serveur de Vosk l'adresse IP de votre appareil, les
  informations techniques courantes que tout téléchargement comporte (version d'Android et modèle du
  téléphone, dans l'en-tête « User-Agent » de la requête) et le pack de langue téléchargé. Aucune autre fonctionnalité de Kürve n'utilise le réseau : aucun kit d'analyse,
  de rapport de plantage, de publicité ou de suivi n'est inclus (le journal d'erreurs ci-dessus reste
  sur votre appareil et n'est jamais envoyé par Kürve), et les polices sont intégrées à
  l'application au lieu d'être téléchargées.
- **Sauvegardes de l'appareil.** Kürve n'ajoute aucune sauvegarde qui lui soit propre, mais la
  sauvegarde système de votre téléphone peut inclure ses données :
  - Sur Android, lorsque la sauvegarde est activée dans les réglages système, la sauvegarde
    automatique d'Android couvre la base de données de vos sessions de travail et les réglages de
    l'application, et rien d'autre. Elle ne couvre jamais le pack de reconnaissance vocale (Kürve le
    télécharge à nouveau lorsque vous en avez besoin), les copies de vos pistes importées ni leurs
    aperçus de forme d'onde. Après une restauration sur un nouveau téléphone, vos sessions reviennent
    donc, mais chaque piste doit être rattachée à nouveau. Ce que fait Android de la sauvegarde en
    ligne dépend de votre version : sur Android 9 à 11, elle n'est faite que si elle est chiffrée sur
    votre téléphone, et un transfert direct d'un téléphone à l'autre ne copie probablement rien de
    Kürve ; sur Android 12 et versions ultérieures, elle n'est faite que si votre téléphone est
    capable de la chiffrer de bout en bout (Android ne vérifie pas que vous l'avez activé), et un
    transfert direct copie les mêmes données ; sur Android 7 et 8, elle va sur votre compte Google
    sans cette condition. Dans tous les cas, la sauvegarde va sur votre propre compte Google ou votre
    nouvel appareil ; le développeur de Kürve n'y a pas accès. Vous pouvez désactiver la sauvegarde à
    tout moment dans les réglages système d'Android.
  - Sur iPhone, une sauvegarde iCloud ou sur ordinateur inclut la base de données de vos sessions et
    les réglages de l'application, mais pas les copies de vos pistes importées ni leurs aperçus de
    forme d'onde, conservés dans un stockage temporaire et de cache qu'iOS ne sauvegarde pas.
  - Le journal d'erreurs n'est inclus dans aucune des deux sauvegardes.

## Ce que Kürve ne fait pas

- Kürve ne crée pas de compte utilisateur et ne demande pas de connexion.
- Kürve ne partage, ne vend ni ne transmet aucune donnée à des tiers, puisqu'il n'en collecte aucune.
  Le journal d'erreurs n'est jamais envoyé par Kürve ; il n'est partagé que si vous le choisissez,
  comme décrit ci-dessus.
- Kürve n'utilise ni cookies, ni identifiants publicitaires, ni kit d'analyse.
- Kürve n'accède ni aux contacts, ni à la localisation, ni à la caméra, ni à aucune donnée autre que
  l'audio du microphone décrit ci-dessus et les fichiers que vous importez explicitement. Sur
  Android, Kürve utilise deux autorisations que vous pouvez voir : le microphone et l'accès réseau
  (uniquement pour le pack vocal). Vous choisissez vos fichiers dans le sélecteur de fichiers du
  système, qui ne nécessite aucune autorisation de stockage.

## Supprimer vos données

Tout ce que Kürve conserve se trouve sur votre appareil. Désinstaller l'application, ou effacer son
stockage dans les réglages système, supprime l'ensemble. Sur Android, vider uniquement le cache de
l'application supprime les copies de vos pistes importées, leurs aperçus de forme d'onde et le
journal d'erreurs, mais conserve vos sessions (chaque piste doit alors être rattachée à nouveau).
« Effacer le journal » dans les réglages supprime le journal et toute copie que Kürve ou la feuille
de partage a conservée dans le cache de l'application ; une copie que vous avez déjà envoyée ou
enregistrée ailleurs échappe à Kürve. Une copie de vos données dans votre propre sauvegarde système
se gère depuis votre compte Google ou Apple.

## Confidentialité des mineurs

Kürve ne collecte sciemment aucune donnée personnelle, y compris auprès des mineurs, puisqu'il ne
collecte de donnée personnelle auprès d'aucun utilisateur.

## Modifications de cette politique

Si les pratiques de Kürve en matière de données venaient à changer, ce document serait mis à jour
avant que le changement ne soit déployé, et la date d'entrée en vigueur ci-dessus serait révisée en
conséquence.

## Contact

Pour toute question sur cette politique ou sur vos données, écrivez à contact.kurveio@gmail.com. Les e-mails reçus à cette adresse ne servent qu'à vous répondre.
