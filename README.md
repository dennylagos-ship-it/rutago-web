<p align="center">
  <img src=".github/frontino-oso.png" alt="Frontino Software Solutions" height="96">
</p>

<h1 align="center">RutaGo · Sitio web</h1>
<p align="center"><b>Mototaxis, taxis y envíos de tu pueblo. Tú pones el precio.</b><br>Página pública, versión web de la app y páginas legales para Google Play</p>

<p align="center">
  <img src="https://img.shields.io/badge/sitio-est%C3%A1tico-1B2A41?logo=html5&logoColor=white" alt="sitio: estático">
  <img src="https://img.shields.io/badge/hosting-GitHub%20Pages-1B2A41?logo=github&logoColor=white" alt="hosting: GitHub Pages">
  <img src="https://img.shields.io/badge/licencia-propietaria-25D366" alt="licencia: propietaria">
</p>

---

## ¿Qué es?

Sitio público de **RutaGo**, la app de taxis, mototaxis y envíos con tarifa negociada (el código de la app está en el repositorio privado `RutaGo`). Aquí viven las páginas que Google Play pide y una versión web de la app para probarla desde el navegador.

🌐 **Dirección:** https://dennylagos-ship-it.github.io/rutago-web/

## Páginas

| Archivo | Qué es |
|---|---|
| `index.html` | Presentación de RutaGo y cómo funciona |
| `app/` | Versión web de la app, exportada con Expo (`npx expo export --platform web`) |
| `privacidad.html` | Política de privacidad (requerida por Google Play) |
| `eliminar-cuenta.html` | Cómo pedir que se borre la cuenta y los datos (requerida por Google Play) |
| `404.html` | Página de “no encontrada” |
| `estilo.css` | Diseño de las páginas |

## Actualizar la versión web de la app

1. En el proyecto de la app: `npx expo export --platform web`
2. Copia el contenido de la carpeta `dist/` dentro de `app/` de este repositorio.
3. Haz commit y push: GitHub Pages publica los cambios en uno o dos minutos.

## Ver en local

```bash
python3 -m http.server 8080
```

Y abre http://localhost:8080 en el navegador.

---

## Licencia

**Software propietario.** © 2026 Lcdo. Denny Lagos · Frontino Software Solutions. Todos los derechos reservados.

<p align="center">
  <img src=".github/frontino-oso.png" alt="Frontino Software Solutions" height="56"><br>
  <b>Frontino Software Solutions</b> · Táchira, Venezuela<br>
  <i>«El poder de las grandes ideas hecho software»</i><br>
  Apps Android · páginas web · aulas virtuales · sistemas a la medida · chatbots con IA<br>
  📱 WhatsApp: <a href="https://wa.me/584247714625">+58 424 771 4625</a> · Instagram: <a href="https://instagram.com/frontino.software">@frontino.software</a>
</p>
