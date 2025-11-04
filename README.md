# Proyecto SDAW_5426

## Descripción

Este proyecto ha sido desarrollado por Ramón Rueda Pérez como parte de la tarea “Uso de
repositorios digitales (Git) I”.
El objetivo es crear una pequeña aplicación web en Node.js que muestre un mensaje
personalizado mediante JavaScript y gestionar su desarrollo utilizando Git y GitHub con un flujo
completo de trabajo en ramas, commits y pull requests.
El servidor web se ejecuta con Express y sirve un archivo HTML que muestra un botón para
saludar al usuario.

## Estructura del proyecto

SDAW_5426

--- index.html

--- script.js

--- package.json

--- server.js

--- README.md

--- .gitignore
## Instrucciones para ejecutar el proyecto localmente

1. Clonar o descargar este repositorio.
2. Abrir una terminal dentro de la carpeta del proyecto SDAW_5426.
3. Instalar las dependencias necesarias ejecutando:
npm install
4. Iniciar el servidor con:
npm start
5. Abrir el navegador y visitar: http://localhost:3000

## Comandos Node.js utilizados

npm init -y: Inicializa un proyecto Node.js.

npm install express: Instala el framework Express.

npm start: Inicia el servidor.

## Comandos Git utilizados

git init : Inicializa un repositorio local.
git add . : Añade todos los archivos al área de preparación.
git commit -m "" : Guarda los cambios en el historial.
git branch : Lista o crea ramas.
git checkout -b : Crea y cambia a una nueva rama.
git merge : Fusiona ramas.
git push origin : Sube los cambios al repositorio remoto.
git pull origin : Descarga los cambios del remoto.
git status : Muestra el estado actual del repositorio.
git log --oneline : Muestra el historial resumido.

## Información técnica añadida desde rama 1

- git init: Inicializa un nuevo repositorio Git local en la carpeta actual.
- git add: Añade archivos al área de preparación.
- git commit: Registra los cambios con un mensaje descriptivo.
- git branch: Crea o lista ramas.
- git merge: Fusiona los cambios de una rama en otra.
- git push: Envía los commits locales al repositorio remoto.
## Información técnica añadida desde rama 2

Simulación del comando git log --oneline:
b3a42f9 docs: añadir log resumido (rama2)
5cd64a1 docs: añadir explicación de comandos Git (rama1)
8a3e129 chore: añadir .gitignore
2c14a57 feat: inicializar proyecto SDAW_5426 - estructura base

## Capturas y comprobaciones recomendadas

- Estructura del proyecto en VS Code.
- Ejecución del servidor (npm start) mostrando la URL.
- Navegador con el mensaje “Hola Agustín Franco Ruiz”.
- Salida de git status y git log --oneline.
- GitHub mostrando ramas y pull requests mergeados.

## Conclusiones personales

Durante la práctica he aprendido a usar Git para gestionar versiones,
crear y fusionar ramas, documentar el trabajo y ejecutar un servidor básico
con Node.js y Express. Comprendí mejor el flujo de trabajo colaborativo con GitHub
y la importancia de mantener un historial de commits claro y ordenado.

## Autor

Ramón Rueda Pérez

Alumno del módulo “Sistemas de Desarrollo de Aplicaciones Web”

IES Ramón Arcas Meca

Año académico 2025/2026