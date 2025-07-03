# Malla Interactiva - Psicología UOH 🧠

![Contribuidores](https://img.shields.io/github/contributors/BooterMan98/malla-interactiva)
![package version](https://img.shields.io/github/package-json/v/BooterMan98/malla-interactiva)
![license](https://img.shields.io/github/license/BooterMan98/malla-interactiva)
![Docker build status](https://img.shields.io/github/actions/workflow/status/BooterMan98/malla-interactiva/docker.yml?label=docker%20build)
![Docker image size](https://img.shields.io/docker/image-size/booterman/malla-interactiva?label=docker%20image%20size)
![Docker pull count](https://img.shields.io/docker/pulls/booterman/malla-interactiva)

Este proyecto fue adaptado por mí con el objetivo de visualizar de manera clara, ordenada e interactiva la malla curricular de la carrera de **Psicología** en la **Universidad de O'Higgins**. Se basa en el proyecto open-source original de [@csarman](https://github.com/csarman/malla-interactiva), el cual modifiqué para incorporar los ramos, semestres y particularidades de esta carrera.

---

## 🧩 Características

- Visualiza créditos SCT por ramo.
- Activa/desactiva ramos para simular tu avance académico.
- Muestra prerrequisitos y cómo se desbloquean según tu avance.
- Permite crear una malla personalizada.
- Cambios se guardan automáticamente en el navegador.
- Compatible con modo oscuro o claro.

---

## ⚙️ Cómo funciona

Cada carrera usa dos archivos JSON:

- `data_PSI.json`: lista los ramos organizados por semestre.
- `colors_PSI.json`: define las categorías y colores de los ramos.

Ambos archivos están en la carpeta `/data`.

---
