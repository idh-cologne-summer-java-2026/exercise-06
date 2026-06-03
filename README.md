Programmierung 2

# Übung 6

Klonen Sie dieses Repository direkt in Eclipse und importieren Sie das Projekt. Im Gegensatz zu den vorherigen Übungen machen Sie diese nur teilweise in Ihrem eigenen Branch.

## Aufgabe 1

Bearbeiten Sie diese Aufgabe im `main`-Branch. 

In der Klasse `idh.java.Koffer` finden Sie ein einfaches Programm, dass nur einen Satz ausgibt. Der Satz ist grob am "Ich packe meinen Koffer ..."-Kinderspiel orientiert, bei dem jede Person erst alle bisher eingepackten Objekte wiederholen muss, bevor sie ein neues hinzufügt.

Ergänzen Sie dort ein Objekt dass Sie gerne einpacken würden. Machen Sie einen Commit auf dem main-Branch, und pushen Sie. Wenn dabei ein Merge-Konflikt auftritt, beheben Sie ihn, committen und pushen erneut. Achten Sie beim Beheben darauf, dass Sie keine bisher eingepackten Gegenstände unter den Tisch fallen lassen, und dass es sich immer um ein funktionsfähiges Java-Programm handelt.

(es geht bei dieser Aufgabe natürlich nicht wirklich um einen Koffer. Der ganze Sinn davon ist, dass Sie Merge-Konflikte beheben).

## Aufgabe 2

In den Aufgaben 2 und 3 geht es darum, dass Sie etwas Erfahrung im Umgang mit pull requests machen. 

Legen Sie zunächst einen eigenen Branch an, den Sie z.B. nach Ihrem Benutzernamen benennen.

In der Klasse `idh.java.ATM` finden Sie die ATM-Implementierung, die wir in der Sitzung verwendet haben. Machen Sie eine kleine Änderung. Es ist letztlich egal welche, es sollte aber hinterher immer noch ausführbarer Code sein. Z.B. könnten Sie die Fehlermeldungen umformulieren, oder einen neuen Geldscheintyp erfinden (wäre es nicht praktisch, wenn es 23€-Scheine gäbe?).

Committen und pushen Sie wie üblich.

Gehen Sie dann auf [die GitHub-Seite](https://github.com/idh-cologne-summer-java-2026/exercise-06/pulls) und erstellen einen pull request. Dabei müssen Sie auswählen, welche Branches Sie mergen möchten. Ihr eigener, vorher neu erstellter Branch ist dabei der "compare"-Branch. Der "base"-Branch ist der, in den Sie ihre Änderungen übernommen bekommen möchten. Wählen Sie als "base"-Branch einen beliebigen anderen aus (aber nicht den main-Branch).

## Aufgabe 3

Alle gestellten pull requests finden Sie [hier](https://github.com/idh-cologne-summer-java-2026/exercise-06/pulls). Suchen Sie sich einen aus, und arbeiten Sie ihn ab. Er muss keinen ihrer eigenen Branches betreffen. Versuchen Sie ihn zu mergen, stellen Sie ggf. Rückfragen an die/den Einreicher:in des pull requests. Wenn Sie für Ihren pull request aus Aufgabe 2 Rückfragen bekommen, reagieren Sie in geeigneter Weise.