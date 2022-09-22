### Cluedo Daten Modell implementieren

Die Personen, Waffen und Räume erscheinen als Tabellen in der View.

(c) P. Rutschmann 2022

Wie lange die App läuft: 30 Min wenn inaktiv

Applikation ausschalten: 
heroku ps:scale web=0

Applikation anschalten:
heroku ps:scale web=1

Applikation löschen:
heroku apps:destroy