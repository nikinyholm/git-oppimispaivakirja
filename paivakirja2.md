# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Helppoa oli uuden haaran luominen, haarojen välillä liikkuminen ja muutosten lisääminen, koska näitä harjoiteltiin jo aikaisemmin.

Vaikeampaa oli paikallisen repositorion ja Githubin etärepositorion käyttäminen yhdessä. Opin paremmin erottamaan paikallisen haaran ja etärepositorion haaran.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git remote add origin "osoite" | Lisää etärepositorion nimellä |
| git remote -v | Näyttää määritetyt epärepositoriot |
| git switch -c new-feat | Luo uuden haaran ja siirtyy siihen |
| git push -u origin new-feat | Vie new-feat-haaran etärepositorioon |
| git fetch | Hakee etärepositorion uudet muutokset yhdistämättä niitä |
| git switch --detach origin/new-feat | Siirtyy tarkastelemaan origin/new-feat-haaran committia detached HEAD -tilassa
| git merge origin/new-feat | Yhdistää etärepositorion new-feat-muutokset paikalliseen haaraan |
| git switch main | Siirtyy main-haaraan |
| git merge new-feat | Yhdistää new-feat-haaran main-haaraan |
| git push origin main |  Vie päivitetyn main-haaran GitHubiin |
| git tag harjoitus5 | Lisää harjoitus5-tunnisteen nykyiseen committiin |
| git log --oneline --decorate --graph --all |Näyttää commit-historian, haarat ja tagit graafisesti |