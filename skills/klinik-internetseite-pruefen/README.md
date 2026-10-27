# Internetseite eines Krankenhauses prüfen

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Öffentlichkeitsarbeit und Informationstechnik.

Prüfe die Auffindbarkeit, Ladeleistung und Kontaktwege einer Krankenhausseite anhand vorhandener Berichte oder einer lesenden Untersuchung. Erstelle belegte Verbesserungsvorschläge.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Seite und Zielgruppe, Beobachtung mit Fundstelle, Art des Nachweises und Datum, Auswirkung, Vorschlag, Zuständigkeit, Nachprüfung.

## Benötigte Angaben

Öffentliche Seitenadressen oder bereitgestellte Seitenauszüge; Zielgruppen; vorhandene Lighthouse-Berichte und Auszüge aus Google Search Console mit Zeitraum. Personenbezogene Besuchsdaten werden nicht benötigt.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Patient:innen, Zuweiser:innen und Bewerber:innen benötigen unterschiedliche Wege. Erhalte bestehende Notfall- und Erreichbarkeitsangaben unverändert, bis die Klinik eine Änderung bestätigt. Prüfe deutsche Orts- und Abteilungsbezeichnungen. Feste Zeichenlängen, eine bestimmte Zahl von Überschriften und Platzierungen einzelner Suchbegriffe sind keine starren Google-Vorschriften.

## Grundlagen und Grenzen

- [Lighthouse](https://github.com/GoogleChrome/lighthouse/blob/1a4ffa418258919adbbf6ccca548c02e0092bafd/readme.md)
- [Google Search Central](https://developers.google.com/search/docs/fundamentals/seo-starter-guide?hl=de)
- [marketingskills](https://github.com/coreyhaines31/marketingskills/blob/17772c7a80b7b8c7a47af30f648374cd8bd8adc5/skills/seo-audit/SKILL.md)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Fehlt ein ausführbares Prüfwerkzeug, werte vorhandene Berichte aus und liefere einen Prüfauftrag für offene Punkte. Erfinde keine Messwerte. Sende keine Formulare ab und ändere keine öffentliche Seite ohne Auftrag.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Diese Arbeitshilfe erweitert die frei zugänglichen Materialien von aiomics um die Prüfung öffentlicher Krankenhausseiten. Sie richtet sich an die Öffentlichkeitsarbeit und kann unabhängig von der aiomics-Plattform verwendet werden.

[Gründer und Auftrag von aiomics](https://www.aiomics.io/de/ueber-uns)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
