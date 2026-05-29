## git branch:
    Este comando sirve para trabajar con ramas en git. Una rama es como una “copia” del proyecto donde podes hacer cambios sin afectar la rama principal. Con git branch podes ver las ramas existentes o crear una nueva rama para trabajar separado.

**Comando:**
```
git branch
git branch nombre-rama
```

## git checkout / git switch:
    Estos comandos se utilizan para cambiar de una rama a otra. Cuando cambias de rama, git reemplaza los archivos de tu carpeta por la versión correspondiente a esa rama.
    git checkout tambien permite crear y cambiar a una nueva rama en un solo comando, mientras que git switch fue creado especificamente para cambiar entre ramas de una forma mas clara.

**Comando:**
```
git checkout nombre-rama
git checkout -b nueva-rama
git switch nombre-rama
git switch -c nueva-rama
```

## git merge:
    Este comando une ramas. Lo que hace es traer los cambios realizados en una rama y combinarlos con la rama en la que estas actualmente. Generalmente se usa cuando terminaste de trabajar en una rama secundaria y queres pasar esos cambios a la rama principal.

**Comando:**
```
git checkout main
git merge nombre-rama 
```
------

## git remote:
    Este comando sirve para conectar tu proyecto local con un repositorio remoto, por ejemplo uno de GitHub.
    También permite ver qué conexiones remotas tiene el proyecto. Básicamente es el “enlace” entre tu computadora y el repositorio de internet.

**Comando para ver los remotos:**
```
git remote -v
```

**Comando para agregar uno:**
```
git remote add origin https://github.com/usuario/repositorio.git
```

## git fetch:
    Este comando sirve para traer los cambios nuevos que hay en el repositorio remoto, pero sin mezclarlos todavía con tus archivos.
    O sea, descarga la información más actualizada de GitHub para que puedas verla antes de actualizar tu rama.

**Comando:**
```
git fetch
```
------

## git pull:
    Este comando sirve para traer los cambios del repositorio remoto y aplicarlos directamente en tu proyecto.
    Es como hacer git fetch + git merge al mismo tiempo, porque descarga y actualiza tu rama automáticamente.

**Comando:**
```
git pull origin main
```

## git stash:
    Este comando sirve para guardar cambios que todavía no querés committear.
    Es útil cuando estás trabajando y necesitás cambiar de rama o actualizar el proyecto sin perder lo que estabas haciendo. Git guarda esos cambios “aparte” temporalmente y después los podés recuperar.

**Comando:**
```
git stash
```

**Para volver a traer los cambios guardados:**
```
git stash pop
```