# Python

# Step 1

Script Python che itera in ordine alfabetico sui file della cartella files e, a seconda del tipo (audio, documento, immagine), li sposta nella relativa sottocartella. Se la sottocartella non esiste, lo script dovrà crearla automaticamente.

Durante il ciclo, lo script deve stampare le informazioni dei file: nome, tipo e dimensione in byte. Questo è l'output desiderato.

Oltre a stamparne le informazioni via via che li spostio, tiene traccia dei file creando un documento recap.csv con le stesse informazioni.

# Step 2

Aggiungere al notebook dello Step 1 uno script che itera sulla sottocartella images e costruisca una tabella riassuntiva che dovrà riportare oltre al nome del file:

• altezza dell'immagine, in pixel
• larghezza dell'immagine, in pixel
• se l'immagine è in scala di grigio, la colonna grayscale indica la media dei valori dell'unico livello di colore
• se l'immagine è a colori, le altre colonne indicano la media dei valori di ogni livello di colore.

(Una immagine in scala di grigio ha un solo livello di colore, una RGB ne ha 3, una RGBA 4 (l'ultimo è detto canale alpha).

Per maggiori dettagli sugli step eseguiti vedere la cartella "fileorganizer".
