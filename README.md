# Descrizione

Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.

# Bonus

1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce

# Consigli del giorno

- regola d'oro: riciclare ovunque possibile! Questo significa che per la parte di markup possiamo recuperare html e css dell'esercizio svolto qualche giorno fa: è già tutto pronto!
- il riciclo spesso va a braccetto con le funzioni! Sapendole sfruttare bene, l'esercizio si riduce a poche righe

# Scomposizione del problema

Devo impostare l'istanza Vue, così da utilizzare lo scambio dati tra script e DOM per stampare un messaggio a schermo per l'utente

1 - inizializzo l'istanza Vue invocando la funzione createApp()

2 - utilizzo la proprietà 'data' degli options object per connettermi al DOM e scambiare dati

3 - utilizzo la proprietà methods per definire delle funzioni al suo interno da poter utilizzare nel DOM

4 - utilizzo il metodo '.mount()' per connettere l'istanza al tag HTML con id "#app" e renderizzare l'app