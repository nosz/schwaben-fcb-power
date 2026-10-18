**⚽ Live ansehen: [https://nosz.github.io/schwaben-fcb-power](https://nosz.github.io/schwaben-fcb-power)**

[![Stammtisch-Quiz: Was weißt du über den FC Bayern? / What do you know about FC Bayern? / Wos woasst du iwa den FC Bayern?](fcbayern_vorschau.jpg)](https://nosz.github.io/schwaben-fcb-power)

# Schwaben FCB Power: Stammtisch-Quiz

**Von den FCB Hardcore Fans: Arno & Udo & Nobbe** (inoffizielles Fan-Projekt)

**Datei:** `index.html` (eine Datei, offline lauffähig, Version 1.7.0, Stand 18.10.2026). Einfach im Browser öffnen oder auf einem Webserver ablegen.

> **Veröffentlichung:** GitHub-Repository `schwaben-fcb-power` (Benutzer `nosz`), Adresse `https://nosz.github.io/schwaben-fcb-power/`. Alle Dateien der Liste unten ins Hauptverzeichnis des Repositories legen (ohne Unterordner), GitHub Pages auf den Hauptzweig (Branch) stellen. Bei anderer Adresse in `index.html` (canonical, og:url, og:image, twitter:image) und in dieser README anpassen.

## Inhalt
Fan-Quiz mit 7 Spieltagen, viel Humor, Zertifikaten und Personalisierung, in **Deutsch, Englisch und Bairisch** (Umschalter oben, wird gespeichert).

| Nr. | Spieltag | Fragen |
|---|---|---|
| 1 | Blitzstart: 1900 in 60 Sekunden | 2 |
| 2 | Die Meistermaschine | 2 |
| 3 | Legenden: Beckenbauer, Kahn & Co. | 4 |
| 4 | Europa: Sechs Sterne und ein Finale dahoam | 4 |
| 5 | Allianz Arena & Kurve: Zahlen zum Staunen | 4 |
| 6 | Spitznamen & Triple: Stern des Südens | 4 |
| 7 | Bossrunde: Elfmeterschießen | 5 |

- **Hinweis ganz oben:** In der Kopfzeile direkt unter "Stammtisch-Quiz" steht groß und fett: "von den FCB Hardcore Fans: Arno & Udo & Nobbe" (Deutsch, Englisch, Bairisch), ebenso auf jedem Zertifikat und in der Fußzeile.
- **Stammtisch-Spruch & Fakt:** Karte auf der Startseite mit 16 Sprüchen und Fakten (Gags von Arno, Udo & Nobbe plus belegte Zahlen aus den Quellen), Knopf "Noch einer!" zeigt den nächsten.
- **Startseite:** "Servus! Was weißt du über den FC Bayern?" mit zwei Wegen ("Ich bin neu im Stadion" / "Ich bin schon ewig Fan"). Name optional, nur lokal gespeichert, steckt in Begrüßung, Quiz, Ergebnis und Zertifikat.
- **Spielmechanik:** 10 Tore je richtiger Antwort, 1 bis 3 Sterne je Spieltag, 5 Ränge von "Bankdrücker" bis "Vereinslegende", Konfetti, Hell- und Dunkelmodus.
- **Zertifikate:** je Spieltag ein "Stammtisch-Zertifikat", zum Abschluss das "Meisterschalen-Zertifikat" (PNG speichern oder drucken). Unterschrieben "Arno, Udo & Nobbe (inoffiziell)".
- **Der kleine Bayer:** Ab und zu läuft ein Pixel-Männchen mit Bayernhut über den Bildschirm (rein dekorativ, nicht klickbar, aus bei „Bewegung reduzieren“). Er spricht immer Boarisch, egal welche Sprache eingestellt ist, und macht Witze über andere Vereine, immer respektvoll und mit Augenzwinkern. Zu Beginn fragt er freundlich nach dem Namen und zeigt auf das Eingabefeld (höchstens dreimal). Test mit Adresse `?lauf=witz` (weitere: `name`, `stammtisch`, `brezn`, `tor`, `fass`, `karriere` u. a.).
- **Installieren-Knopf:** Auf der Startseite steht direkt nach Begrüßung und Namensfrage „Mir gefällt die App, ich möchte sie installieren“ (nur solange die App nicht installiert ist). Er startet die Installation oder zeigt die passende Anleitung (iPhone, Android, Computer).
- **PWA:** installierbar, läuft offline, Update-Hinweis. Dateien (alle ins Hauptverzeichnis): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `favicon.png`, `favicon.svg`, `apple-touch-icon.png`, `fcbayern_vorschau.jpg`. Bei jeder neuen Version `VERSION` in `index.html` **und** `sw.js` gemeinsam erhöhen.

## Tests (14.10.2026, lokaler Testserver)
Daten und Texte (alle in 3 Sprachen, 93 Oberflächentexte, 16 Sprüche), 7 Spieltage x 3 Sprachen komplett durchgespielt, Namensfrage und Personalisierung, 168 Urkunden (7 Namen, 3 Sprachen, 8 Urkunden) im Rand, PWA (Manifest, Icons, Service Worker, Offline bei gestopptem Server, Fortschritt nach Neuladen), UX-Suite U1 bis U10 auf dem Handy (375 px) hell und dunkel. Nicht getestet: echtes Gerät, GitHub Pages selbst, fcbayern.com-Links.

## Marke und Look
Farben nach dem Auftritt von fcbayern.com/de (Rot, Weiß, Dunkel, zarter Rosa-Blau-Verlauf), aus einem Screenshot geschätzt, nicht aus dem Quelltext der Seite. Es werden **kein Vereinswappen, keine Logos, keine Spielerfotos und keine kopierten Texte** verwendet. Das Logo ist ein selbst gezeichneter Pixel-Fanschal. Die Seite ist ein inoffizielles Fan-Projekt ohne Verbindung zum FC Bayern München.

## Quellen (Stand Frühjahr 2026, abgerufen 14.10.2026)
- Wikipedia (DE): https://de.wikipedia.org/wiki/FC_Bayern_M%C3%BCnchen
- Wikipedia (EN): https://en.wikipedia.org/wiki/FC_Bayern_Munich

## Bekannte Grenzen
- Wikipedia ist eine Sekundärquelle. Zahlen (Titel, Mitglieder, Umsatz) ändern sich; offizielle Werte gibt es beim Verein.
- Die Bayern-Texte (Bairisch) sind spielerisch gemeint und keine Rechtschreibnorm; Dialekt-Profis dürfen korrigieren. Die englischen Texte sollten Muttersprachler gegenlesen.
- `fcbayern.com` war beim Test von der Entwicklungsumgebung aus nicht erreichbar (Zeitüberschreitung); die Links dorthin sind nicht automatisch geprüft.
- Vor einer öffentlichen Veröffentlichung Marken- und Stil-Anlehnung mit Management/Legal klären.

## Änderungsprotokoll
- 1.7.0 (18.10.2026): Neu: der kleine Bayer mit Bayernhut (Boarisch, Witze über andere Vereine, fragt nach dem Namen) und der Installieren-Knopf auf der Startseite (statt der Karte ganz unten).
- 1.6.0 (15.10.2026): Auf jeder Seite außer der Startseite steht unten eine schlanke Fußzeile mit dem Knopf „Zur Startseite“ (Haus-Symbol), damit man immer wieder auf die Startseite kommt (bei Lektion über der Quellen-Karte). Einheitliche Benennung: Der Zurück-Knopf in der festen Leiste heißt jetzt ebenfalls „Startseite“ (vorher „Übersicht“), in Englisch „Home“.
- 1.5.8 (15.10.2026): Fehler behoben: Die Fortschrittspunkte im Quiz waren in der festen Leiste auf 6 px zusammengefallen und damit unsichtbar. Sie haben jetzt eine Mindestbreite von 90 px und füllen den Rest der Zeile neben „Frage 1 von 4“.
- 1.5.7 (15.10.2026): Symbol-Schritte der Ablaufleiste auf dem Handy jetzt wirklich mindestens 40 px breit.
- 1.5.6 (15.10.2026): Auf dem Handy sind die Symbol-Schritte der Ablaufleiste mindestens 44 px breit (vorher 38 px).
- 1.5.5 (15.10.2026): Bei den Quizfragen steht keine Quellen-Karte mehr (sie lenkte vom Quiz ab). Die Quellen bleiben bei Lektion, Namensabfrage, Ergebnis und Nachweis der jeweiligen Lektion.
- 1.5.4 (15.10.2026): Die Info-Karte („Inoffizielles ...“ mit Übersetzungshinweis) und die Version stehen nur noch auf der ersten Seite (Startseite), nicht mehr unter jeder Lektion, jedem Quiz, Ergebnis und Nachweis. Die Quellen-Karte bleibt bei den Lektions-Ansichten.
- 1.5.3 (15.10.2026): Einfache, eindeutige Menüführung. Prinzip: Die Schritte der Leiste (Lesen · Quiz · Zertifikat) bewegen sich innerhalb der Lektion; der eine Zurück-Knopf heißt in allen Lektions-Ansichten (Lektion, Namensabfrage, Quiz, Ergebnis, Nachweis) gleich „Übersicht“ und verlässt die Lektion (vorher „Zur Lektion“). Die Position steht überall gleich als „Lektion 2 von 7“ in der festen Leiste, auf dem Handy als „2/7“ zwischen Zurück-Knopf und Schritten.
- 1.5.2 (15.10.2026): Die Schritte der Ablaufleiste zeigen Symbole statt der Ziffern 1, 2, 3: Buch (Lesen), Fragezeichen (Quiz) und Auszeichnung (Nachweis); ein Haken heißt erledigt, ein Schloss heißt gesperrt.
- 1.5.1 (15.10.2026): Die Ablaufleiste Lesen · Quiz · Zertifikat ist echte Navigation (Pflicht in allen Projekten): „Lesen“ führt aus Quiz, Namensabfrage und Ergebnis zurück zum Text der Lektion, „Quiz“ startet das Quiz (mit Namensabfrage, wenn nötig), „Zertifikat“ ist erst nach einem bestandenen Quiz anklickbar (vorher gestrichelt und gesperrt, mit Hinweis „Erst das Quiz bestehen“). Der aktuelle Schritt ist beschriftet und nicht klickbar; bei nicht bestandenem Quiz bleibt „Quiz“ der aktuelle Schritt. Die Leiste bleibt dabei fest unter der Kopfzeile.
- 1.5.0 (15.10.2026): Die Orientierungsleiste (Zurück-Knopf mit „Lektion 2 von 7“ und der Ablauf Lesen, Quiz, Zertifikat) bleibt beim Scrollen fest direkt unter der Kopfzeile stehen, in Lektion, Namensabfrage, Quiz, Ergebnis und Nachweis; im Quiz gehören auch „Frage 2 von 4“ und die Fortschrittspunkte dazu. Die Höhen von Kopfzeile und Leiste werden gemessen, der Schatten erscheint nur im festgehefteten Zustand, beim Springen zu Abschnitten und beim Tabulieren wird nichts verdeckt (`scroll-padding-top`, WCAG 2.4.11), beim Drucken ist sie nicht fest. Auf dem Handy (bis 560 px) ist sie einzeilig: Zurück-Knopf links, rechts der Ablauf mit nur dem aktuellen Schritt beschriftet (die anderen zeigen die Nummer, der Name bleibt für Screenreader); die Lektionsnummer steht dort im Kopf der Lektion.
- 1.4.5 (15.10.2026): Fehler behoben: Beim Sprung zur Liste der Zertifikate bzw. Pokale (Knopf neben „Name ändern“, nach einem Ergebnis) lag die Überschrift auf dem Handy unter der festen Kopfzeile (133 px hoch, Abstand war nur 90 px). Auf schmalen Bildschirmen (bis 640 px) sind es jetzt 152 px.
- 1.4.4 (15.10.2026): Auf der Startseite steht neben „Name ändern“ ein Knopf „Meine Zertifikate“ (nur sobald ein Zertifikat verdient ist, auf dem Handy nur mit Symbol und Wort „Zertifikate“); er springt zur Liste der Zertifikate. Dazu UX-Prüfung mit abgeschlossenen Lektionen: 42 Ansichten (Start, Lektion, Namensabfrage, Quiz, Ergebnis, Zertifikat, Meister-Zertifikat in drei Sprachen, hell und dunkel, 360 px) ohne Befund, Klickziel-Test bei 360, 768 und 1280 px bestanden.
- 1.4.3 (15.10.2026): Die Quellen („Quellen (Stand 14.10.2026)“) stehen nicht mehr als kleine Liste im Lektionstext (nur 17 px hohe Links, unter der WCAG-Mindestgröße von 24 px), sondern unten als Karte mit großen Knöpfen (44 px) direkt über dem Hinweis „Inoffizielles Lernprojekt“, in Lektion, Namensabfrage, Quiz, Ergebnis und Zertifikat der jeweiligen Lektion (nicht auf der Startseite). Gefunden mit assets/testsuite_a11y.js.
- 1.4.2 (15.10.2026): Unterer Bereich der Lektion überarbeitet: Die Sprechblase („Gag“) ist gleichmäßig rund mit weichem Schatten (vorher wirkte die Ecke unten links abgeschnitten), die feste Leiste unten ist durchgehend mit feiner Linie statt eines Verlaufs, der Inhalt halb ausblendete, und der leere Platz darunter ist kleiner (24 statt 90 px). In einer abgeschlossenen Lektion gibt es keine doppelte Leiste mehr unten, die Knöpfe stehen in der Karte „Geschafft“.
- 1.4.1 (15.10.2026): Der Link „Mehr vom Verein entdecken“ unter Ergebnis und Zertifikat ist jetzt eine Karte mit Fußball-Symbol, Titel, Adresse und Pfeil (statt eines unterstrichenen Textlinks).
- 1.4.0 (15.10.2026): Benutzerführung überarbeitet: Ablaufleiste „1 Lesen · 2 Quiz · 3 Zertifikat“ mit aktuellem Schritt in Lektion, Namensabfrage, Quiz, Ergebnis und Zertifikat; die Zurück-Leiste nennt den Standort („Lektion 3 von 7“). Wer eine Lektion schon geschafft hat, sieht in der Lektion oben eine Karte „Geschafft! Dein Zertifikat ist fertig“ mit den Knöpfen „Zertifikat ansehen“ und „Nochmal spielen“ (auch unten fest); auf der Startseite haben geschaffte Kacheln einen Knopf „Zertifikat ansehen“, und „Deine Zertifikate“ steht jetzt direkt über den Lektionen. Das Zertifikat führt zur nächsten Lektion und zu „Alle Zertifikate“.
- 1.3.0 (15.10.2026): Fußbereich neu gestaltet: Hinweise (inoffiziell, Übersetzung) in einer Karte mit Info-Symbol, Version als Chip darunter. Der Link zur offiziellen Seite im Fuß entfällt, weil er schon im Bereich Mehr vom Verein steht.
- 1.2.1 (15.10.2026): Manifest: eigene App-ID (/schwaben-fcb-power/) statt "./". Vorher hatten alle Apps auf nosz.github.io dieselbe ID (die Ursprungsadresse) und Android meldete eine App als bereits installiert, obwohl eine andere gemeint war.
- 1.2.0 (15.10.2026): Klick auf Name ändern oder Name eintragen scrollt das Namensfeld automatisch in den sichtbaren Bereich und setzt den Cursor hinein.
- 1.1.0 (15.10.2026): Teilen-Symbol in der Kopfzeile (Teilen-Menü des Geräts, sonst Fenster mit WhatsApp, E-Mail, Link kopieren); „Name ändern“ als Button unter Rang, Münzen und Sternen; „Lieber anonym bleiben“ als Button; Klick auf Logo oder Titel bringt nach oben bzw. zur Startseite; Karten unter „Mehr vom Verein“ gleich groß ohne überlaufende Texte.
- 1.0.2 (14.10.2026): Fix: Wer den Namen leer oder nur mit Leerzeichen bestätigt, kann ihn später über „Name eintragen“ auf der Startseite nachholen.
- 1.0.1 (14.10.2026): Hinweis "von den FCB Hardcore Fans: Arno & Udo & Nobbe" in der Kopfzeile unter dem Titel (größer, 15 px fett), dunklen Extra-Banner entfernt.
- 1.0.0 (14.10.2026): Erstfassung (Technik der Nintendo-Quest-Seite, Inhalte neu), Repository `schwaben-fcb-power`.