# proweb_kelvinreyes
# Evaluacion 1 - Repositorio GitHub

A continuación, se detalla el paso a paso para configurar el repositorio, agregar colaboradores y crear ramas.

## Paso 1: Crear el Repositorio

1. Accede a [GitHub](https://github.com/) y haz clic en "New" para crear un nuevo repositorio.
2. Asigna el nombre de tu preferencia al repositorio (por ejemplo, `mi_proyecto`).
3. Selecciona la opción para inicializar el repositorio con un archivo README.

![Crear Repositorio](https://github.com/Krey22/proweb_kelvinreyes/blob/main/%231.png)

![Asignar nombre](https://github.com/Krey22/proweb_kelvinreyes/blob/main/%232.png)

## Paso 2: Agregar Colaborador

1. En la página del repositorio, haz clic en "Settings" y luego en "Collaborators".
2. Seguidamente podràs visualizar la opciòn "Add people".
3. Escribe el nombre e invita al colaborador.

![Agregar Colaborador](https://github.com/Krey22/proweb_kelvinreyes/blob/main/%233.png)

## Paso 3: Crear Ramas

1. Localmente, abre una terminal, antes de comenzar con la creacion de las ramas debemos clonar el repositorio creado en nuestro github y accedemos a la carpeta donde se encuentra ubicado.
2. Utilizaremos el comando "git branch" para visualizar nuestra lista de ramas establecidas (como te podras fijar, main estara creada por default.
3. Ejecuta el siguiente comando para crear las demas ramas:

git branch nombre_branch
Debes sustituir la palabra "nombre" con el que desees para tu rama.

```bash
git checkout -b main
git push origin main

git checkout -b staging
git push origin staging

git checkout -b develop
git push origin develop
