
# About
Source de la web https://iibmers.org/

# Como contribuir a la web
Hacer fork de este repositorio y hacer pull request cuando hayas completado los cambios


# DevDocs
Para correr hugo localmente y hacer pruebas
## Instalar Hugo y dependencias

https://gohugo.io/getting-started/installing/

## Iniciar hugo en la carpeta del repositorio
`hugo server`

## Arbol de archivos: 
- Carpeta [content](https://github.com/IIBMErs/iibmers.github.io/tree/main/content) :  Contenido (texto en markdown, y html)
- Carpeta [themes/airspace-hugo](https://github.com/IIBMErs/iibmers.github.io/tree/main/themes/airspace-hugo) :  Archivos scss de personalización y visualización del sitio
- Carpeta [images](https://github.com/IIBMErs/iibmers.github.io/tree/main/static/images) :  Contenido (Imágenes, fotos, etc)
- Archivos [/content/english/_index](https://github.com/IIBMErs/iibmers.github.io/blob/main/content/english/_index.md) :  Contenido de la pagina de inicio

## Usar el repositorio como plantilla web
Para usar este repo como plantilla para otra pagina web: 
Opcion 1. 
- Hacer fork del repositorio, activar y configurar git hub pages (Settings > Pages) para que haga deploy de la web desde el /root de la branch gh-pages

Opcion 2. 
- Descargar el repo (branch main) y copiar los archivos a un nuevo repositorio (asi no aparecerá como un fork)

- Configurar el workflow, (eg el dominio o cname a usar), el build y deploy es automático desde la branch ***main*** (ojo con eso, ya que github tambien usa opcionalmente con una branch *master*) hacia la branch ***gh-pages***
