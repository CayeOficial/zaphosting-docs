---
id: gameserver-tebex
title: TEBEX Gameserver Monetarisierung einrichten
description: Informationen wie du mit TEBEX mit deinem Gameserver von ZAP-Hosting Geld verdienen kannst und wie du TEBEX auf deinem Server einrichtest - ZAP-Hosting.com Dokumentation
sidebar_label: TEBEX Monetarisierung
---



## Einführung

TEBEX ist eine Plattform die dir erlaubt, mit deinem Gameserver bares Geld zu verdienen,
indem du in-game Gegenstände, Ränge und vieles mehr verkaufen kannst. Die Plattform 
stellt dir einen professionellen Webstore zur Verfügung, mit dem du digitale Güter verkaufen
und einige Statistiken zu deinen Verkäufen einsehen kannst. Besuche 
[tebex.io](https://affiliate.tebex.io/r/690a6731-fee1-4054-84e1-30c26729403a)
für weitere Informationen über die Funktionsweise.

## Welche Spiele werden von TEBEX unterstützt?
Die Plattform unterstützt aktuell folgende Spiele: [Hier klicken](https://www.tebex.io/games)



## Wie wird TEBEX mit dem ZAP Interface konfiguriert?

TEBEX mit ZAP 2.5 einzurichten ist kinderleicht.

### Schritt 1 - Installation eines unterstützten Spiels auf deinem Gameserver
Wähle ein Spiel aus, welches aktuell durch TEBEX unterstützt wird und installiere es auf deinem
Gameserver. Klicke hierzu auf "Spiele" in der Seitenleiste. Wähle nun unter "Verfügbare Spiele"
ein unterstütztes Spiel auf und klicke auf den Download-Button, um es zu installieren. Sobald 
dieser Vorgang abgeschlossen ist, kannst du mit Schritt 2 fortfahren.

### Schritt 2 - Sende dir selbst eine TEBEX Einladung
Wenn das Spiel, welches du ausgewählt hast, TEBEX unterstützt, siehst du nun den Tab "TEBEX Shop"
in der Seitenleiste. Klicke nach dem laden der Seite auf das Bild mit dem TEBEX Logo. 

![](https://user-images.githubusercontent.com/61839701/165710944-616d743c-94da-49c8-8e07-340a857a300c.png)

TEBEX sendet dir nun eine Einladung an die E-Mail Adresse, die in deinem ZAP-Hosting Kundenaccount hinterlegt
ist. Bitte folge den Schritten in der E-Mail um deinen TEBEX Account zu aktivieren. Du wirst im 
Anschluss durch die Einrichtung deines Webshops durchgeführt.

### Schritt 3 - Installiere das TEBEX Plugin auf deinem Gameserver
Dieser Prozess wird in der Regel automatisiert durchgeführt. Wenn wir kein Plugin für 
die automatisierte Installation auf unseren Servern finden können oder das Pingback von 
TEBEX fehlt, musst du das Plugin manuell installieren.

#### Schritt 4 - Installiere & konfiguriere das TEBEX Plugin
Installiere das passende Plugin für dein Spiel manuell auf deinem Gameserver. Der Prozess
unterscheidet sich von Spiel zu Spiel. Eine grundlegende Schritt für Schritt Anleitung zur 
Installation einiger Plugins findest du [hier](https://docs.tebex.io/store/integrating-with-your-game-server-or-website/minecraft-java-edition).

#### Schritt 5 - Bestätige die erfolgreiche Installation im Webinterface
Zu guter letzt solltest du noch die erfolgreiche Installation des Plugins bestätigen. 

![](https://user-images.githubusercontent.com/61839701/165711089-dc26184c-74b3-4207-bfe8-6d75208b0091.png)

In einigen Fällen kann es sein, dass du uns noch einmal den TEBEX Webstore API Schlüssel 
mitteilen musst, damit wir aus ZAP 2.5 eine Verbindung zu deinem TEBEX Shop aufbauen können.

Im Anschluss kannst du dann sehen, dass die Verbindung erfolgreich angelegt wurde:
![](https://user-images.githubusercontent.com/61839701/165711219-bcc42cfb-45da-4575-a98d-66b8ab76430b.png)
