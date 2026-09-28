# Mente de Hierro

Mini-app web estática para entrenamientos de plancha.

## Incluye

- Series editables.
- Trabajo editable en segundos.
- Descanso editable en segundos.
- Temporizador basado en timestamps, no en un simple decremento.
- Pausa/reanudación.
- Reinicio de la serie actual desde cero.
- Una serie solo cuenta cuando termina completamente.
- Descanso automático entre series.
- Avisos sonoros y vibración cuando el navegador/dispositivo lo permite.
- Screen Wake Lock cuando el navegador lo permite.
- Configuración persistente mediante `localStorage`.
- Historial local de las últimas 20 sesiones.
- Atajo de teclado: `Espacio` pausa/reanuda; `R` reinicia la serie.
- PWA básica.
- Sin backend, sin base de datos y sin dependencias externas.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `mente-de-hierro`.
2. Sube todo el contenido de esta carpeta manteniendo la ruta `.github/workflows/deploy.yml`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment → Source**, selecciona **GitHub Actions**.
5. Haz push a `main`.
6. GitHub Actions publicará el sitio.

La URL de un proyecto será:

`https://TU_USUARIO.github.io/mente-de-hierro/`

## Importante

GitHub Pages sirve HTML/CSS/JavaScript estático. Esta versión no necesita servidor.

El historial se guarda únicamente en el navegador/dispositivo de cada usuario.
