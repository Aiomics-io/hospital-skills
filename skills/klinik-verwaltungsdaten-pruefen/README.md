# Verwaltungsdaten mit OpenRefine prüfen

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Verwaltung, Controlling und Qualitätsmanagement.

Bereite eine nachvollziehbare Bereinigung nichtklinischer Krankenhausdaten mit OpenRefine vor oder begleite vorhandene Arbeitsschritte. Erhalte Schlüssel, Rohdaten und Änderungsverlauf.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Spalte, Beobachtete Abweichung, Bedeutung und Datentyp, OpenRefine-Arbeitsschritt, Vorschauergebnis, Vorher-nachher-Prüfung, Offene Ausnahme.

## Benötigte Angaben

Freigegebene nichtklinische Beispieldatei, Spaltenbeschreibung, Zeilenbedeutung, Schlüssel und gewünschte Bereinigung. Für sensible Daten muss die gesamte Verarbeitung einschließlich KI-Zugriff zugelassen sein.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Verwende lokale Grundfunktionen. Externe Abgleichsdienste, Erweiterungen und Abrufe aus Zellinhalten benötigen einen eigenen zulässigen Zweck und Freigabe. Begrenze den ersten Einsatz auf nichtklinische Verzeichnisse, Bestände oder freigegebene Verwaltungsdaten.

## Grundlagen und Grenzen

- [OpenRefine](https://github.com/OpenRefine/OpenRefine/blob/ba887cacc5a3a6dc06c1f66f0fdc5f61694ae6e4/README.md)
- [OpenRefine: Zellbearbeitung](https://openrefine.org/docs/manual/cellediting)
- [OpenRefine: lokaler Betrieb](https://openrefine.org/docs/manual/running)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Ohne vorhandenes OpenRefine erstelle konkrete Arbeitsschritte und Prüfregeln für eine zuständige Person. Behaupte keine ausgeführte Bereinigung. Schreibe keinen eigenen Ersatz und führe keine automatische Personen- oder Einrichtungszusammenführung durch.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Aiomics beschreibt die Zuordnung strukturierter Angaben zu ihren Dokumentquellen. Für die hier behandelten Verwaltungslisten bleibt OpenRefine das vorgesehene Bearbeitungswerkzeug; die Anleitung dokumentiert jede vorgeschlagene Änderung und ihre Grundlage.

[Arbeitsweise von aiomics: Quellen und fachliche Freigabe](https://www.aiomics.io/de/arbeitsweise)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
