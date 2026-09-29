<div align="center">

# Lucas Antunes Ferreira

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=Desenvolvedor+Fullstack+com+foco+em+backend;C%23+%7C+.NET+%7C+React+%7C+PostgreSQL+%7C+PostGIS;Sistemas+distribu%C3%ADdos+%7C+Regras+de+neg%C3%B3cio+%7C+Seguran%C3%A7a;Produtos+B2B+publicados+e+validados+em+produ%C3%A7%C3%A3o" alt="Typing SVG" />

<p>
  Desenvolvedor <strong>Fullstack com foco em backend .NET</strong>.<br/>
  Construo produtos B2B do domínio à produção, com atenção a consistência, segurança, testes e operação em cloud.
</p>

<p>
  <a href="https://www.lucasafvr.com.br/">
    <img src="https://img.shields.io/badge/Portfólio-lucasafvr.com.br-111827?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/lucasantunesferreira/">
    <img src="https://img.shields.io/badge/LinkedIn-Lucas%20Antunes%20Ferreira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:lucas.afvr@gmail.com">
    <img src="https://img.shields.io/badge/Email-lucas.afvr%40gmail.com-111827?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p>
  <img src="https://komarev.com/ghpvc/?username=Lucasantunesribeiro&label=visitas&color=58A6FF&style=flat" />
  <img src="https://img.shields.io/badge/Foco-Fullstack%20%2F%20Backend-58A6FF?style=flat" />
</p>

</div>

---

## Destaques rápidos

- **C#/.NET no centro da stack**, com React/TypeScript no frontend.
- Produtos B2B publicados com **APIs REST, PostgreSQL/PostGIS, multi-tenancy, RBAC e processamento assíncrono**.
- Experiência prática com **idempotência, concorrência, Transactional Outbox, mensageria e sistemas distribuídos**.
- Projetos com **CI/CD, testes automatizados, Security Gates, pentest e observabilidade**.
- Deploy e troubleshooting em **AWS, Oracle Cloud, Vercel e Neon**.

---

## Stack principal

<div align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,react,ts,postgres,aws,docker,githubactions" />
</div>

<br/>

<details>
  <summary><strong>Ver stack completa</strong></summary>

**Backend:** C#/.NET, ASP.NET Core, Node.js, Java/Spring Boot, Python/FastAPI/Flask/Django  
**Frontend:** React, Next.js, TypeScript, Angular, Vite, Tailwind CSS  
**Banco:** PostgreSQL, PostGIS, SQL Server, MySQL, DynamoDB, Redis, Supabase  
**Cloud/DevOps:** AWS, Azure, Oracle Cloud, Docker, GitHub Actions, CI/CD, infraestrutura como código  
**Engenharia:** DDD, monólito modular, Outbox Pattern, idempotência, mensageria, observabilidade, testes automatizados e segurança

</details>

---

## Projetos principais

> Três projetos construídos para demonstrar competências diferentes: **operação em tempo real**, **sistemas distribuídos** e **domínio de negócio complexo**.

<div align="center">
  <sub><strong>01 · OPERAÇÃO EM TEMPO REAL</strong></sub>
</div>

<table>
  <tr>
    <td valign="top">
      <h3>Torre Logística <sub>— v1.0.1 · em produção</sub></h3>
      <p>
        Plataforma B2B que conecta <strong>console operacional, PWA do motorista e rastreamento público</strong>
        durante todo o ciclo de uma entrega.
      </p>
      <p>
        <strong>Engenharia:</strong> .NET 10, React 19, PostgreSQL 17/PostGIS, SignalR, geofencing, ETA/SLA,
        processamento idempotente, Transactional Outbox, prova de entrega, URLs assinadas, multi-tenancy e RBAC.
      </p>
      <p>
        <strong>Produção e qualidade:</strong> demo pública em Oracle Cloud Always Free, HTTPS, CI,
        testes de contrato contra a API real, Security Gate com gitleaks e pentest gray-box documentado.
      </p>
      <p align="center">
        <img src="https://raw.githubusercontent.com/Lucasantunesribeiro/torre-logistica/main/docs/assets/screenshots/console-painel.png" alt="Console operacional da Torre Logística" width="100%" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat&logo=react&logoColor=111827" />
        <img src="https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/PostGIS-336791?style=flat" />
        <img src="https://img.shields.io/badge/SignalR-512BD4?style=flat" />
        <img src="https://img.shields.io/badge/v1.0.1-22c55e?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/torre-logistica"><img src="https://img.shields.io/badge/Repositório-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://operacao.torre.lucasafvr.com.br"><img src="https://img.shields.io/badge/Demo%20ao%20vivo-22c55e?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
        <a href="https://github.com/Lucasantunesribeiro/torre-logistica/releases/tag/v1.0.1"><img src="https://img.shields.io/badge/Release-v1.0.1-2563eb?style=for-the-badge&logo=github&logoColor=white" /></a>
      </p>
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <sub><strong>02 · SISTEMAS DISTRIBUÍDOS</strong></sub>
</div>

<table>
  <tr>
    <td valign="top">
      <h3>Central Antifraude <sub>— em produção</sub></h3>
      <p>
        Plataforma B2B para <strong>avaliação de risco, monitoramento e investigação de transações suspeitas</strong>,
        com decisão explicável entre Permitir, Revisar ou Bloquear.
      </p>
      <p>
        <strong>Engenharia:</strong> .NET 10, React 19, PostgreSQL 17, idempotência sob concorrência,
        transações serializáveis, regras versionadas, Transactional Outbox, Inbox, SQS/DLQ e processamento assíncrono.
      </p>
      <p>
        <strong>Produção e qualidade:</strong> API e workers em AWS Lambda, frontend na Vercel,
        banco no Neon, <strong>1.215 testes automatizados</strong> e pentest gray-box documentado com <strong>19 vetores</strong>.
      </p>
      <p>
        <img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat&logo=react&logoColor=111827" />
        <img src="https://img.shields.io/badge/PostgreSQL_17-4169E1?style=flat&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS_SQS-FF9900?style=flat&logo=amazonaws&logoColor=white" />
        <img src="https://img.shields.io/badge/Produção-22c55e?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/central-antifraude"><img src="https://img.shields.io/badge/Repositório-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://central-antifraude.vercel.app"><img src="https://img.shields.io/badge/Demo%20ao%20vivo-22c55e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
        <a href="https://github.com/user-attachments/assets/9afe53b9-7b4a-4c3c-8f45-e6d966042673"><img src="https://img.shields.io/badge/Vídeo-24s-2563eb?style=for-the-badge" /></a>
      </p>
    </td>
  </tr>
</table>

<br/>

<div align="center">
  <sub><strong>03 · DOMÍNIO DE NEGÓCIO COMPLEXO</strong></sub>
</div>

<table>
  <tr>
    <td valign="top">
      <h3>Prisma RH <sub>— folha de pagamento brasileira · v1.0.0</sub></h3>
      <p>
        Plataforma B2B de <strong>gestão, cálculo e conferência de folha de pagamento</strong>,
        com rastreabilidade de folha mensal, férias, 13º, rescisões, INSS, FGTS e IRRF.
      </p>
      <p>
        <strong>Engenharia:</strong> .NET 10, React, PostgreSQL, monólito modular, multi-tenancy,
        histórico por vigência, workflow, auditoria somente-inserção e importação CSV/XLSX com processamento assíncrono.
      </p>
      <p>
        <strong>Qualidade:</strong> <strong>1.286 testes de backend</strong>, <strong>171 de frontend</strong> e
        <strong>50 testes de segurança</strong>, incluindo isolamento entre tenants e validações de cálculo.
      </p>
      <p>
        <img src="https://img.shields.io/badge/.NET_10-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=111827" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
        <img src="https://img.shields.io/badge/v1.0.0-22c55e?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/prisma_rh"><img src="https://img.shields.io/badge/Repositório-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://portfolio-prisma-rh.vercel.app"><img src="https://img.shields.io/badge/Demo%20ao%20vivo-22c55e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
        <a href="https://github.com/Lucasantunesribeiro/prisma_rh/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/Release-v1.0.0-2563eb?style=for-the-badge&logo=github&logoColor=white" /></a>
      </p>
    </td>
  </tr>
</table>

---

## Outros projetos

<div align="center">
  <sub>Mais projetos que reforçam backend, arquitetura, mensageria e produto fullstack.</sub>
</div>

<br/>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 SmartFinance</h3>
      <p>Plataforma de gestão financeira com <strong>.NET 8 + Next.js</strong>, autenticação, analytics, Outbox Pattern, RabbitMQ, SignalR, Docker e AWS.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/Next.js-111827?style=flat&logo=nextdotjs&logoColor=white" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white" />
        <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/smart_finance"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="http://3.223.37.57/login"><img src="https://img.shields.io/badge/Demo-22c55e?style=for-the-badge&logo=google-chrome&logoColor=white" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏢 TenantCore</h3>
      <p>SaaS B2B multi-tenant com <strong>.NET 9 + React</strong>, RBAC, refresh token rotativo, SQL Server, Redis, Quartz e OpenTelemetry.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_9-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=111827" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" />
        <img src="https://img.shields.io/badge/OpenTelemetry-111827?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/tenant_core"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://purple-dune-018763b0f.4.azurestaticapps.net"><img src="https://img.shields.io/badge/Demo-22c55e?style=for-the-badge&logo=microsoftazure&logoColor=white" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 BillingLedger</h3>
      <p>Backend distribuído para cobranças e conciliação em ledger com <strong>.NET 9</strong>, DDD, Outbox, idempotência, HMAC e AWS SNS/SQS.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_9-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/SNS%2FSQS-FF9900?style=flat&logo=amazonaws&logoColor=white" />
        <img src="https://img.shields.io/badge/HMAC-111827?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/billing_ledger"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔗 LinkGuardião</h3>
      <p>Gestão segura de links com <strong>.NET 8 + React</strong>, refresh token, rate limiting e analytics assíncrono com SQS + Lambda.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=111827" />
        <img src="https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
        <img src="https://img.shields.io/badge/Rate%20Limiting-111827?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/LinkGuardiao"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://linkguardiao.pages.dev/"><img src="https://img.shields.io/badge/Demo-22c55e?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📄 Emissão de NF-e e Estoque</h3>
      <p>Arquitetura serverless com <strong>.NET 8 + Go + Angular</strong>, Lambda, API Gateway, Cognito, EventBridge, SQS/DLQ, DynamoDB e CDK.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat&logo=dotnet&logoColor=white" />
        <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white" />
        <img src="https://img.shields.io/badge/EventBridge-FF4F8B?style=flat&logo=amazonaws&logoColor=white" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/emissao_nfe"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://d1gdw7rlsi8u42.cloudfront.net/"><img src="https://img.shields.io/badge/Demo-22c55e?style=for-the-badge&logo=amazonaws&logoColor=white" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 Article Summarizer</h3>
      <p>Processamento assíncrono de artigos com <strong>Python + Flask + React</strong>, Redis, Celery, RabbitMQ, Outbox e IA generativa.</p>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Flask-111827?style=flat&logo=flask&logoColor=white" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white" />
        <img src="https://img.shields.io/badge/IA-111827?style=flat" />
      </p>
      <p>
        <a href="https://github.com/Lucasantunesribeiro/article_summarizer_agent"><img src="https://img.shields.io/badge/Repo-111827?style=for-the-badge&logo=github&logoColor=white" /></a>
        <a href="https://article-summarizer-agent.onrender.com/"><img src="https://img.shields.io/badge/Demo-22c55e?style=for-the-badge&logo=render&logoColor=white" /></a>
      </p>
    </td>
  </tr>
</table>

---

## Como eu trabalho

- **Domínio primeiro:** invariantes e comportamento antes das abstrações.
- **Consistência:** idempotência, concorrência, transações e efeitos assíncronos tratados explicitamente.
- **Qualidade:** testes unitários, integração com banco real, arquitetura, frontend e gates de segurança.
- **Segurança:** autenticação, autorização, isolamento entre tenants, rate limiting, secrets e hardening.
- **Produção:** CI/CD, observabilidade, health checks e troubleshooting orientado por evidência.
- **Documentação:** ADRs, decisões técnicas, limitações e resultados medidos junto do código.

---

## GitHub Stats

<div align="center">
  <img
    height="165"
    src="https://github-readme-stats-delta-gilt-78.vercel.app/api?username=Lucasantunesribeiro&show_icons=true&hide_title=true&theme=transparent&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&hide_border=true&include_all_commits=true&count_private=true&cache_seconds=86400&v=2"
    alt="GitHub Stats"
  />
  <img
    height="165"
    src="https://github-readme-stats-delta-gilt-78.vercel.app/api/top-langs/?username=Lucasantunesribeiro&layout=compact&langs_count=8&theme=transparent&title_color=58A6FF&text_color=C9D1D9&hide_border=true&cache_seconds=86400&v=2"
    alt="Top Languages"
  />
</div>

---

## Contato

<div align="center">
  <a href="https://www.lucasafvr.com.br/">
    <img src="https://img.shields.io/badge/Ver%20Portfólio-111827?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/lucasantunesferreira/">
    <img src="https://img.shields.io/badge/Conectar%20no%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:lucas.afvr@gmail.com">
    <img src="https://img.shields.io/badge/Enviar%20Email-111827?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</div>