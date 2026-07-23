# 🧬 BioCompetencial 2º Bach (PAU Ready)
> **Marco de Caracterización, Evaluador MCC-Bio2 v2.0 y Andamiaje Didáctico para la Elaboración de Preguntas Competenciales en Biología de 2º de Bachillerato.**

![LOMLOE](https://img.shields.io/badge/Normativa-LOMLOE%20%7C%20Decreto%20108%2F2022-blue)
![Comunitat Valenciana](https://img.shields.io/badge/Ámbito-Comunitat%20Valenciana-orange)
![Idiomas](https://img.shields.io/badge/Idiomas-Castellà%20%7C%20Valencià-brightgreen)
![PAU 2025](https://img.shields.io/badge/PAU-Modelo%202025%20Competencial-purple)

---

## 📌 Presentación y Finalidad Pedagógica

Este repositorio reúne el trabajo completo desarrollado para transformar la enseñanza y evaluación de la **Biología en 2º de Bachillerato** adaptada al marco LOMLOE y a las directrices de la nueva **Prueba de Acceso a la Universidad (PAU)**.

El objetivo principal es proporcionar un **andamiaje didáctico (*scaffolding*)** para que el propio alumnado no solo responda exámenes, sino que aprenda a **analizar, diseñar y autoevaluar sus propias preguntas competenciales** a partir de escenarios científicos y noticias del mundo real.

---

## 🗂️ Estructura del Repositorio

El proyecto se organiza en 4 grandes documentos de referencia y una aplicación web interactiva bilingüe:

```
📁 PREGUNTAS COMPETENCIALES BIOLOGIA 2BAT/
├── 📄 README.md                             <- Guía general del repositorio
├── 📄 marcos_competenciales_biologia.md     <- Documento Marco Maestro (Fase 1 y 2)
├── 📄 analisis_propuesta_aragon_bloqueA.md  <- Informe de Auditoría del Banco de Aragón (Fase 3)
├── 📄 andamiaje_didactico_alumnado.md       <- Guía de Andamiaje Didáctico Estándar (Fase 4)
├── 📄 andamiaje_didactico_alumnado_v2_IA.md  <- Guía de Andamiaje Didáctico con IA (Fase 4 - Edición v2.0)
│
├── 📁 app_interactiva/
│   └── 🌐 index.html                        <- Suite Web Interactiva Bilingüe (ES / VA)
│
├── 📁 EJEMPLOS/                             <- Exámenes reales PAU Cataluña (2023-2025)
├── 📁 PROPUESTAS A ANALIZAR/               <- Banco de preguntas oficiales analizadas
└── 📁 currículo biología/                   <- Decretos y Saberes Básicos oficiales (Bloques A-F)
```

---

## 🌐 Aplicación Web Interactiva (`app_interactiva/index.html`)

La aplicación web es completamente autónoma (no requiere instalación ni servidores backend) y puede ejecutarse directamente abriendo `index.html` en cualquier navegador web o alojarse gratuitamente en **GitHub Pages**.

### 🌟 Características Principales:
1. **🌐 Soporte Bilingüe Instantáneo (Castellà / Valencià):** Conmutador `ES | VA` en la cabecera que traduce toda la interfaz al momento.
2. **⚡ Auto-Evaluador en Tiempo Real:** Algoritmo en JavaScript que analiza la pregunta redactada por el estudiante y calcula automáticamente su puntuación competencial (0 a 15 pts).
3. **🖼️ Creador Multimedia & Fuentes Reales:** Permite subir imágenes o gráficos locales (png, jpg, svg) y pegar citas de artículos, noticias o transcripciones de podcasts.
4. **🧬 Selección Flexible de los 6 Bloques Curriculares (A - F):** Permite al estudiante marcar qué bloques del currículo oficial (*Biomoléculas, Genética, Célula, Metabolismo, Biotecnología e Inmunología*) está conectando en su ejercicio.
5. **🔍 Probador PEC (Prueba de Eliminación del Contexto):** Herramienta interactiva con interruptor deslizante para ocultar el enunciado y comprobar si la pregunta es un "falso envoltorio".
6. **🤖 Copiloto IA & Guía Anti-Copia:** Sección dedicada con explicación pedagógica sobre la *fricción cognitiva útil* y prompts precocinados para usar la IA de forma crítica.
7. **📚 Banco de Ejemplos PAU:** 4 ejercicios reales listos para importarse en el creador con un solo clic.
8. **📥 Centro de Descargas:** Enlace directo para descargar todos los documentos de andamiaje en formato `.md`.

---

## 📥 Documentos para Descarga Didáctica

* [📄 Documento Marco Maestro (marcos_competenciales_biologia.md)](./marcos_competenciales_biologia.md)
* [📄 Informe Auditoría Aragón (analisis_propuesta_aragon_bloqueA.md)](./analisis_propuesta_aragon_bloqueA.md)
* [📄 Guía Andamiaje Alumnado Estándar (andamiaje_didactico_alumnado.md)](./andamiaje_didactico_alumnado.md)
* [📄 Guía Andamiaje Alumnado con IA (andamiaje_didactico_alumnado_v2_IA.md)](./andamiaje_didactico_alumnado_v2_IA.md)

---

## 🚀 Despliegue en GitHub Pages

Para publicar la aplicación web de forma pública y accesible para todo tu alumnado:
1. Sube este repositorio a tu cuenta de **GitHub**.
2. Ve a **Settings -> Pages**.
3. Selecciona la rama `main` (o `master`) y la carpeta `/root` o `/app_interactiva`.
4. En pocos segundos tendrás una URL pública tipo `https://tu-usuario.github.io/PREGUNTAS-COMPETENCIALES-BIOLOGIA-2BAT/app_interactiva/`.

---

## ✒️ Autoría y Licencia
Proyecto desarrollado para la optimización didáctica y competencial de la materia de **Biología de 2º de Bachillerato** en la **Comunitat Valenciana**.  
*Licencia:* CC BY-NC-SA 4.0 (Uso educativo no comercial).
