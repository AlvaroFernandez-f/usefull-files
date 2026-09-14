<div align="center">

# ✦ Usefull Tools

### Pequeñas herramientas web para convertir ideas en entregables útiles

<p>
  <strong>Portfolio estructurado.</strong> <strong>Notas bajo control.</strong> <strong>Todo local.</strong>
</p>

<p>
  <img src="https://img.shields.io/badge/HTML%2FCSS%2FJS-vanilla-14211f?style=for-the-badge&labelColor=ff8f72" alt="Vanilla HTML CSS JS">
  <img src="https://img.shields.io/badge/sin_dependencias-100%25-2d7c58?style=for-the-badge&labelColor=d5f0df" alt="Sin dependencias">
  <img src="https://img.shields.io/badge/privacidad-local-f4d76d?style=for-the-badge&labelColor=14211f" alt="Datos locales">
</p>

<p>
  Una colección de utilidades web autocontenidas, pensadas para abrirse directamente en el navegador y resolver tareas concretas sin montar un proyecto complejo.
</p>

<p>
        <a href="#español">🇪🇸 Español</a> · <a href="#english">🇬🇧 English</a>
</p>

</div>

---

## Español

## ¿Qué hay dentro?

| Herramienta | Para qué sirve | Salida |
| --- | --- | --- |
| **Generador de portfolio** | Rellenas un formulario con tu información, proyectos, experiencia y preferencias. | Un archivo `.json` listo para entregárselo a un agente de IA que genere tu portfolio. |
| **Notalia** | Gestiona asignaturas, evaluaciones, porcentajes y notas con medias automáticas. | Un panel de estudio persistente en tu navegador. |

> La idea es sencilla: cada herramienta vive en un archivo HTML independiente y puede usarse sin instalación, servidor ni build.

---

## 01 · Generador de portfolio

El formulario convierte tu información en un JSON limpio y portable. Ese archivo funciona como un briefing estructurado para un agente de IA: en lugar de explicarle tu portfolio desde cero, le entregas todos los datos organizados.

### Flujo

```text
Rellenar formulario
        ↓
Revisar la información
        ↓
Exportar portfolio.json
        ↓
Entregar el JSON a tu agente de IA
        ↓
Generar el portfolio
```

### Incluye

- Datos personales y de contacto.
- Presentación y propuesta profesional.
- Experiencia, formación y habilidades.
- Proyectos y enlaces relevantes.
- Preferencias visuales y de contenido.
- Exportación directa a `.json`.

Abre el HTML del formulario desde el explorador de archivos y pulsa el botón de exportación cuando hayas terminado.

---

## 02 · Notalia

[**Abrir Notalia →**](notalia.html)

Un gestor visual de notas para llevar el seguimiento de tus evaluaciones sin perderte entre hojas de cálculo.

### Lo que puedes hacer

- Crear asignaturas y repartir su nota entre exámenes, proyectos y trabajos.
- Introducir notas y calcular automáticamente la nota ponderada.
- Marcar asignaturas como no computables.
- Crear evaluaciones nuevas conservando las asignaturas.
- Copiar la configuración de la evaluación anterior sin copiar sus notas.
- Consultar medias por evaluación y medias globales del curso.
- Bloquear una evaluación completada para dejarla en modo lectura.
- Desbloquearla si necesitas corregir un dato.
- Guardar toda la información en el navegador mediante `localStorage`.
- Usar el onboarding interactivo para aprender el flujo principal.

> **Privacidad:** los datos de Notalia se guardan en tu ordenador, dentro del navegador. No se envían a ningún servidor.

---

## Empezar

No necesitas instalar nada.

1. Descarga o clona este repositorio.
2. Abre el HTML de la herramienta que quieras utilizar.
3. Sigue el flujo de la interfaz.

```bash
git clone <URL-del-repositorio>
cd <carpeta-del-repositorio>
```

También puedes abrir los archivos directamente con doble clic desde el explorador de archivos.

---

## Estructura

```text
.
├── notalia.html                 # Gestor de notas y evaluaciones
├── cursor-alt-svgrepo-com.svg   # Recurso visual del cursor
└── README.md                    # Documentación del repositorio
```

El formulario de portfolio es la otra herramienta del repositorio y exporta el JSON que utilizarás como contexto para tu agente de IA.

---

## Decisiones del proyecto

### Cero fricción

Son herramientas HTML autocontenidas. No hay dependencias que instalar, comandos de build ni servidor obligatorio.

### Datos bajo control

La información de Notalia se queda en el navegador. El JSON del portfolio se descarga localmente y tú decides dónde entregarlo.

### Pensado para reutilizar

Cada utilidad resuelve un flujo concreto, pero puede abrirse, copiarse y adaptarse sin una arquitectura pesada detrás.

---

## Licencia

**All rights reserved.**

Copyright © 2026. Todos los derechos reservados.

El contenido de este repositorio no puede copiarse, modificarse, distribuirse, publicarse ni utilizarse con fines comerciales sin autorización expresa del titular.

<div align="center">

**Hecho para convertir trabajo disperso en cosas que ya se pueden usar.**

</div>

---

## English

<div align="center">

### Small web tools for turning ideas into useful deliverables

<strong>Structured portfolio.</strong> <strong>Grades under control.</strong> <strong>Everything local.</strong>

</div>

## What's inside?

| Tool | What it does | Output |
| --- | --- | --- |
| **Portfolio generator** | Fill in a form with your information, projects, experience and preferences. | A `.json` file ready to give to an AI agent that can generate your portfolio. |
| **Notalia** | Manage subjects, evaluations, weights and grades with automatic averages. | A study dashboard persisted in your browser. |

> The idea is simple: each tool lives in its own HTML file and can be used without installation, a server or a build step.

---

## 01 · Portfolio generator

The form turns your information into clean, portable JSON. That file works as a structured brief for an AI agent: instead of explaining your portfolio from scratch, you give it all your data in an organized format.

### Flow

```text
Fill in the form
        ↓
Review your information
        ↓
Export portfolio.json
        ↓
Give the JSON to your AI agent
        ↓
Generate the portfolio
```

### Includes

- Personal and contact details.
- Introduction and professional positioning.
- Experience, education and skills.
- Projects and relevant links.
- Visual and content preferences.
- Direct `.json` export.

Open the form's HTML file from your file explorer and press the export button when you are done.

---

## 02 · Notalia

[**Open Notalia →**](notalia.html)

A visual grade manager for tracking evaluations without getting lost in spreadsheets.

### What you can do

- Create subjects and split their grades between exams, projects and assignments.
- Enter grades and automatically calculate weighted results.
- Mark subjects as excluded from the average.
- Create new evaluations while keeping the same subjects.
- Copy a previous evaluation's structure without copying its grades.
- View averages by evaluation and global course averages.
- Lock a completed evaluation in read-only mode.
- Unlock it if you need to correct something.
- Store all information in the browser using `localStorage`.
- Use the interactive onboarding to learn the main workflow.

> **Privacy:** Notalia data stays on your computer, inside your browser. Nothing is sent to a server.

---

## Getting started

There is nothing to install.

1. Download or clone this repository.
2. Open the HTML file for the tool you want to use.
3. Follow the interface flow.

```bash
git clone <repository-URL>
cd <repository-folder>
```

You can also open the files directly with a double click from your file explorer.

---

## Project structure

```text
.
├── notalia.html                 # Grade and evaluation manager
├── cursor-alt-svgrepo-com.svg   # Cursor visual asset
└── README.md                    # Repository documentation
```

The portfolio form is the other repository tool and exports the JSON you can use as context for your AI agent.

---

## Project principles

### Zero friction

These are self-contained HTML tools. There are no dependencies to install, build commands or required server.

### Your data stays yours

Notalia information stays in the browser. The portfolio JSON is downloaded locally, and you decide where to send it.

### Built to be reused

Each utility solves a focused workflow, but can be opened, copied and adapted without a heavy architecture behind it.

---

## License

**All rights reserved.**

Copyright © 2026. All rights reserved.

The contents of this repository may not be copied, modified, distributed, published or used commercially without the express permission of the rights holder.

<div align="center">

**Built to turn scattered work into things you can actually use.**

</div>
