# Buyer Arena: preparado para lanzar

**Preparación para el lanzamiento: 95/100 · ★★★★★ (5/5)** — 25/9/2026, 15:02:43

| Panel | % | ★ | Atención |
|---|---:|---|---:|
| Usuarios finales | 100 | ★★★★★ | 40% |
| Desarrolladores | 100 | ★★★★★ | 15% |
| Inversores | 83 | ★★★★☆ | 15% |
| Equipo rojo | 94 | ★★★★½ | 15% |
| Segmentos | 91 | ★★★★½ | 15% |

## Usuarios finales — 100/100 ★★★★★

_¿Llegan los clientes al objetivo, y dónde se pierden?_

| Comprobaciones | % | ★ | Qué hacer: |
|---|---:|---|---|
| Objetivo alcanzado | 100 | ★★★★★ | Empieza por la principal fricción de la pestaña Usuarios finales. |
| El precio se encuentra | 100 | ★★★★★ | Pon los precios en el menú y junto al botón principal. |
| Forma clara de empezar | 100 | ★★★★★ | Usa un único botón principal explícito en la primera pantalla. |
| Sin errores del navegador | 100 | ★★★★★ | Corrige los errores listados en Ingeniería, en la pestaña Usuarios finales. |
| Poca fricción | 100 | ★★★★★ | Elimina bucles, pop-ups y rechazos de formularios. |
| Camino corto hasta el objetivo | 100 | ★★★★★ | Quita páginas y campos entre la llegada y el primer valor. |

## Desarrolladores — 100/100 ★★★★★

_¿Puede alguien que desarrolla ponerlo en marcha desde el README?_

| Comprobaciones | % | ★ | Qué hacer: |
|---|---:|---|---|
| README que explica y guía | 100 | ★★★★★ | Añade una sección de inicio rápido con los comandos exactos y una captura del resultado. |
| Los comandos de inicio rápido funcionan | 100 | ★★★★★ | Haz que cada comando del README corresponda a un script real, en el orden en que se ejecutan. |
| Los requisitos están indicados | 100 | ★★★★★ | Indica la versión en el README, en engines de package.json y en .nvmrc. |
| El CI ejecuta los tests | 100 | ★★★★★ | Añade un workflow de CI que instale y ejecute los tests en cada push. |
| Hay tests automáticos | 100 | ★★★★★ | Cubre el camino principal con tests automáticos antes de invitar a colaborar. |
| Documentación para colaborar | 100 | ★★★★★ | Añade CONTRIBUTING, SECURITY y un CHANGELOG. |
| Licencia clara | 100 | ★★★★★ | Añade una licencia estándar (Apache-2.0 o MIT para la adopción). |
| Herramientas de calidad | 100 | ★★★★★ | Activa tipos estrictos, un linter y un formateador, e incluye ejemplos. |
| La instalación limpia funciona | 100 | ★★★★★ | Haz que una instalación limpia funcione solo con el lockfile (npm ci). |
| La compilación funciona | 100 | ★★★★★ | Arregla la compilación para que funcione en una máquina limpia. |
| Tiempo hasta el primer éxito | 100 | ★★★★★ | Ofrece un comando que muestre un resultado real en menos de un minuto. |

## Inversores — 83/100 ★★★★☆

_¿Qué puede verificar un inversor sobre el valor y el modelo de negocio?_

**Modelo de negocio con más respaldo:** Open core · Potencial de viralidad: 100/100

| Comprobaciones | % | ★ | Qué hacer: |
|---|---:|---|---|
| Problema y promesa claros | 100 | ★★★★★ | Abre el README con una frase de valor y una sección breve de «Por qué». |
| Diferenciación explícita | 85 | ★★★★½ | Añade una tabla «frente a las alternativas» con lo que solo haces tú. |
| Demo y prueba visual | 100 | ★★★★★ | Muestra una demo de un comando y una captura o GIF en la primera pantalla. |
| Modelo de negocio articulado | 100 | ★★★★★ | Escribe quién paga, por qué y cómo la parte gratuita lleva hasta ahí. |
| La licencia encaja con el modelo | 95 | ★★★★★ | Elige una licencia que sirva a la adopción y mantenga aparte la capa de pago. |
| Prueba de ejecución | 92 | ★★★★½ | Muestra ejecución constante: tests, CI, versiones y changelog. |
| Evidencia de adopción | 5 | ½☆☆☆☆ | Consigue usuarios reales antes de buscar inversión: publica una versión, lista quién lo usa y reúne dos o tres testimonios. |
| Defensibilidad | 100 | ★★★★★ | Explica qué mejora con el uso (datos, calibración, integraciones). |
| Mercado objetivo claro | 90 | ★★★★½ | Nombra el primer segmento de clientes y el trabajo por el que te paga. |
| Límites y riesgos honestos | 100 | ★★★★★ | Declara las limitaciones con claridad; la honestidad genera confianza. |
| Gobernanza de código abierto | 100 | ★★★★★ | Añade archivos de gobernanza para que las empresas puedan adoptar y colaborar con seguridad. |

## Equipo rojo — 94/100 ★★★★½

_¿Cuán expuesto está, también frente a agentes de IA?_

**Índice de riesgo:** 6/100 (Riesgo bajo) · **Riesgo ante agentes de IA:** 5/100

| Comprobaciones | % | ★ | Qué hacer: |
|---|---:|---|---|
| Sin secretos en el repositorio | 100 | ★★★★★ | Revoca cualquier clave expuesta, bórrala del historial y añade escaneo de secretos al CI. |
| Sin dependencias vulnerables conocidas | 100 | ★★★★★ | Actualiza o sustituye los paquetes vulnerables. |
| No se ejecuta código al instalar | 100 | ★★★★★ | Evita los hooks de instalación; pasa la configuración a un comando explícito. |
| CI reforzado | 100 | ★★★★★ | Pasa las entradas por variables de entorno, declara permisos mínimos y fija las acciones. |
| Sin prompt injection en archivos que leen los agentes | 100 | ★★★★★ | Elimina el Unicode oculto y las instrucciones dirigidas a la IA de documentación, skills y prompts. |
| Herramientas MCP con mínimo privilegio | 100 | ★★★★★ | Dale a cada herramienta MCP entradas acotadas, listas permitidas y nada de shell; descripciones sin instrucciones. |
| Sin permisos de agente demasiado amplios | 100 | ★★★★★ | Nunca recomiendes saltar permisos; ofrece configuraciones acotadas e instaladores firmados. |
| La salida del modelo se valida | 80 | ★★★★☆ | Trata el contenido web como datos: valida cada respuesta del modelo con un esquema antes de actuar. |
| Ejecución de shell limitada | 76 | ★★★★☆ | Evita shell:true; pasa argumentos como lista y nunca interpoles datos del usuario. |
| Superficie web (Argus) | 71 | ★★★½☆ | Añade cabeceras de seguridad, redirecciones HTTPS y páginas de privacidad accesibles. |
| Privacidad: cookies y terceros | 100 | ★★★★★ | Quita llamadas a terceros innecesarias y crea cookies solo tras el consentimiento. |

## Segmentos — 91/100 ★★★★½

_¿Funciona para todo el mundo, no solo para la visita media?_

| Comprobaciones | % | ★ | Qué hacer: |
|---|---:|---|---|
| Accesibilidad | 66 | ★★★½☆ | Etiqueta cada campo, añade texto alternativo, agranda los objetivos pequeños y corrige el contraste. |
| Funciona con conexión lenta | 100 | ★★★★★ | Reduce el peso de la página y muestra la acción principal antes que nada. |
| Funciona sin crear cuenta | 100 | ★★★★★ | Ofrece un camino de invitado o un inicio sin contraseña (enlace mágico, prueba sin registro). |
| Zoom al 200 % y pantallas pequeñas | 100 | ★★★★★ | Deja que el contenido se reacomode; nada de anchos fijos mayores que la pantalla. |
| Otros idiomas | 100 | ★★★★★ | Declara el idioma de la página y ofrece páginas traducidas con hreflang. |
| Igualdad en el móvil | 100 | ★★★★★ | Prueba el camino completo en un móvil: menús, pop-ups y formularios. |

## Plan de acción

1. **Evidencia de adopción** — Consigue usuarios reales antes de buscar inversión: publica una versión, lista quién lo usa y reúne dos o tres testimonios. _(Inversores, impact 57)_
2. **Accesibilidad** — Etiqueta cada campo, añade texto alternativo, agranda los objetivos pequeños y corrige el contraste. _(Segmentos, impact 20.4)_
3. **Superficie web (Argus)** — Añade cabeceras de seguridad, redirecciones HTTPS y páginas de privacidad accesibles. _(Equipo rojo, impact 13.1)_

## Prometido frente a construido — 100%

- [x] El repositorio se instala
- [x] La demo arranca con un comando
- [x] 20 compradores sintéticos pueden ejecutarse
- [x] Existen 5 arquetipos
- [x] Existen historias de cliente
- [x] Se capturan recorridos reales de navegador
- [x] La evidencia se guarda y cada hallazgo la cita
- [x] Funciona la comparación actual vs candidata
- [x] Análisis de cinco auditores
- [x] Se genera ROI_BACKLOG.md
- [x] Funciona el informe HTML
- [x] Reproducción y trazas inspeccionables
- [x] Servidor MCP funcional
- [x] Tests y demo sin API de pago
- [x] Existe adaptador para proveedores LLM externos
- [x] Los presupuestos se hacen cumplir
- [x] Una interrupción se puede reanudar
- [x] Existe integración continua
- [x] Los secretos están protegidos
- [x] El proyecto parece creíble en GitHub
- [x] Cinco paneles (usuario, desarrollador, inversor, red team, segmentos)
- [x] Todo puntuado con estrellas 0–5 y 0–100 %
- [x] Exportación CSV, PNG, JPG, Markdown, JSON y PDF
- [x] Interfaz en ES · EN · NL de verdad
- [x] Mezcla configurable por panel con progreso en vivo
- [x] Auditoría de la superficie de agentes IA (skills, MCP, prompt injection)
- [x] Conexión con Argus
- [x] Web oficial ES/EN/NL
- [x] Ejecutable desde el móvil vía GitHub Actions