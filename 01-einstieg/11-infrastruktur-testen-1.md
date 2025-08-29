---
date: Schuljahr 2025/2026
lang: de-DE
subtitle: Lernfeld 10b -- Serverdienste bereitstellen und
  Administrationsaufgaben automatisieren
title: Infrastruktur testen
---

Grundlage: Abschnitt 4.7, S. 415--419

## Aufgabe 1

Beschreiben Sie, wie Sie Netzwerkkabel auf Ihre Funktion prüfen können.

:::
Kabeltester verwenden → misst, ob alle Adern korrekt aufgelegt sind (Durchgangsprüfung, Verdrahtung).

Mit Notebook/PC testen → Kabel anschließen und prüfen, ob eine Verbindung aufgebaut wird (z. B. Link-LED am Switch/PC).

Netzwerkanalysegerät → kann zusätzlich Signalqualität, Länge oder Störungen prüfen.
:::

## Aufgabe 2

Recherchieren Sie den Einsatzzweck von Crosskabeln.

:::
Dienen zum direkten Verbinden zweier gleichartiger Geräte ohne Switch/Hub.

Typische Beispiele:

PC ↔ PC

Switch ↔ Switch (ältere Geräte, heute oft nicht mehr nötig wegen Auto-MDI-X).

Heute weniger verbreitet, da moderne Netzwerkkarten automatisch die Belegung erkennen.
:::

## Aufgabe 3

Beschreiben Sie eine Möglichkeit, wie Sie die NetzwerkKonfiguration
eines Server überprüfen.
:::
ipconfig /all
:::
## Aufgabe 4

Nennen Sie ein Shell-Kommando inklusive Beispiel, mit dem Sie die
Funktion des DHCP-Servers überprüfen.
:::
ipconfig /renew
:::
## Aufgabe 5

Nennen Sie ein Shell-Kommando inklusive Beispiel, mit dem Sie die
Funktion des DNS-Servers überprüfen.

:::
dig @8.8.8.8 www.google.com
:::
## Aufgabe 6

Nennen Sie ein Shell-Kommando, mit dem Sie die Netzwerkkomponenten
innerhalb des Subnetzes auflisten können.
:::
ping -b 192.168.0.2557
arp -a
:::
