# Orkas

**Un equipo de agentes de IA de código abierto en tu escritorio transforma tus objetivos en trabajo terminado y lo mantiene en movimiento.**

Orkas es una aplicación de escritorio multiagente de código abierto (MIT) que prioriza el trabajo en local, y también un equipo de asistentes de IA que colaboran entre sí. Dile al **comandante** (Commander) qué necesitas: puede resolver muchas tareas por sí mismo. Para trabajos más grandes, divide el encargo en pasos y coordina a los agentes especializados con los agentes de programación y personales que ya usas: **Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent**.

Orkas está pensado para que tus proyectos sigan adelante, no solo para responder a una consulta. Un **proyecto** reúne objetivos, reglas, memoria y archivos para que cada conversación retome el trabajo anterior. Puedes repartir las **tareas pendientes** entre personas y agentes. Con **Auto-advance**, el equipo pasa por su cuenta a la siguiente tarea; las **automatizaciones programadas** repiten trabajos cada hora, día, semana o mes. Todos tus datos se quedan en tu ordenador y recibes los resultados para revisarlos. Así puedes confiarle a Orkas las tareas de tu negocio que necesitan avanzar de forma continua.

**[⬇ Descarga Orkas para macOS y Windows](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** — gratis, con 500 créditos para el modelo Orkas integrado. No necesitas una clave de API para empezar. También puedes usar tus propias claves de Claude, OpenAI, Gemini, DeepSeek, Kimi, GLM, Qwen, MiniMax o Doubao, o conectarte a un punto de conexión local compatible con OpenAI.

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

## Qué puede preparar el equipo

- **Vídeos, locuciones e imágenes** — VideoStudio, VoiceStudio, ImageStudio
- **Informes de investigación, auditorías SEO y estudios de mercado** — DeepResearcher, SeoGeoAgent, StockAnalyser
- **Publicaciones, artículos, informes breves y diapositivas** — ContentWriter, PptMaker
- **Sitios web, interfaces y código** — UIDesigner, ProductDeveloper
- **Archivos de Word, Excel, PowerPoint y PDF** — OfficeWorker
- **Comercio electrónico** — cinco agentes cubren la selección de productos, los textos de producto, el análisis de reseñas, el análisis del negocio y la gestión de productos
- **Encargos complejos en los que intervienen varios agentes** — el comandante divide la tarea, asigna cada parte al agente adecuado e integra los resultados. De un estudio de mercado, por ejemplo, pueden salir un informe, unas diapositivas y un vídeo de lanzamiento

La aplicación incluye 16 agentes especializados, cada uno con sus propias habilidades, memoria y herramientas. En la [biblioteca de agentes](https://orkas.ai/views/marketplace/gs/agents/?source=gh-orkas) puedes elegir entre más de 30. También puedes describir el perfil que necesitas y pedirle al comandante que cree un agente a medida.

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
| | **VideoStudio** | Producción y edición de vídeo, con locución, presentadores de IA, subtítulos, doblaje, extracción de fragmentos, localización y recreación de vídeos de referencia con tu propio contenido y materiales |
| | **VoiceStudio** | Locución, audio con varias voces, transcripción y subtítulos, edición y mezcla de audio |
| | **UIDesigner** | Crea interfaces editables, principalmente en HTML, a partir de objetivos del producto, un PRD, capturas de pantalla o materiales de Figma |
| Desarrollo y oficina | **ProductDeveloper** | Analiza repositorios de código, implementa requisitos de un PRD, corrige errores, refactoriza y revisa código, con resultados verificables |
| | **OfficeWorker** | Crea, edita, comprueba y entrega archivos Word / Excel / PowerPoint / PDF, uno a la vez o en lotes |
| Comercio electrónico | **ECommerceResearcher** | Selecciona productos según el presupuesto, el mercado y las restricciones de aprovisionamiento; presenta candidatos, motivos de descarte y un plan de validación |
| | **ECommerceWriter** | Redacta títulos, fichas de producto, preguntas frecuentes, textos para imágenes y guiones de vídeo con la voz de tu marca |
| | **ECommerceReviewer** | Analiza reseñas y reputación para identificar temas recurrentes entre clientes, causas de las malas reseñas y prioridades de mejora |
| | **ECommerceAnalyzer** | Comprueba los datos de ventas, beneficios, publicidad, reembolsos e inventario en archivos exportados y ofrece recomendaciones para el negocio |
| | **ECommerceOperator** | Planifica cambios de productos, precios, promociones e inventario; solo los ejecuta a través de las herramientas que ya has conectado |

Más sobre cada agente[orkas.ai/agentes](https://orkas.ai/agents/?source=gh-orkas)

</details>

### Recrea un video de referencia con tu propio contenido

**VideoStudio** puede tomar como referencia la estructura narrativa, el estilo visual y el ritmo de edición de un vídeo viral para crear uno nuevo con tu producto, tus textos y tus materiales. Si le das el archivo de referencia y tus propios recursos, el agente analiza el gancho, el orden de la información, el ritmo visual y la llamada a la acción. Antes de producir el vídeo, indica qué conservará y qué sustituirá.

Es útil para explicaciones con texto animado, demostraciones de SaaS o de aplicaciones y anuncios creados con materiales de producto que ya tienes. Puedes editar por separado el texto, los subtítulos, la locución y los fragmentos creados como elementos independientes. Para cambiar texto incrustado en imágenes generadas por IA, hay que modificar las imágenes correspondientes.

> «Usa reference.mp4 como referencia para crear un vídeo promocional vertical de 30 segundos. Conserva el gancho, el estilo tipográfico y el ritmo, pero usa mi producto y mis grabaciones de pantalla. Enséñame primero el análisis y el plan de producción».

Necesitas un archivo de vídeo que el agente pueda leer. No hay una función integrada para descargar vídeos desde enlaces compartidos en redes sociales. No se garantiza reproducir con exactitud los movimientos de cámara, las actuaciones de personas reales ni el vídeo fotograma a fotograma. Consulta el [flujo de trabajo para recrear vídeos de referencia](./resources/builtin/marketplace/agents/79df9cc89f5f/skills/video-craft/references/reference-recreation.md).

---

## Mantenga el trabajo en movimiento

Terminar una tarea es solo el comienzo. Orkas también está diseñado para el trabajo que necesita continuidad.

- **Proyectos** — Los objetivos, las reglas, la memoria y los archivos se comparten dentro del proyecto. Cada conversación nueva puede retomar el trabajo sin que tengas que volver a explicar el contexto.
- **Tareas pendientes y Auto-advance** — Puedes asignar tareas del proyecto a personas o agentes. Al activar Auto-advance, el equipo pasa por su cuenta a la siguiente tarea y te entrega el resultado para que lo revises.
- **Automatizaciones programadas** — Ejecuta tareas cada hora, día, semana o mes. Orkas funciona en tu ordenador. Desde la versión 1.9, al reactivarse el ordenador o iniciarse Orkas, cada automatización recupera solo la ejecución omitida más reciente de las últimas 12 horas.
- **Conectores** — Conecta Gmail, Google Calendar, Sheets, Drive, Notion, Slack, Shopify, Stripe y otros servicios. Por defecto, Orkas te consulta antes de enviar, publicar o eliminar algo.
- **Aplicaciones** — Describe la herramienta que necesitas y Orkas la crea como una aplicación local dentro de la aplicación de escritorio. En la versión instalable, quienes tengan un plan de pago también pueden publicarla como una aplicación web con un enlace público.
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
- **Almacenamiento local por defecto** — Las conversaciones, los archivos, las bases de conocimiento y los agentes personalizados se guardan por defecto en tu ordenador. En la versión instalable puedes activar la sincronización en la nube. Si usas tu propia clave, las peticiones al modelo van directamente de tu ordenador al proveedor; el modelo integrado de Orkas usa un servicio gestionado por Orkas.
- **Cambia de modelo en cualquier momento** — El comandante y los agentes integrados comparten la configuración del modelo: puedes elegir el modelo Orkas integrado, tu propio proveedor o un punto de conexión local. Los agentes de CLI externos conservan su propia configuración.
- **Agentes que aprenden con la práctica** — Cada agente conserva sus propias habilidades y memoria de forma privada. Cuando la aplicación está inactiva, una revisión en segundo plano examina la actividad nueva y puede mejorar la autoevaluación, los métodos reutilizables y las habilidades adquiridas.
- **Código abierto y auditable** — La licencia MIT permite inspeccionar cómo están implementados Orkas, sus agentes y sus habilidades.

> ⭐ Si Orkas es útil para usted, una estrella ayuda a más personas a encontrar el proyecto.

---

## Descarga

| | Versión instalable (recomendada) | Versión desde el código fuente |
| --- | --- | --- |
| Las plataformas | macOS 12+ (Apple Silicon e Intel), Windows 10+ | macOS, Windows, glibc 2.34+ Linux x64/arm64 |
| Cuenta | 500 créditos gratis al iniciar sesión | No hace falta una cuenta |
| Modelos | Modelo Orkas integrado o tus propias claves | Tus propias claves o un punto de conexión a un modelo local |
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
| **Claude Code** | Agente de programación de Anthropic basado en modelos Claude, disponible en el terminal, el IDE, el escritorio y la web. | No tienes que elegir: Orkas ejecuta Claude Code como parte del equipo. Además, ofrece un equipo que no depende de un solo modelo y se ocupa de tareas que van más allá del código, como investigación, contenidos o vídeo. Los proyectos, las tareas pendientes y las automatizaciones permiten dar continuidad al trabajo. [Orkas frente a Claude Code →](https://orkas.ai/compare/orkas-vs-claude-code/?source=gh-orkas) |
| **Codex** | Agente de programación de OpenAI, disponible en el terminal, el editor y la nube. | No tienes que elegir: Orkas ejecuta Codex como un agente más, junto a Claude Code y OpenCode. El comandante puede asignar la programación a Codex y la revisión a otro agente, y después completar las partes del lanzamiento que no son código: documentación, publicaciones y vídeos. [Orkas frente a Codex →](https://orkas.ai/compare/orkas-vs-codex/?source=gh-orkas) |
| **Claude Cowork** | Agente de Anthropic para el trabajo diario, ahora integrado en Claude. Está disponible en escritorio, web y móvil con un plan de pago de Claude. Por defecto, se ejecuta en la nube de Anthropic y usa modelos Claude. | Alternativa de código abierto (MIT) a Claude Cowork. Puedes empezar gratis con 500 créditos. Los agentes se ejecutan en tu ordenador y los datos se guardan en local por defecto. Puedes usar el modelo Orkas integrado, una clave de tu proveedor o un punto de conexión local. El comandante también puede coordinar agentes de CLI como Claude Code y Codex. A cambio, Orkas necesita que tu ordenador no entre en suspensión, mientras que las tareas de Cowork en la nube pueden seguir sin él. [Alternativas a Claude Cowork →](https://orkas.ai/compare/claude-cowork-alternatives/?source=gh-orkas) |
| **Manus** | Un agente de IA que planifica y ejecuta tareas en la nube de Manus por defecto. La aplicación de escritorio de Manus Studio (macOS y Windows) también puede trabajar en una carpeta que elija, con tareas aún planeadas en la nube. | Una alternativa de código abierto (MIT) a Manus. Orkas ejecuta sus agentes en su computadora y mantiene sus datos locales por defecto, con el modelo Orkas incorporado, sus propias claves de proveedor o un punto final local. Proyectos, tareas y automatizaciones mantienen el trabajo en movimiento. La compensación: Orkas necesita que su computadora esté despierta, mientras que las tareas en la nube de Manus pueden seguir funcionando sin ella.[Alternativa Manus de código abierto →](https://orkas.ai/open-source-manus-alternative/?source=gh-orkas) |
| **LangChain** | Entorno de desarrollo para aplicaciones y agentes con LLM que se integra mediante código en aplicaciones Python o JavaScript. | Orkas es una aplicación de escritorio que manejas por chat. Los datos se guardan en local por defecto. |
| **CrewAI** | Marco de trabajo para coordinar agentes autónomos mediante equipos y roles definidos en código Python. | Orkas lleva la coordinación multiagente al escritorio, con proyectos, tareas pendientes, automatizaciones y mecanismos para que cada agente aprenda con la práctica. |
| **OpenClaw** | Plataforma de agentes personales con integración de canales de mensajería, enrutamiento entre agentes y subagentes. | Orkas ofrece un espacio de trabajo de escritorio orientado a entregar resultados, con especialistas integrados y coordinación de agentes de CLI como Claude Code, Codex y OpenCode. OpenClaw también puede incorporarse al equipo. |
| **Hermes-Agent** | Agente de Nous Research que mejora con el uso, con memoria y habilidades, disponible como CLI, pasarela de mensajería y aplicación de escritorio. | El comandante de Orkas coordina a varios especialistas y agentes externos de CLI; Hermes-Agent también puede incorporarse al equipo. |

**Orkas es para ti si** quieres que un equipo de agentes colabore, dé continuidad al trabajo durante varios días y guarde por defecto los datos, las claves y los agentes en tu propio disco.

**No para ti si** Sólo quieres un chatbot universal, o una biblioteca de código puro para incrustar en tu propia aplicación.

**¿Estás eligiendo un agente de programación?** [Codex frente a OpenCode](https://orkas.ai/compare/codex-vs-opencode/?source=gh-orkas) · [Claude Code frente a Codex y OpenCode](https://orkas.ai/compare/claude-code-vs-codex-vs-opencode/?source=gh-orkas) · [Alternativas a Claude Code](https://orkas.ai/compare/claude-code-alternatives/?source=gh-orkas)

**Comparaciones detalladas →** [Frente a Claude Code](https://orkas.ai/compare/orkas-vs-claude-code?source=gh-orkas) · [Frente a Codex](https://orkas.ai/compare/orkas-vs-codex?source=gh-orkas) · [Frente a Cline](https://orkas.ai/compare/orkas-vs-cline?source=gh-orkas) · [Frente a LangChain](https://orkas.ai/compare/orkas-vs-langchain?source=gh-orkas) · [Frente a ChatGPT](https://orkas.ai/compare/orkas-vs-chatgpt?source=gh-orkas) · [Frente a OpenClaw](https://orkas.ai/compare/orkas-vs-openclaw?source=gh-orkas) · [Frente a Hermes-Agent](https://orkas.ai/compare/orkas-vs-hermes-agent?source=gh-orkas)

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

Para ejecutar Orkas desde el código fuente en Linux necesitas glibc 2.34 o posterior. No se admiten Alpine ni otras distribuciones basadas en musl. Al arrancar desde el código fuente por primera vez, se descargan y verifican el entorno de ejecución de whisper.cpp correspondiente a tu arquitectura y el modelo multilingüe, para transcribir voz en local.

En el primer arranque, `run.sh` / `run.cmd` instalan las dependencias de npm fijadas en el archivo de bloqueo y preparan versiones fijadas de Python, uv, Node, el modelo de representaciones vectoriales (unos 95 MB), OfficeCLI, FFmpeg, whisper.cpp y el modelo de voz multilingüe. En Linux también se comprueba la compatibilidad de los módulos nativos de la plataforma y del entorno de ejecución de Whisper con la ABI de Electron antes de abrir la aplicación. El OCR y los paquetes de Python específicos de cada habilidad se instalan en entornos locales aislados la primera vez que se usan las funciones correspondientes. El primer arranque crea un espacio de trabajo en `~/.orkas/` (macOS / Linux) o en `<smallest non-system drive>:\.orkas\` (Windows, en la unidad más pequeña que no sea la del sistema). Después, ve a **Configuración → Proveedores de IA** para configurar una clave de API u OAuth.

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

La biblioteca divide los documentos en párrafos y crea un índice vectorial local en SQLite. El modelo de representaciones vectoriales se ejecuta en tu ordenador. Con `library`, los agentes pueden listar archivos, buscar pasajes relacionados y leer el contenido original de la biblioteca global o del proyecto actual. Las conversaciones anteriores se buscan por separado con `chat_history`.

Consulta la [memoria por ámbitos](./src/main/features/memory.ts), la [extracción de documentos](./src/main/util/file_to_chunks.ts), las [herramientas de la biblioteca](./src/main/model/core-agent/kb-tools.ts) y la [búsqueda en conversaciones](./src/main/model/core-agent/chat-history-tools.ts).

### Límites de ejecución y recuperación

Los bloqueos de sesión y los límites de concurrencia controlan cuánto trabajo puede ejecutarse en paralelo. Los límites de rondas de herramientas, los puntos de control de progreso, la detección de llamadas repetidas y la supervisión de inactividad por fases ayudan a controlar tareas estancadas o repetidas. Las tareas asignadas a agentes identificados por su nombre se pueden rastrear y cancelar individualmente. Una tarea aceptada o en cola no cuenta como terminada.

Consulta los [límites por actor](./src/main/features/group_chat/actor-budgets.ts), el [entorno de ejecución del agente](./src/core-agent/src/agent/runner.ts) y el [adaptador de modelos para escritorio](./src/main/model/core-agent/client.ts).

### Aprender de la actividad

La revisión en segundo plano comprueba si hay actividad nueva de los agentes cuando la aplicación está inactiva, respetando unos intervalos y límites de ejecución. Puede actualizar la autoevaluación (`COMPETENCE.md`), los métodos reutilizables (`LEARNING_STRATEGIES.md`) o las habilidades aprendidas, o concluir que no hay nada que guardar. Se programa según la actividad nueva, no por el número de tareas completadas.

Consulta la [programación de revisiones](./src/main/features/reflection-orchestrator.ts) y las [instrucciones de revisión](./src/core-agent/src/evolution/metacognition.ts).

---

## Las preguntas frecuentes

**¿Qué es Orkas?**
Orkas es una aplicación de escritorio multiagente de código abierto (MIT) que prioriza el trabajo en local. Su comandante divide tus objetivos en tareas pendientes y coordina a 16 agentes especializados integrados, además de Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent, para entregar archivos terminados.

**¿Necesito una llave de API?**
No. La versión instalable incluye 500 créditos para usar el modelo Orkas integrado. Cuando se agoten, puedes comprar créditos, elegir un plan de pago o añadir tus propias claves de proveedor. El proveedor cobra su uso por separado.

**¿Orkas es un modelo de lenguaje de gran tamaño (LLM) que se ejecuta en local?**
No. Orkas se ejecuta en tu ordenador y llama al modelo que elijas: el modelo Orkas integrado, uno conectado con tu clave de API o un modelo disponible en un punto de conexión local. Orkas coordina agentes y herramientas, pero no es un modelo.

**¿Puede Orkas responder preguntas de mis documentos, con citas?**
Sí. Añade tus PDF y documentos a la biblioteca local. Orkas puede buscarlos y citar los fragmentos originales para que puedas abrir la fuente y comprobar la respuesta. El índice se crea en tu ordenador.

**¿Puedo usar modelos locales como Ollama o LM Studio?**
Sí. Ve a **Ajustes de la cuenta → Modelos → Chat → Añadir modelo → Personalizado** y elige **Compatible con OpenAI** o **Compatible con Anthropic**. Introduce la URL base, el identificador exacto del modelo y la clave de API. Después, elige el modelo guardado en el selector de modelos de la tarea.

**¿Dónde se guardan mis claves de API y mis datos?**
Los datos y las claves se guardan por defecto en tu ordenador. Las claves de tus proveedores se cifran en local y no se sincronizan con la nube. Si usas tu propia clave, las peticiones al modelo van directamente de tu ordenador al proveedor. El modelo integrado usa el servicio gestionado por Orkas. Si utilizas la sincronización opcional en la nube o los proyectos compartidos de la versión instalable, los datos seleccionados se guardan en servidores de Orkas. [Seguridad y tratamiento de los datos →](https://orkas.ai/security/?source=gh-orkas)

**¿Se puede usar Orkas completamente sin conexión?**
La versión desde el código fuente puede funcionar completamente sin conexión con un punto de conexión a un modelo local. La versión instalable requiere iniciar sesión, y las llamadas a modelos en la nube requieren conexión a Internet.

**¿Sigue funcionando cuando mi ordenador está apagada?**
No. Tanto Auto-advance como las automatizaciones programadas requieren que el ordenador esté activo y que Orkas se esté ejecutando. Desde la versión 1.9, al reactivarse el ordenador o iniciarse Orkas, cada automatización recupera solo la ejecución omitida más reciente de las últimas 12 horas.

**¿Puedo crear y publicar aplicaciones?**
Sí. Las aplicaciones locales que se ejecutan dentro de Orkas son gratuitas. Publicar aplicaciones web mediante un enlace público requiere un plan de pago: Lite permite publicar 5, Pro 8 y Max 15. Las aplicaciones web públicas no incluyen todas las funciones de la aplicación de escritorio de Orkas.

**¿Necesito una cuenta de Orkas?**
La versión instalable requiere iniciar sesión la primera vez que se abre. La versión desde el código fuente de este repositorio no tiene un módulo de cuentas: al iniciarla, se accede directamente a la aplicación.

**¿Puede Orkas trabajar con Claude Code y otros agentes de CLI?**
Sí. Orkas puede ejecutar cinco agentes de CLI externos como subprocesos locales: Claude Code, Codex, OpenCode, OpenClaw y Hermes-Agent. También puede integrar herramientas de código abierto como HyperFrames y coordinarlas desde una misma conversación.

**¿En qué se diferencia Orkas de Claude Code / Codex / CrewAI / LangChain?**
Claude Code y Codex son agentes de programación. Orkas puede ejecutar los dos como miembros de su equipo, así que no tienes que elegir entre ellos. CrewAI y LangChain son marcos de trabajo orientados al código. Orkas es una aplicación de escritorio de código abierto en la que un comandante coordina agentes especializados y agentes de CLI. Puedes elegir entre distintos proveedores de modelos, y los datos y las claves se guardan en local por defecto. [Consulta las comparaciones completas](https://orkas.ai/compare/?source=gh-orkas).

**¿Qué plataformas apoya Orkas?**
Hay instaladores para macOS 12+ (Apple Silicon e Intel) y Windows 10+. En Linux x64/arm64 con glibc 2.34 o posterior aún no hay instalador: debes ejecutar Orkas desde el código fuente. El primer arranque prepara una versión fija del entorno de ejecución de whisper.cpp para la transcripción local. No se admiten Alpine ni otras distribuciones basadas en musl. Para ejecutar desde el código fuente necesitas Node 22.12 o posterior. Python 3 y las herramientas de compilación de C/C++ solo son necesarios si un paquete nativo de npm no tiene un binario precompilado compatible y hay que recompilarlo en el equipo.

**¿Es Orkas libre y de código abierto?**
Sí. La aplicación se distribuye con licencia MIT y es gratuita. La versión instalable incluye 500 créditos. Los planes de pago parten de $11.99 al mes y añaden créditos mensuales, sincronización en la nube, más proyectos compartidos y la posibilidad de publicar aplicaciones web. Si usas tus propias claves, tu proveedor te cobra el uso del modelo sin que Orkas añada ningún recargo. [Precios →](https://orkas.ai/pricing/?source=gh-orkas)

---

## Licencia

[MIT](./LICENSE)
