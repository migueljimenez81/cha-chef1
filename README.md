# Cha-Chef

App de recetas, macros, plan semanal y lista de la compra (PWA). Funciona en iPhone, Android y ordenador, también sin conexión.

## Publicarla con GitHub Pages (gratis)

1. Crea una cuenta en https://github.com si no tienes una.
2. Pulsa **New repository**, ponle un nombre (por ejemplo `cha-chef`), déjalo en **Public** y créalo.
3. Pulsa **Add file → Upload files** y arrastra TODOS los ficheros de esta carpeta (no el .zip): `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`. Pulsa **Commit changes**.
4. Ve a **Settings → Pages**. En **Build and deployment** elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. Espera 1–2 minutos. La app quedará en: `https://TU-USUARIO.github.io/cha-chef/`

## Instalarla en el iPhone

1. Abre esa dirección en **Safari** (tiene que ser Safari, no Chrome).
2. Pulsa el botón **Compartir** (cuadrado con flecha).
3. Elige **Añadir a pantalla de inicio** y confirma.

Se abrirá a pantalla completa, con su icono, y funcionará sin conexión después de la primera carga.

## Actualizar la app

Sube el `index.html` nuevo al repositorio (Add file → Upload files, sobrescribe) y en `sw.js` cambia `cha-chef-v1` por `cha-chef-v2`, `v3`, etc. Así los móviles recogen la versión nueva.

## Datos

Tu plan, objetivos y casillas de la compra se guardan en el propio dispositivo (localStorage). Ten en cuenta:
- La app instalada en la pantalla de inicio y Safari **no comparten** datos.
- No se sincroniza entre dispositivos.
- Si borras los datos del sitio en los ajustes del navegador, se pierde el plan.
