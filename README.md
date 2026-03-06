# GastApp - Proyecto Nuevas Tecnologías

## Descripción

GastApp es una aplicación diseñada para gestionar gastos personales.
Permite registrar ingresos, gastos y visualizar la información para llevar un mejor control financiero.

Este proyecto fue desarrollado como parte de la asignatura **Nuevas Tecnologías**.

---

# Configuración del Proyecto

Para trabajar con el proyecto se debe seguir el siguiente proceso.

## Clonar el repositorio

git clone https://github.com/Anavalencia17/GastApp-proyecto-NuevasTecnologias.git

## Entrar al proyecto

cd GastApp-proyecto-NuevasTecnologias

## Abrir el proyecto

Abrir el archivo **index.html** en el navegador.

---

# Reglas de Colaboración

1. Prohibido hacer commits directos a **main** o **develop**.
2. Cada tarea debe tener su propia rama **feature/nombre-tarea**.
3. Toda fusión debe pasar por un **Pull Request** y ser aprobada por al menos un compañero.
4. Los commits deben tener mensajes claros.

Ejemplo de commit:

feat: agregar validación de formulario

---

# Modelo de Trabajo (GitFlow)

El proyecto utiliza un modelo de trabajo basado en **GitFlow** para organizar el desarrollo.

## Ramas principales

| Rama    | Descripción                                   |
| ------- | --------------------------------------------- |
| main    | Contiene el código final estable del proyecto |
| develop | Rama donde se integran nuevas funcionalidades |

---

# Flujo de Trabajo

## 1 Crear una rama

git checkout -b feature/nombre-tarea

## 2 Guardar cambios

git add .
git commit -m "Descripción del cambio"

## 3 Subir cambios

git push origin feature/nombre-tarea

## 4 Crear Pull Request

En GitHub se debe crear un **Pull Request** para que el código sea revisado antes de fusionarlo con la rama **develop**.

---

# Tarea: Creación y Configuración del Proyecto con Git y GitHub

## Objetivo

El objetivo de esta tarea es aprender a utilizar **Git y GitHub** para gestionar un proyecto de desarrollo de software, aplicando buenas prácticas de control de versiones y trabajo colaborativo mediante el modelo **GitFlow**.

---

## Descripción de la actividad

En esta actividad se debe crear un repositorio en GitHub para el proyecto **GastApp**, configurar el entorno de trabajo con Git y elaborar un archivo **README.md** que describa el proyecto y establezca las reglas de colaboración del equipo.

---

# Desarrollo de la actividad

## 1. Creación de la cuenta en GitHub

Primero se creó una cuenta en la plataforma **GitHub**, que es un servicio de alojamiento de repositorios que permite almacenar proyectos y controlar versiones del código.

---

## 2. Instalación y configuración de Git

Se instaló **Git** en el computador para poder trabajar con repositorios de manera local.

Luego se configuró el usuario con los siguientes comandos:

git config --global user.name "Tu Nombre"
git config --global user.email "[tu@email.com](mailto:tu@email.com)"

Esto permite identificar al autor de cada cambio realizado en el proyecto.

---

## 3. Creación del repositorio

Se creó un repositorio en GitHub con el nombre:

GastApp-proyecto-NuevasTecnologias

El repositorio incluye un archivo inicial **README.md**, el cual sirve para documentar el proyecto.

---

## 4. Clonar el repositorio

El repositorio fue clonado en el computador local utilizando el siguiente comando:

git clone https://github.com/Anavalencia17/GastApp-proyecto-NuevasTecnologias.git

Esto permite trabajar con los archivos del proyecto desde el entorno local.

---

## 5. Creación de ramas

Para organizar el desarrollo se utilizó el modelo **GitFlow**, que divide el trabajo en diferentes ramas.

### Las ramas principales son:

* **main:** contiene la versión estable del proyecto.
* **develop:** se utiliza para integrar nuevas funcionalidades.

Además, se crean ramas temporales llamadas **feature**, que se utilizan para desarrollar nuevas tareas o funcionalidades.

Ejemplos:

feature/login
feature/registro-gastos

---

## 6. Creación del README

Se elaboró un archivo **README.md** que incluye:

* descripción del proyecto
* tecnologías utilizadas
* estructura del proyecto
* reglas de colaboración
* flujo de trabajo con Git

El README permite que cualquier persona entienda el propósito del proyecto y cómo trabajar con él.
