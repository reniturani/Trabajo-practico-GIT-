git branch:
Este comando sirve para trabajar con ramas en git. Una rama es como una “copia” del proyecto donde podes hacer cambios sin afectar la rama principal. Con git branch podes ver las ramas existentes o crear una nueva rama para trabajar separado.

Comando:
git branch
git branch nombre-rama

git checkout / git switch:
Estos comandos se utilizan para cambiar de una rama a otra. Cuando cambias de rama, git reemplaza los archivos de tu carpeta por la versión correspondiente a esa rama.
git checkout tambien permite crear y cambiar a una nueva rama en un solo comando, mientras que git switch fue creado especificamente para cambiar entre ramas de una forma mas clara.

Comando:
git checkout nombre-rama
git checkout -b nueva-rama
git switch nombre-rama
git switch -c nueva-rama