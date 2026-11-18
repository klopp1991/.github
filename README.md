<div align="center">

# .github – Issue-Vorlagen

**Zentrale Issue-Vorlagen für alle Repos von klopp1991.**

Wer in einem beliebigen Repo von klopp1991 ein Issue öffnet, wählt eine von fünf vorgefertigten Vorlagen und füllt nur die passenden Felder aus. So sind Berichte in allen Projekten einheitlich und vollständig.
</div>

## Warum

Ohne Vorlagen fehlt in Berichten oft die Stelle, wo etwas passiert, oder die Schritte zum Nachstellen. Die zentralen Vorlagen stellen diese Fragen in jedem Repo gleich und sparen beiden Seiten Rückfragen.

## Funktionen

- [Bug](.github/ISSUE_TEMPLATE/1-bug.yml) – etwas funktioniert nicht wie gedacht
- [Feature](.github/ISSUE_TEMPLATE/2-feature.yml) – ein Wunsch nach etwas Neuem
- [Epic](.github/ISSUE_TEMPLATE/3-epic.yml) – ein grösseres Thema mit mehreren Teilen
- [Change](.github/ISSUE_TEMPLATE/4-change.yml) – etwas Bestehendes soll anders werden
- [Task](.github/ISSUE_TEMPLATE/5-task.yml) – technische Arbeit ohne sichtbare Wirkung

Jede Vorlage setzt beim Erstellen automatisch ein Label für die Art des Issues (`type:bug`, `type:feature`, `type:epic`, `type:change`, `type:task`). Leere Issues ohne Vorlage sind ausgeschaltet (`blank_issues_enabled: false`).

## Bedienung

Beim Öffnen eines neuen Issues in einem beliebigen Repo von klopp1991 erscheint die Auswahl der fünf Vorlagen.

- Titel: kurz und konkret, z. B. „Login-Button reagiert nicht auf dem Handy“ statt „Bug“.
- Bericht: möglichst genau beschreiben, wo es passiert (Seite oder Funktion), was erwartet wurde und wie man es nachstellen kann – das beschleunigt die Bearbeitung.

Priorität (`prio:1` = sehr dringend bis `prio:5` = kann warten) und Grösse (`size:xs` bis `size:xl`, der geschätzte Aufwand) werden nach dem Erstellen ergänzt. Fehlen diese Labels zunächst, ist das normal – die Vorlage verlangt sie nicht.

## Neuigkeiten

Der Änderungsverlauf listet alle nennenswerten Änderungen: [CHANGELOG.md](CHANGELOG.md) und die [Releases](https://github.com/klopp1991/.github/releases).

## Für Entwickler

- `.github/ISSUE_TEMPLATE/` enthält die fünf Vorlagen und `config.yml`.
- Die Vorlagen sind YAML-Dateien im GitHub-Format; Änderungen wirken in allen Repos von klopp1991.
- Hinweise zur Bearbeitung dieses Repos stehen in [AGENTS.md](AGENTS.md).
- Gebaut oder getestet wird hier nicht: Die Vorlagen wirken unmittelbar über GitHub.
