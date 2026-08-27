# Análisis y Visualización Interactiva en Python

Material del taller. Cada tema tiene su propio notebook, ejecutable directamente en **Google Colab**.

📖 **Libro navegable (con índice):** `https://fmatcasici.github.io/taller-visualizacion-python` *(reemplaza USUARIO; se publica automáticamente tras seguir la configuración de `_config.yml` y activar GitHub Pages)*

## Temario y notebooks

| # | Tema | Duración | Ponente | Notebook |
|---|---|---|---|---|
| 01 | Introducción a Colab y Pandas | 30 min | — | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/01-intro-colab-pandas/notebook.ipynb) · [Descargar](01-intro-colab-pandas/notebook.ipynb) |
| 02 | Matplotlib | 60 min | Carlitos | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/02-matplotlib/notebook.ipynb) · [Descargar](02-matplotlib/notebook.ipynb) |
| 03 | Seaborn | 60 min | Carlitos | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/03-seaborn/notebook.ipynb) · [Descargar](03-seaborn/notebook.ipynb) |
| 04 | Plotly | 60 min | Luis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/04-plotly/notebook.ipynb) · [Descargar](04-plotly/notebook.ipynb) |
| 05 | Dash | 60 min | Luis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/05-dash/notebook.ipynb) · [Descargar](05-dash/notebook.ipynb) |
| 06 | Bokeh | 45 min | Curi | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/06-bokeh/notebook.ipynb) · [Descargar](06-bokeh/notebook.ipynb) |
| 07 | Folium | 45 min | Curi | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/USUARIO/taller-visualizacion-python/blob/main/07-folium/notebook.ipynb) · [Descargar](07-folium/notebook.ipynb) |

## Estructura del repositorio

```
taller-visualizacion-python/
├── intro.md                    # Portada del libro (Jupyter Book)
├── _config.yml                 # Configuración del libro
├── _toc.yml                    # Índice / tabla de contenidos
├── requirements.txt            # Librerías usadas en el taller
├── .github/workflows/deploy.yml# Publica el libro en GitHub Pages automáticamente
├── 01-intro-colab-pandas/
│   ├── notebook.ipynb
│   └── data/
├── 02-matplotlib/
│   ├── notebook.ipynb
│   └── data/
├── ... (resto de temas, misma estructura)
```

## Cómo usar este repo (para asistentes)

1. Entra al **libro publicado** (enlace arriba) para navegar el índice por tema, o revisa la tabla de este README.
2. Haz clic en el badge **"Open in Colab"** del tema que corresponda.
3. En Colab: `Archivo > Guardar una copia en Drive` antes de editar, así conservas tus cambios.
4. Si prefieres trabajar localmente, usa el enlace **Descargar** y abre el `.ipynb` con Jupyter/VS Code.

## Cómo publicar / actualizar el libro (para el profesor)

1. Reemplaza `USUARIO` por tu usuario u organización de GitHub en `README.md` y `_config.yml`.
2. Sube este contenido a un repositorio nuevo en GitHub (rama `main`).
3. En **Settings → Pages** del repo, selecciona la rama `gh-pages` como fuente (se crea sola la primera vez que corra el workflow).
4. Cada `git push` a `main` reconstruye y republica el libro automáticamente (ver `.github/workflows/deploy.yml`).
5. Para probar localmente antes de subir: `pip install jupyter-book && jupyter-book build .` y abre `_build/html/index.html`.

## Notas

- Los notebooks están en blanco (plantilla) con la celda de badge de Colab ya lista — solo falta que cada ponente complete teoría y práctica de su tema.
- Si algún tema requiere datasets grandes, considera Git LFS o cargarlos desde una URL pública dentro del propio notebook.
# taller-visualizacion-python-concei3
