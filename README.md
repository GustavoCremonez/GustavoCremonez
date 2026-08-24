<h1 align="center">Gustavo Cremonez</h1>

<p align="center">
  <b>Desenvolvedor Fullstack</b> · .NET 8 · Next.js · SQL Server<br>
  Londrina, PR — Brasil
</p>

<p align="center">
  <a href="https://gustavocremonez.dev">Portfólio</a> ·
  <a href="https://linkedin.com/in/gustavoscremonez">LinkedIn</a> ·
  <a href="mailto:gustavocremonezgc@gmail.com">E-mail</a>
</p>

---

Trabalho em backend .NET com Clean Architecture, mensageria e observabilidade — e no tempo livre
publico ferramentas de linha de comando que resolvem incômodos meus.

Meu foco é sistema que roda em produção e não acorda ninguém de madrugada: contratos bem
definidos, testes de domínio, deploy automatizado e telemetria desde o primeiro dia.

## Publicado

- **[git-diary](https://pypi.org/project/git-diary/)** · `pip install git-diary`

  Transforma seu histórico do git em um diário narrativo, não em mais um painel de estatísticas.
  Varre os repositórios da sua workspace e detecta padrões de comportamento — sequências de dias
  seguidos, sessões de flow (2+ commits na mesma hora) e commits de madrugada — e escreve isso
  como texto corrido, por dia e por projeto.
  Sem LLM, sem chave de API, sem nuvem: roda inteiro na sua máquina, no seu fuso.
  Por padrão nunca imprime a mensagem do commit, porque commit tem senha, token e nome de cliente.
  <br>`Python 3.11+` · `Rich`

- **[remotepad](https://www.npmjs.com/package/remotepad)** · `npx remotepad`

  Seu celular como superfície de controle programável para o PC — sem app de loja, sem conta,
  sem nuvem. Um comando no terminal gera um QR code e a tela do celular vira um deck de botões
  que **muda sozinho conforme o programa em foco** e **mostra a saída dos comandos em tempo real**.
  Mais de 90 ações prontas com busca, editáveis pelo navegador ou direto no `deck.yaml`.
  O pareamento usa Noise handshake com verificação de código de dez dígitos, então a confiança
  vem das chaves trocadas — não do certificado autoassinado.
  <br>`Node 22+` · `Fastify` · `WebSocket` · `Preact` · `nut.js` · `koffi` · Windows

## No trabalho

Atuo no **[Registro Ponto](https://registroponto.com.br)**, um SaaS de controle de jornada e
gestão de RH.

- **APIs de Gestão, Ponto Web e Espelho de Ponto** — três serviços .NET 8 em Clean Architecture
  (Domain, Application, Infra, Jobs), comunicando por **MassTransit/RabbitMQ**, com rotinas em
  **Hangfire**, cache em **Redis** e tracing via **OpenTelemetry**.
  Deploy em Docker com pipelines separadas de homologação, produção e rollback.

- **Painéis web em Next.js** — interfaces de gestão e do colaborador em React + TypeScript,
  com TanStack Query, React Hook Form + Zod, Radix/Tailwind e Storybook como base de componentes.

- **[@registroponto/icons](https://www.npmjs.com/package/@registroponto/icons)** e
  **[@registroponto/illustrations](https://www.npmjs.com/package/@registroponto/illustrations)** —
  design system open source de ícones e ilustrações para produtos de RH, publicado no npm
  e documentado em [Storybook](https://registro-ponto.github.io/registro-ponto-libs/).

## Stack

| | |
|---|---|
| **Backend** | C#, .NET 8, ASP.NET Core, EF Core, Dapper, FluentValidation, Polly |
| **Frontend** | TypeScript, Next.js, React, Tailwind, Radix UI, Zustand, Storybook |
| **Dados & Mensageria** | SQL Server, Redis, RabbitMQ, MassTransit, Hangfire |
| **Infra & Observabilidade** | Docker, GitHub Actions, AWS (S3, SES), OpenTelemetry, Sentry |
| **Testes** | xUnit, NSubstitute, FluentAssertions, coverlet |

## Antes disso

- **[TarefAI](https://tarefai-eta.vercel.app/)** — extrai tarefas de reuniões diárias com NLP + LLM.
  FastAPI, spaCy e Angular. [[front](https://github.com/GustavoCremonez/front-end)] · [[back](https://github.com/GustavoCremonez/backend)]
- **[GestureBoard](https://gestureboard.vercel.app)** — interface controlada por gestos, em Angular e TypeScript.
- **[CleanArchMVC](https://github.com/GustavoCremonez/CleanArchMVC)** — estudo de Clean Architecture em .NET que virou a base de como escrevo backend hoje.

## GitHub

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=GustavoCremonez&show_icons=true&hide_border=true&hide_title=true&include_all_commits=true&theme=github_dark">
    <img src="https://github-readme-stats.vercel.app/api?username=GustavoCremonez&show_icons=true&hide_border=true&hide_title=true&include_all_commits=true" height="150" alt="Estatísticas do GitHub de Gustavo Cremonez">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=GustavoCremonez&layout=compact&hide_border=true&theme=github_dark">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GustavoCremonez&layout=compact&hide_border=true" height="150" alt="Linguagens mais usadas">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/GustavoCremonez/GustavoCremonez/output/snake-dark.svg">
    <img src="https://raw.githubusercontent.com/GustavoCremonez/GustavoCremonez/output/snake.svg" alt="Gráfico de contribuições animado">
  </picture>
</p>
