Threadoptimierung: by Thomas Wellmann da Riva Cesar

In diese Aufgabe habe ich mit eine Procedual-Dungeon-Generator gearbeitet. Ich habe das Selbe Code einmal mit und einmal ohne Thread-Verteilung analysiert und die Ergebnisse vergleicht.
Zu achten sind Eigne Punkte:
-Auf Playmode drücke ich:
	-"Space", um das Dungeon zu generieren;
	-";" oder "Entf" auf der Numpad, um das Dungeon zu löschen (falls kein Numpad zur Verfügung, bitte im GameInput ändern).
	-"Tab", um das Generation-Script zwischen Threaded und Normal zu ändern.
-Im Inspector sollen folgende Werte kommen, damit es richtig Funktioniert:
	-'Size' ist am besten x:10, y:10. Wenn weniger ist der Unterschied zu klein. Wenn größer leidet mein PC.
	-'Offset' ist für diese Prefab immer x:34, y:34.
	-'Start Point' kann, falls nicht 0, zu Fehlern in der Generierung führen.
	-'Prefab' = "Room".
