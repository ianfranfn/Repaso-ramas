# Clase 06 - Bootcamp

##  Repaso GIT 

##  Creo el repositorio en GIT

```sh
git init
```

## Listo el estado de los archivos 

```sh
git status
```

## Haciendo un commit

1. Agrego al área de staging, los archivos que necesito que formen parte del commit.

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre-archivo>
git add . # Agrego todos los archivos que tengo en el working directory.
```
2. Hago el commit.

```sh
git commit -m "mensaje descriptivo"
git commit 
```

## Cambiar el editor por Nano

```sh
git config --global core.edit nano
```

## Ver el listado de commits que hice en el repo

```sh
git log # version larga
git log --oneline # version corta
```

## Agregar el repo remoto

```sh
git remote add origin <link-del-repo-remoto>
git remote add origin <https://github.com/ianfranfn/Repaso-ramas.git>
```

## Ver si se agregó el repo

```sh
git remote -v
```

## Subo al remoto el repositorio local

```sh
git push -u origin main # la primera vez
git push 
```