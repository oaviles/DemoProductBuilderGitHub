# ACME Retail — Creador de productos con IA

## Escenario

ACME Retail es una empresa minorista de tamaño mediano que experimenta un crecimiento lento en sus ventas digitales. Los clientes tienen dificultades para encontrar productos relevantes, lo que deriva en bajas tasas de conversión y una alta tasa de abandono de carritos de compra. La dirección de ACME desea lanzar una experiencia de compra digital personalizada, pero aún no cuenta con un producto definido; solo dispone de una necesidad de negocio y objetivos generales.

## Objetivo de negocio

Transformar la idea de negocio inicial en una definición validada de Producto Mínimo Viable (MVP) y un prototipo interactivo, utilizando GitHub Copilot Desktop y Canvas como herramienta de colaboración de productos basada en agentes.

## Contenido de este repositorio

Este repositorio proporciona únicamente el **contexto inicial del cliente**:

- **Caso de negocio** — Problema, objetivos, resultados deseados y métricas de éxito.
- **Perfiles de usuario (Personas)** — Usuarios objetivo y sus necesidades.
- **Restricciones** — Cronograma, capacidad y limitaciones técnicas y estratégicas.
- **Backlog de funcionalidades** — Funcionalidades candidatas para que Copilot las analice y priorice.

La definición del producto, el alcance del MVP, el prototipo y el documento de requisitos del producto (PRD) se **generan durante la sesión** mediante la interacción con Copilot.

## Estructura del repositorio

```
AIProductBuilder/
├── README.md
├── context/
│   ├── business_case.md
│   ├── personas.md
│   └── constraints.md
├── data/
│   └── feature_backlog.md
└── outputs/
    └── .gitkeep
```
## Resultado esperado

Al finalizar la sesión, se contará con:

1. Un **Canvas interactivo** que incluya la visión del producto, los perfiles de usuario (*personas*), el recorrido del cliente (*journey*), las prioridades de funcionalidades y el alcance del MVP.
2. Un **prototipo funcional** del recorrido principal del cliente.
3. Un **Documento de Requisitos del Producto** listo para ser revisado por las partes interesadas.

Todo ello generado a partir del contexto empresarial mencionado anteriormente; no se requiere desarrollo manual durante la sesión.

## Mensaje clave

GitHub Copilot Desktop no se limita a la generación de código. Puede actuar como un colaborador con capacidades de agente que acelera el descubrimiento, la definición y la creación de prototipos del producto, reduciendo así la brecha entre una conversación de negocios y un producto tangible.