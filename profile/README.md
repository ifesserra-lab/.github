# ifesserra-lab · IFES Campus Serra

![Banner GitHub Org](https://raw.githubusercontent.com/ifesserra-lab/.github/main/profile/banner.png)

![IFES](https://img.shields.io/badge/IFES-Campus_Serra-006b3f?style=flat-square&labelColor=1a2b22)
![Laboratório de dados](https://img.shields.io/badge/laborat%C3%B3rio-de_dados-009640?style=flat-square)
![Código aberto](https://img.shields.io/badge/c%C3%B3digo-aberto-1a2b22?style=flat-square)

> ### O que o campus faz, em dados — não em relatórios perdidos.
>
> Construímos os pipelines (ETL), painéis e agentes que extraem, cruzam e publicam os dados de **extensão, pesquisa e editais** do Campus Serra. Código aberto, reprodutível e **sem dados pessoais de alunos**.

**[Site → ifesserra-lab.github.io](https://ifesserra-lab.github.io/)** &nbsp;·&nbsp; **[Painel de Extensão →](https://ifesserra-lab.github.io/src/)**

---

## Em produção

| # | Painel | O que é |
|:--|:--|:--|
| 01 | **[Extensão — SRC](https://ifesserra-lab.github.io/src/)** | ações, atividades, extensionistas, temas, investimento e o índice FORPROEX |
| 02 | **[Editais](https://ifesserra-lab.github.io/portal_edital/)** | editais de pesquisa, extensão e fomento — reunidos, filtráveis e atualizados |
| 03 | **[Salários & carreira de egressos](https://ifesserra-lab.github.io/egressos/)** | trajetória e faixa salarial dos formados (visão executiva anonimizada) |
| 04 | **[Diretoria](https://ifesserra-lab.github.io/diretoria/)** | indicadores consolidados de ensino, pesquisa e extensão para a gestão |
| 05 | **[Horizon](https://github.com/ifesserra-lab/horizon_dashboard)** | inteligência sobre grupos de pesquisa, produção e editais (Prefect + Supabase) |

## Projetos

**Painéis & visualização**
- [src](https://github.com/ifesserra-lab/src) — painel de extensão do Campus Serra (Astro + ETL Python)
- [horizon_dashboard](https://github.com/ifesserra-lab/horizon_dashboard) — dashboard de pesquisa (Projeto Horizon)
- [egressos](https://github.com/ifesserra-lab/egressos) — carreira e salários de egressos (anonimizado)
- [diretoria](https://github.com/ifesserra-lab/diretoria) — indicadores de apoio à gestão

**ETL & bibliotecas de dados**
- [horizon_etl](https://github.com/ifesserra-lab/horizon_etl) — pipeline ETL (Prefect + Supabase, arquitetura hexagonal)
- [factor_lib](https://github.com/ifesserra-lab/factor_lib) — extração de projetos do portal Facto (Playwright)
- [scriptLattes](https://github.com/ifesserra-lab/scriptLattes) — extrai dados do Lattes para JSON
- [research_domain_lib](https://github.com/ifesserra-lab/research_domain_lib) · [dgp.cnqp_lib](https://github.com/ifesserra-lab/dgp.cnqp_lib)

**Agentes & automação**
- [hermes](https://github.com/ifesserra-lab/hermes) — agente de integração Pesquisa/Ensino/Editais
- [sigpesq_agent](https://github.com/ifesserra-lab/sigpesq_agent) — baixa relatórios do portal Sigpesq
- [retrieve_edital](https://github.com/ifesserra-lab/retrieve_edital) — download automatizado de editais (Playwright)
- [homologacao-ponto](https://github.com/ifesserra-lab/homologacao-ponto) — extração do Espelho de Ponto do SIGRH

**Portais, sites & busca**
- [portal_edital](https://github.com/ifesserra-lab/portal_edital) — portal de editais (Astro + Tailwind + BDD)
- [gedoc-ifes-busca](https://github.com/ifesserra-lab/gedoc-ifes-busca) — busca de documentos
- [sbf](https://github.com/ifesserra-lab/sbf) — Simpósio Regional de Física (Campus Serra)

> Lista sempre atualizada em **[ifesserra-lab.github.io](https://ifesserra-lab.github.io/)** · [todos os repositórios](https://github.com/orgs/ifesserra-lab/repositories)

## Como construímos

![Python](https://img.shields.io/badge/Python-006b3f?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-006b3f?style=flat-square&logo=playwright&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-006b3f?style=flat-square&logo=astro&logoColor=white)
![Prefect](https://img.shields.io/badge/Prefect-006b3f?style=flat-square&logo=prefect&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-006b3f?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-006b3f?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-006b3f?style=flat-square&logo=docker&logoColor=white)

---

**IFES — Campus Serra** · [serra.ifes.edu.br](https://serra.ifes.edu.br/) · [github.com/ifesserra-lab](https://github.com/ifesserra-lab)
