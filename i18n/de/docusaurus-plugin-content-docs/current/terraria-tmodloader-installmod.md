---
id: terraria-tmodloader-installmod
title: Installation von Mods (tModLoader)
description: Informationen, wie du Mods auf deinen Terraria-Server mit tModLoader installieren kannst - ZAP-Hosting.com Dokumentation
sidebar_label: Mods installieren (tModLoader)
---


## Modinstallation via tModLoader

Beim tModLoader für Terraria handelt es sich um eine wichtige Modifikation welche das laden von Mod's auf deinem Terraria Server ermöglicht. 
Die Installation geschieht via Drag & Drop und mit nur einer Anpassung an deinem Server, das ganze ist also kinderleicht und in wenigen Minuten erledigt. 


## Installation von tModLoader auf deinem PC

Falls du tModLoader noch nicht installier hast, kannst du dir diesen **kostenlos** direkt via Steam herunterladen.
Suche dazu im Steam Store einfach nach **tModLoader** oder verwende folgenden Link: [tModLoader im Steam Store](https://store.steampowered.com/app/1281930/tModLoader/)

Nach dem Download und der Installation kannst du deinen tModLoader direkt über Steam starten.


## Hinzufügen von Mod's auf deinem PC

Im Hauptmenü angekommen öffnest du deinen Mod-Ordner, dies tust du durch einen Klick auf **Workshop** und im Anschluss auf **Mods verwalten** dann :

![image](https://user-images.githubusercontent.com/26007280/189974782-6b669299-887f-4bb8-acb6-98e8b7976ac6.png)

![image](https://user-images.githubusercontent.com/26007280/189974811-244adf07-ea64-4fb2-ac44-5dd3e2927020.png)

In den nun geöffneten Ordner welcher sich standartmäßig unter **C:\Users\Benutzername\Documents\My Games\Terraria\ModLoader\Mods** befindet kannst du nun deine gewünschten Mod's legen.
In diesem Beispiel installieren wir die Calamity-Mod.

![image](https://user-images.githubusercontent.com/26007280/189974838-c5b4f3de-29d0-4497-b066-0d94ae7d868f.png)

:::info
Eine Mod muss immer die Endung **.tmod** haben, sonst kann diese nicht vom Server geladen werden! 
:::


Danach kannst du den Ordner wieder schließen, klickst dann im Spiel auf **Zurück** und im Anschluss erneut auf **Mods**: 

![image](https://user-images.githubusercontent.com/26007280/189974856-20bc40c8-cc29-4c78-bd25-59ca78a48625.png)

Dort wird dir nun deine hinzugefügte Mod angezeigt welche du mit einem Klick auf **Deaktiviert** aktivieren kannst: 

![image](https://user-images.githubusercontent.com/26007280/189974874-1d63f182-70eb-4e14-8795-7fb0e510fe62.png)

Damit die Mod aktiv wird klickst du nun auf **Mods neu laden**, danach kannst du das Spiiel erst einmal wieder schließen und du beginnst mit der Installation der Mod auf deinem Server.


## Installation von Mod's auf deinem Server

Um die Mod nun auch auf deinem Server installieren zu können verbindest du dich via FTP zu deinem Server, wie das funktionkiert erfährst du hier: [FTP Dateizugriff](https://zap-hosting.com/guides/docs/de/gameserver_ftpaccess/)

Dort navigierst du in folgendes Verzeichnis: /g******/terraria/mods/ wo du ebenfalls die zuvor verwendete **.tmod** Datei einfügst:

![image](https://user-images.githubusercontent.com/26007280/189974897-5721d422-b608-451e-ab3f-b35de3fa9caf.png)

:::info
Sollte dort keine Datei mit dem Namen **enabled.json** existieren musst du den Server zuerst einmal starten, danach sollte diese erscheinen. Alternativ kannst du die Datei auch selbst erstellen.
:::


Im Anschluss öffnest du die Datei **enabled.json** via **Rechtsklick > Bearbeiten** und fügst dort den Namen deiner Mod ein, was so aussehen sollte: 

![image](https://user-images.githubusercontent.com/26007280/189974918-9fb18b3e-41cf-459a-9f0b-2313ebed6f7a.png)

Solltest du mehrere Mod's einfügen wollen, kannst du dies so tun: 

![image](https://user-images.githubusercontent.com/26007280/189974942-5006a4b7-fe10-4fe8-9d83-db74a6fc2011.png)

:::info
Beachte bitte dass hinter jedem Mod-Namen ein Komma gesetzt werden muss, außer beim Namen der letzten Mod!
:::

Nun kannst du die FTP Verbindung schließen, deinen Server starten und mit dem bei Steam heruntergeladenen tModLoader auf deinen Server verbinden. 

Durch das drücken von **ESC**, einem anschließenden Klick auf **Einstellungen** und dann einem Klick auf **Mod Configuration** siehst du deine auf dem Server geladenen Mod's:
