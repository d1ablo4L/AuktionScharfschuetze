# AuktionScharfschütze - V.2.0.0

> **Hinweis:** Dies ist eine aktualisierte Version von CecchinoDelleAste, angepasst, um mit der deutschen Version des Spiels zu funktionieren. Sie hat keinerlei Verbindung zur kostenpflichtigen V2 von Frosty.


## 🚀 Neuerungen in V.2:
* **Neue Funktionen:** Die Funktionen *Auto-Aktualisierung*, *Höchstgebot* und *Höchstkaufpreis* wurden hinzugefügt, um die Auto-Erkennung zu maximieren und bereits beendete Auktionen zu vermeiden.
* **Leistung:** Allgemeine Leistung optimiert; das Tool ist von Haus aus deutlich schneller und reaktionsfreudiger als die Vorgängerversion.
* **Code und Anpassung:** Gründliche Bereinigung des Codes und Entfernung fest codierter (hardcoded) Grenzwerte. Du kannst jetzt jeden Parameter zu 100 % anpassen, um ihn an die Hardware deines PCs und die Geschwindigkeit deines Netzwerks abzustimmen.
* **Benutzeroberfläche (UI):** Von Grund auf neu aufgebaut für ein detaillierteres und umfassenderes Erlebnis im Vergleich zur V.1.
* **Fehlerbehebung:** Mehrere strukturelle Verbesserungen vorgenommen und kleinere Fehler behoben.

## Wichtigste Änderungen
* **Multi-Auflösungs-Unterstützung hinzugefügt.** (getestet und funktionsfähig: 720p, 1080p, 2K und 4K)
* **HDR-Unterstützung hinzugefügt.**
* **Unterstützung für das Spiel auf Deutsch hinzugefügt.**
* **Einstellungsseite im Overlay hinzugefügt.**
* **Vollständige Übersetzung des Tools ins Deutsche.**
* **Individuell gestaltete Benutzeroberfläche.**
* **Sauberer und vereinfachter Code für bessere Optimierung und Wartung.**
* **Kleinere Fehler behoben.**

## Geplante Änderungen
* Unterstützung für benutzerdefinierte Auflösungen und nicht standardmäßige Seitenverhältnisse hinzufügen

---

# AuktionScharfschütze für FH6

## Automatischer Sniper für das Auktionshaus von Forza Horizon 6

Überwacht das Auktionshaus nach dem von dir konfigurierten Auto, kauft es sofort, sobald es erscheint, holt es ab und beginnt von vorne – in einer Schleife. Stelle die Filter einmal ein und lass es laufen. Dieses Tool hat eine Sofortkaufrate von etwa 10 % und erzielt einen *Snipe* normalerweise in weniger als 5 Minuten.

<img width="1655" height="792" alt="image-3" src="https://github.com/user-attachments/assets/61b58048-c3e6-4156-9510-0c2600aa7e9f" />

---

# Funktionen

- Automatische Suche und Sofortkauf
- Überspringt bereits verkaufte Anzeigen, um eine neue zu finden
- Holt jedes gewonnene Auto automatisch ab
- Kleines, immer sichtbares Overlay (always-on-top) mit Echtzeit-Statistiken
- F8 Start/Stopp, F9 Notaus
- Automatischer Stopp nach einer festgelegten Anzahl von Autos oder Minuten
- Intelligente Bildschirmerkennung, um versehentliche Klicks auf anderen Bildschirmen zu vermeiden

---

# Voraussetzungen und Einstellungen

- Windows 10 oder 11
- Forza Horizon 6 auf dem PC
- Auflösung 4K/2K/1080p/720p – Vollbild, entsperrte Bildrate – HUD-Größe 100 %
- Grafik-Voreinstellung „Sehr niedrig"
- Animierter Hintergrund (Barrierefreiheit) **Deaktiviert**
- Spielsprache auf **Deutsch** eingestellt
- Kabelgebundene Ethernet-Verbindung dringend empfohlen

<img width="1386" height="763" alt="image-4" src="https://github.com/user-attachments/assets/fd2bf173-259f-4458-938b-2267144ce3ab" />
<img width="1386" height="758" alt="image-5" src="https://github.com/user-attachments/assets/34f3fe88-9575-4ec5-aa6c-0c9e04a9964c" />

---

# Download

Lade die neueste Version von **AuktionScharfschütze.zip** von der [Releases-Seite](https://github.com/d1ablo4L/AuktionScharfschuetze/releases) herunter und entpacke sie in einen beliebigen Ordner auf deinem PC.

---

# Einrichtung

## Schritt 1 – Öffne das Auktionshaus

Starte Forza Horizon 6 und gehe zum Auktionshaus auf dem Festivalgelände.

<img width="1916" height="971" alt="image-1" src="https://github.com/user-attachments/assets/2e4c412e-974e-4bf4-9d4d-bbc31fcd2432" />

---

## Schritt 2 – Suche konfigurieren

Öffne **Auktionen suchen** und stelle die Filter ein:

- **Marke** und **Modell** des gewünschten Autos
- **Maximaler Kaufpreis** als Sicherheitsgrenze. Der Bot kauft das erste passende Auto, ohne den Preis zu prüfen – dies ist also der Höchstbetrag, den du pro Auto ausgeben kannst. Stelle ihn sorgfältig ein.

Gehe zurück, bis der Bildschirm die **Suchkonfigurations-Ansicht** zeigt. Genau dort erwartet der Bot den Start.

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/7fac68c0-f89d-45ee-a10a-5133b02da681" />

---

## Schritt 3 – Sniper starten

Doppelklicke auf **AuktionScharfschütze.exe**. In der oberen rechten Bildschirmecke erscheint ein kleines Overlay.

Wechsle zurück zu FH6, drücke **F8** oder **START** und lass es laufen.

Zum Stoppen: Drücke erneut **F8**, **F9** für den Notaus oder klicke im Overlay auf **STOPP**.

<img width="1902" height="1062" alt="image-2" src="https://github.com/user-attachments/assets/ccdfba46-4c90-42de-bb79-fe26658bb262" />

---

# SmartScreen-Warnung

Windows SmartScreen zeigt eine Warnung an, weil die ausführbare Datei nicht digital signiert ist. So führst du sie trotzdem aus:

1. Klicke auf **Weitere Informationen**
2. Klicke auf **Trotzdem ausführen**

---

# Tastenkürzel

| Taste | Aktion |
|---|---|
| **F8** | Start / Stopp |
| **F9** | Notaus |
| Schaltfläche **STOPP** | Wie F8 |
| **✕** im Overlay | Schließen und beenden |

---

# Wichtig

> [!WARNING]
> - Die Automatisierung des Auktionshauses kann gegen den Verhaltenskodex von Forza verstoßen.
> - Die Ergebnisse können je nach PC- und Netzwerkkonfiguration variieren.
> - Du riskierst eine Verwarnung, eine Sperre oder einen dauerhaften Bann.
> - Nutzung auf eigene Gefahr.

---

# Hinweise

- Der Bot funktioniert nur, solange FH6 das aktive Fenster ist. Das Overlay zeigt **PAUSIERT** an, wenn du zu einem anderen Fenster wechselst. Klicke erneut ins Spiel, um fortzufahren.
- Das Overlay ist auf Screenshots ausgeblendet, du kannst es also an einer beliebigen Stelle des Bildschirms lassen.
- Ziehe das Overlay, indem du die Titelleiste anklickst und gedrückt hältst.
- Du wirst nicht jeden Snipe gewinnen. Der Bot ist – wie jedes andere Tool – durch die Menü-Animationen von FH6 und die Antwortzeit des Auktionsservers begrenzt.
- Wenn die Server langsam oder überlastet sind, funktioniert der Bot möglicherweise nicht mehr richtig (eine Lösung folgt bald).

---

# Fehlerbehebung

**Das Overlay zeigt „PAUSIERT"** – FH6 ist nicht das aktive Fenster. Klicke ins Spiel.

**F8 reagiert nicht** – möglicherweise fängt eine andere Anwendung auf deinem PC die F8-Taste ab. Schließe sie oder ändere das Tastenkürzel in `config.json`.

**Der Bot verliert sich auf einem Bildschirm und friert ein** – starte FH6 und den Bot neu. Stelle sicher, dass die Grafik-Voreinstellung **„Sehr niedrig"** und die Auflösung **1920 × 1080** ist.

**Wenn du bot-bezogene Probleme meldest** – füge die Datei Sniper.log bei, damit ich sie analysieren kann. Falls das Problem weiterhin besteht, [öffne ein Issue](https://github.com/d1ablo4L/AuktionScharfschuetze/issues) oder kontaktiere mich auf Discord „d1ablo4l".
