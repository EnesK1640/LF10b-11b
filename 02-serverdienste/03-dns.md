---
css: ../css/style.css
date: Schuljahr 2025/2026
lang: de-DE
subtitle: Lernfeld 10b -- Serverdienste bereitstellen und
  Administrationsaufgaben automatisieren
title: Serverdienste -- DNS
---

## Aufgabe 1

Erläutern Sie am Beispiel von `h394.dc23.eu.mycloud.eu` die Begriffe
FQDN, Subdomain und TLD.

Geben Sie dazu auch die Bedeutung der Akronyme an.

## Aufgabe 2

Erklären, sie was ein DNS-Root-Server und dessen Aufgabe ist.

## Aufgabe 3

Unterscheiden Sie die Begriffe Forward- und Reverse-Lookup.

## Aufgabe 4

Erläutern Sie, inwiefern eine Fritzbox als DNS-Forwarder arbeitet und
inwiefern Sie als authoritativer Server arbeitet.

## Aufgabe 5

Beschreiben Sie, was Cache-Poisoning ist und wie es mit DNSSEC
verhindert werden kann.

## Aufgabe 6

Erklären Sie, wozu »DNS over TLS« eingeführt wurde und wie es
funktioniert.

## Aufgabe 7

Sie sollen die Funktionsweise des DNS-Protokolls genauer betrachten.
Ohne eine funktionierende Namensauflösung sind viele Anwendungen nicht
nutzbar.

a)  Beschreiben Sie, was mit einem DNS-Forward-Lookup erreicht wird und
    geben Sie den Ablauf an.

<!-- -->

b)  Entscheiden Sie, ob die folgenden Aussagen zum DNS richtig oder
    falsch sind.

    a)  Die Datei „hosts" wurde historisch für die Namensauflösung
        verwendet und kommt heute nicht mehr zum Einsatz.

    <!-- -->

    b)  Eine Zone legt fest, für welchen Bereich in der DNS-Hierarchie
        ein Server autoritativ ist.

    <!-- -->

    c)  Die DNS-Root-Server sind in der Hierarchie die obersten Server
        und werden von Resolvern als erstes angefragt. Sie kennen jedoch
        nur die IP-Adressen von DNS-Servern der Top-Level-Domänen.

    <!-- -->

    d)  Aus Sicherheitsgründen gibt es die 13 DNS-Root-Server mehrfach.
        Über IP-Multicast wird der geografisch am nächsten gelegene
        Server ausgewählt.

    <!-- -->

    e)  Root-Hint ist eine Textdatei, die von der IANA-Webseite
        heruntergeladen werden kann. Sie enthält die 13 IPv4- und
        IPv6-Adressen der DNS-Root-Server. Sofern kein Forwarder
        eingetragen ist, benötigt jeder Resolver diese Datei, um eine
        Abfrage in der DNS Hierarchie starten zu können.

    <!-- -->

    f)  DNS over TLS (DoT) und DNS over HTTPS (DoH) zielen darauf ab,
        die Verbindung vom DNS-Client zum DNS-Resolver abzusichern.

    <!-- -->

    g)  DNSSEC zielt darauf ab, die Abfrage eines DNS-Clients zum
        DNS-Resolver abzusichern.

<!-- -->

c)  Erklären Sie den Unterschied zwischen einem Fully Qualified Domain.
    Name (FQDN) und einem Uniform Resource Locator (URL).

<!-- -->

d)  Eine Angriffsart auf das DNS-System ist ein sogenanntes
    „DNS-Cache-Poisoning". Beschreiben Sie den Ablauf dieses Angriffs
    und erläutern Sie eine Möglichkeit, sich davor zu schützen.
