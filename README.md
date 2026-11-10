# premote x Shopware

Erstgespräch / Demo am **03.11.2026** (49 min) — Cedric (premote) mit Leonie Rehorst (shopware AG, People & Culture).
Timo Pelster war eingeladen, aber nicht dabei.

- Aufzeichnung & Transkript: https://app.bluedothq.com/preview/6ae998cb2aef9a85c0ba8f07
- Nächster Termin: **Mi, 11.11.2026, 11:00–11:45** (Leonie; Timo hat abgesagt)
- Follow-up-Mail: [`docs/follow-up-email.md`](docs/follow-up-email.md)
- Vorbereitung nächster Termin: [`docs/prep-2026-11-11.md`](docs/prep-2026-11-11.md)

## Kontakte

| Name | Rolle | E-Mail |
|---|---|---|
| Leonie Rehorst | People & Culture, verantwortlich für Working Abroad, A1, Entsendungen | l.rehorst@shopware.com |
| Timo Pelster | Approver bei >30 Tagen, stimmt Policies mit Leonie ab | t.pelster@shopware.com |

## Ausgangslage

- **Mitarbeitende:** 400+ gesamt, ca. 350 national (Wohnsitz DE); internationale Kolleg:innen über Employer of Record (EoR)
- **Volumen:** ca. 100 Anträge/Jahr (Working Abroad + Business Trips), geschätzte Dunkelziffer 3–5×
- **Tools:** BambooHR (Stammdaten, Dokumente; evtl. Wechsel), TravelPerk (Buchung, liegt bei Finance), Jira Service Desk (Anträge), SV-Meldeportal
- **Prozess heute (manuell):**
  1. Jira-Ticket mit Art (Business Travel / Workation), Ort, Zeitraum
  2. Automatisch an Vorgesetzte:n — Zustimmung zum Aufenthaltsort (nicht budgetbezogen)
  3. Leonie prüft Voraussetzungen, recherchiert, meldet im SV-Meldeportal (teils Papier, z. B. Vietnam; Indien inzwischen digital)
  4. Manueller Upload von Meldebescheinigung und KK-Genehmigung in BambooHR
  5. Jira-Ticket genehmigt → Automatisierung informiert Finance
- **TravelPerk:** keine echte Schnittstelle. Bei Workation wird der Zeitraum gesperrt (Mitarbeitende buchen selbst auf eigene Kosten), bei Business Trips nur Info an Finance. Business Trips werden oft direkt in Perk gebucht — dann ist es zu spät.
- **Visa:** nicht im Scope — Mitarbeitende kümmern sich selbst, shopware stellt nur Tätigkeitsbescheinigungen aus. Mitarbeitende unterschreiben ein Agreement.
- **PWD:** unklar, bisher Einzelfälle — Leonie prüft
- **Eigene Einschätzung Leonie:** Prozess läuft nach bestem Wissen, aber nicht vollständig compliant. Bisher keine Behördenpost.

## Policies / Voraussetzungen (vorläufig, Wording folgt von Leonie)

- Probezeit (erste 6 Monate) gesperrt
- Kein PIP, keine Kündigung / Eigenkündigung
- Zustimmung Vorgesetzte:r
- 183-Tage-Orientierung; Working from Abroad max. 30 Tage, 2 Anträge/Jahr (insgesamt 4 inkl. „All over the World“ bis 30 Tage)
- „Mindestens 2 Wochen am Stück“ und Antragsgrenzen werden flexibel gehandhabt (familiäre Hintergründe)
- Reisewarnungen werden manuell geprüft, ggf. frühe Ablehnung
- Häufige Länder: Europa, Indien, Vietnam, USA, zunehmend Japan; Einzelfälle Thailand, Südafrika

## Best Case aus Sicht von Leonie

- Wegfall von Beantragung, Datenpflege, Datenübertragung und Dokumentenablage
- Jede internationale Reise automatisch im Prozess (Dunkelziffer minimieren), ohne wochenlange Wartezeiten
- Approval-Prozesse abbildbar, Leonie selbst als Approver mit ihren Rahmenbedingungen
- BambooHR bleibt Single Source of Truth für Dokumente und Abwesenheiten

## Gezeigt in der Demo

- Admin- und Reisenden-Ansicht, digitales Profil mit Echtzeit-Abgleich aus BambooHR, Reisehistorie, Reisekalender, Dokumentenablage
- Rollen (Superadmin, User, Viewer), Approval-Routing mit Wenn-dann-Logik (gestaffelt <10 / 14 / 30 Tage, >30 Tage zusätzlich Timo)
- Policies: Länderkombinationen, Länderausschlüsse, Vorlaufzeiten, Verlängerungen, Kontingente
- Compliance Assessment über 8 Dimensionen mit Ampelsystem (Haftung bei grün/gelb; rot = Entscheidung bei shopware)
- Vorläufige A1 innerhalb von Minuten nach Approval
- TravelPerk-Partnerschaft: Buchung stößt Compliance-Prozess automatisch an (zusätzliches Feld „Reisegrund“ für PWD-Prüfung)
- Reporting, Workflows (Checklisten, Finance-Info, Reisewarnungen, Data Roaming) — im nächsten Termin vertiefen

## Offene Punkte

- [ ] BambooHR: Dokumentenablage, Reisekalender, Abwesenheiten bidirektional abbildbar? (bei Personio als Nicht-Standardintegration in 3 Monaten gebaut)
- [ ] EoR-Mitarbeitende: Assessment möglich, Bescheinigungen eher nicht — EoR müsste premote mandatieren
- [ ] PWD-Relevanz bei shopware
- [ ] Keine feste Timeline, frühe Phase; Nutzen muss die Kosten bei knappen Ressourcen rechtfertigen

## Nächste Schritte

**shopware (Leonie)**
- [ ] Reiseauswertung aus TravelPerk (Ticket bei Finance)
- [ ] Geschätzte Anzahl grenzüberschreitender Reisen (Wohnsitz DE)
- [ ] Policies, Rahmenbedingungen, Prüfvoraussetzungen inkl. Wording — mit Timo abgestimmt, im Projektraum
- [ ] PWD prüfen
- [ ] Fragen für nächsten Termin sammeln

**premote (Cedric)**
- [ ] Projektraum einrichten, Leonie einladen, Infos hochladen
- [ ] Tech: BambooHR-Integration klären
- [ ] Rücksprache EoR-Thematik
- [ ] Personalisierte Demo („Zwilling“) für shopware
- [ ] Kostenaufstellung mitbringen
