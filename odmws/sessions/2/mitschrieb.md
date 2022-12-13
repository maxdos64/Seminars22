# L Peukert
- Started writing
- VMHunt does not work currently (compiles)
- Problems to get Intel PIN (3.2) to get to run

# Maximilian Frühauf - Debin
- Literaturrecherche, verstehen der paper
- introduction geschrieben
- dataset gefunden ~1000 binarys elf, pe each - coreutils, findutils, ...
- debin läuft ok
- classifier training gestratet
- moa computing power pls
- todo: understanding the mapping algorithm
## nextup
- 64 bit dataset analysieren
- malware.. (provided by us probably)

# Luca Pawlik - TIRO
- Paper schreiben angefangen
- Problem beim organisieren des quellcodes
- Target step -> based on intellidroid - fokusiert auf API
- wenn code nicht verfügbar: vergleichen intellidroid mit target step in TIRO

# Alina Weber
- c++ binaries oberflächlich angeschaut
- fokus tools zum laufen bringen
- c++ lernen / 1000 zeilen code
- Im docker compiliert
- andere windows compiler evlt (mingw, älteres Visual Studio)

# Petra Pauker - Driller
- Verbesserung: Reihenfolge ändern (nicht erste mit der Idee: Aber hatte schon jemand, code evtl nicht öffentlich)
- eiarbeitung in die fuzzer komponente (AFL)
- Gliederung steht, stichpunkte
- problemen mit der environment
- freut sich auch VM

# Axel Strodel - QSim
- FUSER, hybrid fuzzer
- grundlagen ins paper eingearbeitet
- VM aufgesetzt
- auch probleme mit pintools (wird für dynamic binary translation hergenommen)
## Todo
- mit echten samples ausprobieren
- überprüfung von claims die im paper gemacht werden (path explosion ist nicht das problem, snapshoting is das problem)

# Florian Freud - Amora
- related work durchlesen (redqueen)
- code analyse
- auch probleme mit PIN
- ziel von amora: code coverage
## eindruck vom tool
	- buffer overflow undetected, 
	- atoi, strtol, ... zum teil ignoriert
- mittelmäßiger eindruck vom tool (buffer overflow undetected)

# Fabian Kilger - Accelerating Array Constraints in symbolic execution environments
- Setup complete
- experimente laufen
- mim draft angefangen (struktur)
- parallel building produces weird errors
- LAVA probleme in setup.py 404 errors
## braucht mehr
