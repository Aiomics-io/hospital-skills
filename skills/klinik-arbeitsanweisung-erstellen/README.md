# Administrative Arbeitsanweisung erstellen und vergleichen

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Qualitätsmanagement und Prozessverantwortliche.

Überführe belegte Verwaltungsabläufe im Krankenhaus in eine Arbeitsanweisung oder vergleiche zwei Fassungen. Bewahre örtliche Zuständigkeiten und offene Fragen.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Schritt und Auslöser, Ausführende Rolle, Entscheidungsverantwortung, Eingabe, Tätigkeit, Ergebnis und Nachweis, Ausnahme und Übergabe.

## Benötigte Angaben

Bestehende Fassung, freigegebene Abläufe oder Gesprächsnotizen; Geltungsbereich; Rollen; Ausnahmen; Freigabeverfahren. Medizinische Behandlungsvorgaben gehören außerhalb dieses Umfangs.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Nutze den örtlichen Dokumentenlenkungsprozess und den organisatorischen Bezug der Qualitätsmanagement-Richtlinie. Eine vorgeschlagene Rolle wird erst nach örtlicher Bestätigung zur Zuständigkeit. Beachte gegebenenfalls Mitbestimmung, ohne aus dieser Arbeitshilfe eine pauschale rechtliche Aussage abzuleiten.

## Grundlagen und Grenzen

- [WHO: Qualitätsdokumentation im Labor](https://www.who.int/publications/m/item/laboratory-quality-manual)
- [Gemeinsamer Bundesausschuss: Qualitätsmanagement-Richtlinie](https://www.g-ba.de/richtlinien/87/)
- [Anthropic: process-doc](https://github.com/anthropics/knowledge-work-plugins/blob/c75fda00ff0e41c8ee331ae312c8a07f1967653b/operations/skills/process-doc/SKILL.md)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Erfinde keine tatsächlich praktizierten Schritte, Fristen oder Freigaben. Bei klinischen Behandlungsschritten beschränke dich auf die Dokumentstruktur und benenne die notwendige fachliche Zuarbeit. Veröffentliche den Entwurf nicht selbstständig im Kliniksystem.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Die Arbeitsweise von aiomics beschreibt die Zuordnung von Quellen und die fachliche Freigabe vorbereiteter Dokumente. Eine örtliche Arbeitsanweisung hält fest, welche Personen diese Schritte im Krankenhaus übernehmen und wie offene Angaben weiterbearbeitet werden.

[Arbeitsweise von aiomics: Quellen und fachliche Freigabe](https://www.aiomics.io/de/arbeitsweise)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
