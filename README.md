<div align="center">

<img src="./assets/header.svg" width="100%" alt="Luiz Eduardo Melo — Software Engineer · Founder & CEO @ Codevelop Solutions" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=1200&color=818CF8&center=true&vCenter=true&width=760&lines=Arquiteto+plataformas+SaaS+multi-tenant+de+n%C3%ADvel+banc%C3%A1rio;Kotlin+%C2%B7+Spring+Boot+%C2%B7+Node.js+%C2%B7+React+%C2%B7+AWS;Sistemas+de+miss%C3%A3o+cr%C3%ADtica+para+bancos+e+governo;Produtos+com+IA+do+conceito+%C3%A0+produ%C3%A7%C3%A3o" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiz-eduardo-270204a3)
[![Codevelop](https://img.shields.io/badge/cdsolutions.com.br-1e1b4b?style=flat-square&logo=googlechrome&logoColor=white)](https://www.cdsolutions.com.br)
[![Email](https://img.shields.io/badge/luiz.melo@cdsolutions.com.br-4f46e5?style=flat-square&logo=maildotru&logoColor=white)](mailto:luiz.melo@cdsolutions.com.br)
![Salvador](https://img.shields.io/badge/Salvador%20·%20BA%20·%20Brasil-0b1020?style=flat-square&logo=googlemaps&logoColor=white)

</div>

<br/>

> **Eu transformo regras de negócio complexas em plataformas seguras, escaláveis e mensuráveis.**
> Engenheiro de software há mais de 6 anos em sistemas de missão crítica para o setor financeiro e o setor público,
> hoje lidero a **Codevelop Solutions** — software house e consultoria em cibersegurança — e construo produtos próprios
> de SaaS e Inteligência Artificial, da arquitetura ao go-live.

<br/>

## ◆ O que eu construo

<table>
<tr>
<td width="33%" valign="top">

### 🏛️ SaaS B2B Multi-tenant
Plataformas com **isolamento de dados por cliente**, controle de acesso hierárquico, auditoria completa e
planos por capacidade — desenhadas para operar dados trabalhistas e financeiros sensíveis com **segurança de nível bancário**.

</td>
<td width="33%" valign="top">

### 🏦 Missão Crítica
Sistemas que não podem parar: **BACEN, Bradesco Seguros, PicPay, Banco do Nordeste, MPPE** e órgãos federais.
Alta disponibilidade, processamento em larga escala, integrações e conformidade regulatória.

</td>
<td width="33%" valign="top">

### 🤖 Produtos com IA
IA aplicada ao negócio — não demonstração. Assistentes especializados com base legal, trilhas de aprendizagem
adaptativas e automações que reduzem trabalho operacional de verdade.

</td>
</tr>
</table>

## ◆ Princípios de engenharia

| Pilar | Como eu aplico |
|---|---|
| 🔐 **Security by design** | Isolamento por tenant, WAF, MFA, menor privilégio, criptografia em trânsito e em repouso, trilha de auditoria e conformidade com a **LGPD** |
| 🧪 **Qualidade não negociável** | Pipeline com **≥ 90% de cobertura**, testes unitários e de integração em toda entrega, code review obrigatório e branches protegidas |
| 📐 **Arquitetura que envelhece bem** | Clean Architecture, DDD e SOLID — domínio independente de framework, infraestrutura substituível |
| 📜 **Contratos primeiro** | APIs e BFF documentados em **OpenAPI/Swagger**, rotas rastreáveis e testáveis de ponta a ponta |
| 📈 **Operação observável** | Logs estruturados, métricas, alertas e filas confiáveis — o sistema conta o que está acontecendo antes do cliente reclamar |
| ⚙️ **Tudo automatizado** | CI/CD, infraestrutura como código e deploys reproduzíveis na **AWS** |

## ◆ Arquitetura de referência

Padrão que uso em plataformas SaaS que lidam com dados sensíveis:

```mermaid
flowchart LR
    U([Usuários]) --> E[Route 53 · AWS WAF · Load Balancer]
    E --> W[Web App<br/>React + TypeScript]
    W --> B[BFF<br/>Node.js · OpenAPI]
    B --> A[Core API<br/>Kotlin · Spring Boot]
    A --> T[(Base por tenant<br/>PostgreSQL)]
    A --> Q[[Mensageria]]
    A --> C[(Cache)]
    Q --> J[Workers<br/>e-mail · relatórios · IA]
    A -.-> O[Observabilidade<br/>logs · métricas · alertas]
```

## ◆ Empreendimentos

| | Produto | O que é |
|---|---|---|
| 💼 | **[Codevelop Solutions](https://www.cdsolutions.com.br)** | Software house e consultoria em cibersegurança — desenvolvimento sob medida, integração de sistemas, segurança de redes e cloud |
| 🎙️ | **[SpeakFlow](https://www.speakflow.ia.br)** | Plataforma de IA para profissionais brasileiros que usam inglês no trabalho — web e mobile, software registrado no INPI |
| 🎒 | **[SpeakFlow Escolas](https://www.speakflowescola.com.br)** | Reforço escolar com IA para o ensino fundamental, com acompanhamento dos responsáveis e arquitetura por rede de ensino |
| 📊 | **SaaS de gestão trabalhista** *(em construção)* | Plataforma multi-tenant para escritórios contábeis: carteiras de clientes, rotinas de DP, BI gerencial, portal do cliente e IA especialista em direito do trabalho |

## ◆ Trajetória

| Cliente | Domínio | Stack |
|---|---|---|
| **BACEN** — Banco Central do Brasil | Ingestão e processamento de dados em larga escala | Java · Spring Boot · DB2 · OpenShift · Cucumber |
| **PicPay** — Chargeback | Sistemas financeiros críticos e observabilidade | Kotlin · Angular · AWS Lambda · API Gateway · S3 · Grafana |
| **Bradesco Seguros** | Transações de sinistros e integrações corporativas | Java EE · Spring Boot · Oracle · WebSphere · REST/SOAP |
| **Banco do Nordeste · FNDE** | Sistemas financeiros e de políticas públicas | Java · Spring Boot · Angular |
| **MPPE** — Ministério Público de PE | Sistemas de missão crítica e APIs seguras | Java · Spring Boot · Angular · PostgreSQL · GitLab CI/CD |
| **SICAR** — Governo da Bahia | Controle ambiental e dados georreferenciados | Java · Spring Boot · PostgreSQL · Docker |

<sub>EBIX → CAST Group → Netra (ACP Group) → NTT DATA → G4F Soluções Corporativas</sub>

## ◆ Stack

<div align="center">

**Back-end**<br/>
<img src="https://skillicons.dev/icons?i=kotlin,java,spring,nodejs,ts,python,rust" />

**Front-end & Mobile**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,angular,tailwind" />

**Dados, Cloud & DevOps**<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,aws,docker,githubactions,gitlab,grafana,linux" />

</div>

## ◆ Atividade

<div align="center">


<img src="https://streak-stats.demolab.com/?user=Luiz-code-dev&hide_border=true&background=0b1020&ring=818cf8&fire=818cf8&currStreakLabel=818cf8&sideLabels=c9d1d9&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff&locale=pt_BR" />

</div>

## ◆ Formação

- 🎓 Pós-graduação em **Engenharia de Software**
- 🤖 Pós-graduação em **Inteligência Artificial**
- ☁️ **Java & AWS Developer** — Digital Innovation One

<br/>

<div align="center">

*Arquitetura limpa, código que se sustenta e sistemas que não caem.*


</div>
