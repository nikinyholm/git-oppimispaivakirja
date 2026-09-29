# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Gitin avulla pystyy seuraamaan mitä muutoksia olen tehnyt ja milloin. Jos teen muutoksia, jotka rikkoo ohjelman, voin tarvittaessa palata toimivaan versioon. Haarojen välillä on myös kätevä kokeilla uusia ominaisuuksia muuttamatta toimivaa päähaaraa. 

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Jokainen voi tehdä muutoksia omissa haaroissaan ilman, että muiden työ häiriintyy. Hyväksi todetut muutokset voidaan myöhemmin lisätä päähaaraan.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Käyttäisin GitHub-repositoriota, jossa olisi "main"- ja "develop"-haarat. "main" eli päähaara sisältäisi testatun ja valmiin version. Kehittäminen tapahtuisi "develop"-haaran kautta.

Kun tiimin jäsen aloittaa uuden ominaisuuden tekemisen, hän hakee ensin uusimmat muutokst ja luo oman "develop"-haaran. Muutokset tehdään ja commitetaan tähän haaraan. Commit-viestin pitää kertoa mitä on tehty.

Valmis ominaisuus viedään GitHubiin ja siitä tehdään Pull Request "develop"-haaraan. Vähintään yksi toinen tiimin jäsen tarkistaa muutokset ennen Mergeä. Kun ominaisudet on testattu toimiviksi, valmis "develop" yhdistetään "main"-haaraan.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakso oli hyödyllinen, koska pääsin vahvistamaan Git-osaamistani. Alkuun oli hankaluuksia ymmärtää, mitä terminaaliin kirjoitettiin ja mitä eri komennot tekivät, mutta harjoitusten edetessä niiden tarkoitus alkoi hahmottua paremmin.
Tykkäsin siitä, että harjoitukset rakentuivat aikaisempien harjoitusten päälle. Viimeiset tehtävät tuntuivat olevan aidosti hyödyllisiä. 
Työmäärä oli mielestäni hyvin suhteutettu kurssin kokoon (3op).