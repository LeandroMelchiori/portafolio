# Portafolio profesional — Leandro Melchiori

Sitio personal orientado a presentar proyectos, experiencia y capacidades técnicas mediante evidencia concreta de producto.

## Sitio publicado

- [www.sachadev.me](https://www.sachadev.me/)

## Posicionamiento

El portafolio presenta un perfil **Full Stack** con foco en:

- backend con Java y Spring Boot;
- frontend con React, Next.js y TypeScript;
- automatización y procesamiento documental con Python;
- RAG, embeddings e inteligencia artificial generativa aplicada;
- testing, CI/CD, contenedores y despliegue cloud;
- productos vinculados con economía social, gestión y educación.

## Proyectos destacados

1. **TechRetAI:** asistente corporativo RAG desplegado en OCI.
2. **Herramientas para Emprendedores:** suite PWA de costos, ventas y marketing.
3. **LiteraLura:** sistema Full Stack de gestión bibliotecaria.
4. **EcoSocial:** backend para catálogo y comunidad de economía social.
5. **TaskFlow:** gestor local-first de tareas y agenda.
6. **Club Deportivo:** aplicación Android de gestión integral para clubes, con clientes unificados, socios, actividades, profesores, horarios, cuotas, pagos, vencimientos y resumen mensual de ingresos. El código público se encuentra actualmente en [`LeandroMelchiori/App_Clubdeportivo`](https://github.com/LeandroMelchiori/App_Clubdeportivo).

## Casos de estudio privados

Los proyectos privados se presentan mediante el problema, la solución y el impacto operativo, ya que su código y sus datos no pueden exponerse públicamente.

- **Observatorio de Datos Banco Solidario:** consolida Excel y Word, normaliza la información, detecta inconsistencias y produce automáticamente indicadores, tablas, gráficos y reportes estadísticos exportables.
- **Gestión Integral de Talleres y Certificaciones:** administra asistentes y tandas, valida fuentes de datos, genera certificados personalizados y automatiza correos, plantillas, colas, reintentos, rebotes y reenvíos.
- **Pulse — Plataforma Transaccional de Eventos y Ticketing:** backend multi-tenant que modela la operación completa de productoras, clubes, teatros y festivales. Implementa stock atómico, checkout idempotente, Mercado Pago Marketplace con OAuth de vendedores, split de comisión, webhooks firmados y reembolsos, emisión de entradas, billetera del comprador, staff, RBAC administrativo, OTP, emails transaccionales y check-in. La API pública opera detrás de Cloudflare con SSL/TLS, WAF, rate limiting, mitigación DDoS y guard de origen hacia Render.

## Mejoras de esta versión

- Incorpora TechRetAI como proyecto principal de IA aplicada.
- Jerarquiza los proyectos según impacto, alcance y disponibilidad pública.
- Presenta los casos privados como historias de problema, solución e impacto.
- Renombra los casos privados según el alcance real de cada producto.
- Actualiza Club Deportivo a su repositorio personal y documenta sus mejoras de gestión y reportes.
- Añade una sección de experiencia profesional y formación actual.
- Actualiza LiteraLura a su alcance Full Stack real.
- Refuerza el posicionamiento en automatización, RAG e infraestructura.
- Actualiza Pulse al alcance transaccional actual: Mercado Pago Marketplace, OAuth, webhooks, refunds, seguridad, RBAC e infraestructura de borde.
- Documenta Cloudflare para DNS, proxy del tráfico, SSL/TLS, Transform Rules, WAF, rate limiting y mitigación DDoS.
- Documenta la protección del origen de Pulse en Render y el uso de la IP real del cliente detrás del proxy para el rate limiter.
- Mejora la experiencia responsive sin ocultar la navegación móvil.
- Incorpora metadatos SEO, Open Graph, URL canónica y datos estructurados.
- Mantiene navegación semántica, foco visible, skip link y reducción de movimiento.

## Tecnologías

**Backend:** Java, Spring Boot, Spring Security, JWT, JPA, Hibernate, Flyway, JUnit, Mockito y Testcontainers.

**Frontend:** React, Next.js, TypeScript, JavaScript, HTML, CSS, IndexedDB, PWA, Vitest y Playwright.

**IA y automatización:** Python, RAG, Gemini, OpenAI, embeddings, ChromaDB, Streamlit, Excel, procesamiento de documentos, PDF y Gmail API.

**Infraestructura:** Git, GitHub Actions, Docker, OCI, Vercel, Render, Caddy, Cloudflare (DNS, proxy, SSL/TLS, Transform Rules, WAF, rate limiting y mitigación DDoS), MinIO y almacenamiento compatible con S3.

## Estructura

```text
/
├── index.html
├── css/
│   └── styles.css
├── img/
└── README.md
```

## Ejecución local

El sitio es estático y no requiere un proceso de compilación.

```bash
git clone https://github.com/LeandroMelchiori/portafolio.git
cd portafolio
python -m http.server 8000
```

Luego abrir `http://localhost:8000`.

## Autor

**Leandro Melchiori**

- [Sitio](https://www.sachadev.me/)
- [LinkedIn](https://www.linkedin.com/in/leandromelchiori-developer/)
- [GitHub](https://github.com/LeandroMelchiori)
