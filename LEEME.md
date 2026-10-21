# Examen de seguridad en redes — Vercel

Web estática con 23 preguntas, tres opciones, orden aleatorio, corrección explicada y resultados por tema. No requiere base de datos, dependencias ni variables de entorno.

## Publicar desde GitHub

1. Descomprimí el ZIP.
2. Subí vercel.json y la carpeta public a la raíz de un repositorio de GitHub. Conservá la estructura de las carpetas.
3. En Vercel, creá un proyecto e importá ese repositorio.
4. Usá estas opciones si se solicitan:
   - Framework Preset: Other.
   - Root Directory: la raíz del repositorio (donde está vercel.json).
   - Build Command: vacío (sin compilación).
   - Output Directory: public.
5. Seleccioná Deploy. La configuración incluida ya define la carpeta de salida y omite la compilación.

## Archivos

- public/index.html: página y estilos.
- public/app.js: navegación, mezcla, guardado y resultados.
- public/questions.js: preguntas, opciones y explicaciones.
- vercel.json: configuración de despliegue.

Para probar sin publicar, abrí public/index.html en tu navegador.

El progreso se guarda en el navegador de cada visitante. No se transfiere automáticamente desde la versión anterior, porque cambia la dirección del sitio. La web es un recurso de práctica: las soluciones forman parte de los archivos descargados por el navegador.

Documentación oficial: https://vercel.com/docs/builds/configure-a-build
