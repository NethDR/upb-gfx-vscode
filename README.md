# upb-gfx-vscode

Adauga cateva configuratii pentru vscode ca sa folositi vscode ca IDE cu https://github.com/UPB-Graphics/gfx-framework si https://github.com/UPB-Graphics/gfx-framework-ppbg.

# Instalare

Din radacina framework-ului dati comanda:
```shell
git clone https://github.com/NethDR/upb-gfx-vscode.git .vscode
```

Asta da clone la repo-ul asta si pune continutul intr-un folder numit .vscode (daca e deja un folder .vscode existent, puteti copia cele 2 fisiere direct acolo)

# Utilizare

Inainte de a da compila si rula prima oara proiectul si de fiecare data cand adaugati un fisier nou/stergeti un fisier, dati run la build task-ul 'Generate GFXF project' (posibil sa aveti nevoie sa creati folderul build inainte de asta). Asta la mine apare in tab-ul `Terminal` cu default hotkey `F7`.

Ca sa compilati si rulati folositi configuratia de launch pentru sistemul vostru de operare (Windows sau Linux) (asta face automat si build).
