# Lionheart Invest

[Deutsch](#deutsch) · [English](#english)

---

## Deutsch

Lionheart Invest ist eine Windows-App für private Finanzentscheidungen: Anschaffungen über verschiedene
Erwerbswege vergleichen und die Vermögensentwicklung unter Unsicherheit simulieren. Dieses Repository enthält
nur die Installer und Updates. Deine Daten bleiben auf deinem Rechner.

### Herunterladen und installieren

1. Öffne das **[neueste Release](https://github.com/Thorgromm/lionheart-invest-releases/releases/latest)**.
2. Lade unter **Assets** die Datei herunter, die auf **`_x64-setup.exe`** endet. Die anderen Dateien
   (`.sig`, `latest.json`) braucht nur die App selbst für Updates.
3. Starte die heruntergeladene Datei. Die Installation braucht keine Administratorrechte.

Voraussetzung: Windows 10 oder 11, 64 Bit. Gibt es noch kein Release, ist die erste Version noch nicht freigegeben.

### Warnungen beim ersten Start

Die App ist nicht mit einem kostenpflichtigen Zertifikat signiert. Windows kennt sie deshalb nicht und warnt.

**Microsoft Edge meldet „… wird nicht häufig heruntergeladen“:** In der Download-Liste auf **…** (Weitere Aktionen)
klicken, dann **Beibehalten**, dann **Mehr anzeigen** und **Trotzdem beibehalten**.

**„Der Computer wurde durch Windows geschützt“ (SmartScreen):** Auf **Weitere Informationen** klicken, dann auf
**Trotzdem ausführen**. Das ist nur beim ersten Start nötig.

### Blockiert durch Smart App Control

Erscheint statt der SmartScreen-Warnung eine Meldung von **Smart App Control** ohne „Trotzdem ausführen“, dann
blockiert Windows 11 die App vollständig. Smart App Control fragt zuerst einen Cloud-Dienst von Microsoft. Kann der
die App nicht als sicher einstufen, lässt es nur signierte Apps zu. Eine Ausnahme für einzelne Apps gibt es nicht.

So prüfst du den Status: **Windows-Sicherheit** → **App- & Browsersteuerung** → **Smart App Control-Einstellungen**
(oder `windowsdefender://smartapp/` in die Adresszeile des Explorers eingeben).

- **Bewertungsmodus** oder **Aus**: Smart App Control blockiert nichts. Die SmartScreen-Anleitung oben reicht.
- **Ein**: Die App lässt sich nur starten, wenn du Smart App Control dort auf **Aus** stellst.

Smart App Control ist eine Schutzfunktion. Schalte sie nur ab, wenn du das bewusst willst. Mit aktuellen
Windows-Updates (ab KB5079391, März 2026) lässt sie sich später wieder einschalten. Auf älteren Windows-Ständen
ging das nur über eine Neuinstallation von Windows. Installiere deshalb vorher alle Updates.

Wirst du blockiert, sag bitte der Person Bescheid, die dir diesen Link geschickt hat. Dann prüfen wir eine
Signierung der App.

### Updates

Die App prüft beim Start, ob es eine neue Version gibt, und fragt dich, ob sie sie jetzt installieren soll. Ohne
Internet startet sie normal. Unter **Einstellungen → Über Lionheart Invest** kannst du auch selbst nach Updates suchen.

### Deinstallieren

**Einstellungen** → **Apps** → **Installierte Apps** → **Lionheart Invest** → **…** → **Deinstallieren**.

---

## English

Lionheart Invest is a Windows app for personal finance decisions: compare purchases across different ways of
acquiring them and simulate how your wealth develops under uncertainty. This repository only holds
the installers and updates. Your data stays on your computer.

### Download and install

1. Open the **[latest release](https://github.com/Thorgromm/lionheart-invest-releases/releases/latest)**.
2. Under **Assets**, download the file ending in **`_x64-setup.exe`**. The other files (`.sig`, `latest.json`)
   are only used by the app for updates.
3. Run the downloaded file. Installing does not need administrator rights.

Requirements: Windows 10 or 11, 64-bit. If there is no release yet, the first version has not been published.

### Warnings on first launch

The app is not signed with a paid certificate, so Windows does not recognise it and shows a warning.

**Microsoft Edge says "… isn't commonly downloaded":** In the downloads list, click **…** (More actions), then
**Keep**, then **Show more** and **Keep anyway**.

**"Windows protected your PC" (SmartScreen):** Click **More info**, then **Run anyway**. You only need to do
this on the first launch.

### Blocked by Smart App Control

If you see a **Smart App Control** message without a "Run anyway" option instead of the SmartScreen warning,
Windows 11 blocks the app completely. Smart App Control first asks a Microsoft cloud service. If that service
cannot classify the app as safe, only signed apps are allowed. There is no exception for individual apps.

To check the status: **Windows Security** → **App & browser control** → **Smart App Control settings**
(or type `windowsdefender://smartapp/` into the File Explorer address bar).

- **Evaluation** or **Off**: Smart App Control blocks nothing. The SmartScreen steps above are enough.
- **On**: The app only starts if you set Smart App Control to **Off** there.

Smart App Control is a security feature. Only turn it off if you deliberately want to. With current Windows
updates (KB5079391, March 2026, or later) you can turn it back on later. On older Windows versions this required
reinstalling Windows, so install all updates first.

If you are blocked, please tell the person who sent you this link. We will then look into signing the app.

### Updates

The app checks for a new version on startup and asks whether to install it now. Without internet it starts
normally. You can also check for updates yourself under **Settings → About Lionheart Invest**.

### Uninstall

**Settings** → **Apps** → **Installed apps** → **Lionheart Invest** → **…** → **Uninstall**.
