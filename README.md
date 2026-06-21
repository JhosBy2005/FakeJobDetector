# FakeJob Detector

Landing page del proyecto FakeJob Detector, una solución digital orientada a prevenir fraudes laborales mediante el análisis de ofertas sospechosas, la verificación de empresas y la educación preventiva para usuarios que buscan empleo.

## Información del proyecto

FakeJob Detector ayuda a identificar señales de riesgo antes de postular a una oferta laboral. El avance de implementación está construido solo con HTML, CSS y JavaScript, siguiendo la estructura solicitada para el challenge de participación del curso.

## Autores

Team Coworkers:

- Darnell Cuba
- Mauricio Valverde
- Jimena Curi
- José Martinez
- José Santana

## Segmentos objetivo

- Estudiantes y recién egresados que buscan su primer empleo.
- Personas en búsqueda activa de empleo por plataformas digitales.
- Trabajadores remotos expuestos a ofertas por redes sociales o mensajería.
- Freelancers que necesitan verificar clientes, empresas y condiciones de contratación.

## Características principales

- Análisis de ofertas laborales para detectar pagos previos, urgencia artificial, phishing, salarios irreales y solicitud de datos sensibles.
- Verificación de empresas mediante nombre, RUC, correo, sitio web y señales comunitarias.
- Resultado de riesgo con porcentaje, nivel, explicación y recomendaciones preventivas.
- Historial local de análisis para revisar, buscar, ordenar y eliminar evaluaciones previas.
- Comunidad de reportes para registrar y validar alertas sobre posibles fraudes.
- Recursos educativos para reconocer patrones comunes de estafa laboral.
- Interfaz responsiva con navegación, formularios, modo oscuro y estados interactivos.

## Estructura del proyecto

```text
FakeJobDetector/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── assets/
│       ├── README.md
│       ├── images/
│       ├── scripts/
│       │   └── main.js
│       └── styles/
│           └── styles.css
├── api/
├── docs/
├── participacion/
├── README.md
└── CONTRIBUCIONES_REALES.md
```

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts
- Git y GitHub con flujo de trabajo GitFlow

## GitFlow

El proyecto mantiene `main` como rama estable y `develop` como rama de integración. Las nuevas funcionalidades deben crearse desde `develop` usando la convención:

```text
feature/nombre-de-la-funcionalidad
```

Ejemplo usado para este avance:

```text
feature/landing-page-structure
```

## Cómo ver el avance

Abre el archivo:

```text
public/index.html
```

También puedes servir la carpeta `public` con cualquier servidor estático local.
