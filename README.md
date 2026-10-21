# klopp1991/.github

Zentrale Issue-Vorlagen für alle Repos von klopp1991.

## Vorlagen

- [Bug](.github/ISSUE_TEMPLATE/1-bug.yml) – etwas funktioniert nicht wie gedacht
- [Feature](.github/ISSUE_TEMPLATE/2-feature.yml) – ein Wunsch nach etwas Neuem
- [Epic](.github/ISSUE_TEMPLATE/3-epic.yml) – ein grösseres Thema mit mehreren Teilen
- [Change](.github/ISSUE_TEMPLATE/4-change.yml) – etwas Bestehendes soll anders werden
- [Task](.github/ISSUE_TEMPLATE/5-task.yml) – technische Arbeit ohne sichtbare Wirkung

## Was passiert nach dem Erstellen?

Jede Vorlage setzt beim Erstellen automatisch ein Label für die Art des Issues
(`type:bug`, `type:feature`, `type:epic`, `type:change`, `type:task`).

Priorität (`prio:1` = sehr dringend bis `prio:5` = kann warten) und Grösse
(`size:xs` bis `size:xl`, der geschätzte Aufwand) ergänzt danach das Team bei
der Triage. Fehlen diese Labels zunächst, ist das normal – die Vorlage
verlangt sie nicht.

Das Label `sascha` bedeutet: Das Team hat eine Rückfrage gestellt und wartet
auf eine Antwort, bevor es weitergeht.

## Guter Titel, guter Bericht

- Titel: kurz und konkret, z. B. „Login-Button reagiert nicht auf dem Handy“
  statt „Bug“.
- Bericht: möglichst genau beschreiben, wo es passiert (Seite oder Funktion),
  was erwartet wurde und wie man es nachstellen kann – das beschleunigt die
  Bearbeitung.
