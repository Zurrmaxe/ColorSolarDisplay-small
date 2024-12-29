


Hier erstmal die wichtigsten Infos zum Display:
https://randomnerdtutorials.com/cheap-yellow-display-esp32-2432s028r/
https://randomnerdtutorials.com/cheap-yellow-display-esp32-2432s028r/#config-file-windows-pc
https://github.com/witnessmenow/ESP32-Cheap-Yellow-Display/tree/main


Hinweis:
Bitte unbedingt die Einstellungen in der Arduino IDE und der Librarys beachten !
Nicht alle aktuellen Librarys laufen problemlos. Die aufgeführten Versionsnummern bitte beachten.
Die Einstellungen für das Display müssen vorgfälltig vorgenommen werden.
Sind an einer Arduino IDE gleichzeitig unterschiedliche Displays und ESPs angeschlossen, kann es zu Problemen kommen.

Diese Anzeige kann natürlich auch für andere Inverter oder DTUs angepaßt werden. DAzu sind die entsprechenden Code für die Abfrage der JSON-Files entsprechend zu ändern.

Diese Anzeige ist noch nicht fertig und wird von mir laufend verändert.

Beim Druck auf dem Bildschirm wird die Beleuchtung für 5 Sekunden heller eingestellt.

Eine Nachabschaltung ist noch nicht vorhanden aber in Arbeit.

Neben dem Wochentag und der Uhrzeit wird noch die Qualität des WLAN angezeigt um das Display optimal zu plazieren.

Dann ist da noch Anzeige der Raumtemperatur mit einem DHT11-Sensor, welcher am Display angeschlossen ist.

Wenn kein Solarinverter bzw. die dazugehörige DTU "erreichbar" ist, wird das jeweilige Feld ausgeblendet.


Natürlich alles ohne Garantie und Haftung für irgendwelche Schäden.

Alf
