# VL-Einstiegsfolien

Einstiegsfolien mit neuem Layout

# Einstiegsfolien für die Vorlesungstermine mit Fallstudien im Modul Statistische Modellierung

## Personalisierung

In der Datei `_quarto.yaml` können Sie die Einstiegsfolien personalisieren (Name in den Zeilen 3 und 9, Standort in Zeile 2). Falls Sie im DLS lesen, können Sie das Folien-Layout in Zeile 23 umstellen (Zeile 22 dann bitte auskommentieren).

## Einmalige Installation der Erweiterungen für interaktive Inhalte

Bevor die Folien erzeugt werden, müssen einmalig folgende Schritte ausgeführt werden:

-   Öffnen Sie RStudio.
-   Prüfen Sie, ob die neueste Version von quarto vorhanden ist (in der Console über `quarto::quarto_version()`), sonst ggf. installieren oder auf die aktuelle Version updaten.
-   Wählen Sie unten den Reiter Terminal aus.
-   Wechseln Sie dort ins Verzeichnis, in dem Sie die Intro-Folien abgelegt haben.
-   Führen Sie dann nacheinander folgende Befehle im Terminal aus:
```         
> quarto install extension quarto-ext/fontawesome
> quarto install extension jmbuhr/quarto-qrcode
> quarto add coatless/quarto-webr
```
