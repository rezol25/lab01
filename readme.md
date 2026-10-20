## Autor 
Farhat Dany
Gr 1B

## Git status

On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")

## Git diff

diff --git a/.gitignore b/.gitignore
index e69de29..6cbb645 100644
--- a/.gitignore
+++ b/.gitignore
@@ -0,0 +1,9 @@
+# .gitignore – fișiere care nu se versionează
+# Rezultate de compilare
+build/
+*.hex
+*.o
+# Jurnale
+*.log
+# Setări personale ale editorului
+.vscode/
diff --git a/readme.md b/readme.md
index e69de29..9d31008 100644
--- a/readme.md
+++ b/readme.md
@@ -0,0 +1,3 @@
+## Autor 
+Farhat Dany
+Gr 1B
\ No newline at end of file

## Hardware

Arduino Uno R3, senzor de temperatura TMP36


Platformă: Arduino Uno R3 (ATmega328P)

Autor laborator: <Farhat Dany>

## Parametri 

config.h

#define CONFIG_H
#define SENSOR_PIN A0 // intrarea analogică a senzorului
#define SAMPLE_PERIOD_MS 500 // perioada de eșantionare (ms)
#define SERIAL_BAUD 19200 // viteza portului serial
#define LED_PIN 13 // LED de stare
