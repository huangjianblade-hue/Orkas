# Orkas

**Uma equipa de agentes de IA em código aberto no seu desktop transforma os seus objetivos em trabalho acabado e mantém-no em movimento.**

O Orkas é uma aplicação multiagente para computador, de código aberto (MIT), que dá prioridade à execução local e reúne uma equipa de assistentes de IA. Diga ao **Commander** o que precisa de fazer. Ele resolve muitas tarefas sozinho e, quando o trabalho é maior, divide-o em etapas e coordena os agentes especializados com os agentes pessoais e de programação que já utiliza: **Claude Code, Codex, OpenCode, OpenClaw e Hermes-Agent**.

O Orkas foi concebido para dar continuidade ao trabalho de um projeto, não apenas para responder a uma pergunta. Cada **projeto** reúne objetivos, regras, memória e ficheiros, permitindo retomar o trabalho numa nova conversa. As **tarefas** podem ser atribuídas a pessoas ou agentes. Com o **Auto-advance**, a equipa assume a tarefa seguinte sem intervenção. As **automatizações agendadas** repetem rotinas de hora a hora, diariamente, semanalmente ou mensalmente. Todos os seus dados ficam no seu computador e o trabalho concluído é-lhe entregue para revisão. Assim, pode confiar à Orkas as tarefas do seu negócio que exigem acompanhamento contínuo.

**[ — Descarregar Orkas para macOS e Windows](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** — gratuito, com 500 créditos para o modelo Orkas incorporado, então você não precisa de uma chave API para começar. Prefere suas próprias chaves? Claude · OpenAI · Gemini · DeepSeek · Kimi · GLM · Qwen · MiniMax · Doubao, ou um endpoint local compatível com OpenAI.

[![Download for macOS & Windows](https://img.shields.io/badge/Download-macOS%20%26%20Windows-5b57d6?style=for-the-badge)](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Orkas-AI/Orkas?style=flat&logo=github&label=Stars&color=yellow)](https://github.com/Orkas-AI/Orkas/stargazers)
[![Release](https://img.shields.io/github/v/release/Orkas-AI/Orkas?color=blue)](https://github.com/Orkas-AI/Orkas/releases)
[![X: @leochenpm](https://img.shields.io/badge/X-%40leochenpm-black?logo=x)](https://x.com/leochenpm)
[![Website: orkas.ai](https://img.shields.io/badge/Website-orkas.ai-5b57d6)](https://orkas.ai/?source=gh-orkas)

[English](./README.en.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [한국어](./README.ko.md) · [Español](./README.es.md) · [Bahasa Indonesia](./README.id.md) · [Español (Latinoamérica)](./README.es-419.md) · [Русский](./README.ru.md) · [Português (Brasil)](./README.pt-BR.md) · [Türkçe](./README.tr.md) · [繁體中文](./README.zh-TW.md) · [Tiếng Việt](./README.vi.md) · [Deutsch](./README.de.md) · [ไทย](./README.th.md) · [Français](./README.fr.md) · [Italiano](./README.it.md) · [Português (Portugal)](./README.pt-PT.md) · [العربية](./README.ar.md)

---

https://github.com/user-attachments/assets/4f8b16c8-a192-45a4-b19f-80e8d02c3dab

![Orkas desktop      conversa de tarefas e resultados](./resources/app-ui/task-en.png)

---

## O que a equipa pode entregar

- **Vídeos, locuções e imagens** — VideoStudio, VoiceStudio, ImageStudio
- **Relatórios de investigação, auditorias de SEO e estudos de mercado** — DeepResearcher, SeoGeoAgent, StockAnalyser
- **Publicações, artigos, sínteses e diapositivos** — ContentWriter, PptMaker
- **Sítios Web, interfaces e código** — UIDesigner, ProductDeveloper
- **Ficheiros de Word, Excel, PowerPoint e PDF** — OfficeWorker
- **Comércio eletrónico** — cinco agentes tratam da seleção de produtos, da redação de textos de produto, da análise de avaliações, da análise do negócio e da gestão de produtos
- **Tarefas complexas que envolvem vários agentes** — o coordenador divide o trabalho, atribui cada parte ao agente adequado e reúne os resultados. De um estudo de mercado, por exemplo, podem resultar um relatório, diapositivos e um vídeo de lançamento

A aplicação inclui 16 agentes especializados, cada um com as suas competências, memória e ferramentas. Na [biblioteca de agentes](https://orkas.ai/views/marketplace/gs/agents/?source=gh-orkas) pode escolher entre mais de 30. Também pode descrever a função pretendida e pedir ao coordenador que crie um agente à medida.

<details>
<summary><b>Todos os 16 agentes incorporados</b></summary>

| Área | Agente . | O que ele oferece |
| --- | --- | --- |
| Pesquisa e análise | **DeepResearcher** | Pesquisa baseada em evidências com fontes verificadas, contradições marcadas e relatório auditável |
| | **SeoGeoAgent** | Dê-lhe uma URL — auditoria técnica, qualidade do conteúdo, Core Web Vitals, citabilidade da resposta AI (GEO), lista de correções classificada |
| | **StockAnalyser** | Investigação sobre ações, ecrãs de fatores, backtests e verificações de risco de carteira, com painéis rastreáveis |
| Conteúdo & mídia | **ContentWriter** | Postos, artigos, newsletters e estudos de caso prontos para publicação a partir de um objetivo, fontes ou um esboço aproximado |
| | **PptMaker** | Decks de PPTX editáveis e revisaveis a partir de um tópico, esquema ou documento |
| | **ImageStudio** | Posters, capa, imagens sociais e infográficos |
| | **VideoStudio** | Narrativa, apresentadores de IA, legendas e dobras, clips destacados, localização e recriação de vídeo de referência com seu próprio conteúdo e imagens |
| | **VoiceStudio** | Narrativa, áudio multi-voz, transcrições e subtítulos, edição e mistura de áudio |
| | **UIDesigner** | Interfaces de interface editáveis, HTML-primeiro a partir de objetivos de produtos, PRDs, captura de tela ou material Figma |
| Construção e escritório | **ProductDeveloper** | Engenharia de re-consciência      implementar um PRD, corrigir erros, refactor, revisão, com resultados verificáveis |
| | **OfficeWorker** | Criar, editar, verificar e entregar ficheiros Word / Excel / PowerPoint / PDF, um por vez ou em lotes |
| Comércio eletrônico | **ECommerceResearcher** | Seleção de produtos por orçamento, mercado e limites de abastecimento    candidatos, razões de rejeição, planos de validação |
| | **ECommerceWriter** | Títulos, páginas de detalhes, FAQs, cópias de imagem e scripts de vídeo na voz da sua marca |
| | **ECommerceReviewer** | Análise de opiniões e reputação   temas dos clientes, causas fundamentais de críticas ruins, prioridades |
| | **ECommerceAnalyzer** | Vendas, lucros, anúncios, reembolsos e inventário das suas exportações |
| | **ECommerceOperator** | Planeja alterações de catálogo, preço, promoção e inventário; executa apenas através de ferramentas que você conecta |

Mais sobre cada agente[orkas.ai/agentes](https://orkas.ai/agents/?source=gh-orkas)

</details>

### Recrear um vídeo de referência com o seu próprio conteúdo

**VideoStudio** Pode recriar a estrutura narrativa, estilo visual e ritmo de edição de um vídeo viral usando seu próprio produto, roteiro e imagens. Forneça um arquivo de vídeo de referência e seus ativos: o agente analisa o gancho, ordem de informações, batidas visuais e chamada à ação, depois propõe o que preservar e o que substituir antes da produção.

Isso funciona melhor para explicadores de motion-graphic, SaaS ou demonstrações de aplicações e anúncios de produtos construídos a partir de suas imagens existentes.

> "Use o reference.mp4 como referência para uma promoção vertical de 30 segundos. Mantenha seu gancho, tipografia e ritmo, substitua o conteúdo com meu produto e gravações de tela, e me mostre a descomposição e planejar primeiro".

Comece com um arquivo de vídeo que o agente possa ler; download de links compartilhados em plataformas sociais não está incorporado.[fluxo de trabalho de referência e recreação](./resources/builtin/marketplace/agents/79df9cc89f5f/skills/video-craft/references/reference-recreation.md).

---

## Mantém o trabalho em movimento

Uma tarefa é um bom começo.

- **Projeto** — metas e regras, memória e ficheiros que todas as conversas no projeto começam a partir, para que você nunca abrevia do zero.
- **Ações e Avanços Automáticos** — cada projeto tem uma lista de tarefas para pessoas e agentes; com o Auto-advance, a equipa pega o próximo item por conta própria e traz o trabalho acabado para sua revisão.
- **Automatizações agendadas** — Execute tarefas de hora a hora, diariamente, semanalmente ou mensalmente. O Orkas funciona no seu computador. Desde a versão 1.9, quando o computador retoma da suspensão ou o Orkas é iniciado, cada automatização recupera apenas a última execução que não ocorreu nas 12 horas anteriores.
- **Conectores** — Gmail, Google Calendar, Sheets and Drive, Notion, Slack, Shopify, Stripe e muitos outros.
- **Aplicações** — Descreva a ferramenta de que precisa. O Orkas cria uma aplicação local que pode usar dentro da aplicação de computador. Na versão instalável, as pessoas com um plano pago também a podem publicar como aplicação Web com uma ligação pública.
- **Projetos partilhados** (versão instalável) — Convide colegas ou assistentes virtuais e atribua cada tarefa a uma pessoa ou a um agente.

> [!NOTE]
> Os projetos partilhados, a sincronização em nuvem e a publicação de aplicações web estão apenas no pacote de aplicações.**[baixar Orkas para macOS e Windows](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** (gratuito, com 500 créditos para começar).

---

## Execute o código Claude, Codex, OpenCode, OpenClaw e Hermes-Agent juntos

A Orkas administra os agentes de CLI que já instalou como sessões locais, ao lado dos seus próprios especialistas**Claude Code, Codex e OpenCode**, e os agentes pessoais** OpenClaw e Hermes-Agent**O Comandante entrega a cada um a parte que é melhor e mantém um plano em todos eles, para que um único chat possa corrigir o bug, rever as alterações e redigir a nota de lançamento. Ferramentas de código aberto como HyperFrames plug-in da mesma maneira.

[Usando o Claude Code e o Codex juntos →](https://orkas.ai/blog/claude-code-codex-together/?source=gh-orkas)

---

## Por que Orkas

- **Um comandante que planeja, delega e faz o resto** — que descompõe os objectivos, escolhe os agentes, habilidades, conectores e ferramentas adequados e lida sozinho com a análise, a escrita, a investigação e o trabalho de arquivo quando nenhum especialista é mais adequado.
- **Armazenamento local por predefinição** — As conversas, os ficheiros, as bases de conhecimento e os agentes personalizados são guardados no seu computador por predefinição. Na versão instalável, pode ativar a sincronização com a nuvem. Com a sua própria chave, os pedidos ao modelo seguem diretamente do computador para o fornecedor; o modelo integrado do Orkas usa um serviço gerido pela Orkas.
- **Qualquer modelo, muda a qualquer momento.** — o Comandante e os agentes integrados compartilham uma configuração de modelo: o modelo Orkas integrado, o seu próprio fornecedor ou um ponto final local.
- **Agentes que melhoram** — As revisões de antecedentes examinam novas atividades quando o aplicação está inactivo e podem refinar a autoavaliação, os métodos reutilizáveis e as habilidades aprendidas.
- **código aberto, sem caixa preta** — Leia exatamente o que os Orkas e todos os agentes e habilidades fazem.

> ⭐ Se a Orkas for útil para você, uma estrela ajuda mais pessoas a encontrar o projeto.

---

## Descarga

| | Aplicação embalada (recomendada) | Execução a partir da fonte |
| --- | --- | --- |
| Plataformas | macOS 12+ (Apple Silicon & Intel), Windows 10+ | macOS, Windows, glibc 2.34+ Linux x64/arm64 |
| Conta | 500 créditos ao iniciar sessão | Não é necessário ter conta |
| Modelos | Modelo Orkas integrado, ou suas próprias chaves | As suas próprias chaves ou um ponto de saída local |
| Inclui também | Colaboração de projetos, publicação de aplicações, sincronização em nuvem e muito mais | — |
| - Apanha-o. | **[Descarregar Orkas](https://orkas.ai/download/?source=gh-orkas&entry_point=github_readme&download=1)** | [Começo rápido](#começo-rápido) |

O link de download detecta o seu sistema e inicia o instalador certo.

---

## Para que as pessoas usam

- **Conteúdo de comercialização** — lançar vídeos, páginas de produtos, publicações e newsletters com a sua voz.[Escrita de conteúdo](https://orkas.ai/use/content-writing/?source=gh-orkas) · [Vídeos](https://orkas.ai/use/make-videos/?source=gh-orkas)
- **Operações de armazenamento** — Informações semanais sobre as vendas, respostas de revisão, listagem e verificações dos concorrentes.[Comércio eletrônico](https://orkas.ai/use/ecommerce/?source=gh-orkas)
- **Investigação e relatórios** — relatórios e decks, sob demanda ou semanalmente.[Pesquisa](https://orkas.ai/use/researchers/?source=gh-orkas) · [Análise de dados](https://orkas.ai/use/data-analysis/?source=gh-orkas)
- **- Falar com os seus documentos .** — respostas baseadas nos seus próprios ficheiros, com citações de volta às passagens da fonte.[Chat com documentos](https://orkas.ai/use/chat-with-documents/?source=gh-orkas)
- **Trabalho com clientes** — relatórios de reuniões, relatórios mensais de clientes e de actualização em seu modelo.[Modelo de relatório mensal do cliente](https://orkas.ai/blog/monthly-client-report-template/?source=gh-orkas)
- **Lançamento de produtos** — páginas de destino, correções de erros com testes, registros de mudanças e postos de lançamento.[Desenvolvedores](https://orkas.ai/use/developers/?source=gh-orkas)
- **Crie um aplicação** — Calculadores de citações, formulários de reserva, ferramentas internas.[Crie aplicações](https://orkas.ai/use/build-apps/?source=gh-orkas)
- **Pequenas equipes** — um projecto para pessoas e agentes.[Pequenas equipes](https://orkas.ai/use/small-teams/?source=gh-orkas)

---

## Como as orcas comparam

| Ferramenta | O que é | Como as orcas diferem |
| --- | --- | --- |
| **Claude Code** | A ferramenta de codificação agente da Anthropic — no terminal, IDE, desktop e web, construída sobre modelos Claude. | Não quer-ou: a Orkas executa o Claude Code como um de seus agentes. Ao redor dele, a Orkas adiciona uma equipa modelo-agnóstica para o trabalho além do código — pesquisa, conteúdo, vídeo e mais    ‡ com projetos, tarefas e automações que mantêm em movimento.[Orkas vs Claude Code →](https://orkas.ai/compare/orkas-vs-claude-code/?source=gh-orkas) |
| **Codex** | O agente de codificação da OpenAI está no terminal, o seu editor e na nuvem. | Não é um ou dois: a Orkas executa o Codex como um de seus agentes, ao lado do Claude Code e OpenCode. O Comandante pode entregar a codificação ao Codex e a revisão a outro agente, depois cobrir a metade não-código de um lançamento — documentos, postos de lançamento e vídeos.[Orkas vs Codex →](https://orkas.ai/compare/orkas-vs-codex/?source=gh-orkas) |
| **Claude Cowork** | Agente da Anthropic para o trabalho cotidiano, agora parte de Claude — em desktop, web e móvel com um plano Claude pago. | Uma alternativa de código aberto (MIT) para Claude Cowork que é gratuita para começar, com 500 créditos. Orkas executa seus agentes em seu computador e mantém seus dados locais por padrão, com o modelo Orkas integrado, suas próprias chaves de fornecedor ou um endpoint local. O Comandante também pode trazer Claude Code, Codex e outros agentes CLI. A troca: Orkas precisa do seu computador acordado, enquanto as tarefas da nuvem de Cowork podem continuar a funcionar sem ele.[Claude Cowork alternativas →](https://orkas.ai/compare/claude-cowork-alternatives/?source=gh-orkas) |
| **Manus** | Um agente de IA que planeja e executa tarefas na nuvem do Manus por padrão. O aplicação de desktop do Manus Studio (macOS e Windows) também pode trabalhar em uma pasta que você escolher, com tarefas ainda planejadas na nuvem. | O Orkas executa seus agentes no seu computador e mantém seus dados locais por padrão, com o modelo Orkas integrado, suas próprias chaves de fornecedor ou um endpoint local. Projetos, tarefas e automações mantêm o trabalho em movimento. A compensação: a Orkas precisa que o seu computador esteja acordado, enquanto as tarefas da nuvem do Manus podem continuar funcionando sem ele.[Alternativa Manus de código aberto →](https://orkas.ai/open-source-manus-alternative/?source=gh-orkas) |
| **LangChain** | Framework de desenvolvimento de aplicações e agentes com LLM, que se integra por código em aplicações Python ou JavaScript. | O Orkas é uma aplicação de computador que se controla por conversa. Os dados são guardados localmente por predefinição. |
| **CrewAI** | Um framework Python para orquestar agentes autônomos de roteiro      você define equipes e agentes em código. | A Orkas traz a orquestração multi-agente para um aplicação de desktop, com projetos, tarefas, automações e auto-melhoria por agente incorporada. |
| **OpenClaw** | Uma plataforma de agente pessoal com integrações de mensagens, roteamento multi-agente e sub-agentes. | A Orkas fornece um espaço de trabalho de desktop para entregas acabadas, com especialistas e coordenação em todo o Claude Code, Codex, OpenCode e outros agentes CLI. |
| **Hermes-Agent** | Agente de auto-melhoria da Nous Research      1 agente com memória e habilidades, disponível como CLI, um portal de mensagens e um aplicação de desktop. | A Orkas coordena uma equipa: o Comandante dirige muitos especialistas e outros agentes da CLI, e o Hermes-Agent entra como um deles. |

**O Orkas é para ti se** Quer uma equipa de agentes em vez de um assistente, trabalho que se move durante dias, e os seus dados, chaves e agentes no seu próprio disco.

**Não para ti se** Só queres um único chatbot universal, ou uma biblioteca de código pura para integrar no teu próprio aplicação.

**Escolher entre agentes de codificação?** [Codex versus OpenCode](https://orkas.ai/compare/codex-vs-opencode/?source=gh-orkas) · [Claude Code vs Codex versus OpenCode](https://orkas.ai/compare/claude-code-vs-codex-vs-opencode/?source=gh-orkas) · [Alternativas do Claude Code](https://orkas.ai/compare/claude-code-alternatives/?source=gh-orkas)

**Comparativos completos lado a lado →** [Contra Claude Code](https://orkas.ai/compare/orkas-vs-claude-code?source=gh-orkas) · [Contra o Codex](https://orkas.ai/compare/orkas-vs-codex?source=gh-orkas) · [Contra Cline](https://orkas.ai/compare/orkas-vs-cline?source=gh-orkas) · [Contra a LangChain](https://orkas.ai/compare/orkas-vs-langchain?source=gh-orkas) · [contra o ChatGPT](https://orkas.ai/compare/orkas-vs-chatgpt?source=gh-orkas) · [Contra OpenClaw](https://orkas.ai/compare/orkas-vs-openclaw?source=gh-orkas) · [Contra Hermes-Agent](https://orkas.ai/compare/orkas-vs-hermes-agent?source=gh-orkas)

---

## Começo rápido

Preferes usar um instalador? Consulta a secção [Transferências](#descarga). Para executar a partir do código-fonte:

**Requisitos**: Node 22.12+ · macOS / Windows 10+ / glibc 2.34+ Linux x64 ou arm64. Mantenha Python 3 e uma cadeia de ferramentas de construção C/C++ disponíveis para o incomum fallback de construção de código-fonte do módulo nativo.

```bash
git clone https://github.com/Orkas-AI/Orkas.git
cd Orkas
./run.sh           # macOS / Linux
run.cmd            # Windows
```

Para executar o Orkas a partir do código-fonte em Linux, é necessário glibc 2.34 ou posterior. Não são suportadas a distribuição Alpine nem outras baseadas em musl. No primeiro arranque a partir do código-fonte, o Orkas descarrega e verifica o ambiente de execução do whisper.cpp adequado à arquitetura do computador e o modelo multilingue para transcrição de voz local.

No primeiro arranque, `run.sh` / `run.cmd` instala as dependências npm fixadas no ficheiro de bloqueio e prepara as versões definidas de Python, uv, Node, do modelo de embeddings (cerca de 95 MB), de OfficeCLI, FFmpeg, whisper.cpp e do modelo de voz multilingue. Em Linux, antes de abrir a aplicação, o arranque verifica os módulos nativos da plataforma e o ambiente de execução do Whisper com a ABI do Electron. Os pacotes Python para OCR e os específicos de cada Skill são instalados em ambientes locais isolados na primeira utilização das funcionalidades correspondentes. No primeiro arranque é criado um espaço de trabalho em `~/.orkas/` (macOS / Linux) ou `<smallest non-system drive>:\.orkas\` (Windows). Em seguida, abre **Definições → Fornecedores de IA** para configurar uma chave de API ou OAuth.

Se ocorrer um erro nas dependências nativas, usa o Node.js 24 LTS (versão mínima: 22.12.0) e executa
`npm run native:repair` nesta pasta do código-fonte. O comando repõe as dependências opcionais,
repara a compilação do SQLite para Electron e verifica SQL e sqlite-vec. O comando
também prepara o ambiente de execução Node incluído e verifica sharp num processo separado antes de indicar que a reparação foi concluída com êxito.
Utilização`npm run native:check`para um cheque sem instalação.
Veja o[script de verificação de dependência nativa](./scripts/verify-native-dependencies.cjs)para os controlos efectuados.

---

## Como funciona

### Roteamento de tarefas

O Comandante encarrega-se do trabalho geral e delega o trabalho especializado através de três ferramentas:

- **`dispatch_to`** — Pode esperar o resultado ou correr assíncrono e notificar o Comandante quando a tarefa terminar.
- **`hand_off_to`** passa o trabalho que falta a um agente indicado pelo nome e termina o turno atual do Commander. O agente responde diretamente. Se for definido um passo de seguimento, o Commander pode retomar a tarefa mais abrangente mais tarde.
- **`run_worker`** — executa uma sub-tarefa anônima e isolada e retorna um resultado privado. Não recebe histórico de conversação ou habilidades de um agente nomeado.

As tarefas dos agentes nomeados e os trabalhadores anónimos têm controles de simultaneidade separados.[Implementação do envio](./src/main/features/group_chat/bus.ts)e[bloqueios de execução](./src/main/util/locks.ts).

### Gestão de contexto

O contexto de orçamentos de tempo de execução contra a capacidade de entrada utilizável do modelo selecionado, contabilização de pedidos, ferramentas e estado de tempo de execução persistente. Diálogo concluído usa uma janela limitada de história recente; tarefas ativas longas usam checkpoints para condensar mensagens de processo anteriores enquanto retêm trabalho recente. Leituras de ficheiros, alterações de arquivo e execuções de comandos também têm registros estruturados que podem sobreviver à compactação de contexto.

Veja[orçamentos de contexto](./src/core-agent/src/agent/context-budget.ts), [História da sessão e pontos de controlo](./src/core-agent/src/agent/session.ts)e[Registros de espaço de trabalho](./src/core-agent/src/agent/workspace-state.ts).

### Memória e Biblioteca

As notas duráveis mantêm as preferências dos usuários, os fatos do projeto e o conhecimento reutilizável de cada agente em escopo separado.

A biblioteca extrai parágrafos dos documentos e cria um índice vetorial local em SQLite. O modelo de representações vetoriais funciona no seu computador. Com `library`, os agentes podem listar ficheiros, procurar excertos relevantes e ler o conteúdo original na biblioteca global ou na do projeto atual. Para pesquisar conversas anteriores, usa-se `chat_history` separadamente.

Veja[Memória de alcance](./src/main/features/memory.ts), [Extração de documentos](./src/main/util/file_to_chunks.ts), [Ferramentas de biblioteca](./src/main/model/core-agent/kb-tools.ts)e[conversas de recuperação](./src/main/model/core-agent/chat-history-tools.ts).

### Limite de execução e recuperação

Os bloqueios de sessão e os limites de concurência ligam o trabalho paralelo. Orçamentos de rodada de ferramentas, pontos de controle de progresso, verificações repetidas de chamadas e vigilantes passivos conscientes de fase ajudam a conter corridas que impedem ou repetem o trabalho. As tarefas do agente nomeado podem ser rastreadas e canceladas individualmente; uma tarefa admitida ou em fila não é tratada como um resultado concluído.

Veja[orçamentos dos actores](./src/main/features/group_chat/actor-budgets.ts), o[tempo de execução do agente](./src/core-agent/src/agent/runner.ts)e o[adaptador de modelo de desktop](./src/main/model/core-agent/client.ts).

### Aprender com a atividade

A revisão em segundo plano analisa a nova atividade dos agentes quando a aplicação está inativa, com intervalos de espera e limites de execução. Pode atualizar a autoavaliação (`COMPETENCE.md`), métodos reutilizáveis (`LEARNING_STRATEGIES.md`) ou competências adquiridas. Pode também concluir que nada precisa de ser guardado. A revisão é agendada com base na nova atividade, não no número de tarefas concluídas.

Veja o[programação de reflexão](./src/main/features/reflection-orchestrator.ts)e[urgência de revisão](./src/core-agent/src/evolution/metacognition.ts).

---

## FAQ

**O que é o Orkas?**
O Orkas é uma aplicação multiagente para computador, de código aberto (MIT), que dá prioridade à execução local. O Commander divide o objetivo em tarefas e coordena 16 agentes especializados integrados, além de Claude Code, Codex, OpenCode, OpenClaw e Hermes-Agent, para entregar ficheiros prontos a usar.

**Preciso de uma chave de API?**
Não. A versão instalável inclui 500 créditos para usar o modelo integrado do Orkas. Quando os créditos se esgotarem, pode comprar mais, escolher um plano pago ou adicionar as suas próprias chaves de API. Os fornecedores externos cobram à parte.

**O Orkas é um modelo de linguagem de grande dimensão (LLM) que funciona localmente?**
Não. O Orkas funciona no computador e chama o modelo que escolher: o modelo integrado do Orkas, um modelo ligado através da sua chave de API ou um modelo acessível num endpoint local. O Orkas coordena agentes e ferramentas; não é um modelo.

**O Orkas pode responder a perguntas sobre os meus documentos com citações?**
Sim. Adicione ficheiros PDF e outros documentos à sua biblioteca local. O Orkas pode pesquisá-los e citar as passagens de origem nas respostas, para que possa consultar e verificar o original. O índice é criado no seu computador.

**Posso usar modelos locais como Ollama ou LM Studio?**
Sim. Abra **Definições da conta → Modelos → Conversa → Adicionar modelo → Personalizado** e selecione **Compatível com OpenAI** ou **Compatível com Anthropic**. Introduza o URL base, o identificador exato do modelo e a chave de API. Escolha o modelo guardado no seletor da tarefa.

**Onde estão as minhas chaves e dados da API?**
Por predefinição, os dados e as chaves ficam guardados no computador. As chaves dos seus fornecedores são cifradas localmente e não são sincronizadas com a nuvem. Ao usar a sua própria chave, os pedidos seguem diretamente do computador para o fornecedor. O modelo integrado usa um serviço gerido pela Orkas. Na versão instalável, se usar a sincronização opcional com a nuvem ou os projetos partilhados, os dados selecionados são guardados nos servidores da Orkas. [Segurança e tratamento de dados →](https://orkas.ai/security/?source=gh-orkas)

**O Orkas pode ser usado totalmente offline?**
A versão executada a partir do código-fonte funciona totalmente offline se estiver ligada a um endpoint de modelo local. A versão instalável exige o início de sessão; as chamadas a modelos na nuvem exigem uma ligação à Internet.

**Continua a funcionar quando o meu computador está desligado?**
Não. O Auto-advance e as automatizações agendadas requerem que o computador não esteja suspenso e que o Orkas esteja em execução. Desde a versão 1.9, quando o computador retoma da suspensão ou o Orkas é iniciado, cada automatização recupera apenas a última execução que não ocorreu nas 12 horas anteriores.

**Posso criar e publicar aplicações?**
Sim. As aplicações locais que correm no Orkas são gratuitas. Para publicar uma aplicação Web com uma ligação pública, é necessário um plano pago. Os planos Lite, Pro e Max permitem publicar, respetivamente, 5, 8 e 15 aplicações. As aplicações Web publicadas não incluem todas as funcionalidades disponíveis na aplicação Orkas para computador.

**Preciso de uma conta Orkas?**
A versão instalável para computador exige que inicie sessão no primeiro arranque. A versão executada a partir do código-fonte deste repositório não tem módulo de conta e abre diretamente a aplicação.

**O Orkas pode executar o Claude Code e outros agentes de linha de comandos?**
Sim. O Orkas pode executar cinco agentes externos de linha de comandos como subprocessos locais: Claude Code, Codex, OpenCode, OpenClaw e Hermes-Agent. Também pode integrar ferramentas de código aberto como o HyperFrames e coordená-las na mesma conversa.

**Como é que Orkas difere do Claude Code / Codex / CrewAI / LangChain?**
O Claude Code e o Codex são agentes de programação. O Orkas pode executar ambos na mesma equipa, sem teres de escolher entre eles. O CrewAI e o LangChain são frameworks centradas no código. O Orkas é uma aplicação de código aberto para computador em que o Commander coordena agentes especializados e agentes de linha de comandos. Podes escolher entre diferentes fornecedores de modelos. Por predefinição, os dados e as chaves são guardados localmente. [Ver a comparação completa](https://orkas.ai/compare/?source=gh-orkas)

**Que plataformas são suportadas pelo Orkas?**
Existem instaladores para macOS 12+ (Apple Silicon e Intel) e Windows 10+. Em Linux x64/arm64 com glibc 2.34 ou posterior, o Orkas corre a partir do código-fonte e ainda não existe instalador. No primeiro arranque, o Orkas prepara uma versão fixa do ambiente de execução do whisper.cpp para transcrever voz localmente. Não são suportadas a distribuição Alpine nem outras baseadas em musl. Para arrancar a partir do código-fonte, é necessário Node 22.12 ou posterior. O Python 3 e as ferramentas de compilação de C/C++ só são precisos se um pacote nativo de npm não tiver um binário pré-compilado compatível e tiver de ser compilado localmente.

**O Orkas é gratuito e de código aberto?**
Sim. A aplicação está disponível gratuitamente ao abrigo da licença MIT. A versão instalável inclui 500 créditos para o modelo integrado do Orkas. Os planos pagos começam nos 11,99 USD por mês e acrescentam créditos mensais, sincronização na nuvem, mais projetos partilhados e a possibilidade de publicar aplicações Web. Se usar as suas próprias chaves de API, o fornecedor cobra a utilização do modelo, sem acréscimos por parte do Orkas. [Preços →](https://orkas.ai/pricing/?source=gh-orkas)

---

## Licença

[MIT](./LICENSE)
