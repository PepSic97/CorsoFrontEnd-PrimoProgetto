# Primo proogetto Corso Front End

## Sito Evento Sportivo 
1. [Creazione sito per un evento sportivo](#creazione-sito-per-un-evento-sportivo)
2. [CTA per l'acquisto del biglietto](#cta-perl-acquisto-del-biglietto)
3. [CTA per le informazioni sull'evento](#cta-per-le-informazioni-sull-evento)
4. [CTA per le informazioni di contatto](#cta-per-le-informazioni-di-contatto)
5. [CTA per le informazioni social](#cta-per-le-informazioni-social)


## Prototipo
![Screenshot of the application](/images/readMeImages/wireframe.png)

## Palette Colori
#141716 - Dark Background
#941b0c - Primary Accent
#f0f2ef - Light Text


## Creazione sito per un evento sportivo

-Header fisso in alto, con CTA e titolo evento ed un background
-Footer fisso in basso, con CTA per i social
-CTA per le informazioni sull'evento
-CTA per le informazioni di contatto

## CTA per l'acquisto del biglietto

Nell'header e Come CTA nel body

```html
<a href="#tickets" class="cta">Acquista il biglietto!</a>

<a href="https://www.eventbrite.it/e/rookie-fc-8-mma-tickets-1824742577169?fbclid=IwY2xjawN5RPpleHRuA2FlbQIxMABicmlkETBMUzFDYmlvVzlRVnhYYTByc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHkbsR1em2leobwWEOXR94ldeh68_0JIhSLxCUvlvRoKpJ9BoXiwgxCSoWZiV_aem_Ctjd6FajYw2z4ZaYP8a5WQ" class="cta">Compra Biglietti</a>
'''

## CTA per le informazioni sull'evento

Nel body. porta ad un secondo file/pagina html

```html
<a href="fighters.html" class="cta">Vedi Elenco Fighters</a>
'''

Porta ad un secondo file/pagina html

## CTA per le informazioni di contatto

Nel body, porta ad un link esterno

```html
<a href="https://www.eventbrite.it/e/rookie-fc-8-mma-tickets-1824742577169?fbclid=IwY2xjawN5RPpleHRuA2FlbQIxMABicmlkETBMUzFDYmlvVzlRVnhYYTByc3J0YwZhcHBfaWQQMjIyMDM5MTc4ODIwMDg5MgABHkbsR1em2leobwWEOXR94ldeh68_0JIhSLxCUvlvRoKpJ9BoXiwgxCSoWZiV_aem_Ctjd6FajYw2z4ZaYP8a5WQ"
class="cta">Compra Biglietti</a>
'''

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
'''
