# Orkas

**Un equipo de agentes de IA de código abierto en tu escritorio transforma tus objetivos en trabajo terminado y lo mantiene en movimiento.**

Orkas es una aplicación de escritorio multiagente de código abierto (MIT) que prioriza el trabajo en local, y también un equipo de asistentes de IA que colaboran entre sí. Dile al **comandante** (Commander) qué necesitas: puede resolver muchas tareas por sí mismo. Para trabajos más grandes, divide el encargo en pasos y coordina a los agentes especializados con los agentes de programación y personales que ya usas: **Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent**.

Orkas está diseñado para ayudarte a avanzar en tus proyectos, no para responder una sola consulta. Cada **proyecto** reúne objetivos, reglas, memoria y archivos, así que puedes retomar el trabajo al abrir una conversación nueva. Asigna los **pendientes** a personas o agentes y usa **Auto-advance** para que el equipo tome la siguiente tarea. Las **automatizaciones programadas** repiten el trabajo cada hora, día, semana o mes. Todos tus datos se quedan en tu computadora y recibes los resultados para revisarlos. Así puedes confiarle a Orkas el trabajo que tu negocio necesita seguir impulsando.

**[⬇ Descarga Orkas para macOS y Windows](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** — úsalo gratis con 500 créditos para el modelo Orkas integrado, sin necesidad de una clave de API para empezar. Si prefieres usar tus propias claves, puedes conectar Claude, OpenAI, Gemini, DeepSeek, Kimi, GLM, Qwen, MiniMax o Doubao, o un endpoint local compatible con OpenAI.

[![Download for macOS & Windows](https://img.shields.io/badge/Download-macOS%20%26%20Windows-5b57d6?style=for-the-badge)](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Orkas-AI/Orkas?style=flat&logo=github&label=Stars&color=yellow)](https://github.com/Orkas-AI/Orkas/stargazers)
[![Release](https://img.shields.io/github/v/release/Orkas-AI/Orkas?color=blue)](https://github.com/Orkas-AI/Orkas/releases)
[![X: @leochenpm](https://img.shields.io/badge/X-%40leochenpm-black?logo=x)](https://x.com/leochenpm)
[![Website: orkas.ai](https://img.shields.io/badge/Website-orkas.ai-5b57d6)](https://orkas.ai/?source=gh-orkas)

[English](./README.en.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md) · [Bahasa Indonesia](./README.id.md) · [Español (Latinoamérica)](./README.es-419.md) · [Русский](./README.ru.md) · [Português (Brasil)](./README.pt-BR.md) · [Türkçe](./README.tr.md) · [繁體中文](./README.zh-TW.md) · [Tiếng Việt](./README.vi.md) · [Deutsch](./README.de.md) · [ไทย](./README.th.md) · [Français](./README.fr.md) · [Italiano](./README.it.md) · [Português (Portugal)](./README.pt-PT.md) · [العربية](./README.ar.md)

---

https://github.com/user-attachments/assets/4f8b16c8-a192-45a4-b19f-80e8d02c3dab

![Orkas desktop      conversación de tareas y resultados](./resources/app-ui/task-en.png)

---

## Qué puede entregar el equipo

- **Videos, locuciones e imágenes** — VideoStudio, VoiceStudio, ImageStudio
- **Informes de investigación, auditorías de SEO y análisis de mercado** — DeepResearcher, SeoGeoAgent, StockAnalyser
- **Publicaciones, artículos, resúmenes y presentaciones** — ContentWriter, PptMaker
- **Sitios web, interfaces de usuario y código** — UIDesigner, ProductDeveloper
- **Archivos de Word, Excel, PowerPoint y PDF** — OfficeWorker
- **Comercio electrónico** — cinco agentes se encargan de seleccionar productos, redactar textos comerciales, analizar reseñas, evaluar el desempeño del negocio y gestionar productos
- **Tareas complejas que requieren varios agentes** — el comandante divide el trabajo y asigna cada parte al agente adecuado y reúne los resultados. Por ejemplo, puede convertir un estudio de mercado en un informe, una presentación y un video de lanzamiento

La aplicación viene con 16 agentes especializados, cada uno con sus propias habilidades, memoria y herramientas. Puedes explorar más de 30 opciones en la [biblioteca de agentes](https://orkas.ai/views/marketplace/gs/agents/?source=gh-orkas) o describir el rol que necesitas para que el comandante cree un agente personalizado.

<details>
<summary><b>Todos los 16 agentes incorporados</b></summary>

| Área | Agente | Qué entrega |
| --- | --- | --- |
| Investigación y análisis | **DeepResearcher** | Investigación basada en la evidencia con fuentes verificadas, contradicciones marcadas y un informe auditable |
| | **SeoGeoAgent** | A partir de una URL, audita el SEO técnico, la calidad del contenido, Core Web Vitals y el potencial de citación en respuestas de IA (GEO); entrega una lista priorizada de correcciones |
| | **StockAnalyser** | Análisis bursátil, selección por factores, pruebas retrospectivas y comprobaciones del riesgo de cartera, con paneles de datos trazables |
| Contenido y medios | **ContentWriter** | Redacta publicaciones, artículos, informes breves y casos de estudio listos para publicar a partir de un objetivo, fuentes o un borrador |
| | **PptMaker** | Crea diapositivas PPTX editables y fáciles de revisar a partir de un tema, un esquema o un documento |
| | **ImageStudio** | Carteles, portadas, imágenes sociales e infografías |
| | **VideoStudio** | Producción y edición de video, con locución, presentadores de IA, subtítulos, doblaje, extracción de fragmentos, localización y recreación de videos de referencia con tu propio contenido y materiales |
| | **VoiceStudio** | Locución, audio con varias voces, transcripción y subtítulos, edición y mezcla de audio |
| | **UIDesigner** | Crea interfaces editables, principalmente en HTML, a partir de objetivos del producto, un PRD, capturas de pantalla o materiales de Figma |
| Desarrollo y oficina | **ProductDeveloper** | Analiza repositorios de código, implementa requisitos de un PRD, corrige errores, refactoriza y revisa código, con resultados verificables |
| | **OfficeWorker** | Crea, edita, comprueba y entrega archivos Word / Excel / PowerPoint / PDF, uno a la vez o en lotes |
| Comercio electrónico | **ECommerceResearcher** | Selecciona productos según el presupuesto, el mercado y las restricciones de abastecimiento; presenta candidatos, motivos de descarte y un plan de validación |
| | **ECommerceWriter** | Redacta títulos, fichas de producto, preguntas frecuentes, textos para imágenes y guiones de video con la voz de tu marca |
| | **ECommerceReviewer** | Analiza reseñas y reputación para identificar temas recurrentes entre clientes, causas de las malas reseñas y prioridades de mejora |
| | **ECommerceAnalyzer** | Comprueba los datos de ventas, ganancias, publicidad, reembolsos e inventario en archivos exportados y ofrece recomendaciones para el negocio |
| | **ECommerceOperator** | Planifica cambios de productos, precios, promociones e inventario; solo los ejecuta a través de las herramientas que ya has conectado |

Más sobre cada agente[orkas.ai/agentes](https://orkas.ai/agents/?source=gh-orkas)

</details>

### Recrea un video de referencia con tu propio contenido

**VideoStudio** puede tomar como referencia la estructura narrativa, el estilo visual y el ritmo de edición de un video viral para crear uno nuevo con tu producto, tus textos y tus materiales. Si le das el archivo de referencia y tus propios recursos, el agente analiza el gancho, el orden de la información, el ritmo visual y la llamada a la acción. Antes de producir el video, indica qué conservará y qué sustituirá.

Es útil para explicaciones con texto animado, demostraciones de SaaS o de aplicaciones y anuncios creados con materiales de producto que ya tienes. Puedes editar por separado el texto, los subtítulos, la locución y los fragmentos creados como elementos independientes. Para cambiar texto incrustado en imágenes generadas por IA, hay que modificar las imágenes correspondientes.

> «Usa reference.mp4 como referencia para crear un video promocional vertical de 30 segundos. Conserva el gancho, el estilo tipográfico y el ritmo, pero usa mi producto y mis grabaciones de pantalla. Enséñame primero el análisis y el plan de producción».

Necesitas un archivo de video que el agente pueda leer. No hay una función integrada para descargar videos desde enlaces compartidos en redes sociales. No se garantiza reproducir con exactitud los movimientos de cámara, las actuaciones de personas reales ni el video fotograma a fotograma. Consulta el [flujo de trabajo para recrear videos de referencia](./resources/builtin/marketplace/agents/79df9cc89f5f/skills/video-craft/references/reference-recreation.md).

---

## Mantenga el trabajo en movimiento

Terminar una tarea es solo el comienzo. Orkas también está diseñado para el trabajo que necesita continuidad.

- **Proyectos** — Los objetivos, las reglas, la memoria y los archivos se comparten dentro del proyecto. Cada conversación nueva puede retomar el trabajo sin que tengas que volver a explicar el contexto.
- **Pendientes y Auto-advance** — Asigna los pendientes del proyecto a personas o agentes. Al habilitar Auto-advance, el equipo toma el siguiente pendiente por su cuenta y te entrega el resultado para que lo revises.
- **Automatizaciones programadas** — Programa tareas para que se ejecuten cada hora, día, semana o mes. Orkas corre en tu computadora. A partir de la versión 1.9, cuando la computadora sale del modo de suspensión o se inicia Orkas, cada automatización recupera únicamente la ejecución omitida más reciente de las últimas 12 horas.
- **Conectores** — Conecta Gmail, Google Calendar, Sheets, Drive, Notion, Slack, Shopify, Stripe y otros servicios. Por defecto, Orkas te consulta antes de enviar, publicar o eliminar algo.
- **Aplicaciones** — Describe la herramienta que necesitas y Orkas la crea como una aplicación local dentro de la aplicación de escritorio. En la versión instalable, quienes tengan un plan pagado también pueden publicarla como una aplicación web con un enlace público.
- **Proyectos compartidos** — *(versión instalable)* Invita a compañeros de equipo o asistentes virtuales y asigna cada tarea a una persona o a un agente.

> [!NOTE]
> Los proyectos compartidos, la sincronización en la nube y la publicación de aplicaciones web solo están disponibles en la versión instalable; la versión de código abierto aún no los admite. Para usar estas funciones, **[descarga Orkas para macOS y Windows](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** (gratis, con 500 créditos para empezar).

---

## Ejecuta Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent juntos

Orkas ejecuta los agentes de CLI que ya tienes instalados como sesiones locales, junto a los especialistas integrados: los agentes de programación **Claude Code, Codex y OpenCode** y los agentes personales **OpenClaw y Hermes-Agent**. El comandante reparte el trabajo y mantiene un plan común, de modo que en una sola conversación puedes corregir un error, revisar el cambio y redactar las notas de la versión. También puedes incorporar herramientas de código abierto como HyperFrames al mismo flujo de trabajo.

[Usa Claude Code y Codex juntos →](https://orkas.ai/blog/claude-code-codex-together/?source=gh-orkas)

---

## ¿Por qué Orkas?

- **Un comandante que planifica, delega y también ejecuta** — Divide los objetivos y elige los agentes, las habilidades, los conectores y las herramientas adecuados. Si no hay un especialista más indicado, se encarga del análisis, la redacción, la investigación y el trabajo con archivos.
- **Almacenamiento local por defecto** — Las conversaciones, los archivos, las bases de conocimiento y los agentes personalizados se guardan en tu computadora de forma predeterminada. En la versión instalable puedes activar la sincronización en la nube. Con tu propia clave, las solicitudes al modelo van directo de tu computadora al proveedor; el modelo integrado de Orkas usa un servicio administrado por Orkas.
- **Cambia de modelo en cualquier momento** — El comandante y los agentes integrados comparten la configuración del modelo: puedes elegir el modelo Orkas integrado, tu propio proveedor o un endpoint local. Los agentes de CLI externos conservan su propia configuración.
- **Agentes que aprenden con la práctica** — Cada agente conserva sus propias habilidades y memoria de forma privada. Cuando la aplicación está inactiva, una revisión en segundo plano examina la actividad nueva y puede mejorar la autoevaluación, los métodos reutilizables y las habilidades adquiridas.
- **Código abierto y auditable** — La licencia MIT permite inspeccionar cómo están implementados Orkas, sus agentes y sus habilidades.

> ⭐ Si Orkas es útil para usted, una estrella ayuda a más personas a encontrar el proyecto.

---

## Descarga

| | Versión instalable (recomendada) | Versión desde el código fuente |
| --- | --- | --- |
| Las plataformas | macOS 12+ (Apple Silicon e Intel), Windows 10+ | macOS, Windows, glibc 2.34+ Linux x64/arm64 |
| Cuenta | Recibes 500 créditos al iniciar sesión | No se requiere cuenta |
| Modelos | Modelo Orkas integrado o tus propias claves | Tus propias claves o un endpoint de un modelo local |
| También incluye | Colaboración de proyectos, publicación de aplicaciones, sincronización en la nube y más | — |
| Cómo obtenerlo | **[Descarga Orkas](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** | [Inicio rápido](#inicio-rápido) |

El enlace de descarga detecta tu sistema e inicia la descarga del instalador correspondiente.

---

## ¿Para qué la usan las personas?

- **Contenido de marketing** — Vídeos de lanzamiento, páginas de producto, publicaciones y boletines con la voz de tu marca. [Escribir contenido](https://orkas.ai/use/content-writing/?source=gh-orkas) · [Vídeos](https://orkas.ai/use/make-videos/?source=gh-orkas)
- **Gestión de tiendas** — Informes semanales de ventas, respuestas a reseñas, textos de producto y análisis de la competencia. [Comercio electrónico](https://orkas.ai/use/ecommerce/?source=gh-orkas)
- **Investigación e informes** — Informes y diapositivas con fuentes, bajo demanda o de forma periódica. [Investigación](https://orkas.ai/use/researchers/?source=gh-orkas) · [Análisis de datos](https://orkas.ai/use/data-analysis/?source=gh-orkas)
- **Habla con tus documentos** — respuestas basadas en sus propios archivos, con citas de los pasajes fuente.[Hablar con documentos](https://orkas.ai/use/chat-with-documents/?source=gh-orkas)
- **Proyectos de clientes** — Informes breves para reuniones, informes mensuales para clientes y diapositivas de seguimiento a partir de tus plantillas. [Modelo de informe mensual del cliente](https://orkas.ai/blog/monthly-client-report-template/?source=gh-orkas)
- **Lanzamiento de productos** — páginas de destino, correcciones de errores con pruebas, registros de cambios y publicaciones de lanzamiento.[Desarrolladores](https://orkas.ai/use/developers/?source=gh-orkas)
- **Construir una aplicación** — Calculadores de cotizaciones, formularios de reserva, herramientas internas.[Construir aplicaciones](https://orkas.ai/use/build-apps/?source=gh-orkas)
- **Colaboración en equipos pequeños** — Personas y agentes colaboran en un mismo proyecto. [Equipos pequeños](https://orkas.ai/use/small-teams/?source=gh-orkas)

---

## Cómo se compara Orkas

| Herramienta | Qué es | En qué se diferencia Orkas |
| --- | --- | --- |
| **Claude Code** | Agente de programación de Anthropic basado en modelos Claude, disponible en el terminal, el IDE, el escritorio y la web. | No tienes que elegir: Orkas ejecuta Claude Code como parte del equipo. Además, ofrece un equipo que no depende de un solo modelo y se ocupa de tareas que van más allá del código, como investigación, contenidos o video. Los proyectos, las tareas pendientes y las automatizaciones permiten dar continuidad al trabajo. [Orkas vs. Claude Code →](https://orkas.ai/compare/orkas-vs-claude-code/?source=gh-orkas) |
| **Codex** | Agente de programación de OpenAI, disponible en el terminal, el editor y la nube. | No tienes que elegir: Orkas ejecuta Codex como un agente más, junto a Claude Code y OpenCode. El comandante puede asignar la programación a Codex y la revisión a otro agente, y después completar las partes del lanzamiento que no son código: documentación, publicaciones y videos. [Orkas vs. Codex →](https://orkas.ai/compare/orkas-vs-codex/?source=gh-orkas) |
| **Claude Cowork** | Agente de Anthropic para el trabajo diario, ahora integrado en Claude. Está disponible en escritorio, web y móvil con un plan pagado de Claude. Por defecto, se ejecuta en la nube de Anthropic y usa modelos Claude. | Alternativa de código abierto (MIT) a Claude Cowork. Puedes empezar gratis con 500 créditos. Los agentes se ejecutan en tu computadora y los datos se guardan localmente de forma predeterminada. Puedes usar el modelo Orkas integrado, una clave de tu proveedor o un endpoint local. El comandante también puede coordinar agentes de CLI como Claude Code y Codex. A cambio, Orkas necesita que tu computadora no entre en suspensión, mientras que las tareas de Cowork en la nube pueden seguir sin él. [Alternativas a Claude Cowork →](https://orkas.ai/compare/claude-cowork-alternatives/?source=gh-orkas) |
| **Manus** | Un agente de IA que planifica y ejecuta tareas en la nube de Manus por defecto. La aplicación de escritorio de Manus Studio (macOS y Windows) también puede trabajar en una carpeta que elija, con tareas aún planeadas en la nube. | Una alternativa de código abierto (MIT) a Manus. Orkas ejecuta sus agentes en su computadora y mantiene sus datos locales por defecto, con el modelo Orkas incorporado, sus propias claves de proveedor o un punto final local. Proyectos, tareas y automatizaciones mantienen el trabajo en movimiento. La compensación: Orkas necesita que su computadora esté despierta, mientras que las tareas en la nube de Manus pueden seguir funcionando sin ella.[Alternativa Manus de código abierto →](https://orkas.ai/open-source-manus-alternative/?source=gh-orkas) |
| **LangChain** | Marco de trabajo para desarrollar aplicaciones y agentes con LLM e integrarlos por código a aplicaciones en Python o JavaScript. | Orkas es una aplicación de escritorio que puedes dirigir por chat. Los datos se almacenan localmente de forma predeterminada. |
| **CrewAI** | Marco de trabajo para coordinar agentes autónomos mediante equipos y roles definidos en código Python. | Orkas lleva la coordinación multiagente al escritorio, con proyectos, tareas pendientes, automatizaciones y mecanismos para que cada agente aprenda con la práctica. |
| **OpenClaw** | Plataforma de agentes personales con integración de canales de mensajería, enrutamiento entre agentes y subagentes. | Orkas ofrece un espacio de trabajo de escritorio orientado a entregar resultados, con especialistas integrados y coordinación de agentes de CLI como Claude Code, Codex y OpenCode. OpenClaw también puede incorporarse al equipo. |
| **Hermes-Agent** | Agente de Nous Research que mejora con el uso, con memoria y habilidades, disponible como CLI, pasarela de mensajería y aplicación de escritorio. | El comandante de Orkas coordina a varios especialistas y agentes externos de CLI; Hermes-Agent también puede incorporarse al equipo. |

**Orkas es para ti si** quieres que un equipo de agentes colabore, dé continuidad al trabajo durante varios días y guarde por defecto los datos, las claves y los agentes en tu propio disco.

**No para ti si** Sólo quieres un chatbot universal, o una biblioteca de código puro para incrustar en tu propia aplicación.

**¿Estás eligiendo un agente de programación?** [Codex vs. OpenCode](https://orkas.ai/compare/codex-vs-opencode/?source=gh-orkas) · [Claude Code vs. Codex y OpenCode](https://orkas.ai/compare/claude-code-vs-codex-vs-opencode/?source=gh-orkas) · [Alternativas a Claude Code](https://orkas.ai/compare/claude-code-alternatives/?source=gh-orkas)

**Comparaciones detalladas →** [vs. Claude Code](https://orkas.ai/compare/orkas-vs-claude-code?source=gh-orkas) · [vs. Codex](https://orkas.ai/compare/orkas-vs-codex?source=gh-orkas) · [vs. Cline](https://orkas.ai/compare/orkas-vs-cline?source=gh-orkas) · [vs. LangChain](https://orkas.ai/compare/orkas-vs-langchain?source=gh-orkas) · [vs. ChatGPT](https://orkas.ai/compare/orkas-vs-chatgpt?source=gh-orkas) · [vs. OpenClaw](https://orkas.ai/compare/orkas-vs-openclaw?source=gh-orkas) · [vs. Hermes-Agent](https://orkas.ai/compare/orkas-vs-hermes-agent?source=gh-orkas)

---

## Inicio rápido

¿Prefieres usar el instalador? Consulta la sección [Descarga](#descarga). A continuación se explica cómo ejecutar Orkas desde el código fuente, que es la forma disponible actualmente en Linux:

**Requisitos**: Node 22.12+ · macOS / Windows 10+ / Linux x64 o arm64 con glibc 2.34+. Se recomienda tener Python 3 y las herramientas de compilación de C/C++ por si algún módulo nativo necesita compilarse desde el código fuente.

```bash
git clone https://github.com/Orkas-AI/Orkas.git
cd Orkas
./run.sh           # macOS / Linux
run.cmd            # Windows
```

En Linux, ejecutar Orkas desde el código fuente requiere glibc 2.34 o una versión más reciente. Alpine y las demás distribuciones basadas en musl no son compatibles. En el primer arranque desde el código fuente, Orkas descarga y verifica el entorno de ejecución de whisper.cpp para la arquitectura de tu computadora y el modelo multilingüe, para que puedas transcribir audio en el equipo.

En el primer arranque, `run.sh` / `run.cmd` instalan las dependencias de npm fijadas en el archivo de bloqueo y preparan versiones fijadas de Python, uv, Node, el modelo de embeddings (unos 95 MB), OfficeCLI, FFmpeg, whisper.cpp y el modelo de voz multilingüe. En Linux también se comprueba la compatibilidad de los módulos nativos de la plataforma y del entorno de ejecución de Whisper con la ABI de Electron antes de abrir la aplicación. El OCR y los paquetes de Python específicos de cada habilidad se instalan en entornos locales aislados la primera vez que se usan las funciones correspondientes. El primer arranque crea un espacio de trabajo en `~/.orkas/` (macOS / Linux) o en `<smallest non-system drive>:\.orkas\` (Windows, en la unidad más pequeña que no sea la del sistema). Después, entra en **Configuración → Proveedores de IA** para configurar una clave de API u OAuth.

Si encuentras errores de dependencias nativas, usa Node.js 24 LTS (mínimo 22.12.0) y ejecuta en este directorio del código fuente
`npm run native:repair`. El comando restaura las dependencias opcionales,
repara SQLite para Electron y comprueba SQL y sqlite-vec.
También prepara el Node incluido y comprueba `sharp` en un proceso independiente antes de indicar que ha terminado correctamente.
Para comprobar las dependencias sin instalar nada, ejecuta `npm run native:check`.
Consulta el [script de verificación de dependencias nativas](./scripts/verify-native-dependencies.cjs) para saber qué comprueba.

---

## Cómo funciona

### Enrutamiento de tareas

El comandante se encarga del trabajo general y usa tres herramientas para delegar las tareas especializadas:

- **`dispatch_to`** — Llama a un agente identificado por su nombre y usa el resultado para continuar. Puede esperar la respuesta o ejecutar la tarea de forma asíncrona y recibir un aviso al terminar.
- **`hand_off_to`** — Transfiere el trabajo restante a un agente identificado por su nombre y termina el turno actual del comandante. El agente responde directamente. Si queda una tarea más amplia por completar, se puede programar una continuación para que el comandante retome el trabajo después.
- **`run_worker`** — Ejecuta una subtarea anónima y aislada y devuelve el resultado en privado. No recibe el historial de la conversación ni las habilidades de un agente identificado por su nombre.

Las tareas de los agentes identificados por su nombre y las de los ejecutores anónimos tienen controles de concurrencia independientes. Consulta la [implementación de la delegación](./src/main/features/group_chat/bus.ts) y los [bloqueos de ejecución](./src/main/util/locks.ts).

### Gestión del contexto

El entorno de ejecución asigna el contexto en función de la capacidad de entrada disponible del modelo seleccionado, teniendo en cuenta las instrucciones, las herramientas y el estado de ejecución persistente. Para los turnos completados, conserva una ventana limitada de historial reciente. En las tareas largas en curso, los puntos de control condensan los mensajes de proceso anteriores y conservan el trabajo reciente. Las lecturas y los cambios de archivos, así como la ejecución de comandos, también se registran de forma estructurada para que puedan conservarse tras compactar el contexto.

Consulta el [presupuesto de contexto](./src/core-agent/src/agent/context-budget.ts), el [historial de sesión y los puntos de control](./src/core-agent/src/agent/session.ts) y los [registros del espacio de trabajo](./src/core-agent/src/agent/workspace-state.ts).

### La memoria y la biblioteca

La memoria persistente guarda por separado las preferencias del usuario, los datos del proyecto y los conocimientos reutilizables de cada agente. No debe confundirse con el índice de documentos de la biblioteca ni con el historial de conversaciones guardado.

La biblioteca separa los documentos en párrafos y crea un índice vectorial local en SQLite. El modelo de embeddings corre en tu computadora. Los agentes usan `library` para listar archivos, encontrar pasajes pertinentes y leer las fuentes en la biblioteca general o en la de tu proyecto. Las conversaciones anteriores se consultan por separado con `chat_history`.

Consulta la [memoria por ámbitos](./src/main/features/memory.ts), la [extracción de documentos](./src/main/util/file_to_chunks.ts), las [herramientas de la biblioteca](./src/main/model/core-agent/kb-tools.ts) y la [búsqueda en conversaciones](./src/main/model/core-agent/chat-history-tools.ts).

### Límites de ejecución y recuperación

Los bloqueos de sesión y los límites de concurrencia controlan cuánto trabajo puede ejecutarse en paralelo. Los límites de rondas de herramientas, los puntos de control de progreso, la detección de llamadas repetidas y la supervisión de inactividad por fases ayudan a controlar tareas estancadas o repetidas. Las tareas asignadas a agentes identificados por su nombre se pueden rastrear y cancelar individualmente. Una tarea aceptada o en cola no cuenta como terminada.

Consulta los [límites por actor](./src/main/features/group_chat/actor-budgets.ts), el [entorno de ejecución del agente](./src/core-agent/src/agent/runner.ts) y el [adaptador de modelos para escritorio](./src/main/model/core-agent/client.ts).

### Aprender de la actividad

Cuando la aplicación no está ocupada, la revisión en segundo plano examina la actividad reciente de los agentes, con intervalos de espera y límites de ejecución. Puede actualizar la autoevaluación (`COMPETENCE.md`), los métodos que se pueden volver a usar (`LEARNING_STRATEGIES.md`) o las habilidades adquiridas. También puede decidir que no hay nada que guardar. Se activa por actividad nueva, no por cantidad de tareas finalizadas.

Consulta la [programación de revisiones](./src/main/features/reflection-orchestrator.ts) y las [instrucciones de revisión](./src/core-agent/src/evolution/metacognition.ts).

---

## Las preguntas frecuentes

**¿Qué es Orkas?**
Orkas es una aplicación de escritorio multiagente de código abierto (MIT) que prioriza el trabajo en local. Su comandante divide tus objetivos en tareas pendientes y coordina a 16 agentes especializados integrados, además de Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent, para entregar archivos terminados.

**¿Necesito una llave de API?**
No. La versión instalable incluye 500 créditos para usar el modelo Orkas integrado. Cuando se agoten, puedes comprar créditos, elegir un plan pagado o agregar tus propias claves de proveedor. El proveedor cobra su uso por separado.

**¿Orkas es un modelo de lenguaje grande (LLM) que funciona de manera local?**
No. Orkas corre en tu computadora y usa el modelo que selecciones: el modelo Orkas integrado, uno que hayas conectado con tu clave de API o un modelo accesible desde un endpoint local. Su función es coordinar agentes y herramientas, no actuar como modelo.

**¿Puede Orkas responder preguntas de mis documentos, con citas?**
Sí. Agrega tus PDF y documentos a la biblioteca local. Orkas puede buscarlos y citar los fragmentos originales para que puedas abrir la fuente y comprobar la respuesta. El índice se crea en tu computadora.

**¿Puedo usar modelos locales como Ollama o LM Studio?**
Sí. Entra en **Configuración de la cuenta → Modelos → Chat → Agregar modelo → Personalizado** y selecciona **Compatible con OpenAI** o **Compatible con Anthropic**. Ingresa la URL base, el ID exacto del modelo y la clave de API. Después selecciona el modelo guardado en el menú de modelos de la tarea.

**¿Dónde se guardan mis claves de API y mis datos?**
De forma predeterminada, tus datos y claves se almacenan en tu computadora. Las claves de tus proveedores se cifran en el equipo y quedan fuera de la sincronización en la nube. Cuando usas tu propia clave, las solicitudes al modelo van directo de tu computadora al proveedor. El modelo integrado se ejecuta en un servicio administrado por Orkas. Si usas la sincronización opcional en la nube o los proyectos compartidos de la versión instalable, los datos que selecciones se guardan en los servidores de Orkas. [Seguridad y manejo de datos →](https://orkas.ai/security/?source=gh-orkas)

**¿Se puede usar Orkas completamente sin conexión?**
La versión desde el código fuente puede funcionar completamente sin conexión con un endpoint de un modelo local. La versión instalable requiere iniciar sesión, y las llamadas a modelos en la nube requieren conexión a Internet.

**¿Sigue funcionando cuando mi computadora está apagada?**
No. Para que funcionen Auto-advance y las automatizaciones programadas, la computadora debe estar activa y Orkas debe estar en ejecución. A partir de la versión 1.9, cuando la computadora sale del modo de suspensión o se inicia Orkas, cada automatización recupera únicamente la ejecución omitida más reciente de las últimas 12 horas.

**¿Puedo crear y publicar aplicaciones?**
Sí. Las aplicaciones locales que se ejecutan dentro de Orkas son gratuitas. Publicar aplicaciones web mediante un enlace público requiere un plan pagado: Lite permite publicar 5, Pro 8 y Max 15. Las aplicaciones web públicas no incluyen todas las funciones de la aplicación de escritorio de Orkas.

**¿Necesito una cuenta de Orkas?**
La versión instalable requiere iniciar sesión la primera vez que se abre. La versión desde el código fuente de este repositorio no tiene un módulo de cuentas: al iniciarla, se accede directamente a la aplicación.

**¿Puede Orkas trabajar con Claude Code y otros agentes de CLI?**
Sí. Orkas puede ejecutar cinco agentes de CLI externos como subprocesos locales: Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent. También puede integrar herramientas de código abierto como HyperFrames y coordinarlas desde una misma conversación.

**¿En qué se diferencia Orkas de Claude Code / Codex / CrewAI / LangChain?**
Claude Code y Codex son agentes de programación. Orkas puede ejecutar los dos como miembros de su equipo, así que no tienes que elegir entre ellos. CrewAI y LangChain son marcos de trabajo orientados al código. Orkas es una aplicación de escritorio de código abierto en la que un comandante coordina agentes especializados y agentes de CLI. Puedes elegir entre distintos proveedores de modelos, y los datos y las claves se guardan localmente de forma predeterminada. [Consulta las comparaciones completas](https://orkas.ai/compare/?source=gh-orkas).

**¿Qué plataformas apoya Orkas?**
macOS 12+ (Apple Silicon e Intel) y Windows 10+ cuentan con instaladores. En Linux x64/arm64 con glibc 2.34 o superior, todavía no hay instalador y Orkas se ejecuta desde el código fuente. La primera vez que se inicia, Orkas prepara una versión fija del entorno de ejecución de whisper.cpp para transcribir audio en la computadora. No es compatible con Alpine ni con otras distribuciones basadas en musl. El código fuente requiere Node 22.12 o superior. Solo necesitas Python 3 y las herramientas de compilación de C/C++ si tienes que reconstruir un paquete nativo de npm porque no existe un binario precompilado compatible.

**¿Es Orkas libre y de código abierto?**
Sí. La aplicación se distribuye con licencia MIT y es gratuita. La versión instalable incluye 500 créditos. Los planes de pago parten de $11.99 al mes y añaden créditos mensuales, sincronización en la nube, más proyectos compartidos y la posibilidad de publicar aplicaciones web. Si usas tus propias claves, tu proveedor te cobra el uso del modelo sin que Orkas añada ningún recargo. [Precios →](https://orkas.ai/pricing/?source=gh-orkas)

---

## Licencia

[MIT](./LICENSE)
