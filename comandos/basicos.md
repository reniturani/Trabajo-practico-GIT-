## Comandos básicos de git

### git init: 
    Es lo principal para empezar a crear un proyecto, lo que hace es transformar una carpeta común en un repositorio de git, por dentro, oculta una carpeta llamada .git donde guarda todo el historial de cambios.

**Comando:**
``` 
mkdir mi-proyecto
cd mi proyecto
git init
```


### git clone:
    Este sirve para traer un proyecto ya existente en internet (en nuestro caso github) a nuestra computadora, lo que hace es descargar una copia exacta de todo el proyecto, con las carpetas, archivos y todo el historial de commits y ramas.

**Comando:**
```
git clone https://github.com/usuario/nombre-del-repositorio.git
```


### git status:
    Es el que se va a usar mas seguido, lo que hace es dar un reporte de tu situacion, te dice en que rama estas parado y te meustra el estado de tus archivos usando colores:

_En rojo:_ Los archivos modificados o creados pero que git todavia no esta "guardando".
_En verde:_ Los archivos que ya se actualizaron con git add  y que estan listos para el commit.

**Comando:**
```
git status
```