# Denote Top Ads

[EN](README.md) · [ZH](README.zh.md) · [JA](README.ja.md) · [KO](README.ko.md) · [ES](README.es.md) · [NL](README.nl.md) · DE · [FR](README.fr.md)

Finde Anzeigen, die dir als Vorlage für deine nächste Kampagne dienen können. Denote erfasst mehr als 10 Millionen Anzeigen und aktualisiert die Ranglisten jede Woche. Mit einem kostenlosen Konto erhältst du für die letzte abgeschlossene Woche drei Ranglisten für Spiele oder Apps mit jeweils bis zu zehn Anzeigen. [Denote Top Ads entdecken](https://denote.net/top-ads).

| Kostenlose Rangliste | Was du darin findest |
| --- | --- |
| Beliebte Anzeigen | Anzeigen, die in der vergangenen Woche besonders viel Aufmerksamkeit erhielten. |
| Aufsteiger | Anzeigen, deren Beliebtheit gegenüber der Vorwoche am stärksten zunahm. |
| Neue Anzeigen | Erstmals erfasste Anzeigen, sortiert nach ihrer anfänglichen Beliebtheit. |

## Deinen ersten Wochenüberblick abrufen

Führe diesen Befehl in deinem OpenClaw-Arbeitsbereich aus. Du benötigst Python 3.

```sh
git clone https://github.com/Denote-Business/denote-top-ads.git skills/denote-top-ads
```

1. Öffne eine neue Sitzung und frage: „Welche Anzeigen kann ich mit Denote entdecken?“
2. [Kostenloses Denote-Konto erstellen](https://denote.net/user/register). Wenn du schon ein Konto hast, melde dich an. Erstelle einen Denote-API-Schlüssel mit der Berechtigung `top_ads:read` oder füge sie einem vorhandenen Schlüssel hinzu.
3. Speichere den Schlüssel in der Geheimnisverwaltung deines Agenten als `DENOTE_API_KEY`. Bitte ihn dann: „Zeig mir die App-Anzeigen der letzten Woche.“ Du erhältst alle drei Ranglisten. Ohne Kategorieangabe werden Spiele ausgewählt.

**Rang · Anzeigentitel · Werbetreibender · Format · Plattformen · Vorschau**

## Eine Anzeige im Detail ansehen

Frage zum Beispiel: „Öffne den zweiten Platz der Aufsteiger.“ Mit Top Ads Pro oder Business kannst du verfügbare Daten zur Anzeigenleistung und Zielgruppe ansehen. Alle drei Wochenranglisten sind kostenlos.
