# Workflow: TN-Fragen individuell beantworten

## Ziel
Fragen von Teilnehmenden (TN) zu Eigenheiten der deutschen Sprache werden individuell beantwortet:
als responsive HTML-Seite, online über GitHub Pages abrufbar und lokal archiviert.

## Ablauf
1. **Anfrage** der Lehrkraft im Claude-Projekt „TN-Fragen individuell beantworten“
   - Frage der TN + Kürzel für die Übersetzung, z. B. `Ü-Franz`, `Ü-Engl`
2. **HTML-Seite erstellen** (eine Datei, responsive, Hell-/Dunkelmodus)
   - Erklärung erst einfach, dann fachlich (Wortart, Fachbegriffe)
   - Beispiele aus Alltag, Arbeit, Studium, jeweils mit Übersetzung in die Muttersprache der TN
   - farbliche Hervorhebung wichtiger Wörter, Buchstaben, Endungen
   - Tabelle „Typische Fehler“ (falsch → richtig → warum)
   - interaktive Übung mit sofortigem Feedback (Begründung + Übersetzung bei richtig, Hinweis bei falsch)
   - Zusammenfassung am Ende
3. **Vorschau** als Claude-Artefakt, Korrekturen der Lehrkraft einarbeiten
4. **Veröffentlichen** im öffentlichen GitHub-Repository `Signifikator/tn-fragen`
   - Datei `<thema>.html` ins Repository (Branch `main`, Ordner root)
   - Eintrag in der Startseite `index.html` ergänzen
   - GitHub Pages ist auf `main` / root eingestellt
5. **Link** an die TN weitergeben:
   `https://signifikator.github.io/tn-fragen/<thema>.html`
6. **Lokal ablegen** in
   `D:\Seafile\Seafile\Public\Hobbys\basteln\digital\KI\Unterrichtsmaterialien\TN-Fragen_individuell_beantworten`
   - `WORKFLOW.md`, `index.html`, alle `<thema>.html`

## Technische Hinweise
- GitHub-Konto in Claude verbinden: claude.ai → Einstellungen → Konnektoren → GitHub (eingebaute Integration)
- Claude kann keine neuen Repositories anlegen und GitHub Pages nicht selbst einschalten: das macht die Lehrkraft einmalig
- Lokaler Ordner: in der Claude-Desktop-App über „+“ → „Ordner hinzufügen“ freigeben

## Bisherige Seiten
| Datum | Thema | Sprache | Datei |
|---|---|---|---|
| 23.11.2026 | hierin, hierher, hierhin | Ü-Franz | `hierin-hierher-hierhin.html` |
