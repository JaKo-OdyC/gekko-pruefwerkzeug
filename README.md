# GEKKO-Prüfwerkzeug

Statisches Werkzeug (GitHub Pages) für das GEKKO-Projektteam — Qualitätssicherung
der fachlichen Auftraggeberseite. Zwei Ebenen:

1. **Annahme prüfen** — projektrelevante Aussagen in fünf Felder legen
   (Behauptung, Kontext, Evidenzbasis, Gegenprobe, Bruchbedingung),
   Prüf-Prompt für ein frisches KI-Fenster erzeugen.
2. **Handlungsoptionen entwickeln** — aus geprüften Befunden fachliche
   Erfolgskriterien und Optionen ableiten, jede Option mit Herkunft,
   Sicherheit und dem Label „EMPFEHLUNG — keine Vorgabe".

Kernsatz: *Das Werkzeug verhindert, dass ungeprüfte Projektannahmen zu
Anforderungen an die Implementierungsfirma werden.* Es spezifiziert keine
technische Lösung — die liegt beim Implementierungspartner.

## Technik

Eine einzige `index.html`, keine Abhängigkeiten, kein Backend. Die Prompts
entstehen vollständig im Browser; es werden keine Daten gespeichert oder
übertragen.

## Deployment

GitHub Pages: Repo-Settings → Pages → Branch `main`, Ordner `/ (root)`.

## Methodische Grundlage

Die Fünf-Felder-Struktur und ihre Autorenregeln wurden in drei
präregistrierten Bruchtests empirisch geprüft (2026-08-11/12); der
Abschnitt „Was davon geprüft ist" auf der Seite trennt belegte von
ungetesteten Bestandteilen. Belege liegen in der privaten OdyC-Ablage
(`batch/gekko-bruchtest/`), nicht in diesem Repo.

Version 1.0 · 2026-08-12
