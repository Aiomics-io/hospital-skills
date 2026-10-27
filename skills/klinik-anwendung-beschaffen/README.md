# Beschaffung einer digitalen Anwendung vorbereiten

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Einkauf, ärztliche Leitung, Informationstechnik und Datenschutz.

Strukturiere die fachliche Vorprüfung einer digitalen Gesundheitsanwendung für ein deutsches Krankenhaus. Verknüpfe Anbieterbehauptungen mit produktbezogenen Nachweisen und offenen Entscheidungen.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Prüffeld, Anforderung und Herkunft, Anbieteraussage, Nachweis und Produktfassung, Bewertungsstand, Offene Frage, Fachzuständigkeit.

## Benötigte Angaben

Anwendungszweck, Produktfassung, Nutzer:innen, Einsatzort, Datenfluss, Anbieterunterlagen und konkrete Beschaffungsfrage. Eine allgemeine Personal- oder Finanzanwendung braucht ein gesondertes Raster.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Übertrage die Prüffelder in das örtliche Verfahren. Britische Nachweise und Rollenbezeichnungen werden nicht als deutsche Pflicht eingeführt. Für Schnittstellen verlange die konkrete Fassung, unterstützte Vorgänge, Fehlerbehandlung und einen Abnahmetest mit dem vorhandenen Krankenhausinformationssystem; „FHIR-fähig“ allein reicht als Funktionsnachweis nicht.

## Grundlagen und Grenzen

- [NHS England DTAC](https://digital.nhs.uk/services/digital-technology-assessment-criteria-dtac)
- [NHS England: Geltungsbereich](https://digital.nhs.uk/services/digital-technology-assessment-criteria-dtac/how-dtac-works)
- [NHS England: Durchführung](https://digital.nhs.uk/services/digital-technology-assessment-criteria-dtac/conduct-a-dtac-assessment)
- [Verordnung (EU) 2016/679](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32016R0679)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Das Ergebnis bereitet eine Beschaffungsentscheidung vor. Ein DTAC-Dokument, ein Werbesiegel oder die Größe eines Anbieters begründet keine Freigabe. Fehlende entscheidungsrelevante Nachweise bleiben offen. Allgemeine Vertrags-, Vergabe- und Medizinprodukteprüfungen werden nicht vollständig abgedeckt.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Der ergänzende Beitrag von aiomics erläutert, welche Nachweise ein Krankenhaus bei Anwendungen für die Klinikdokumentation anfordern kann. Die Arbeitshilfe lässt sich für unterschiedliche Anbieter verwenden; auch Angaben von aiomics sind anhand der konkreten Nachweise zu prüfen.

[Beschaffung von KI für Klinikdokumentation: Nachweise einordnen](https://www.aiomics.io/de/blog/ki-klinikdokumentation-beschaffung-nachweise-2026)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
