<div align="center">

# Eduardo Ciudad

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2500&pause=1200&color=58A6FF&center=true&vCenter=true&repeat=true&width=550&height=30&lines=Backend+Developer+%7C+Java+%26+Spring+Boot;Construindo+APIs+REST+em+produ%C3%A7%C3%A3o;Automatizando+fluxos+com+IA+e+filas+ass%C3%ADncronas" />

<br>

</div>

---

### Sobre

Backend developer autodidata. Stack: Java 17 · Spring Boot · PostgreSQL · Flyway · Spring Security/JWT · RabbitMQ · Docker · Nginx. Projetos em produção com deploy em VPS (Ubuntu), integrações de pagamento e frete (Mercado Pago, Correios), integração com IA generativa (Anthropic, Gemini), auditoria de segurança e testes com JUnit 5 e Mockito.

Também construo e mantenho a **CiudadLab**, meu estúdio de desenvolvimento, onde aplico o que aprendo no backend em projetos de frontend para clientes.

Buscando minha primeira oportunidade como **Desenvolvedor Backend Junior**.

São José do Rio Preto, SP &nbsp;·&nbsp; [Portfólio](https://eduardo-ciudad-portfolio.vercel.app) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/eduardociudadf/) &nbsp;·&nbsp; [CiudadLab](https://ciudadlab.com.br)

---

### Tech Stack

<div align="center">

**Core** &nbsp;&nbsp;&nbsp; <img src="https://skillicons.dev/icons?i=java,spring,postgres,docker&theme=dark" height="32" />

**Infra & Tools** &nbsp;&nbsp;&nbsp; <img src="https://skillicons.dev/icons?i=git,github,linux,idea&theme=dark" height="32" />

**Frontend** &nbsp;&nbsp;&nbsp; <img src="https://skillicons.dev/icons?i=js,html,css,react,nextjs,tailwind&theme=dark" height="32" />

</div>

<br>

<div align="center">

```
Spring Security · JWT · Flyway · JPA/Hibernate · RabbitMQ · JUnit 5 · Mockito
Docker · Docker Compose · Render · Vercel · Swagger/OpenAPI · Anthropic API · Gemini API
```

</div>

---

### Projetos

<table>
<tr>
<td width="50%" valign="top">

#### 🤖 PromoBot &nbsp; <sup><code>em produção · 24/7</code></sup>

Bot que monitora promoções no Mercado Livre, gera legendas únicas com IA generativa (Gemini) e distribui automaticamente para um grupo do Telegram. Roda continuamente em VPS própria.

**Features:** arquitetura hexagonal, scraper isolado em processo independente (Playwright) para contornar bloqueio de IP de datacenter, fila assíncrona com RabbitMQ, padrão Outbox com lease e backoff para envio confiável de mensagens, deduplicação e testes com JUnit 5.

[`Repositório`](https://github.com/eduardo-Ciudad/promo-bot-mercadolivre)

`Java 17` · `Spring Boot 4` · `RabbitMQ` · `Gemini API`
`Playwright` · `PostgreSQL` · `Flyway` · `Docker` · `Nginx`

</td>
<td width="50%" valign="top">

#### 🛍️ GabiKids E-commerce &nbsp; <sup><code>freelance pago</code></sup>

API REST completa para e-commerce de moda infantil, cobrindo o fluxo inteiro de compra: catálogo com variações de tamanho, carrinho persistente, frete em tempo real e checkout com pagamento real.

**Features:** checkout Mercado Pago (Pix e cartão) com webhook validado por HMAC-SHA256 e idempotência, integração com o ERP Bling para sincronização de catálogo, cálculo de frete via API dos Correios (PAC/SEDEX), imagens via Cloudflare R2, lock pessimista contra overselling, rate limiting com Bucket4j e Caffeine, RBAC (ADMIN/CLIENT), 100+ testes.

[`Repositório`](https://github.com/eduardo-Ciudad/ecommerce)

`Java 17` · `Spring Boot 3.5` · `Mercado Pago API` · `Bling API`
`Correios API` · `PostgreSQL` · `Flyway` · `Cloudflare R2` · `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🎨 CiudadLab &nbsp; <sup><code>estúdio próprio</code></sup>

Site institucional e vitrine do meu estúdio de desenvolvimento, onde ofereço serviços de frontend para clientes e mostro cases reais entregues.

**Features:** animações com Framer Motion, páginas de documentação de serviço dinâmicas (`/servicos/[slug]`), carrossel horizontal, preloader com sessionStorage, páginas legais (política de privacidade, cookies, termos de uso), SEO completo (sitemap, JSON-LD, Open Graph), cases reais como GabiKids e PromoBot.

[`Site`](https://ciudadlab.com.br) · [`Repositório`](https://github.com/eduardo-Ciudad/ciudad.dev)

`Next.js 14` · `TypeScript` · `Tailwind CSS v4`
`Framer Motion` · `Vercel`

</td>
<td width="50%" valign="top">

#### 💰 Controle Financeiro &nbsp; <sup><code>freelance pago</code></sup>

Sistema financeiro multi tenant entregue para fornecedora de tecidos. Arquitetura append only (ledger): saldo sempre via `SUM`, correções via estorno, nunca edita ou deleta.

**Features:** vendas com baixa automática de estoque, contas pessoais com parcelas, dashboard com resumo diário, fluxo completo de reset de senha, conformidade LGPD, email verification assíncrono, CI automatizado.

[`Backend`](https://controlefinanceirolab.duckdns.org) · [`Frontend`](https://cadin-financeiro.vercel.app) · [`Repositório`](https://github.com/eduardo-Ciudad/controle-financeiro-lab)

`Java 17` · `Spring Boot 3` · `Spring Security + JWT`
`PostgreSQL` · `Flyway` · `Docker` · `Nginx` · `VPS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🧠 StudyMind

Plataforma de estudos com onboarding via IA. O usuário conversa com um assistente que gera um plano de 6 semanas, populando matérias, tópicos e tarefas no banco.

**Features:** integração com Anthropic Claude, email verification assíncrono, rate limiting, refresh token JWT, Docker e docker compose, 58 testes passando.

[`Backend`](https://studymind-l3ej.onrender.com) · [`Frontend`](https://studymind-mu.vercel.app) · [`Arquitetura`](https://eduardo-ciudad.github.io/StudyMind/) · [`Repositório`](https://github.com/eduardo-Ciudad/StudyMind)

`Java 17` · `Spring Boot 3` · `Anthropic API`
`PostgreSQL` · `Flyway` · `Docker` · `JUnit 5`

</td>
<td width="50%" valign="top">

#### 📄 ATSReady

API stateless que analisa currículos contra vagas usando IA. Upload de PDF, extração com PDFBox, scoring via Anthropic API, arquitetura hexagonal (Ports & Adapters).

**Features:** 24/24 testes passando, CI com GitHub Actions, análise em quatro dimensões com pontuação e sugestões de melhoria.

[`Repositório`](https://github.com/eduardo-Ciudad/ATS-analyse)

`Java 17` · `Spring Boot 3` · `Anthropic API`
`PDFBox` · `Hexagonal Architecture` · `GitHub Actions`

</td>

</table>

---

### GitHub Stats

<div align="center">

<img src="https://github-readme-stats-self-rho-71.vercel.app/api?username=eduardo-Ciudad&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&ring_color=58a6ff" height="160" />

<br><br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=eduardo-Ciudad&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="160" />

</div>

---

<div align="center">

<a href="mailto:eduardociudadfigueredo@gmail.com">
  <img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=58a6ff"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/eduardociudadf/">
  <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58a6ff"/>
</a>
&nbsp;
<a href="https://www.instagram.com/ciudad_dev">
  <img src="https://img.shields.io/badge/Instagram-0d1117?style=for-the-badge&logo=instagram&logoColor=58a6ff"/>
</a>
&nbsp;
<a href="https://ciudadlab.com.br">
  <img src="https://img.shields.io/badge/ciudadlab.com.br-0d1117?style=for-the-badge&logo=vercel&logoColor=58a6ff"/>
</a>
&nbsp;
<a href="https://github.com/eduardo-Ciudad">
  <img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=58a6ff"/>
</a>

</div>
