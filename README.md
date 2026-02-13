### Comandos Basicos de GIT

- Crear un repositorio nuevo
```shell
git init
```

- Clonar un repositorio existente
```shell
git clone URL
```

- Mostrar el estado de nuestros archivos
```shell
git status
```

- Añadir archivos al area de staging
```shell
git add <file>
git add .
git add -A
git add *
```

- Guardar los archivos en el repositorio
```shell
git commit
git commit -m "descripcion de los cambios realizados"
```

- Subir los cambios a un repositorio remoto
```shell
git push origin rama (branch)
```

- Descargar los cambios de un repositorio remoto
```shell
git pull origin rama (branch)
```

- Listar las ramas existentes
```shell
git branch
```

- Crear una nueva rama (branch)
```shell
git branch rama
```

- Eliminar una rama (branch)
```shell
git branch -D rama
```

- Activar una rama
```shell
git checkout rama
```

- Ver el historio de cambios
```shell
git log
```

