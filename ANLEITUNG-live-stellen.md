# mittelhessen·digital — Anleitung zum Live-Stellen

Alles ist eingebaut. Hier die letzten Schritte, damit die Seite auf Strato online geht.

---

## 1. Die Schriften (einmalig, wichtig fürs Aussehen)

Ich konnte die Schrift-Dateien hier nicht herunterladen (kein Internetzugriff).
Sie fehlen also noch — **die Seite funktioniert trotzdem**, zeigt vorerst aber eine
System-Schrift. Für den originalen Look lädst du die zwei Schriften einmal herunter:

1. Öffne **https://gwfh.mranftl.com/fonts** (Google-Webfonts-Helper)
2. **Fraunces** suchen → unter „Select styles" die Stärken **300–600, normal + italic** wählen
   → Format **woff2** → herunterladen
3. Dasselbe für **Instrument Sans** (Stärken 400–700, normal + italic)
4. Die entpackten `.woff2`-Dateien in den Ordner **`fonts/`** legen und so benennen:
   - `fraunces.woff2`
   - `fraunces-italic.woff2`
   - `instrument-sans.woff2`
   - `instrument-sans-italic.woff2`

Die passende `fonts/fonts.css` liegt bereits im Ordner — du musst nichts am Code ändern.

> Tipp: Wenn dir die System-Schrift reicht, kannst du diesen Schritt auch überspringen.
> Es entstehen dann **keine** Google-Verbindungen (gut für den Datenschutz).

---

## 2. Auf Strato hochladen

Lade den **kompletten Inhalt** dieses Ordners per FTP (z. B. FileZilla) oder über den
Strato-Datei-Manager in das Web-Verzeichnis (meist `/` oder `htdocs`):

```
mittelhessen-digital-improved.html   →  bitte umbenennen in  index.html
muster-voltwerk.html
muster-goldamsel.html
muster-marlen.html
muster-lindenhof.html
fonts/  (ganzer Ordner mit fonts.css + den 4 Schrift-Dateien)
```

**Wichtig:** Die Startseite muss `index.html` heißen, damit sie unter
`https://mittelhessen-digital.de` direkt erscheint. Einfach die Datei
`mittelhessen-digital-improved.html` in `index.html` umbenennen.

Alle Dateien gehören ins **gleiche Verzeichnis** (die Muster und `fonts/` daneben),
sonst finden sich die Vorschau-Fenster und Schriften nicht.

---

## 3. Domain & E-Mail

- **Domain:** In deinem Strato-Konto `mittelhessen-digital.de` auf das Web-Paket
  zeigen lassen (falls noch nicht geschehen). SSL/HTTPS ist bei Strato meist mit
  einem Klick aktivierbar — unbedingt einschalten (Schloss-Symbol).
- **E-Mail:** Lege bei Strato das Postfach **info@mittelhessen-digital.de** an
  (steht überall auf der Seite und im Impressum).

---

## 4. Formular testen

Das Kontakt- und das Newsletter-Formular senden an deine Formspree-Adresse
(`xykqagjd`). **Beim allerersten Absenden** schickt Formspree dir eine
Bestätigungs-Mail an die bei der Registrierung genutzte Adresse — einmal bestätigen,
dann kommen alle Anfragen bei dir an.

Formspree schickt die Anfragen an die in deinem Formspree-Konto hinterlegte
E-Mail. Wenn sie an **info@mittelhessen-digital.de** gehen sollen, stelle das im
Formspree-Dashboard unter den Form-Einstellungen ein.

---

## 5. Kurz gegenprüfen (Rechtliches)

- **Impressum** (Fußzeile → „Impressum"): Name, Mühlbergweg 10, 35083 Wetter,
  Telefon, E-Mail, Kleinunternehmer — bitte einmal auf Richtigkeit durchlesen.
- **Datenschutz**: nennt jetzt Strato (Hosting) und Formspree (Formular). Passt zu
  deinem Setup. Wenn du später Statistik-Tools o. Ä. einbaust, muss das ergänzt werden.

---

## Fertig ✅

Danach ist die Seite live und voll funktionsfähig:
- Startseite lädt schnell (nur ~80 KB)
- Kontakt- & Newsletter-Formular senden echte E-Mails
- Vier Muster-Websites öffnen sich im Vorschau-Fenster
- Impressum & Datenschutz mit deinen echten Daten

Bei Fragen zu einem Schritt einfach melden.
