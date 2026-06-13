# Spring Boot Docs

Sitio de documentación desarrollado con **MkDocs** y el tema **Material for MkDocs** como parte de una actividad práctica orientada al aprendizaje de herramientas de documentación y despliegue con GitHub Pages.

## Descripción

Este proyecto presenta una guía introductoria sobre **Spring Boot**, abordando conceptos básicos, instalación y ejemplos prácticos para estudiantes y desarrolladores que desean iniciarse en este framework de Java.

La documentación fue construida utilizando Markdown y publicada mediante GitHub.

## Tecnologías utilizadas

* MkDocs
* Material for MkDocs
* Markdown
* Git

## Contenido del sitio

* **Inicio**

  * Introducción a Spring Boot.
  * Objetivos de la guía.

* **Instalación**

  * Requisitos necesarios.
  * Configuración del entorno de desarrollo.

* **Conceptos Básicos**

  * Características principales de Spring Boot.
  * Beneficios y recomendaciones.

* **Ejemplos**

  * Implementación de un controlador REST.
  * Ejemplos de código utilizando pestañas.

## Características implementadas

* Navegación personalizada mediante `nav` en `mkdocs.yml`.
* Tabla con información técnica.
* Bloques de código con pestañas (tabs).
* Enlaces internos entre páginas.
* Uso de imágenes almacenadas en `docs/img/`.
* Bloques de admonición (`note`, `tip` y `warning`).
* Publicación automática mediante GitHub Pages.

## Estructura del proyecto

```text
springboot-docs/
├── docs/
│   ├── index.md
│   ├── instalaciones.md
│   ├── conceptos.md
│   ├── ejemplos.md
│   └── img/
│       └── springboot.png
├── mkdocs.yml
└── README.md
```

## Ejecución local

1. Clonar el repositorio:

```bash
git clone https://github.com/AxelAlvarado/springboot-docs.git
cd springboot-docs
```

2. Instalar las dependencias:

```bash
pip install mkdocs mkdocs-material
```

3. Iniciar el servidor local:

```bash
mkdocs serve
```

4. Abrir en el navegador:

```text
http://127.0.0.1:8000
```

## Autor

AXEL JAHIR ALVARADO ALEGRÍA

Estudiante de Ingeniería Informática – Universidad Centroamericana José Simeón Cañas (UCA).
