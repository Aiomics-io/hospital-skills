# Digitale Barrieren nachvollziehbar prüfen

Eine kostenfreie Arbeitshilfe von [aiomics](https://www.aiomics.io/de/ueber-uns) für Öffentlichkeitsarbeit, Informationstechnik und zuständige Beauftragte.

Bereite eine Prüfung der Barrierefreiheit von Krankenhausseiten vor und werte axe-core-Berichte mit manuellen Beobachtungen aus. Dokumentiere Umfang und offene Prüfschritte.

**Fassung 0.1 · Quellenstand 27. Oktober 2026 · Fachliche Erprobung in Krankenhäusern ausstehend.**

## Ergebnis

Die [Ergebnisvorlage](assets/ergebnisvorlage.md) strukturiert: Seite und Zustand, Kriterium oder Prüfregel, Automatisch oder manuell, Beobachtung, Nutzungshindernis, Abhilfe, Nachprüfung und offener Umfang.

## Benötigte Angaben

Seiten und wichtige Nutzungsvorgänge, Trägerschaft, Zielstandard, axe-core-Bericht mit Fassung und Zeitpunkt sowie vorhandene manuelle Beobachtungen.

## Einstieg

1. Den vollständigen Ordner einschließlich Quellenhinweisen und Vorlagen herunterladen. Für Codex und Claude Code den Ordner nach der [Nutzungsanleitung](NUTZUNG.md) einrichten.
2. Mit dem [synthetischen Beispielauftrag](assets/beispielauftrag.md) beginnen.
3. Die [vollständige Anweisung](SKILL.md) verwenden und das Ergebnis anhand der [Vorlage](assets/ergebnisvorlage.md) prüfen.
4. Örtliche Zuständigkeiten und die freigegebene Verarbeitungsumgebung ergänzen. Für die erste Erprobung sind keine echten Personen- oder Vertragsdaten erforderlich.

## Für deutsche Krankenhäuser angepasst

Prüfe Bundes- oder Landesrecht für öffentliche Stellen sowie gegebenenfalls das Barrierefreiheitsstärkungsgesetz anhand der konkreten Trägerschaft und angebotenen Dienstleistung. Eine Krankenhausseite fällt nicht allein wegen ihres Bestehens unter jede dieser Regelungen. Fachbegriffe und Kontaktalternativen müssen für die vorgesehenen Nutzer:innen verständlich sein.

## Grundlagen und Grenzen

- [axe-core](https://github.com/dequelabs/axe-core/blob/6b52b841461bd23345970b91ec75fdaff6bad31a/README.md)
- [W3C WCAG-EM](https://www.w3.org/WAI/test-evaluate/conformance/wcag-em/)
- [Bundesfachstelle Barrierefreiheit](https://www.bundesfachstelle-barrierefreiheit.de/DE/Barrierefreiheitsstaerkungsgesetz/FAQ-elektronischer-Geschaeftsverkehr/faq-elektronischer-Geschaeftsverkehr_node)

Die [Methodenhinweise](references/methodik.md) erläutern, welche Schritte übernommen wurden und welche Anpassungen hinzugekommen sind.

Bei fehlenden manuellen Prüfungen ist das Ergebnis eine Teilprüfung. Nutze vorhandenes axe-core oder dessen Originalbericht; baue keine eigenen Prüfregeln. Formuliere eine rechtliche Einordnung als offene Fachfrage, wenn Trägerschaft oder Leistungsumfang fehlen.

Die deutsche KI-Anpassung ist eine Erprobungsfassung. Hinweise aus den Quellen begründen keine Freigabe durch deren Herausgeber:innen. Der [synthetische Prüffall](assets/prueffall.md) hilft, wesentliche Grenzen sichtbar zu machen.

## Bezug zu aiomics

Bei der Einführung digitaler Anwendungen müssen Krankenhäuser auch die Nutzung durch unterschiedliche Beschäftigte berücksichtigen. Die Informationen von aiomics zur Einführungsbegleitung ergänzen diesen organisatorischen Blick; die fachlichen Prüfmaßstäbe dieser Anleitung stammen aus den unten genannten Quellen.

[Begleitung der KI-Einführung im Krankenhaus durch aiomics](https://www.aiomics.io/de/loesungen/services)

## Lizenz und Rückmeldung

Eigene Inhalte unter [Apache-2.0](LICENSE); [Herkunftsvermerk](NOTICE.md). Fachliche Rückmeldungen bitte anhand eines synthetischen Beispiels mit konkreter Quelle in der [öffentlichen Sammlung](https://github.com/Aiomics-io/hospital-skills/issues) einreichen.
