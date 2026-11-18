# Spotify Web · replica in HTML e CSS

Replica dell'interfaccia web di Spotify realizzata con **solo HTML e CSS**, durante il corso Full-Stack di [Boolean](https://boolean.careers/). L'obiettivo era riprodurre fedelmente il layout (barra laterale, griglia delle copertine, player in basso) e renderlo responsive.

## Come avviarlo

Apri `index.html` nel browser: non serve nessuna installazione.

## Punti tecnici

- Layout a colonne con Flexbox e classi di utilità scritte a mano (`style-flex.css`).
- Quattro breakpoint (1200, 992, 768, 576 px): su telefono la barra laterale diventa una colonna di icone e il player mostra solo copertina, titolo e comandi.
- Icone di [Font Awesome](https://fontawesome.com/) e font Montserrat.

## Cosa è cambiato nella revisione del 2026

- Player su mobile ripensato: prima i comandi si sovrapponevano e il cursore del volume usciva dallo schermo.
- Testi segnaposto ("Subtitle", "Brano Nome") sostituiti da quelli reali e titoli limitati a due righe.
- Etichette accessibili sui pulsanti fatti solo di icone, testi alternativi delle copertine, lingua della pagina, favicon.
- Rimosso un file MP3 di 4,5 MB che non era usato e non era distribuibile.

> Progetto didattico senza scopo commerciale. Logo, marchio e copertine appartengono ai rispettivi proprietari.
