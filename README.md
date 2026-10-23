# Dentista Viajero | Tarjeta digital

Micrositio estático, móvil y gratuito para GitHub Pages. No es un sistema de expedientes ni almacena datos de pacientes.

## Instalación
1. Crea un repositorio nuevo, por ejemplo `tarjeta-dentista-viajero` (o usa una carpeta independiente de tu app clínica).
2. Sube **el contenido** de esta carpeta a la raíz del repositorio: `index.html`, `styles.css`, `app.js`, `config.js` y `assets/`.
3. En GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
4. La URL habitual será `https://TU_USUARIO.github.io/tarjeta-dentista-viajero/` cuando GitHub termine de publicarla. Comprueba la URL real en Settings → Pages.
5. Edita `config.js` para completar solo enlaces públicos confirmados. Los botones sin URL muestran “próximamente” y no engañan al visitante.
6. Comprueba cada sección y botón en un celular antes de imprimir el QR. El QR debe apuntar a la URL definitiva.

## Contenido
- Portada ilustrada con los personajes y La Niña; menú de ocho secciones funcionales dentro de la web.
- Secciones educativas y botones de cita/WhatsApp preparados para activar.
- `assets/portada-personajes.png` es una ilustración de referencia generada. Si prefieres otra versión, reemplaza el archivo conservando el nombre.

## Privacidad y agenda
- **No** publiques un calendario personal ni historias clínicas en GitHub Pages.
- Para reservas, crea una página pública de citas de Google Calendar y añade su URL en `config.js`.
- Las citas requieren confirmación humana por WhatsApp; el sitio informa y facilita el contacto, pero no automatiza confirmaciones.
- Si quieres que un clic en Google Calendar envíe automáticamente un WhatsApp, hará falta un servicio adicional con permisos y configuración.

## Cambios
Editar los archivos y subirlos a la rama `main` actualiza el sitio sin cambiar su QR, siempre que mantengas la URL.

## Estado de esta entrega
- Los ocho accesos de la portada navegan a secciones reales dentro del sitio.
- WhatsApp, redes, mapa y agenda necesitan enlaces confirmados en `config.js`.
- Las ilustraciones son referencias; revisa que Pippo y los personajes correspondan a sus diseños oficiales antes de publicar.
- GitHub Pages no permite gestionar de forma segura expedientes clínicos ni automatiza confirmaciones de citas por WhatsApp.
