# Simbolismo en el Espacio | IDC - AAPV

**Escáner de Capas: La Matriz de Pulver — PWA Educativa**

Aplicativo web interactivo diseñado para el análisis semiótico-psicológico de afiches cinematográficos mediante la **Matriz de Pulver**. Desarrollado para la Agencia de Análisis Psicológico Visual (AAPV) del IDC.

---

## 📋 Descripción

Esta aplicación gamificada permite a los estudiantes-agentes registrarse, seleccionar un caso cinematográfico, insertar hotspots interactivos sobre afiches y decodificar el simbolismo espacial según la teoría de Pulver (superior/inferior, izquierda/derecha, esquinas). Incluye cuestionarios reflexivos, validación en tiempo real y exportación de informes en CSV y PDF.

---

## ✨ Características Principales

| Módulo | Descripción |
|--------|-------------|
| **🔐 Registro de Agente** | Formulario validado con nombre, apellidos y correo electrónico. Secuencia de boot estilo terminal. |
| **📁 Expedientes Clasificados** | Galería de 6 casos cinematográficos con metadatos, sinopsis y enlaces a tráilers oficiales. |
| **🎯 Escáner de Capas** | Visualización del afiche con overlay de la Matriz de Pulver (9 zonas espaciales). |
| **📍 Hotspots Interactivos** | Inserción, arrastre, edición y eliminación de hotspots sobre el afiche. Cada hotspot incluye zona, elemento visual e interpretación psicológica. |
| **📋 Protocolo de Decodificación** | 5 pasos validados: orientación de la mirada, hotspots (mín. 5), posición del título, palabra clave y cuestionario reflexivo. |
| **📊 Exportación de Datos** | Generación de informes en **CSV** (datos estructurados) y **PDF** (vista de impresión optimizada). |
| **🎨 Temas Visuales** | 5 temas intercambiables: Default, Matrix, Superman, Terminator y Fifth Element. |
| **📱 Diseño Responsive** | Adaptable a dispositivos móviles y tablets con controles táctiles. |

---

## 🛠 Tecnologías Utilizadas

- **HTML5** — Estructura semántica y accesibilidad
- **CSS3** — Variables CSS, animaciones, flexbox/grid, diseño responsive
- **JavaScript (Vanilla)** — Lógica de negocio, manipulación del DOM, eventos táctiles
- **Bootstrap 5.3.2** — Componentes UI, modales, formularios, toast notifications
- **Bootstrap Icons 1.11.1** — Iconografía vectorial

> *Sin dependencias de frameworks JS pesados. Funcionamiento 100% cliente.*

---

## 🚀 Cómo Usar

### 1. Registro del Agente
Al iniciar la aplicación, complete el formulario de registro con:
- **Nombre completo**
- **Apellidos completos**
- **Correo electrónico** válido

Presione **"INICIAR MISIÓN"** y espere la secuencia de boot del sistema.

### 2. Selección de Caso
En el dashboard, elija uno de los 6 expedientes clasificados:
- *Misión Imposible: Sentencia Mortal*
- *Dune: Parte Dos*
- *Oppenheimer*
- *The Batman*
- *Everything Everywhere All at Once*
- *Napoleón*

### 3. Análisis del Afiche
#### Insertar Hotspots
1. Active el **"MODO INSERCIÓN"**.
2. Haga clic sobre el afiche en la ubicación deseada.
3. Complete el modal con:
   - **Zona espacial** (según Matriz de Pulver)
   - **Elemento visual detectado**
   - **Interpretación psicológica**
4. Mínimo **5 hotspots** requeridos.

#### Overlay de Pulver
Presione **"VER CAPAS"** para visualizar las 9 zonas de referencia sobre el afiche.

### 4. Protocolo de Decodificación
Complete los 5 pasos del panel lateral:
1. ✅ Hackeo del Sistema (automático)
2. 🧭 Escaneo de Orientación (dirección de la mirada)
3. 📍 Inserción de Hotspots (mín. 5)
4. 📝 Rastreo del Título (posición en el afiche)
5. 🔑 Sello de la Matriz (palabra clave de motivación)

### 5. Cuestionario del Agente
Responda las 4 preguntas reflexivas:
- **P1:** Motivación del protagonista
- **P2:** Elemento dominante en zona superior
- **P3:** Análisis de tensión pasado/futuro (mín. 30 palabras)
- **P4:** Análisis reflexivo del proceso de decodificación (mín. 50 palabras)

### 6. Exportación
- **CSV:** Datos estructurados del agente, caso, hotspots y respuestas.
- **PDF:** Informe completo listo para impresión o guardado como PDF.

---

## 📂 Estructura del Proyecto

```
index.html          # Aplicativo completo (HTML + CSS + JS)
README.md           # Documentación del proyecto

/assets (opcional)
  /images           # Afiches locales (Misión Imposible.jpg, etc.)
  /docs             # Documentación complementaria
```

> **Nota:** El aplicativo es un archivo monolítico. Todas las dependencias (Bootstrap, iconos) se cargan vía CDN.

---

## 🎯 Zonas de la Matriz de Pulver

| Zona | Significado Psicológico |
|------|------------------------|
| **Superior** | Espíritu / Intelecto / Idealismo |
| **Inferior** | Biológico / Instinto / Materialismo |
| **Izquierda** | Pasado / Origen / Melancolía |
| **Derecha** | Futuro / Avance / Proyección |
| **Sup-Izq** | Represión / Reserva |
| **Sup-Der** | Expansión / Iniciativa |
| **Inf-Izq** | Obsesión / Depresión |
| **Inf-Der** | Agresión / Rebeldía |
| **Centro** | Yo / Presente / Interacción |

---

## ⚙️ Requisitos Técnicos

- Navegador moderno con soporte para:
  - CSS Variables
  - ES6+ JavaScript
  - LocalStorage (para persistencia futura)
- Conexión a Internet (para CDN de Bootstrap e imágenes externas)
- Resolución recomendada: 768px+ (optimizado para 1920×1080)

---

## 📄 Licencia y Créditos

**Desarrollado para:** Instituto de Diseño y Comunicación (IDC)  
**Asignatura:** Proyecto illustrator / Análisis del Discurso Visual  
**Modelo teórico:** Matriz de Pulver (Análisis Psicológico del Espacio en la Imagen)

> Este aplicativo es de uso educativo exclusivo para fines académicos de análisis semiótico.

---

**© 2025-2026 IDC - AAPV | Agencia de Análisis Psicológico Visual**  
*Sistema de Decodificación Espacial v4.2*