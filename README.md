<h1>Sims-pelin tyylinen sivusto</h1>

Sims 4 pelin inspiroima portfolio-sivusto, joka on tehty käyttäen JavaScriptiä, HTML:ää ja CSS:ää. Tämä sivusto esittää taitojani käyttää muun muassa UI-elementtejä, ponnahdusikkunoita ja uudelleenkäytettäviä komponentteja.

Löydät sen kansiosta: 

<img width="1536" height="816" alt="Image" src="https://github.com/user-attachments/assets/407e7fb1-4d1b-453c-b0d0-25ef83840a7a" />
<h2>Ominaisuudet</h2>

- <b>Sims 4 tyylinen UI</b>
  - Pyöristetyt paneelit, animaatiot
- <b>Uudelleenkäytettävät komponentit</b>
  - Ylä- ja alanavigoinnit ladataan erillisistä HTML tiedostoista
  - Ponnahdusikkunoiden sisältö ladataan dynaamisesti
- <b>Interaktiiviset ponnahdusikkunat</b>
  - Taidot, koulutus ja työkokemus esitetään ponnahdusikkunoissa
  - Sulkeminen klikkaamalla ulkopuolelle tai sulkunäppäimellä
- <b>Selkeä rakenne</b>
  - HTML, CSS ja JS ovat erotettuja toisistaan

<h2>Käytetyt teknologiat</h2>

- <b>HTML</b>
- <b>CSS</b>
  - Flexbox
  - Animations & transitions
  - CSS variables
- JavaScript
  - fetch() uudelleen käytettävien komponenttien käytössä
  - Tapahtumankäsittelijät
  - Dom-manipulaatiot

<h2>Uudelleenkäytettävät komponentit</h2>

<b>Navigaatio</b>
Ylä- ja alanavigaatiopalkit ovat erillisissä HTML tiedostoissa ja lisätään jokaiseen sivuun käyttäen fetch():iä
```JavaScript
fetch("top-nav.html")
  .then(res => res.text())
  .then(html => {
    document.getElementById("nav-container").innerHTML = html;
  });
```

<b>Ponnahdusikkunat</b>
Ponnahdusikkunat ovat sisällytetty popups.html-tiedoston sisään ja niitä hallitaan yksittäisellä JavaScript tiedostolla

<img width="1536" height="816" alt="Image" src="https://github.com/user-attachments/assets/c54836e3-a8b3-46ad-80f1-28d3a8da2408" />

<h2>Tyylin innoite</h2>
Projektia inspiroi Sims 4-pelin UI, pelityylinen vuorovaikutussuunnittelu ja yksinkertainen sekä helppokäyttöinen käyttö.

<h2>Tulevaisuuden parannukset</h2>

- Näppäimistön käytettävyys (ESC ponnahdusikkunoiden sulkemiseen)
- Parannettu ulkoasu mobiilissa
- Graafisia lisäyksiä




