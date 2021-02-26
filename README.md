# Arch-Linux-Presentation
Slides per il seminario "Arch Linux" presso il Dipartimento di Matematica e Informatica dell'Università degli Studi di Catania. Il seminario ha l'obiettivo di spiegare le peculiarità della distrubuzione Arch Linux e fornire delle basi per una sua installazione minimale.

- Cos'è una distribuzione GNU/Linux?
- Cos'è Arch Linux?
- Perché Arch Linux? Cosa lo differenzia dalle altre distribuzioni? A quali contesti si adatta bene?
- Installazione minimale di Arch Linux(con Gnome)
- Strumenti utili(pacman, AUR, makepkg, AUR)
- Conclusioni

# Run server mode with Docker
```
docker run --rm --init -v $PWD:/home/marp/app -e LANG=$LANG -p 8888:8080 -p 37717:37717 marpteam/marp-cli -s .
```
