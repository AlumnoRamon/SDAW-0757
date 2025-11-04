# Proyecto SDAW_0757

## Descripción

Este proyecto ha sido desarrollado por **Ramón Rueda Pérez** como parte de la actividad _“Uso de repositorios digitales (Git) I”_.  
Su finalidad es crear una pequeña aplicación web con **Node.js** que muestre un saludo personalizado mediante JavaScript.  
El repositorio se gestiona utilizando **Git y GitHub**, aplicando un flujo de trabajo con ramas, commits y pull requests.  
El servidor está construido con **Express** y sirve un archivo HTML que contiene un botón para interactuar con el usuario.

---

## Estructura del proyecto

```
SDAW_0757
├── index.html
├── script.js
├── package.json
├── server.js
├── README.md
└── .gitignore
```

---

## Ejecución en local

1. Clonar o descargar este repositorio.
2. Acceder a la carpeta principal:
   ```
   cd SDAW_0757
   ```
3. Instalar dependencias:
   ```
   npm install
   ```
4. Ejecutar el servidor:
   ```
   npm start
   ```
5. Abrir navegador web e ingresar a:
   http://localhost:3000

---

## Comandos Node.js utilizados

- `npm init -y` → Inicializa un proyecto Node.js con configuración por defecto.
- `npm install express` → Instala Express como dependencia.
- `npm start` → Ejecuta el servidor definido en `server.js`.

---

## Comandos Git empleados

- `git init` → Inicializa un repositorio local.
- `git add .` → Añade archivos al área de preparación.
- `git commit -m ""` → Crea un punto en el historial de cambios.
- `git branch` → Lista o crea ramas.
- `git checkout -b` → Crea y se mueve a una nueva rama.
- `git merge` → Integra cambios de otra rama.
- `git push origin` → Sube los cambios al repositorio remoto.
- `git pull origin` → Obtiene cambios desde el remoto.
- `git status` → Muestra el estado actual del repositorio.
- `git log --oneline` → Muestra el historial resumido.

---

## Información técnica desde rama 1

- **git init:** Crea un repositorio vacío.
- **git add:** Añade cambios al área de staging.
- **git commit:** Guarda los cambios en el historial.
- **git branch:** Gestiona ramas.
- **git merge:** Fusiona ramas manteniendo historial.
- **git push:** Envía cambios al repositorio remoto.

---

## Información técnica desde rama 2

Salida simulada de `git log --oneline`:

```
b3a42f9 docs: incluir log resumido (rama2)
5cd64a1 docs: añadir explicación comandos Git (rama1)
8a3e129 chore: agregar .gitignore
2c14a57 feat: crear estructura base proyecto SDAW_0757
```

---

## Capturas recomendadas

- Vista del proyecto en VS Code
- Ejecución del servidor (`npm start`)
- Navegador mostrando mensaje “Hola Ramón Rueda Pérez”
- Resultados de `git status` y `git log --oneline`
- GitHub con ramas y pull requests integrados

---

## Conclusiones

Esta práctica ha permitido comprender el uso de Git y GitHub para el control de versiones, consolidar el manejo de ramas y fusiones, y establecer un flujo de trabajo ordenado mediante commits claros.  
Además, se ha reforzado la ejecución de un servidor básico con Node.js y Express.

---

## Autor

**Ramón Rueda Pérez**  
Estudiante del módulo _Sistemas de Desarrollo de Aplicaciones Web_  
IES Ramón Arcas Meca  
Curso 2025/2026
