# Heuraufensteuerung
12V basierte Steuerung zum automatischen zeitabhängigem Öffnen und Schließen von Heuraufen

Bedienungsanleitung – ganz einfach erklärt
1. Grundprinzip
Die Steuerung bewegt einen Motor (12V DC) um eine Heuraufe zu öffnen oder zu schließen:
•	Öffnen (grüne LED)
•	Schließen (rote LED)
•	Entweder automatisch über die Zeitschaltuhr
•	Oder von Hand über die Taster
Die Fahrzeiten für Öffnen und Schließen sind fest einstellbar (webinterface)
 
2. Verhalten beim Einschalten (anlegen der 12V an die Steuerung)
Nach dem Start zeigt die Steuerung kurz:
1.	Grün leuchtet
2.	Rot leuchtet
Danach:
•	Wenn Auto-Modus AUS ist:
→ die rote LED blinkt (Hinweis: „Handbetrieb aktiv“)
 
3. Auto-Modus oder Handbetrieb
Auto-Modus EIN
•	Die rote LED blinkt nicht mehr
•	Die Zeitschaltuhr darf die Heuraufe automatisch bewegen
Handbetrieb
•	Rote LED blinkt dauerhaft
•	Die Zeitschaltuhr steuert NICHT, sie zeigt nur grün blinkend ein Signal an, wenn sie öffnen würde
•	Bewegen kann man nur über die beiden Taster
 
4. Taster „Auf“ (Öffnen)
Einfach drücken und halten
•	Motor fährt solange du drückst
•	Grüne LED leuchtet
•	Beim Loslassen → Motor stoppt sofort
Doppel-Klick (langsamer drücken als bei der Maus am Rechner)
•	Heuraufe öffnet komplett
•	Grüne LED leuchtet dabei
•	Danach stoppt alles wieder selbst
 
5. Taster „Zu“ (Schließen)
Einfach drücken und halten
•	Motor fährt solange du drückst
•	Rote LED leuchtet
•	Beim Loslassen → Motor stoppt sofort
Doppel-Klick (langsamer drücken als bei der Maus am Rechner)
•	Heuraufe schließt komplett
•	Rote LED leuchtet dabei
•	Danach stoppt alles wieder selbst
 
6. Zeitschaltuhr (Timer)
Der Timer kommt z. B. von einer Zeitschaltuhr oder einem Shelly Plus 1 12V (nicht installiert)
Wenn der Timer „an“ ist:
•	Die grüne LED blinkt
Im Auto-Modus zusätzlich:
•	Timer an → Die Heuraufe öffnet automatisch
•	Timer aus → Die Heuraufe schließt automatisch
Im Handbetrieb:
•	Die grüne LED blinkt nur als Anzeige
•	Die Heuraufe bewegt sich nicht automatisch
 
7. LED-Anzeigen – schnell erklärt
Grüne LED
•	Leuchtet: Die Heuraufe fährt auf
•	Blinkt: Timer aktiv
Rote LED
•	Leuchtet: Die Heuraufe fährt zu
•	Blinkt: Auto-Modus aus → Handbetrieb
 




Übersichtskarte – 6 Fresszeiten für deine Zeitschaltuhr
(ON = Öffnen / OFF = Schließen)




 
🕒 1. Beispiel-Fresszeiten 
Diese Zeiten sind alltagstauglich und orientieren sich an deinem Wunschstart um 06:00.
Fresszeit	Öffnen (ON)	Schließen (OFF)
1	06:00	07:00
2	10:00	11:00
3	13:00	14:00
… bis 20 Zeiten (meist reichen 5-6)
passe es genau an deinen Stall-Rhythmus an.
 
📘 2. Schritt-für-Schritt Anleitung zum Programmieren
🔧 A. Uhrzeit einstellen
1.	CLOCK gedrückt halten
2.	Währenddessen:
o	D+ = Wochentag
o	H+ = Stunde
o	M+ = Minute
3.	CLOCK loslassen → gespeichert
 
🟦 B. Schaltzeiten programmieren
Du programmierst immer ein Paar:
ON1 → OFF1, dann ON2 → OFF2 … bis ON6 → OFF6
 
🥇 Fresszeit 1 programmieren (06:00 – 07:00)
➤ ON1: Öffnen
1.	P drücken → Display zeigt 1 ON
2.	Wochentage mit D+ auswählen (am besten MO–SO)
3.	H+ → 06 einstellen
4.	M+ → 00 einstellen
➤ OFF1: Schließen
1.	P drücken → Display zeigt 1 OFF
2.	H+ → 07
3.	M+ → 00
 
🥈 Fresszeit 2 programmieren (10:00 – 11:00)
➤ ON2
•	P drücken, bis 2 ON erscheint
•	10:00 einstellen
➤ OFF2
•	P drücken, bis 2 OFF erscheint
•	11:00 einstellen
 
🥉 Fresszeit 3 programmieren (13:00 – 14:00)
➤ ON3
•	3 ON → 13:00
➤ OFF3
•	3 OFF → 14:00
 
🟩 Fresszeit 4 …
 
🔁 3. Wichtig: Betriebsmodus einstellen
Oben rechts der Schalter:
•	AUTO → das Programm läuft automatisch (muss aktiv sein)
•	ON → dauerhaft EIN
•	OFF → dauerhaft AUS
👉 Für die Heuraufe immer AUTO verwenden!








