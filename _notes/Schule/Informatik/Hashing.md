---
date: 01.06.2022
title: Hashing
---
Links: [[Schule]], [[Informatik]]

**Das Hashing funktioniert, indem man Daten eine Hashfunktion zuweist und sie so einteilt**

Beim sog. Hashing wird auf den Suchschlüssel eine
Berechnungsfunktion.(Hashfunktion) angewandt, dessen Ergebnis direkt anzeigt, Wo gesucht werden muss.

Da die Daten beim Hashing (engl. to hash - zerhacken) ggf. recht weit über den Speicherbereich verteilt werden, spricht man auch vom sog. Streuspeicherverfahren.

Dass Kollisionen nicht gerade unwahrscheinlich sind, zeigt sich auch am sog. Geburtstagsparadoxon: „Befinden sich in einem Raum mindestens 23 Personen, dann ist die Chance, dass zwei oder mehr dieser Personen am selben Tag (ohne Beachtung des Jahrgangs) Geburtstag haben, größer als 50%." Probieren Sie es in Ihrem Kurs aus!

Buch S.149

Nr.4
B)
Datensatz1 mit modulo 10
| 0          | 1           | 2        | 3        | 4        | 5        | 6        | 7   | 8   | 9        |
| ---------- | ----------- | -------- | -------- | -------- | -------- | -------- | --- | --- | -------- |
| 19031980‘‘ | 09081981‘‘‘ | 06061981 | 14101980 | 29081981 | 11031981 | 17061980 |     |     | 21121979 |

Datensatz1 mit modulo 11
| 0   | 1   | 2         | 3        | 4         | 5        | 6        | 7   | 8   | 9   |
| --- | --- | --------- | -------- | --------- | -------- | -------- | --- | --- | --- |
|     |     | 19031980‘ | 06061981 | 21121979‘ | 14101980 | 7. |     |     |     |
