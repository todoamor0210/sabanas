# Ventas e Inventario (PWA)

## 1. Subir a GitHub
1. Entra a github.com y crea un repositorio nuevo (por ejemplo `ventas`).
2. Pulsa **Add file → Upload files** y arrastra TODO el contenido de esta carpeta (`index.html`, `manifest.webmanifest`, `sw.js`, la carpeta `icons` y `.nojekyll`).
3. Pulsa **Commit changes**.

## 2. Activar GitHub Pages
1. En el repositorio: **Settings → Pages**.
2. En **Branch** elige `main` y carpeta `/ (root)`. Pulsa **Save**.
3. A los 1–2 minutos tu app estará en `https://TU-USUARIO.github.io/ventas/`.

## 3. Instalar
- **Android (Chrome):** abre el enlace → botón "INSTALAR APP" o menú ⋮ → *Instalar aplicación*.
- **iPhone (Safari):** abre el enlace → botón Compartir → *Agregar a pantalla de inicio*.
- **PC (Chrome o Edge):** abre el enlace → icono de instalar en la barra de direcciones (o el botón "INSTALAR APP").

## 4. Actualizar
Sube el nuevo `index.html` a GitHub (Add file → Upload files, mismo nombre). La app se actualiza sola al abrirla y recargarla. Si quieres forzar el cambio en la caché, sube también `sw.js` cambiando `ventas-v1` por `ventas-v2`.

## Importante
- La app necesita internet para leer y guardar datos (Supabase). Sin internet abre, pero muestra "SIN CONEXIÓN".
- Si el repositorio es público, cualquiera que vea el código ve la URL y la clave pública de Supabase. Con las políticas actuales de la tabla `kv`, esa persona podría leer o modificar tus datos. Agrega inicio de sesión antes de compartir el enlace.
