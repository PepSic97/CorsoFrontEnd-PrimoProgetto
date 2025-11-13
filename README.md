# Primo proogetto Corso Front End

## Sito Evento Sportivo 
1. [Creazione sito per un evento sportivo](#creazione-sito-per-un-evento-sportivo)

2. [Prototipo](#prototipo)

3. [Palette dei colori](#palette-colori)

4. [CTA per l'acquisto del biglietto](#cta-perl-acquisto-del-biglietto)

5. [CTA per le informazioni sull'evento](#cta-per-le-informazioni-sull-evento)

6. [CTA per le informazioni di contatto](#cta-per-le-informazioni-di-contatto)

7. [CTA per le informazioni social](#cta-per-le-informazioni-social)


## Prototipo
Prima idea per il sito, a scorrimento, con una navigazione semplice sia verso un'altra pagina del sito (fighters.html), sia verso siti esterni (CTA per acquisto biglietti e per i social)

![Screenshot of the application](/images/readMeImages/wireframe.png)

## Palette Colori
Usati tre semplici colori presi dall'immagine messa in background

#141716 - Dark Background
#941b0c - Primary Accent
#f0f2ef - Light Text

Nell'overlay messa un'opacità per far vedere sia il testo ed il pulsante che il background

```css
.home .overlay {
  position: absolute;
  inset: 0;
  background: rgba(0, 0, 0, 0.6);
}
```

## Creazione sito per un evento sportivo

1. [Header fisso in alto, con CTA e titolo evento ed un background](#header-fisso-in-alto-con-cta-e-titolo-evento-ed-un-background)

2. [Footer fisso in basso, con CTA per i social](#cta-per-le-informazioni-social)

3. [CTA per le informazioni sull'evento](#cta-per-le-informazioni-sullevento)

4. [CTA per le informazioni di contatto](#cta-per-le-informazioni-di-contatto)

5. [Pagina evento]()

## Header fisso in alto, con CTA e titolo evento ed un background

```html
<!-- HOME SECTION -->
<div class="home">
  <div class="home-content">
  <h1>Rookie FC 8</h1>
  <p class="event-date">30 Novembre 2025 - Salerno</p>
  <a href="#tickets" class="cta">Acquista il biglietto!</a>
  </div>
</div>
```

## CTA per l'acquisto del biglietto

Nell'header e come CTA nel body

```html
<a href="#tickets" class="cta">Acquista il biglietto!</a>

<a href="https://www.eventbrite.it/e/rookie-fc-8-mma-tickets-1824742577169?fbclid=IwY2xjawN5RPpleHRuA2FlbQIxMABicmlkETBMUzFDYmlvVzlRVnhYYTByc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHkbsR1em2leobwWEOXR94ldeh68_0JIhSLxCUvlvRoKpJ9BoXiwgxCSoWZiV_aem_Ctjd6FajYw2z4ZaYP8a5WQ" class="cta">Compra Biglietti</a>

```

## CTA per le informazioni sull'evento

Nel body, porta ad un secondo file/pagina html

```html
<a href="fighters.html" class="cta">Vedi Elenco Fighters</a>
```

## CTA per le informazioni di contatto

Nel body, porta ad un link esterno

```html
<a href="https://www.eventbrite.it/e/rookie-fc-8-mma-tickets-1824742577169?fbclid=IwY2xjawN5RPpleHRuA2FlbQIxMABicmlkETBMUzFDYmlvVzlRVnhYYTByc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHkbsR1em2leobwWEOXR94ldeh68_0JIhSLxCUvlvRoKpJ9BoXiwgxCSoWZiV_aem_Ctjd6FajYw2z4ZaYP8a5WQ"
class="cta">Compra Biglietti</a>
```

## CTA per le informazioni social

Nel footer, link esterni

```html
<footer>
  <h3>Seguici sui social</h3>
    <div class="social-links">
        <a href="https://www.instagram.com/rookiefc.ig/" target="_blank" aria-label="Instagram">
            <i class="fab fa-instagram"></i>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100063529695033" target="_blank" aria-label="Facebook">
            <i class="fab fa-facebook-f"></i>
        </a>
        <a href="https://www.youtube.com/@rookiefc" target="_blank" aria-label="YouTube">
            <i class="fab fa-youtube"></i>
        </a>
    </div>
    <p>© 2025 Rookie FC. Tutti i diritti riservati.</p>
</footer>
```

## Pagina evento

Pagina fighters.html che mostra la card dell'evento, con pulsante che ti porta indietro alla landingPage.html

```html
 <header class="fighters-header">
    <h1>Rookie FC 8</h1>
     <a href="./landingPage.html" class="back-btn"> ← Torna alla Home</a>
     <h2>30 Novembre 2025 - Salerno - Palatulimieri</h2>
  </header>
```