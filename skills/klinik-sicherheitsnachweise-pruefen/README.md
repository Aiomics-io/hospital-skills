# Sicherheitsnachweise eines Anbieters einordnen

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Informationssicherheit, Informationstechnik und Einkauf.

Ordne Sicherheitsnachweise für ausgelagerte digitale Krankenhausanwendungen nach geprüftem Umfang, Zeitraum, Ausnahmen und verbleibenden Aufgaben ein.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Nachweis, Aussteller:in und Zeitraum, Geprüfter Umfang, Abweichung zum Einsatz, Ausnahme oder Feststellung, Aufgabe der Klinik, Offene Nachforderung.

## Benötigte Angaben

Produkt und Betriebsmodell; vollständiger freigegebener Prüfbericht oder belastbarer Auszug; Zertifikate mit Geltungsbereich; Unterauftragnehmer:innen und örtliche Anforderungen.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Ein C5-Testat ist eine unabhängige Prüfung in einem bestimmten Umfang; formuliere daraus keine „BSI-Zertifizierung“. Infrastruktur, Anwendung und Betriebsorganisation können unterschiedliche Nachweise brauchen. Prüfe bei ausgelagerter Verarbeitung von Sozial- oder Gesundheitsdaten die Anwendbarkeit des § 393 SGB V: erfasste Stelle, Verarbeitungsort, inländische Niederlassung, aktueller Nachweis und tatsächlich umgesetzte Kund:innenpflichten. Die aktuelle Vorschrift enthält einen Grundsatz zum Typ-2-Testat, eine zeitlich begrenzte Typ-1-Ausnahme für neu in Verkehr gebrachte Systeme und eine Regelung zu gleichwertigen Nachweisen. Prüfe Voraussetzungen und aktuelle Fassung; ordne einen vorhandenen Nachweis nicht allein anhand seines Namens als ausreichend ein.

## Grundlagen und Grenzen

- [BSI: C5](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Informationen-und-Empfehlungen/Empfehlungen-nach-Angriffszielen/Cloud-Computing/Kriterienkatalog-C5/kriterienkatalog-c5_node.html)
- [BSI: Nachweise externer Rechendienste](https://www.bsi.bund.de/DE/Themen/Oeffentliche-Verwaltung/Mindeststandards/Externe_Cloud-Dienste/FAQ_MST_Externe_Cloud-Dienste/faq_mst_Externe_Cloud-Dienste_node.html)
- [§ 393 SGB V](https://www.gesetze-im-internet.de/sgb_5/__393.html)
- [Verordnung (EU) 2016/679](https://eur-lex.europa.eu/legal-content/DE/TXT/?uri=CELEX:32016R0679)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Bei einem fehlenden Bericht bleibt der Nachweis offen. Ein Nachweis des Rechenzentrums wird nicht auf die Anwendungsanbieterin übertragen. Die Arbeitshilfe führt keine Angriffstests aus und stellt kein Sicherheitszertifikat aus.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Aiomics veröffentlicht Angaben zu seiner Informationssicherheit und zum Stand seiner Nachweise. Die Arbeitshilfe verlangt auch bei aiomics die Prüfung von Geltungsbereich, Fassung und produktbezogenen Unterlagen.

[Sicherheit und Datenschutz bei aiomics](https://www.aiomics.io/de/sicherheit)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
