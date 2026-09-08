# Plataforma Web Institucional — EXPOJUY 2026
> *"Conectando Países, Creando Oportunidades"*

Bienvenido al repositorio oficial de la **Plataforma Web Institucional de la EXPOJUY 2026**, la exposición multisectorial más importante de la región. Este proyecto constituye el punto único, central y fundamental de comunicación, gestión de información e interacción entre la organización, expositores, patrocinadores y el público asistente.

---

## 📌 Tabla de Contenidos
- [1. Concepto General del Proyecto](#1-concepto-general-del-proyecto)
- [2. Objetivos](#2-objetivos)
- [3. Arquitectura de la Información y Módulos](#3-arquitectura-de-la-información-y-módulos)
- [4. Criterios de Diseño (UI/UX)](#4-criterios-de-diseño-uiux)
- [5. Stack Tecnológico](#5-stack-tecnológico)
- [6. Estrategia de Accesibilidad (WCAG 2.1)](#6-estrategia-de-accesibilidad-wcag-21)
- [7. Estrategia Responsive & Mobile-First](#7-estrategia-responsive--mobile-first)
- [8. Integración de Inteligencia Artificial](#8-integración-de-inteligencia-artificial)
- [9. Prototipos y Mockups](#9-prototipos-y-mockups)

---

## 1. Concepto General del Proyecto
Diseño, desarrollo e implementación de la plataforma web oficial para la **EXPOJUY 2026**. La plataforma está concebida como el canal digital neurálgico para coordinar la difusión de actividades, visibilizar el sector productivo e industrial y brindar soporte integral a los concurrentes durante las jornadas del evento.

---

## 2. Objetivos
- **Información centralizada:** Proveer datos claros, confiables y actualizados sobre el desarrollo de la exposición.
- **Agenda dinámica:** Facilitar el acceso y consulta del cronograma completo de actividades programadas para octubre.
- **Catálogo interactivo:** Disponer de un directorio de expositores con capacidades avanzadas de búsqueda y filtrado continuo por rubro.
- **Orientación espacial:** Guiar al asistente mediante un mapa digital interactivo de la Ciudad Cultural.
- **Jerarquización de patrocinadores:** Brindar visibilidad destacada a sponsors según sus niveles institucionales (*Diamond, Platinum, Gold, Silver*).
- **Canales de contacto directo:** Agilizar la atención y resolución de dudas mediante formularios integrados y sección FAQ.

---

## 3. Arquitectura de la Información y Módulos

| Módulo / Sección | Descripción y Funcionalidad |
| :--- | :--- |
| **Inicio** | Panel de presentación general, accesos rápidos a la compra de entradas y síntesis del evento. |
| **Noticias** | Grilla dinámica de novedades de relevancia con título, subtítulo, imágenes y cuerpo informativo. |
| **Agenda** | Cronograma interactivo de actividades por fecha (Acto de Inicio, paneles de Turismo, Comex, Inversiones, etc.). |
| **Expositores** | Catálogo visual con barra de búsqueda en tiempo real, filtros por rubro/sector y enlace de postulación *"Quiero ser expositor"*. |
| **Mapa del Predio** | Plano digital del predio dividido por Zonas (A, B, C, D) y Auditorio Principal, con geolocalización en la Ciudad Cultural. |
| **Sponsors** | Módulo de patrocinio institucional estratificado por categorías (*Diamond, Platinum, Gold y Silver*). |
| **Ayuda / Contacto** | Formulario para consultas directas y listado desplegable de Preguntas Frecuentes (FAQ). |

---

## 4. Criterios de Diseño (UI/UX)
- **Tema Visual:** Estética sobria, moderna y tecnológica basada en un **Dark Theme** con acentos en tonos azulados y violetas.
- **Jerarquía:** Fondos oscuros que maximizan el contraste de tarjetas de contenido (*cards*), tipografía clara y logotipos institucionales.
- **Consistencia:** Navegación superior (*header*) con accesos directos persistentes y pie de página (*footer*) unificado en todas las vistas.

---

## 5. Stack Tecnológico

### Backend
- **Python & Django Framework:** Arquitectura basada en patrones robustos de POO, sistema de vistas (*Views*), modelos relacionales (*Models*) y validación estricta de formularios.

### Base de Datos
- **RDBMS (SQL):** Almacenamiento seguro y estructurado para expositores, eventos de agenda, consultas y perfiles de administración.

### Frontend
- **HTML5 Semántico & CSS3**
- **Bootstrap:** Grillas flexibles y componentes adaptativos.
- **JavaScript (Vanilla / Modern JS):** Dinamismo e interactividad del lado del cliente.
- **Django Templates:** Renderizado dinámico y modular de vistas desde el servidor.

---

## 6. Estrategia de Accesibilidad (WCAG 2.1)
El desarrollo incorpora estándares de accesibilidad para garantizar un uso inclusivo:
- **Estructura Semántica y WAI-ARIA:** Marcado estricto de roles y atributos para lectores de pantalla.
- **Navegación por Teclado:** Operabilidad completa y foco visual accesible sin requerir puntero.
- **Contenido Alternativo:** Atributos `alt` descriptivos en imágenes, esquemas de mapas y logos de patrocinadores.
- **Contraste de Color:** Ratios optimizados entre texto y fondo según las pautas WCAG para evitar fatiga visual.

---

## 7. Estrategia Responsive & Mobile-First
Diseño concebido para una experiencia óptima en teléfonos móviles, tablets y monitores de escritorio:
- **Navegación adaptativa:** Menú de navegación colapsable (*hamburguer menu*) en pantallas reducidas.
- **Reorganización de grillas:** Transformación de catálogos y grillas multicolumna a listas verticales fluidas de una columna en pantallas móviles.
- **Optimización de activos:** Compresión y escalamiento dinámico de recursos (mapa del predio, slider de noticias) para reducir la tasa de transferencia y los tiempos de carga (*time-to-load*).

---

## 8. Integración de Inteligencia Artificial
- **Asistente Virtual (Chatbot):**  
  Implementación de un agente conversacional entrenado con información oficial del evento (agenda, expositores, ubicaciones y preguntas frecuentes) integrado en la sección de **Ayuda**, brindando soporte y resolución de consultas a los asistentes en tiempo real.

---

## 9. Prototipos y Mockups
- 💻 **Vista Web para Ordenador:** [Ver Mockup PC](VistaWebPc)
- 📱 **Vista Web para Móviles:** [Ver Mockup Móvil](VistaWebMovil)
