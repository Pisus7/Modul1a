Wir möchten eine Java Bibliothek machen in der Sachen hinzu oder weggenommen werden können (einfach)

Für das was gespeichert werden soll, müssen entsprechend Werte gesetzt werden.
Titel, Wert, Standort etc.

es soll zur Verfügung stehen aufgenommen und angezeigt werden 

leicht erweiterbar keine Codeduplikation

# Zweites Video

Problemstellung angeschaut teile vom ersten Video

# Drittes Video

Klassen die benötigt werden
Enum wird besprochen (Sind typen die bestimmt werden können)

Mutterklasse Medium für die bestimmten Medien

Methode anzeigen zeigt die Werte auf Kommandozeile an

Ich habe mir die Klassen angeschaut und versucht Methoden zu verstehen Nun gehts zum zweiten Modul

# Modul 2

Vererbung erstes Thema... wichtig für bessere Struktur 

Konzepte

Vererbung
Subtyping
Polymorphe Variablen 

Beispiel

Es werden CDs DVDs abgespeichtert mit ihren Infos 
Suchen oder Listen ausgeben muss möglich sein

Getter und Setter und ausgebe Methoden gibt es 

Es gibt eine Datenbank in denen die DVDs bzw CDs gespeichert werden

Arraylists werden parametrisiert (Wichtig!! dadurch können in der Arraylist für CDs nur CDs gespeichert werden)


Datenbank Methode auflisten for each cd.ausgeben alles wrid ausgegeben mit Sout

Es wird bei DoMe oft Code dupliziert was jedoch nicht von Vorteil ist

Vererbung wird mit Tieren erklärt Beispiel Vögel Hunde 

Vererbung extends!

Super Klasse kein extends

Konstruktoren in der Unterklasse müssen alle Werte von der Superklasse setzen (geht auch mit default Werten)

super ist Mutterklassenkonstuktor aufruf (kennen wir schon)

super muss erster Aufruf

Wichtig hier ist!!! Dadurch dass wir CD und DVD jetzt von Medium extenden können wir daraus eine Arraylist machen(es wird nicht so viel Code dupliziert)

Wir können natürlich einem Auto auch als Fahrzeug angeben es ist zwar unspezifischer aber es ist möglich (sieht man auch bei Parametern)
wichtig Fahrzeug kann aber kein Auto sein da es nicht alle Werte hat die Auto enthält

Alle Klassen sind Objects also Erben von Object


