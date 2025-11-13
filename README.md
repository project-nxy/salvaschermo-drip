# Salvaschermo - The Drip

Un salvaschermo animato con il logo di "The Drip" coffee & co. che rimbalza sullo schermo in stile DVD classico.

## 🎯 Uso

Questo progetto è progettato per essere utilizzato come salvaschermo su una Smart TV da 55" o qualsiasi altro display.

### Metodo 1: Accesso Online (Consigliato)
Una volta pubblicato su GitHub Pages, puoi accedere al salvaschermo direttamente dal browser della tua Smart TV:
- URL: `https://project-nxy.github.io/salvaschermo-drip/`

### Metodo 2: Locale
1. Scarica i file `index.html` e `logo.png`
2. Apri `index.html` nel browser della tua Smart TV o computer
3. Premi F11 per la modalità a schermo intero (se necessario)

## ⚙️ Caratteristiche

- ✅ Animazione fluida in stile DVD screensaver
- ✅ Sfondo nero puro per display OLED-friendly
- ✅ Cursore nascosto automaticamente
- ✅ Responsive - funziona su qualsiasi dimensione di schermo
- ✅ Nessuna dipendenza esterna - solo HTML e CSS
- ✅ Durata animazione personalizzabile (attualmente 12 secondi)

## 🛠️ Personalizzazione

Per modificare la velocità dell'animazione, modifica il valore `--anim-duration` nel file `index.html`:

```css
:root{
  --anim-duration: 12s; /* Cambia questo valore */
}
```

## 📺 Compatibilità

Testato e funzionante su:
- Smart TV (browser integrato)
- Chrome, Firefox, Safari, Edge
- Risoluzione ottimale: 1920x1080 (Full HD) e 3840x2160 (4K)
