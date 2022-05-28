# Starten der .jar

Die .jar kann nur gestartet werden, wenn beim Aufruf die VM Options angegeben werden.

Beispiel für Windows:\
java -jar --module-path "pfad\zur\javafx\lib" --add-modules javafx.controls,javafx.fxml RoboRallyProject.jar

1. "pfad\zur\javafx\lib" muss selbstverständlich durch den eigentlichen Pfad zur JavaFX library ersetzt werden\
Der Pfad sollte standardmäßig unter "C:\Program Files\Java\javafx-sdk-17.0.1\lib" zu finden sein.
2. die CMD muss im Ordner im selben Ordner gestartet werden, in dem die .jar Datei liegt
3. wenn die Jar dennoch nicht startet, kann ggf. ein Update von JavaFX helfen
