<!-- ============================================================
     entregableFaceLit — README.md
     Sistema de Reconocimiento Facial de Asistencia
     ============================================================ -->

<div align="center">

```
███████╗ █████╗  ██████╗███████╗██╗     ██╗████████╗
██╔════╝██╔══██╗██╔════╝██╔════╝██║     ██║╚══██╔══╝
█████╗  ███████║██║     █████╗  ██║     ██║   ██║   
██╔══╝  ██╔══██║██║     ██╔══╝  ██║     ██║   ██║   
██║     ██║  ██║╚██████╗███████╗███████╗██║   ██║   
╚═╝     ╚═╝  ╚═╝ ╚═════╝╚══════╝╚══════╝╚═╝   ╚═╝   
```

# 🟢 entregableFaceLit

### Sistema Inteligente de Reconocimiento Facial para Control de Asistencia

![Estado](https://img.shields.io/badge/Estado-En%20Desarrollo-brightgreen?style=for-the-badge&logo=statuspage)
![Tecnología](https://img.shields.io/badge/Tech-Reconocimiento%20Facial-00ff88?style=for-the-badge&logo=opencv)
![Tipo](https://img.shields.io/badge/Tipo-Software%20Académico-33cc66?style=for-the-badge&logo=academia)
![BD](https://img.shields.io/badge/BD-SQL-009933?style=for-the-badge&logo=postgresql)

---

> *"La identidad es el futuro. FaceLit convierte cada rostro en una firma digital."*

</div>

---

## 📡 Descripción General

**FaceLit** es un sistema de software orientado al **control de asistencia mediante reconocimiento facial**. El proyecto integra técnicas de visión por computadora, diseño de bases de datos relacionales y arquitectura de software moderna, con el objetivo de automatizar y digitalizar los registros de asistencia de forma segura, eficiente y sin fricciones.

Este repositorio de entrega (`entregableFaceLit`) concentra todos los artefactos del proyecto, organizados por categoría funcional, desde la especificación de requisitos hasta los scripts SQL de la base de datos.

---

## 🗂️ Estructura de la Carpeta

```
📁 entregableFaceLit/
│
├── 📁 SRS/
├── 📁 Diagramas/
├── 📁 Modelo entidad relación (BD)/
│   └── 📁 BD_FaceID/
├── 📁 Gantt/
├── 📁 Prototipado/
├── 📁 Informe tecnico/
├── 📁 Anexo/
├── 📁 Otros/
└── 📁 trabajo de Motta 2026/
```

---

## 📂 Desglose de Carpetas y Archivos

---

### 🟢 `SRS/` — Especificación de Requisitos de Software

> Documento central que define el **qué** del sistema: alcance, actores, funcionalidades, restricciones y comportamiento esperado.

| Archivo | Descripción |
|---------|-------------|
| `Copia de SRS Original (5) (1).docx` | Documento SRS completo del sistema FaceLit. Define los requisitos funcionales y no funcionales del sistema de reconocimiento facial, casos de uso, restricciones tecnológicas y criterios de aceptación. |

---

### 🟢 `Diagramas/` — Modelado y Arquitectura Visual

> Conjunto de diagramas UML y de flujo que representan la **arquitectura, comportamiento y estructura** del sistema.

| Archivo | Tipo | Descripción |
|---------|------|-------------|
| `Clases.drawio` | Diagrama de Clases | Estructura orientada a objetos del sistema: entidades, atributos, métodos y relaciones entre clases. |
| `Casos de uso.drawio` | Casos de Uso | Interacciones entre los actores del sistema (estudiante, administrador, sistema de reconocimiento) y las funcionalidades. |
| `Secuancial.drawio` | Diagrama Secuencial | Flujo de mensajes entre componentes durante el proceso de reconocimiento facial y registro de asistencia. |
| `Dominio.drawio` | Diagrama de Dominio | Modelo conceptual del dominio del problema, mostrando los conceptos clave y sus relaciones semánticas. |
| `Actividad` | Diagrama de Actividad | Flujo de actividades paso a paso del proceso de toma de asistencia facial. |
| `Transición de estado_` | Diagrama de Estados | Ciclo de vida de los objetos clave del sistema (sesión, usuario, registro). |
| `Diagrama de transición de estado_` | Diagrama de Estados (v2) | Versión actualizada del diagrama de transición de estados del sistema. |
| `Priorización_` | Diagrama de Priorización | Análisis y priorización de funcionalidades del sistema según valor e impacto. |

---

### 🟢 `Modelo entidad relación (BD)/` — Base de Datos

> Diseño completo de la base de datos relacional que soporta el sistema FaceLit.

| Archivo | Descripción |
|---------|-------------|
| `MR` | Modelo Relacional — diagrama de la estructura de tablas, claves primarias, foráneas y relaciones. |
| `Dicionario de datos.docx` | Diccionario de Datos — descripción detallada de cada tabla, campo, tipo de dato, restricciones y significado funcional. |

#### 📁 `BD_FaceID/` — Scripts SQL

| Archivo | Descripción |
|---------|-------------|
| `DDLv1.sql` | **Data Definition Language** — creación del esquema de base de datos: tablas, índices, restricciones y relaciones. |
| `DMLv1.sql` | **Data Manipulation Language** — inserción de datos iniciales, registros de prueba y datos semilla del sistema. |
| `DQLv1.sql` | **Data Query Language** — consultas SQL para reportes de asistencia, búsquedas de usuarios y estadísticas del sistema. |

---

### 🟢 `Gantt/` — Planificación del Proyecto

> Cronograma y gestión temporal del desarrollo.

| Archivo | Descripción |
|---------|-------------|
| `diagrama Gantt.xlsx` | Diagrama de Gantt con las fases del proyecto, tareas asignadas, duraciones, dependencias y fechas de entrega. |

---

### 🟢 `Prototipado/` — Diseño de Interfaz

> Representación visual anticipada del producto final.

| Archivo | Descripción |
|---------|-------------|
| `Prototipado Completo_.docx` | Prototipo completo de la interfaz de usuario del sistema, con pantallas, flujos de navegación y mockups de las vistas principales. |

---

### 🟢 `Informe tecnico/` — Documentación Técnica

> Documentos formales de soporte y respaldo técnico-legal del proyecto.

| Archivo | Descripción |
|---------|-------------|
| `INFORME TECNICO.docx` | Informe técnico completo del sistema: arquitectura, decisiones de diseño, tecnologías utilizadas y justificaciones técnicas. |
| `Copia de Licencia de Software.docx` | Licencia de software asociada al proyecto, términos de uso y propiedad intelectual. |

---

### 🟢 `Anexo/` — Material Complementario

| Archivo | Descripción |
|---------|-------------|
| `Anexo.docx` | Documento de anexos con información de respaldo, tablas complementarias, referencias o material adicional al proyecto. |

---

### 🟢 `Otros/` — Documentos de Soporte

> Documentos generados durante fases tempranas del proyecto.

| Archivo | Descripción |
|---------|-------------|
| `( Borrador )PROPUESTA TECNICA Y ECONOMICA.docx` | Borrador de la propuesta técnica y económica inicial del proyecto, incluyendo estimaciones de costo, alcance y viabilidad. |
| `Actividad teórica  .docx` | Actividad teórica de fundamentación conceptual relacionada con el reconocimiento facial y sistemas biométricos. |

---

### 🟢 `trabajo de Motta 2026/` — Documentos del Ciclo 2026

> Documentación técnica y académica producida durante el período 2026 del proyecto.

| Archivo | Descripción |
|---------|-------------|
| `Planeacio de Software.docx` | Documento de planeación del software: metodología, fases de desarrollo, roles del equipo y estrategia de implementación. |
| `construcción del software.docx` | Documento de la fase de construcción: guías de desarrollo, estándares de código y proceso de implementación. |
| `Configurar herramientas de desarrollo.docx` | Guía de configuración del entorno de desarrollo: instalación de dependencias, herramientas, entornos virtuales y setup inicial. |
| `Introducción a framework.docx` | Introducción al framework seleccionado para el desarrollo del sistema, con ejemplos y buenas prácticas. |

---

## 🧠 Tecnologías Involucradas

<div align="center">

| Capa | Tecnología |
|------|------------|
| 👁️ Reconocimiento Facial | Visión por Computadora / Biometría |
| 🗄️ Base de Datos | SQL Relacional (DDL / DML / DQL) |
| 🖥️ Interfaz | Prototipos UI/UX |
| 📐 Modelado | UML — Draw.io |
| 📊 Gestión | Diagrama de Gantt |

</div>

---

## 📊 Resumen de Artefactos

<div align="center">

| Categoría | Cantidad de Archivos |
|-----------|----------------------|
| 📋 Documentos SRS | 1 |
| 📐 Diagramas UML | 8 |
| 🗄️ Scripts SQL | 3 |
| 📑 Modelos BD | 2 |
| 🖼️ Prototipado | 1 |
| 📄 Informes Técnicos | 2 |
| 📎 Anexos y Otros | 3 |
| 📅 Planificación | 1 |
| 📚 Docs 2026 | 4 |
| **Total** | **25 archivos** |

</div>

---

<div align="center">

---

```
  ·  ·  ·  F A C E L I T  ·  ·  ·
  Sistema de Reconocimiento Facial
       de Asistencia — 2026
  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·  ·
```

*Documentación generada para el proyecto académico FaceLit*
*Todos los derechos reservados — 2025–2026*

</div>
