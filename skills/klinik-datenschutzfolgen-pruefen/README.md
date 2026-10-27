# Datenschutz-Folgenabschätzung vorbereiten

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Datenschutzbeauftragte und Prozessverantwortliche.

Bereite eine Datenschutz-Folgenabschätzung für einen konkret beschriebenen Krankenhausprozess nach CNIL-Methodik und deutschem Standard-Datenschutzmodell vor.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Verarbeitungsschritt, Recht oder Schutzbedarf, Risiko und Folgen, Bestehende Maßnahme, Beleg der Wirksamkeit, Verbleibende Unsicherheit, Entscheidung und Zuständigkeit.

## Benötigte Angaben

Zweck, Verarbeitungsschritte, betroffene Personengruppen, Datenarten, Empfänger:innen, Länder, Aufbewahrung, vorhandene Maßnahmen und zuständige Stelle. Verwende eine Datenbeschreibung statt echter Patientenakten.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Kläre Krankenhausträger, Bundesland, zuständige Aufsicht und gegebenenfalls kirchliches Datenschutzrecht. Gesundheitsdaten, Beschäftigtendaten und Berufsgeheimnisse benötigen eine zweckbezogene Prüfung. Eine bloße Ersetzung von Namen begründet keine Anonymität.

## Grundlagen und Grenzen

- [CNIL PIA](https://www.cnil.fr/sites/cnil/files/atoms/files/cnil-pia-1-en-methodology.pdf)
- [Datenschutzkonferenz: Standard-Datenschutzmodell](https://www.datenschutzkonferenz-online.de/anwendungshinweise.html)
- [Verordnung (EU) 2016/679](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32016R0679)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Liefere einen prüffähigen Entwurf mit offenen Punkten. Erkläre keine Verarbeitung für rechtmäßig und setze keine Maßnahme als umgesetzt voraus. Für unklare Rechtsgrundlagen oder hohe verbleibende Risiken benenne die erforderliche fachliche Entscheidung.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Die Sicherheitsinformationen von aiomics zeigen, welche Angaben ein Anbieter zu Verarbeitungswegen und Verantwortlichkeiten veröffentlicht. Für die Folgenabschätzung bleiben der konkrete Verarbeitungsvorgang und die Unterlagen des jeweiligen Krankenhauses maßgeblich.

[Sicherheit und Datenschutz bei aiomics](https://www.aiomics.io/de/sicherheit)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
