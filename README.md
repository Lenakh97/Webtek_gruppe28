# Webtek_gruppe28

## Laste ned prosjekt for første gang

Åpne terminalen, og gå dit du vil ha prosjektet.
Jeg bruker feks:

```sh
cd Documents/webtek/webtek_gruppe28
```

for å komme inn i riktig mappe. Deretter må du klone prosjektet og gå inn i prosjektmappe:

```sh
git clone https://github.com/Lenakh97/Webtek_gruppe28.git
cd Webtek_gruppe28
```

Du har nå prosjektet på pc'en din, og kan bruke editoren du liker. Jeg liker VSCode<3

## Endre ting i prosjektet etter du har lastet det ned første gang

Husk å gå inn i riktig mappe og ALLTID SKRIVE:

```sh
git pull
```

i terminalen før du gjør noe. Dette er for å hente endringene som er gjort tidligere av andre personer. For å være sikker på at man ikke ødelegger for hverandre kan det være lurt å jobbe i en egen branch. Da skriver du:

```sh
git checkout -b my-branch
```

hvor du bytter ut 'my-branch' med navnet på branchen din. Den skal beskrive hvilke endringer du gjør.

For å holde styr på endringer, slik at man har oversikt og kan gå tilbake, er det lurt å legge til endringene hele tiden. Feks hvis jeg har lagt til et avsnitt på siden min og stylet det, kan det være lurt å legge det til. Da skriver man:

```sh
git status
```

for å se hvilke filer som er endret. For å legge til filer skriver man:

```sh
git add <file-name>
```

hvor man bytter ut filename med navnet på fila. Feks 'git add P0_Requirements.html'. Derretter må du commite fila, ved å skrive:

```sh
git commit -m <commit-message>
```

Her er det vanlig å skrive 'fix: hva du har fiksa' eller 'feat: hva du har lagt inn' hvor fix er når du fikser på noe mens feature er en ny ting som er lagt til. Etter du har commit'et, må du huske å skrive:

```sh
git push
```

Det er for å faktisk sende endringene dine til github.

Når du skriver git push kan det være du må skrive inn brukernavn og passord på github. Jeg pleier å bruke brukernavnet mitt, og som passord bruker jeg en github token. Den kan du lage ved å gå til profilbildet ditt oppe til høyre --> settings --> Developer settings --> Personal access tokens --> generate new token. Dette får du kun se en gang, så husk å lagre det en plass slik at du har det.

Når du har gjort dette vil du se din branch på github. Du kan deretter gå inn på den og lage en Pull Request, slik at vi andre kan se over det som har blitt gjort før den blir lagt til i selve koden på 'main branch'.
