---
css: ../css/style.css
date: Schuljahr 2025/2026
lang: de-DE
subtitle: Lernfeld 10b -- Serverdienste bereitstellen und
  Administrationsaufgaben automatisieren
title: Serverdienste -- NTP
---

## Aufgabe 1

Beschreiben Sie die drei Systeme zur Zeitmessung

- Linux-Zeitmessung mit timestamp
- NTP-Zeitmessung im Timestamp-Format
- NTP-Zeitmessung im Datestamp-Format

## Aufgabe 2

Erklären Sie, was Stratum-0 ist.

## Aufgabe 3

a)  Entscheiden Sie, ob die folgenden Aussagen zu Network Timing
    Protocol (NTP) richtig oder falsch sind.

    1.  Mit dem Begriff „Stratum" wird beim NTP die Ebene des Servers zu
        einer hochgenauen Hardwareuhr bezeichnet. Ein Stratum-1-Server
        ist mit einer Hardwareuhr verbunden. Stratum-2-Server erhalten
        ihre Uhrzeit von Stratum-1- oder anderen Stratum-2-Servern.

    <!-- -->

    2.  Mit dem NTP kann ein Client Zeitsignale von einem Server
        abfragen. Dazu wird die Netzwerklaufzeit zwischen Client und
        Server berechnet, um die Uhrzeit entsprechend anzupassen.

    <!-- -->

    3.  Mit dem NTP wird ein Zeitüberlauf im Jahr 2038 stattfinden.

<!-- -->

b)  Ein Auszubildender bittet Sie, ihm zu erklären, was ein Überlauf bei
    einem Zeitzähler bedeutet. Sie entscheiden sich, dies anhand eines
    vereinfachten Datentyps zu erklären. Dazu wird ein vorzeichenloser
    Integer-Wert verwendet. Zur einfachen Veranschaulichung sollen nur 3
    Bit für die Darstellung von Zahlen verwenden werden. Mit den 3 Bit
    können Werte dargestellt werden. Als vorzeichenlose Zahl können die
    Werte 0, 1, 2, 3, 4, 5, 6 und 7 dargestellt werden.

    jede Sekunde soll der Zähler um eins erhöht werden.

    Erklären Sie anhand des Zählers den Überlauf, der nach der 7-ten
    Sekunde stattfindet.

<!-- -->

c)  Der zuvor verwendete Zähler soll mit dem Wert 0 das Datum und die
    Uhrzeit 01.01.2025 0:00 und 0 Sekunden darstellen.

    Erklären Sie mit dem zuvor beschriebenen Überlauf d1e Darstellung
    der Uhrzeit, die in der 8. Sekunde erfolgt.

<!-- -->

d)  Erklären Sie die Anwendung des Epoch-Wertes, mit dem bei NTP der
    Überlauf verhindert wird.

<!-- -->

e)  Ein Kunde erinnert sich an ein Zeitproblem bei Computern, das beim
    Datumswechsel von 1999 auf 2000 auftrat. Ihn beunruhigt, ob so etwas
    zukünftig zu erwarten ist. Recherchieren Sie zu dem
    Jahr-2000-Datumsproblem, das auch als Millennium-Bug oder Y2K-Bug
    bezeichnet wurde.

    Erklären Sie das technische Problem das sich dahinter verbarg.
    Recherchieren Sie nach dem Aufwand, der betrieben wurde, um einen
    großflächigen Ausfall von Computersystemen zu vermeiden.

<!-- -->

f)  Recherchieren Sie, welche zukünftigen Überlaufe von Zeitsystemen zu
    erwarten sind und notieren Sie wann sie stattfinden werden.
