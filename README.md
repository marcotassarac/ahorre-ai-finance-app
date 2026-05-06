# Ahorr-E

AI Assisted Personal Finance Manager orientado a optimizar decisiones financieras personales mediante control presupuestario estricto, análisis inteligente de gastos y recomendaciones generadas por IA basadas en datos reales del mercado. contiene derechos de autor 

Ahorr-E nace desde una premisa simple:

> El problema financiero no es cuánto gana una persona, sino cómo decide gastar.

---

## 🚀 Visión del Proyecto

Ahorr-E ayuda a los usuarios a **evitar compras impulsivas** y priorizar el ahorro mediante:

- Gestión financiera basada en presupuestos reales
- Evaluación inteligente antes de realizar una compra
- Análisis automatizado de precios retail
- Recomendaciones asistidas por IA con grounding estricto
- Visualización clara del impacto financiero personal

El sistema está diseñado bajo principios de **ingeniería escalable**, separando responsabilidades entre interfaz, lógica de negocio y servicios inteligentes.

---

## 🧠 Concepto Técnico

El proyecto integra tres dominios principales:

### 1. Gestión Financiera
Control estructurado de presupuestos y gastos personales.

### 2. Inteligencia de Mercado
Obtención automatizada de precios retail para apoyar decisiones de compra.

### 3. Inteligencia Artificial Aplicada
Sistema de recomendaciones que analiza exclusivamente datos verificables evitando respuestas especulativas.

---

## ⚙️ Stack Tecnológico

| Layer | Technology |
|---|---|
| Frontend | Next.js (App Router) + React + Tailwind CSS |
| Backend / BFF | Server Actions + API Routes |
| Database | PostgreSQL (Supabase) |
| Seguridad | Supabase Auth + Row Level Security |
| ORM | Prisma |
| AI Integration | Google AI SDK (Gemini) |
| Infraestructura | Serverless Architecture (Vercel) |

---

## 🏗️ Arquitectura

Arquitectura modular basada en principios modernos:

- **BFF Pattern** para orquestación frontend/backend
- **Microservicios serverless** para scraping y procesamiento IA
- **Separación de dominios** entre datos financieros, análisis y recomendaciones
- **Grounded AI** para evitar alucinaciones del modelo
- **Cache inteligente** para optimizar consultas externas

El sistema fue diseñado priorizando:

- mantenibilidad
- escalabilidad
- seguridad por diseño
- bajo acoplamiento

---

## 📌 Requerimientos Funcionales

- Gestión de presupuestos personales
- Registro y seguimiento de gastos
- Evaluación automática de compras según disponibilidad financiera
- Análisis histórico de comportamiento financiero
- Obtención automatizada de precios retail
- Recomendaciones inteligentes basadas en contexto financiero real
- Visualización del impacto económico antes de gastar

---

## 🔒 Requerimientos No Funcionales

- Aislamiento de datos por usuario mediante RLS
- Arquitectura desacoplada orientada a microservicios
- Diseño mobile-first
- Procesamiento asíncrono de servicios externos
- Seguridad basada en infraestructura
- Escalabilidad serverless
- Tolerancia a fallos mediante cache fallback

---

## 📈 Reglas de Negocio

Ahorr-E aplica reglas financieras explícitas:

- No se permite registrar gastos sin presupuesto asociado
- Las recomendaciones IA solo utilizan datos verificados
- Las decisiones de compra consideran impacto futuro del usuario
- El sistema prioriza ahorro sobre consumo
- Las sugerencias se basan en evidencia de mercado y no en generación libre

---

## 🔐 Seguridad

El repositorio público corresponde únicamente a una versión de portafolio.

No incluye:

- credenciales
- configuraciones privadas
- datos reales de usuarios
- infraestructura productiva

---

## 🧑‍💻 Autor

**Marco Tassara**  
Full-Stack Developer · AI Assisted Development  
Enfocado en arquitectura moderna, automatización e integración de inteligencia artificial aplicada a software real.

---

## 📄 Licencia

Repositorio publicado únicamente con fines demostrativos, contiene derechos de autor.