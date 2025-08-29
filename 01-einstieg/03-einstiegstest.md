---
date: Schuljahr 2025/2026
lang: de-DE
subtitle: Lernfeld 10b -- Serverdienste bereitstellen und
  Administrationsaufgaben automatisieren
title: Einstiegstest LF10b
---

Überprüfen Sie Ihr Grundlagenwissen aus dem Lernfeld 9 „Netzwerke und
Dienste bereitstellen".

Bearbeiten Sie die folgenden Teilaufgaben.

## Aufgabe 1

a)  Bringen Sie die folgenden Prozessschritte in eine sachlogische
    Reihenfolge.

    - Ziele, Migrationsstrategie

    - Konzeptionierung

    - Ist-Analyse

    - Betrieb

    - Umsetzung

::::
    - Ist-Analyse

    - Konzeptionierung

    - Ziele, Migrationsstrategie

    - Umsetzung

    - Betrieb
::::
<!-- -->

b)  Beschreiben Sie die folgenden Aspekte des Projektmanagements in
    eigenen Worten.

    - Aufwandsabschätzung

    - Abnahme

    - Projektstrukturplan

    - Stakeholder-Analyse
:::
    Aufwandsabschätzung: Schätzung von Zeit, Kosten, Personalressourcen.

    Abnahme: Offizielle Bestätigung durch den Auftraggeber, dass das Projektergebnis den Anforderungen entspricht.

    Projektstrukturplan (PSP): Gliederung des Projekts in Arbeitspakete und Teilprojekte zur besseren Übersicht.

    Stakeholder-Analyse: Ermittlung aller beteiligten Interessengruppen und ihrer Erwartungen/Einflüsse.
:::
<!-- -->

c)  Geben Sie je zwei Aspekte an, die in einem Lasten- bzw.
    Pflichtenheft enthalten sind.
:::
    Lastenheft: Anforderungen des Auftraggebers, Zielsetzung, Einsatzbereich.

    Pflichtenheft: Technische Umsetzung, detaillierte Lösungsbeschreibung, Zeit-/Ressourcenplanung.
:::
## Aufgabe 2

Entscheiden Sie, ob die folgenden Aussagen richtig oder falsch sind.

a)  DevOps steht für Entwicklung und Betrieb eines Unternehmensbereichs.
:::
Falsch

DevOps steht für Entwicklung und Betrieb eines Unternehmensbereichs. → Falsch (DevOps = Development & Operations, Zusammenarbeit der Bereiche Entwicklung & Betrieb).
:::
<!-- -->

b)  Unter CI versteht man kontinuierliche Identifikation von neuen
    Anforderungen an einen Unternehmensbereich.
:::
Falsch

CI = kontinuierliche Identifikation von neuen Anforderungen. → Falsch (CI = Continuous Integration, kontinuierliches Einbinden von Codeänderungen).
:::
<!-- -->

c)  Der Bereich DevOps kann als Schnittmenge der Bereiche Entwicklung,
    Betrieb und Buchhaltung betrachtet werden.
:::
Falsch

DevOps = Schnittmenge von Entwicklung, Betrieb und Buchhaltung. → Falsch (Schnittmenge = Entwicklung, Betrieb, Qualitätssicherung).
:::

<!-- -->

d)  Der Bereich CD umfasst das Paketxeren Freigeben, Konftguneren und
    Überwachen einer Anwendungssoftware für die Kunden.
:::
Richtig

CD umfasst Paketieren, Freigeben, Konfigurieren und Überwachen. → Richtig (CD = Continuous Delivery/Deployment).
:::

    a) DevOps steht für Entwicklung und Betrieb eines Unternehmensbereichs. → Falsch (DevOps = Development & Operations, Zusammenarbeit der Bereiche Entwicklung & Betrieb).

    b) CI = kontinuierliche Identifikation von neuen Anforderungen. → Falsch (CI = Continuous Integration, kontinuierliches Einbinden von Codeänderungen).

    c) DevOps = Schnittmenge von Entwicklung, Betrieb und Buchhaltung. → Falsch (Schnittmenge = Entwicklung, Betrieb, Qualitätssicherung).

    d) CD umfasst Paketieren, Freigeben, Konfigurieren und Überwachen. → Richtig (CD = Continuous Delivery/Deployment).

## Aufgabe 3

a)  Ordnen Sie der Ethernet-Leitung die entsprechenden Bereiche 1-5 zu.
    Geben Sie weiterhin die Leitungsart (Kurzschreibweise) an.

    ![](images/lan-tp-kabel-querschnitt.png){width="50%"}

    | Nummer | Bereich        |
    |--------|----------------|
    |        | Folienschirm   |
    |        | Geflechtschirm |
    |        | Isolator       |
    |        | Ader           |
    |        |                |

    Leitungsart:

:::
    | Nummer | Bereich        |
    |--------|----------------|
    |    3   | Folienschirm   |
    |    4   | Geflechtschirm |
    |    2   | Isolator       |
    |    1   | Ader           |
    |    5   | Kabelmantel    |

     Leitungsart: Twisted Pair (TP), z. B. Cat 6a STP
:::
<!-- -->

b)  Es sollen die unterschiedlichen Adressierungsarten in einem Netzwerk
    betrachtet werden. Ergänzen Sie die folgende Tabelle zu den
    häufigsten Adressarten.

    | OSI-Schicht | Adressenname | Länge in Bit | Aufgabe |
    |----|----|----|----|
    | 4 |  |  | Identifikation der Anwendung bzw. des Dienstes |
    |  | MAC |  |  |
    | 3 |  |  |  |
    |  |  | 32 Bit |  |
:::
OSI-Schicht	Adressenname	Länge in Bit	Aufgabe
4	Portnummer	16 Bit	Identifikation von Anwendung/Dienst
2	MAC	48 Bit	Eindeutige Identifizierung eines Netzadapters
3	IP-Adresse	32 Bit (IPv4) / 128 Bit (IPv6)	Logische Adressierung Routing
7	Hostname	variabel	Menschlich lesbare Bezeichnung
:::
<!-- -->

c)  Geben Sie für den folgenden Netzplan die statischen Routen für
    Router R1 an, sodass dieser alle Netze erreichen kann.

    ![](images/lan-netzwerkplan.png)

    | Ziel         | Next Hop | Schnittstelle |
    |--------------|----------|---------------|
    | 10.0.10.0/24 |          |               |
    | 10.0.20.0/24 |          |               |
    | 10.0.30.0/24 |          |               |
    | 10.0.40.0/24 |          |               |
    | 10.0.50.0/24 |          |               |
:::
Ziel	Next Hop	Schnittstelle
10.0.10.0/24	10.0.20.1	Gi0/0
10.0.20.0/24	direkt	Gi0/0
10.0.30.0/24	10.0.20.2	Gi0/0
10.0.40.0/24	10.0.50.1	Gi0/1
10.0.50.0/24	direkt	Gi0/1
:::
<!-- -->

d)  Geben Sie jeweils mindestens drei technische Anforderungen an eine
    Firewall, einen Server und ein NAS an.

    1.  DSL-Modem
    2.  Analog-Modem
    3.  LWL-Modem
    4.  Webserver
    5.  Telefonanlage
    6.  TFTP-Server
    7.  WLAN-Accesspoint
    8.  Repeater
    9.  Firewall

    Firewall: Paketfilter, Stateful Inspection, Protokollierung, VPN-Support.

:::
Server: Ausreichende CPU/RAM, Redundanz, Virtualisierungsmöglichkeit, Ausfallsicherheit.

NAS: RAID-Unterstützung, Netzwerkanbindung (Gigabit+), Benutzer-/Rechteverwaltung, Datensicherung.
:::

## Aufgabe 4

Berechnen Sie den Bezugspreis für einen Server mithilfe der gegebenen
Werte.

Listenbreis: 5000,00 €

Lieferrabatt: 3 %

Skonto: 2 %

Transportkosten: 5000,00 € pro 100 Stück

:::
Listenpreis: 5.000,00 €

Lieferrabatt 3 %: –150,00 € → 4.850,00 €

Skonto 2 %: –97,00 € → 4.753,00 €

Transportkosten: 50,00 € pro Stück (5000 € / 100) → 4.803,00 €

Bezugspreis: 4.803,00 €
:::

## Aufgabe 5

Geben Sie die Aufgabengebiete der folgenden Programme an.

Beispiel:

ip (Linux): Konfiguration und Anzeige der IP-Adressen und Routen

- bmon

- netstat

- ipconfig

- nslookup

- arp

- tracert/traceroute

:::
bmon: Bandbreitenmonitor (Netzlast in Echtzeit).

netstat: Anzeige aktiver Verbindungen, Ports, Routingtabellen.

ipconfig (Windows): IP-Konfiguration anzeigen/ändern.

nslookup: DNS-Abfragen testen.

arp: ARP-Cache anzeigen/bearbeiten.

tracert/traceroute: Weg der Pakete durch das Netz anzeigen.
:::

## Aufgabe 6

Erklären Sie kurz die Unterschiede zwischen Docker, VirtualBox und
Proxmox.

:::
Docker: Container-Virtualisierung (Anwendungen, leichtgewichtig, nutzt Kernel des Hosts).

VirtualBox: Vollvirtualisierung (ganze Betriebssysteme, Desktop-orientiert).

Proxmox: Virtualisierungsplattform (Hypervisor + Container, Enterprise-Einsatz mit Clustern und Verwaltung).
:::