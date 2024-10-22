# Grundlagen der systemnahen Programmierung Praktikum - Aufgaben

Willkommen zu den Aufgaben des Praktikums "Grundlagen der systemnahen Programmierung". Dieses Repository enthält die praktischen Übungen, die während des Semesters behandelt werden. Jede Aufgabe ist in einem eigenen Ordner organisiert.

## Struktur des Repositories

Jeder Ordner repräsentiert eine spezifische Übung aus dem Praktikum. Die Aufgaben sind fortlaufend nummeriert, um die Reihenfolge der Bearbeitung zu verdeutlichen. In jedem Ordner finden Sie:

- **Quellcode**: Die Implementierung der Lösung.
- **Zusätzliche Dateien**: Beispielausgaben, Skripte oder Daten, die zur Aufgabe gehören.

## Verzeichnisübersicht

- `Aufgabe_1/` - RPN Taschenrechner (In Entwicklung)
- `Aufgabe_2/` - Drehgeber Polling (In Entwicklung)
- `Aufgabe_3/` - BITMAP (In Entwicklung)
- `Aufgabe_4/` - Wire Bus (In Entwicklung)
- `Aufgabe_5/` - Drehgeber Interrupt (In Entwicklung)

## Voraussetzungen

Um die Aufgaben auszuführen, sollten die folgenden Werkzeuge installiert sein:

- **CMake**
- **STM32CubeIDE**
- **GNU ARM Toolchain arm-none-eabi**
- **Microsoft Visual Studio mit Embedded Systems-Modul** (optional)

## Ausführung der Aufgaben

1. **STM32CubeIDE verwenden**:
   - Öffnen Sie STM32CubeIDE.
   - Wählen Sie im Menü `File -> Open Projects from File System`.
   - Wählen Sie das `.cproject` aus dem entsprechenden Aufgabenordner.
   - Bauen und flashen Sie das Projekt auf ein STM32-Board.

2. **Microsoft Visual Studio mit Embedded Systems-Modul**:
   - Öffnen Sie Microsoft Visual Studio.
   - Stellen Sie sicher, dass das Embedded Systems-Modul installiert ist.
   - Öffnen Sie das `.cproject`-File des entsprechenden Aufgabenordners über `File -> Open -> Import STM32CubeIDE project...`.
   - Bauen und flashen Sie das Projekt auf ein STM32-Board. Wählen Sie das Skript `LAUNCH` and lassen Sie das ausführen.
