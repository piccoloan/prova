# Introduzione a Bootstrap

## 1. Griglia di base (Grid System)

Bootstrap usa un sistema a 12 colonne per creare layout flessibili e responsive. Questo vuol dire che **una riga (.row) contiene 12 “spazi”** che puoi dividere come vuoi.

### Struttura base:

```html
<div class="container">
  <div class="row">
    <div class="col-6">Metà</div>
    <div class="col-6">Metà</div>
  </div>
</div>
```

- `.container` è il contenitore principale.
- `.row` è la riga.
- `.col-6` sono le colonne (6 + 6 = 12, quindi vanno una accanto all’altra).

## 2. Classi responsive (col-sm, col-md, col-lg, etc.)

Bootstrap ti permette di specificare **quante colonne usare in base alla dimensione dello schermo**:

|Classe |Si applica da questa dimensione in su|
|-------|-------------------------------------|
|col-   |Extra small (mobile)                 |
|col-sm-|Small (≥576px)                       |
|col-md-|Medium (≥768px)                      |
|col-lg-|Large (≥992px)                       |
|col-xl-|Extra large (≥1200px)                |

### Esempio pratico:

```html
<div class="row">
  <div class="col-12 col-md-6">Mezza larghezza da md in su</div>
  <div class="col-12 col-md-6">Mezza larghezza da md in su</div>
</div>
```

- Su schermi piccoli (telefono): ogni colonna prende tutta la riga.
- Da tablet in su: due colonne affiancate.

## 3. Colori predefiniti

Bootstrap fornisce una serie di classi CSS utili per applicare colori ai testi, sfondi e componenti come pulsanti, senza bisogno di scrivere CSS personalizzati. Questi sono i più usati:

Colore|Nome classe
------|-----------
Blu|primary
Grigio chiaro|secondary
Verde|success
Rosso|danger
Arancione|warning
Azzurro|info
Nero/grigio scuro|dark
Bianco|light

### Testo colorato:

```html
<p class="text-primary">Testo blu</p>
<p class="text-danger">Testo rosso</p>
```

### Sfondo colorato:

```html
<div class="text-bg-success">Sfondo verde con testo bianco</div>
```

### Pulsante colorato:

```html
<button class="btn btn-warning">Attenzione!</button>
```

## Classi per margin e padding

### Proprietà principali:
- m = **margin**
- p = **padding**

### Lati:

- t = top
- b = bottom
- s = start (sinistra)
- e = end (destra)
- x = orizzontale (sinistra + destra)
- y = verticale (top + bottom)
- niente lato = su tutti i lati

### Valori disponibili (da 0 a 5):

Ogni numero corrisponde a uno spazio crescente (in rem, secondo la scala di Bootstrap).

Esempio:
- p-1 = piccolo padding
- p-5 = padding grande
- m-auto = margine automatico (utile per centrare)

### Esempi pratici:

```html
<div class="mt-3">Margine sopra (top)</div>
<div class="px-2">Padding orizzontale (sinistra + destra)</div>
<div class="m-0">Margine azzerato su tutti i lati</div>
<div class="p-4">Padding ampio su tutti i lati</div>
```
