# 👋 Olá, eu sou o Guilherme! (`@guilhermedev4jarvis`)

**Desenvolvedor de Software · Engenheiro de Agentes Autônomos · Builder de IA local-first**

Eu projeto e construo sistemas em que a inteligência artificial **não fica só no chat**: ela ouve, vê, decide e **age no sistema operacional** — com arquitetura modular, preferência por execução local e integração opcional com modelos em nuvem.

Meu foco está na interseção entre:

- **Agentes autônomos** (tools, outcomes, confirmação humana, undo)
- **IA local** (STT/TTS/LLM no próprio hardware)
- **Automação profunda de desktop** (Windows, Linux e macOS)
- **Microsserviços e painéis** para observação, controle e extensão do agente

> Filosofia: *o assistente deve reportar o que observou, não o que tentou.*  
> Por isso trabalho com contratos explícitos (`done` / `failed` / `ask` / `unverified` / `started`) e barreiras reais de confirmação para ações irreversíveis.

---

## 🔗 Links oficiais (sempre estes)

| Recurso | URL |
|---------|-----|
| 👤 **Perfil GitHub** | [github.com/guilhermedev4jarvis](https://github.com/guilhermedev4jarvis) |
| 💻 **Repositório J.A.R.V.I.S.** | [github.com/guilhermedev4jarvis/J.A.R.V.I.S](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S) |
| 📖 **Wiki do projeto** | [github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki) |
| 🌐 **Site / GitHub Pages** | [guilhermedev4jarvis.github.io/J.A.R.V.I.S](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/) |

---

## 🧠 Sobre mim

Sou o tipo de desenvolvedor que gosta de fechar o ciclo inteiro: da ideia do agente à action que move arquivo, gera código, dispara script PowerShell ou monitora a rede enquanto você joga — sempre com a possibilidade de **não depender da nuvem**.

No dia a dia isso se traduz em:

| Pilar | O que eu construo |
|-------|-------------------|
| **Agent OS** | Núcleo que carrega tools dinamicamente, orquestra LLM e devolve resultados estruturados |
| **Local-first** | Whisper, Ollama/LM Studio, Piper e vozes de sistema como caminho válido, não como “plano B esquecido” |
| **Desktop real** | Controle de apps, janelas, clipboard, arquivos, browser e shell com políticas de segurança |
| **Extensibilidade** | Plugins e actions com o mesmo contrato `TOOL`, hot-reload e analytics de uso |
| **Operação** | Dashboard, autenticação, segredos via `.env`, compactação de memória e governança de recursos |

Também me interesso por **experiência de voz** (wake word, push-to-talk, anti-eco, lip-sync) e por interfaces que fazem o agente parecer presença — não só uma caixa de texto.

Documentação longa, guias e notas de arquitetura ficam na **[Wiki do J.A.R.V.I.S.](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)**; o código vive no **[repositório](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S)**; a vitrine pública no **[GitHub Pages](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/)**.

---

## 🛠️ Tecnologias & ferramentas

### Linguagens e runtime
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Backend, APIs e automação
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

### IA, voz e modelos
![OpenAI](https://img.shields.io/badge/OpenAI_Compatible-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-Local_LLM-111111?style=for-the-badge)

### Sistemas e DevOps
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Stack que aparece com frequência nos meus projetos
- **Python** — núcleo de agentes, actions, STT/TTS, automação de SO  
- **JavaScript / Node** — painéis web, integrações, utilitários  
- **PowerShell & shell** — automação administrativa e geração segura de scripts  
- **Playwright / automação de browser** — fluxos web controlados pelo agente  
- **Flask / servidores locais** — dashboard, pareamento, APIs de apoio  
- **Ollama · Whisper · Piper · Gemini Live** — caminho local e caminho nuvem no mesmo produto  

---

## 🤖 Projeto em destaque: J.A.R.V.I.S. — MARK LVI (56)

O núcleo do meu trabalho open-source está na construção de uma **infraestrutura de agente autônomo de desktop**: o **MARK LVI (56)**, conhecido como **JARVIS**.

Não é um wrapper fino em cima de um chatbot. É um ecossistema com:

- sessão de voz e avatar  
- memória de longo prazo  
- dezenas de actions descobertas automaticamente  
- plugins opcionais  
- providers locais sob demanda  
- outcomes honestos e confirmação humana para o que é irreversível  

### Acesse tudo por aqui

- 💻 **Código:** [guilhermedev4jarvis/J.A.R.V.I.S](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S)  
- 📖 **Wiki (guias, arquitetura, FAQ):** [J.A.R.V.I.S. Wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)  
- 🌐 **Página live:** [guilhermedev4jarvis.github.io/J.A.R.V.I.S](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/)  
- 👤 **Perfil:** [guilhermedev4jarvis](https://github.com/guilhermedev4jarvis)  

### Diferenciais do sistema

**1. Orquestração unificada (Agent OS)**  
Módulos como `code_assist`, `powershell_assist` e `game_assist` concentram famílias inteiras de ferramentas sob o mesmo motor cognitivo — menos tools duplicadas para o modelo, mais clareza para quem desenvolve.

**2. Local-first com chaveamento inteligente**  
Filosofia nativa de resolução local via **Ollama**, **Whisper (STT)** e **Piper / voz do sistema (TTS)**, com possibilidade de usar **Gemini Live** quando a nuvem fizer sentido. O que não está em uso não precisa ser carregado na inicialização.

**3. Actions que mexem no mundo real**  
Arquivos, browser, clipboard, processos, rede, timers, OCR, geração e autocorreção de código Python, scripts PowerShell com varredura de comandos perigosos e gate de confirmação.

**4. Segurança e operação**  
- Segredos preferencialmente em **`.env` / variáveis de ambiente** (`core/secrets`), não só em JSON versionável por engano  
- Dashboard com autenticação e ativos estáticos protegidos  
- `resource_governor`, `memory_compactor`, `hot_reload`, `dependency_health` para o agente não virar peso morto na máquina  

**5. Extensível por design**  
Cada arquivo em `actions/` ou `plugins/` exporta um `TOOL` (`name`, `description`, `parameters`, `handler`). Novas capacidades entram como módulos — não como monólito reescrito.

**6. Documentação viva**  
A **[Wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)** concentra instalação, visão do MARK LVI, contratos de tools e notas de evolução — complementando o README do repositório e a [página pública](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/).

### Recorte técnico (MARK LVI)

```text
voz / HUD  →  core (outcome, confirm, undo, LLM, STT/TTS)
                    ↓
              actions + plugins   (tools do SO e do usuário)
                    ↓
              memory + config + dashboard
```

Se você se interessa por **agentes que executam de verdade** no desktop, comece pelo repositório e pela wiki:

→ [https://github.com/guilhermedev4jarvis/J.A.R.V.I.S](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S)  
→ [https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)

---

## 🧩 O que eu gosto de construir

- Agentes com **tool-calling** sério (não demo de um único plugin)
- Pipelines **áudio → texto → raciocínio → ação → fala**
- Camadas de **permissão** (allowlist, force, confirm na UI)
- UIs de operação (HUD, tray, painel mobile) que não atrapalham o fluxo
- Código que sobrevive a **Linux Wayland**, permissões do macOS e idiossincrasias do Windows
- Documentação e exemplos que um humano consegue rodar no mesmo dia

---

## 📊 Estatísticas do GitHub

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=guilhermedev4jarvis&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Estatísticas do GitHub" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=guilhermedev4jarvis&layout=compact&theme=tokyonight&hide_border=true" alt="Linguagens mais usadas" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=guilhermedev4jarvis&theme=tokyonight&hide_border=true" alt="Streak" />
</p>

---

## 🗺️ Onde contribuir / começar

1. Abra o repositório **[J.A.R.V.I.S](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S)**  
2. Leia a **[Wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)** e o README do MARK LVI (56)  
3. Veja a **[página live](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/)**  
4. Experimente as tools unificadas: `code_assist`, `powershell_assist`, `game_assist`  
5. Sugira actions, plugins ou melhorias de segurança e UX de voz  

Issues e PRs que melhoram **contratos de tools**, **modos offline** e **segurança de execução** são especialmente bem-vindos.

---

## 📞 Contato & redes

- **Perfil:** [https://github.com/guilhermedev4jarvis](https://github.com/guilhermedev4jarvis)  
- **Repositório JARVIS:** [https://github.com/guilhermedev4jarvis/J.A.R.V.I.S](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S)  
- **Wiki:** [https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki](https://github.com/guilhermedev4jarvis/J.A.R.V.I.S/wiki)  
- **Página oficial:** [https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/](https://guilhermedev4jarvis.github.io/J.A.R.V.I.S/)  
- **WhatsApp:** [+55 18 98128-1709](https://wa.me/5518981281709)

---

## ✍️ Nota final

Se você chegou até aqui, provavelmente também acredita que o próximo passo da IA pessoal não é só um modelo maior — é um **agente responsável**, com mãos no sistema, memória local e respeito ao usuário.

Vamos construir isso.

**Guilherme** · [@guilhermedev4jarvis](https://github.com/guilhermedev4jarvis)
