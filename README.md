# Luca Immagine Uomo — sito statico

Una pagina (`index.html`) + `privacy.html`. Niente build, niente JavaScript
esterno, niente cookie, niente moduli: non c'è nulla da aggiornare.

## Struttura
- `index.html` — pagina principale
- `privacy.html` — informativa (il sito non raccoglie dati)
- `style.css` — stile fumetto (muro giallo, adesivi) + palo da barbiere che gira a negozio aperto
- `assets/` — foto, caratteri ospitati in locale, favicon

La versione precedente a fumetto è salvata in git: `git checkout fumetto`.

## Orari
Gli orari stanno in **due punti** di `index.html`: la tabella "Quando" e
l'elenco `ORARI` nello script in fondo (decide "Aperto adesso" e fa girare
il palo). Se cambiano, vanno aggiornati entrambi.

## Prima di consegnarlo al cliente
- [ ] Inserire la **partita IVA** nel piè di pagina (`index.html`, cerca `DA INSERIRE`)
- [ ] Confermare con Luca gli **orari** (Google e altre fonti non coincidono)
- [ ] Confermare che il **338 586 7760** è anche su **WhatsApp**
- [ ] Confermare i servizi (taglio, barba, bambini) ed eventuali prezzi
- [ ] Permesso di Luca per usare le foto
- [ ] Foto più grandi: le due di Luca al lavoro sono 125×125 px (miniature di Google). Sostituire `assets/luca-al-lavoro-1.jpg` e `-2.jpg` con versioni grandi, stesso nome, formato quadrato

## Pubblicare (gratis)
**Netlify Drop:** vai su https://app.netlify.com/drop e trascina questa cartella.

**Cloudflare Pages:** Workers & Pages → Create → Pages → Upload assets → carica la cartella.

Poi collega il dominio del cliente (es. `lucaimmagineuomo.it`, intestato a lui)
dalle impostazioni del progetto.

## Anteprima in locale
Apri `index.html` nel browser.
