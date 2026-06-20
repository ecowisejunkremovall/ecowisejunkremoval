# EcoWise Junk Removal: Sistema Operativo de Gestión Logística (OS)

EcoWise es una plataforma integral de gestión logística y operativa diseñada para optimizar los servicios de remoción de residuos (junk removal). Este sistema centraliza la toma de decisiones, la gestión financiera y la prospección comercial en una arquitectura robusta, escalable y tecnológicamente avanzada.

## 🚀 Visión del Proyecto
Transformar la industria de la remoción de residuos mediante la digitalización de procesos, el blindaje legal de operaciones y la automatización de la inteligencia de negocio. EcoWise combina eficiencia operativa con un enfoque sostenible, escalando desde una gestión manual a una infraestructura impulsada por IA.

## 🛠️ Arquitectura del Sistema
El sistema se divide en dos vertientes operativas principales:

1. **Modo Autónomo (Versión IA):** Integración con modelos de lenguaje avanzado (GPT-4o) para estimación de costos, gestión de inventarios y prospección B2B mediante flujos automatizados.
2. **Modo Manual (Gestión de Control Total):** Interfaz centralizada mediante AppSheet y Google Sheets para un control absoluto de las variables del negocio sin intervención de automatizaciones.

## 📋 Características Principales

* **Doble Blindaje Legal:** Sistema de firma digital (inicio y fin) obligatorio para cada orden, garantizando conformidad y protección ante disputas.
* **Panel de Configuración Maestro:** Control total de variables globales (tarifas, idiomas, radios de viaje) sin necesidad de modificar el código fuente.
* **Prospección B2B:** Módulos dedicados para la conquista de constructoras y administradores de propiedades en el mercado de Texas.
* **Sostenibilidad:** Seguimiento de impacto ambiental y trazabilidad de materiales (donaciones, reciclaje, vertedero).
* **Escalabilidad Territorial:** Lógica de expansión geográfica basada en radios operativos dinámicos (Default: 90 min de Austin).

## ⚙️ Tecnologías Implementadas

- **Frontend/Mobile:** AppSheet (Interfaz de campo para S26 Ultra).
- **Backend/Data:** Google Sheets como fuente de verdad centralizada.
- **Seguridad:** Implementación de acceso condicional basado en `USEREMAIL()` y gestión de propiedades de script en Google Apps Script.
- **Automatización (Opcional):** Integración de APIs de OpenAI para análisis predictivo.

## 🚀 Implementación y Despliegue
El sistema está diseñado para un despliegue modular:
1. **Configuración de Datos:** Integración con Google Sheets para establecer parámetros operativos.
2. **Despliegue de AppSheet:** Configuración de vistas con edición rápida (Quick Edit) para cambios en tiempo real.
3. **Blindaje de Seguridad:** Protección de llaves API y restricciones de acceso mediante scripts protegidos.

## 📈 Roadmap de Expansión
- [ ] Integración de pasarelas de pago (Stripe/Square).
- [ ] Configuración de infraestructura DNS (Dominio propio y anti-spam).
- [ ] Despliegue de orquestación B2B mediante n8n.

---
*Desarrollado para EcoWise Junk Removal | Austin, Texas*
