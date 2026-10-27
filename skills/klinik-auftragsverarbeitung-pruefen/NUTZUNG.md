# Nutzung und Installation

## Zuerst mit einem Beispiel beginnen

Wähle eine Arbeitshilfe. Im zugehörigen Ordner stehen `SKILL.md`, Methodenhinweise, Ergebnisvorlage und ein synthetischer Beispielauftrag. Lass den Assistenten zuerst diesen Beispielauftrag bearbeiten. Vergleiche anschließend Aussagen, Quellen und offene Punkte mit dem Ausgangsmaterial.

## Codex

Kopiere den vollständigen ausgewählten Ordner in `.agents/skills/` deines Arbeitsprojekts oder in `~/.agents/skills/` für die persönliche Nutzung. Beispiel: `.agents/skills/klinik-anwendung-beschaffen/SKILL.md`. Vorhandene gleichnamige Ordner zuerst prüfen und sichern.

In Codex lässt sich die Arbeitshilfe über die Auswahl oder mit ihrem Namen aufrufen, beispielsweise `$klinik-anwendung-beschaffen`. Je nach Oberfläche kann die Auswahl über `@` erfolgen. Die Erkennung anhand einer passenden Aufgabe ist ebenfalls möglich. Die Ordner enthalten zusätzliche Anzeigedaten für Codex; diese verändern die fachlichen Anweisungen nicht. [Offizielle Anleitung](https://learn.chatgpt.com/docs/build-skills).

## Claude Code und Claude

Für Claude Code kopiere den vollständigen Ordner nach `.claude/skills/` im Projekt oder `~/.claude/skills/` für die persönliche Nutzung. Für eine Oberfläche mit eigener Einlesefunktion nutze das einzelne ZIP-Paket der Arbeitshilfe. Ein Gesamtarchiv mit mehreren Arbeitshilfen kann zunächst entpackt werden müssen. Verfügbarkeit und erlaubte Funktionen hängen vom jeweiligen Produkt und der Verwaltungseinstellung ab. [Offizielle Anleitung](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview).

## Andere KI-Assistenten

Ein Assistent mit Unterstützung für das Format `SKILL.md` kann die Ordner entsprechend seiner eigenen Anleitung einlesen. Ohne diese Funktion stelle die Inhalte von `SKILL.md`, `references/methodik.md` und `assets/ergebnisvorlage.md` gemeinsam mit deinem Auftrag bereit. Das ist eine manuelle Nutzung; automatische Erkennung, Dateizugriff und Werkzeuge werden dadurch nicht eingerichtet.

## Benötigte Werkzeuge

Die meisten Aufgaben arbeiten mit bereitgestellten Texten. Für tatsächliche Webseitenmessungen ist ein vorhandenes Lighthouse beziehungsweise axe-core erforderlich. Für die Datenbereinigung ist OpenRefine vorgesehen. Die Sammlung enthält diese Programme nicht und installiert nichts automatisch. Nutze freigegebene Fassungen und dokumentiere die tatsächlich verwendete Version.

Ohne Werkzeugzugriff entstehen eine Auswertung vorhandener Nachweise und ein Plan für ausstehende Prüfungen. Die Anweisungen verlangen eine erkennbare Trennung zwischen ausgeführten und geplanten Schritten.

## Örtliche Anpassung

Ergänze die Einrichtung, Trägerschaft, das Bundesland, den betrachteten Prozess, Zuständigkeiten und freigegebenen Datenweg. Füge keine pauschalen Freigaben in die Anweisung ein. Dokumentiere Änderungen mit Datum und Quelle. Reale Daten dürfen erst in einer dafür zugelassenen Umgebung verwendet werden.

## Weitergabe

Gib vollständige Ordner einschließlich Lizenz- und Herkunftshinweisen weiter. Die Originalquellen sind verlinkt. Ein Werkzeugstand in der Herkunftsdokumentation bezeichnet die geprüfte Quelle; er ist keine Empfehlung, eine Entwicklungsfassung zu installieren.
