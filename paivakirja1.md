# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Tämä Git:in, repositorion ja terminaalin käyttö tuntuu vielä aika hurjalta. Minulla on yhden kurssin verran kokemusta Git:in käytöstä, joten kyllä se siitä pikku hiljaa. Harjoitukset 1 ja 2 olivat helppoja. Harjoituksissa 3 ja 4 käytettiin minulle uusia komentoja, joten ne eivät yhtä helppoja, mutta sain tehtyä.

Oppimisen tukena ja ongelmanratkaisuun käytin Youtubea. Sieltä videot https://www.youtube.com/watch?v=mJ-qvsxPHpY ja https://youtu.be/EGooeHH3hDY olivat hyödyllisiä.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | Luo uuden repositorion |
| git status | Näyttää repositorion nykyisen tilanteen |
| git add . | Lisää kaikki hakemiston muutokset seuraavaan commitiin |
| git commit -m | Tekee muutoksista uuden talletuksen ja "-m" voidaan lisätä kuvaus |
| git rm | Poistaa tiedoston  |
| git log --oneline | Näyttää commit historian, yksi per rivi |
| git restore . | Peruuttaa kaikkien versionhallinnassa olevien tiedostojen tallettamattomat muutokset |
| git revert HEAD | Peruuttaa viimeisimmän commitin, tekemällä uuden, joka kumoaa sen muutokset |
| git branch | Näyttää paikalliset haarat ja kertoo mikä on aktiivinen |
| git switch | Vaihtaa haaraa |
| git merge --no-ff | Yhdistää halutun haaran aktiiviseen haaraan |
| git log --oneline --decorate --graph --all | Näyttää commit historian graafina sekä haarat ja tagit |