
---

# Learn Java Script

Questo repository contiene un semplice template per lo sviluppo di un'applicazione Java Script usando il framework Svelte.

## Installazione ambiente di sviluppo


```bash
git clone https://github.com/mancusoa74/learnjs.git
cd learnjs
npm install
```

## Lezioni

I file delle lezioni seguono questa convenzione: *LezioneJS_01.svelte*, dove ogni lezione è identificata da un numero progressivo.

Per eseguire la lezione, modificare il file `src/main.js` e modifica la prima linea in questo modo:

da
```
import LearnJS from './LearnJS.svelte';
```

a
```
import LearnJS from './LezioneJS_01.svelte';
```


## Sviluppo

Edita il file ```src/LezioneJS_xx.svelte```

...poi lancia il server locale di sviluppo:

```bash
npm run dev
```

Dal tuo browser naviga su [localhost:5000](http://localhost:5000). 

Vedrai la tua applicazione nel browser. Ogni modifica al file sorgente verrà immediatamente ricompilata e ricaricata dal browser.

## Accesso esterno

Di default il server di sviluppo serve l'applicazione solo a *localhost*. Se vuoi raggiungere la tua app dall'esterno, modifica il file *package.json* editando il comando `sirv` in modo che includa il parametro `--host 0.0.0.0`.

## Visual Studio Code

Se usi [Visual Studio Code](https://code.visualstudio.com/) è raccomandato installare il plugin ufficiale [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode).


### Happy Learning Java Script !!!!
