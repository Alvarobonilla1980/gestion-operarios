# gestion-operarios

**Ilunion · Control de operarios**: app para el móvil que reparte a los operarios en los puestos cada día, con bajas, ERTE, calendario laboral, cuadrante semanal y envío por WhatsApp.

## Ponerla en marcha (una sola vez)

1. En GitHub: **Settings → Pages**, en *Branch* elige `main` y carpeta `/ (root)`, y pulsa **Save**.
2. En un par de minutos tendrás la dirección: `https://alvarobonilla1980.github.io/gestion-operarios/`

## Instalarla en el móvil

- **Android (Chrome):** abre la dirección y pulsa **Instalar** (o menú ⋮ → *Instalar app*).
- **iPhone (Safari):** abre la dirección, pulsa **Compartir** → *Añadir a pantalla de inicio*.

Queda con su icono, se abre a pantalla completa y funciona sin conexión. Los datos se guardan en el propio móvil (haz copias en *Más → Copia de seguridad*).

**Pasar los datos desde la versión de Claude:** en la app de Claude, *Más → Copia de seguridad → Copiar copia de seguridad*; en esta app, *Más → Copia de seguridad*, pega y pulsa *Restaurar* dos veces.

## Para quien la mantenga

- La app es `index.html`. `sw.js` la guarda para usarla sin conexión: **sube `VERSION` en `sw.js` cada vez que cambies `index.html`**.
- `manifest.webmanifest` e `icons/` definen el nombre y el icono.
