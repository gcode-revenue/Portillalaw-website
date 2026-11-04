# Portilla Law Firm — portillalaw.com

Sitio web del Programa de Aprendizaje Registrado (WIOA / Conexión Laboral) para patronos en Puerto Rico.

HTML estático, sin build. Todo el sitio está en `index.html`.

## Formularios

Los formularios de evaluación y de charlas abren la aplicación de correo del visitante con un mensaje listo para `gcalderin@portillalaw.com` (no necesita servidor).

## Hosting (GitHub Pages)

1. **Settings → Pages** → Source: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
2. El archivo `CNAME` asigna el dominio `portillalaw.com`.
3. En el registrador del dominio, añadir (sin tocar los registros MX del correo):
   - Registros `A` para `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Registro `CNAME` para `www` → `gcode-revenue.github.io`
4. Cuando el DNS resuelva, activar **Enforce HTTPS** en Settings → Pages.
