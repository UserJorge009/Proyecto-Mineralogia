# GeoGuía | Identificador educativo de minerales

GeoGuía es un proyecto educativo para la clase de Mineralogía. Permite registrar propiedades físicas observadas en una muestra y obtener hasta tres minerales candidatos de un catálogo local.

## Características

- Formulario para color, brillo, raya, pruebas de dureza y propiedades complementarias.
- Campo de densidad en g/cm³.
- Resultados explicados con porcentaje aproximado de coincidencia y familia mineralógica.
- Catálogo inicial con nueve grupos mineralógicos prácticos.
- Panel de administración separado en `admin.html` para gestionar minerales y campos.
- Paleta de marrón, arena y crema inspirada en rocas y muestras minerales.

## Archivos principales

- `index.html`: formulario público de identificación.
- `admin.html`: pantalla de administración.
- `minerales.js`: catálogo inicial de minerales y propiedades.

## Ejecutar localmente

Mantén los tres archivos principales en la misma carpeta y abre `index.html` en el navegador. La mejor experiencia de desarrollo se obtiene con un servidor estático local.

## Publicar con GitHub Pages

En GitHub, abre **Settings → Pages** y configura **Deploy from a branch**, rama `main` y carpeta `/(root)`. Guarda los cambios.

## Subir cambios mediante Git

Copia los archivos actualizados en la raíz de tu repositorio local y ejecuta:

```bash
git status
git add index.html admin.html minerales.js README.md LEEME_GeoGuia.txt
git commit -m "Actualiza GeoGuía con paleta marrón"
git push origin main
```

Si tu rama principal tiene otro nombre, reemplaza `main` por el nombre correcto.

## Consideraciones académicas y técnicas

La herramienta ofrece candidatos orientativos; no sustituye la identificación mineralógica mediante pruebas verificadas. Los cambios hechos en el panel de administración se almacenan en el navegador local y no se comparten automáticamente con otros visitantes. El panel no cuenta todavía con autenticación segura.
