# qualentum

Herramientas de Gestión de Ciclo de Vida.

# Comandos Principales de Git

Este README contiene una lista de los comandos principales de Git para gestionar tus repositorios y control de versiones.

## Clonar un Repositorio

Para copiar un repositorio remoto a tu máquina local:

git clone <URL del repositorio>


## Configuración

Configurar tu nombre y dirección de correo electrónico:

git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"


## Comandos Básicos

- Iniciar un nuevo repositorio Git en tu proyecto:

git init


- Añadir cambios al área de preparación (staging):

git add <archivo>


- Confirmar cambios:

git commit -m "Mensaje de confirmación"


## Ramas (Branches)

- Crear una nueva rama:

git branch <nombre-de-rama>


- Cambiar a una rama específica:

git checkout <nombre-de-rama>


- Fusionar una rama en la rama actual:

git merge <nombre-de-rama>


- Eliminar una rama:

git branch -d <nombre-de-rama>


## Repositorios Remotos

- Agregar un repositorio remoto:

git remote add <nombre-remoto> <URL-del-remoto>


- Descargar cambios desde un repositorio remoto:

git pull <nombre-remoto> <rama-remota>


- Subir cambios a un repositorio remoto:

git push <nombre-remoto> <rama-local>:<rama-remota>


## Historial y Diferencias

- Ver el historial de confirmaciones:

git log


- Ver cambios no confirmados en archivos:

git diff


- Ver cambios en archivos en el área de preparación:

git diff --staged


Estos son algunos de los comandos básicos de Git. ¡Espero que te sean útiles!

