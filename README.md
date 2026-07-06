# 👟 SNKRS S — The Drop Room

Página "link en la bio" de [SNKRS S](https://instagram.com/snkrs.s) — sneakers premium
calidad 1.1 verificados, Medellín, Colombia.

**Una sola página, cero dependencias, cero backend.** HTML + CSS + JS vanilla.

## ✨ Qué tiene

- 🃏 Tarjeta de autenticación **3D** que sigue el mouse (o el giroscopio en el celular), con brillo holográfico
- ⏱ **Countdown al próximo drop** — se recalcula solo cada semana, nunca se vence
- 🛒 Catálogo con botón de pedido **directo a WhatsApp**
- ✦ Ticker de manifiesto, partículas flotantes, rejilla de vault
- 📱 100% responsive

## ⚙️ Configurar

Todo se edita en el bloque `CONFIG` al inicio del `<script>` en `index.html`:

```js
const CONFIG = {
  whatsapp: '573001112233',   // tu número con 57 adelante
  instagram: 'snkrs.s',       // tu usuario de Instagram
  dropDia: 5,                 // día del drop semanal (0=Dom ... 5=Vie)
  dropHora: 20,               // hora Colombia (20 = 8 pm)
  productos: [ ... ]          // los pares que se muestran
};
```

## 🚀 Publicado con GitHub Pages

Cualquier cambio que subas a `main` se publica solo en unos segundos.

---
Hecho con [Claude Code](https://claude.com/claude-code) 🤖
