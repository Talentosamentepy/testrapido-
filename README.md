# Talentosamente · Diagnóstico de empleabilidad

Sitio web estático e interactivo para realizar un diagnóstico de empleabilidad, visualizar resultados por área y compartir un resumen voluntariamente por WhatsApp.

## Publicar con GitHub Pages

1. Creá un repositorio nuevo en GitHub (por ejemplo, `talentosamente-diagnostico`).
2. Subí `index.html`, `README.md` y `.nojekyll` en la raíz del repositorio.
3. Entrá en **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**.
5. Seleccioná la rama `main`, carpeta `/(root)` y hacé clic en **Save**.
6. Cuando GitHub indique que la publicación terminó, entrá en `https://TU-USUARIO.github.io/talentosamente-diagnostico/` (cambiá `TU-USUARIO` por tu usuario real).

## Personalización

- **Marca y colores:** editá las variables CSS de `:root` en `index.html`.
- **Preguntas:** modificá el arreglo `Q` dentro de la etiqueta `<script>`.
- **Número de WhatsApp:** modificá `const WHATSAPP = "595982264134";` (código de país + número sin espacios).
- **Datos profesionales del pie:** modificá el texto dentro de `<p class="foot">`.
- **Logotipo:** actualmente está incrustado dentro del propio HTML en formato base64.

## Cómo funciona y privacidad

El cuestionario se ejecuta en el navegador. No utiliza base de datos ni guarda respuestas en un servidor propio. El visitante puede optar por compartir sus resultados y datos introducidos mediante el enlace de WhatsApp; debe confirmar el envío desde WhatsApp. No hay envío automático de mensajes ni recolección de contactos por GitHub Pages.

**Nota:** este diagnóstico es orientativo; no sustituye una evaluación profesional. Confirmá que tenés autorización para publicar el logotipo, el contenido y los datos de contacto incluidos.
