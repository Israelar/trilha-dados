# 📊 Trilha de Dados — de Engenharia de Produção para Analista de Dados / BI

> Trilha prática e enxuta pra quem **já entende de negócio/produção** e quer **entrar em dados** (análise + Power BI) e conquistar uma **vaga melhor** — sem enrolação, orientada a **projeto de portfólio**.
>
> **Autor/mentor:** Israel Rebouças · **Formato:** você segue os módulos, faz as tarefas, e abre uma [Issue](../../issues/new/choose) quando travar. Eu respondo por lá.

---

## 🎯 A estratégia (leia primeiro — 2 min)

**Seu objetivo não é virar "cientista de dados" em 1 ano.** É ficar **empregável em análise de dados/BI o mais rápido possível.** As vagas pedem "análise de dados, Power BI, SQL" — então é nisso que a gente foca.

**Seu superpoder:** você é **engenheira de produção.** Você já entende OEE, refugo, PCP, lead time, qualidade, indicadores. A maioria de quem entra em dados **não entende o negócio** — você entende. Então seu portfólio vai ser em **domínio de produção/manufatura**, e isso te coloca na frente de qualquer bootcamp genérico numa entrevista.

**Como aprender:** fazendo. Cada módulo tem **tarefa entregável**. Você não "assiste aula" — você constrói. Travou? Abre uma Issue.

---

## 🗺️ A trilha (4 módulos + 1 opcional)

| Módulo | O que você sai sabendo | Tempo | Entregável |
|---|---|---|---|
| **M0** — Setup | ambiente pronto, GitHub, como pedir ajuda | 1 dia | repo forkado + 1ª Issue de teste |
| **M1** — SQL & pensar em dados | consultar dados (SELECT, filtro, JOIN, agrupamento) | ~2 sem | consultas sobre base de produção |
| **M2** — Power BI essencial | ETL (Power Query), modelo, DAX básico, visuais | ~3–4 sem | mini-dashboard de um CSV cru |
| **M3** — Análise aplicada à produção | KPIs (OEE, refugo, PCP), estatística descritiva | ~1 sem | painel de indicadores de produção |
| **M4** — 🏆 Projeto de portfólio | dashboard fim-a-fim publicado + README | ~2 sem | **o projeto que você mostra na entrevista** |
| **M5** *(opcional, depois)* | Python/pandas + noções de eng. de dados | — | só se a vaga pedir |

> **Meta realista:** M0→M4 em **~8–10 semanas** num ritmo leve. No fim, você tem **1 projeto de portfólio** + fundamentos de SQL/Power BI = perfil de **Analista de Dados/BI Jr. com pegada de produção.**

---

## 📚 Os módulos

### M0 — Setup (1 dia)
**Objetivo:** ambiente pronto e você sabendo pedir ajuda pelo GitHub.
- [ ] Criar conta no GitHub + fazer **fork** deste repo (botão "Fork" no topo).
- [ ] Instalar **Power BI Desktop** (grátis, Microsoft Store) e **DB Browser for SQLite** (grátis).
- [ ] Ler o `PROGRESSO.md` — é onde você marca o que já fez.
- [ ] **Tarefa:** abrir uma Issue de teste ("M0 — cheguei!") pra treinar o canal de dúvidas.
- **Material:** [GitHub Skills — Introduction to GitHub](https://skills.github.com/) (grátis, 30 min).

### M1 — SQL & pensar em dados (~2 semanas)
**Objetivo:** buscar e cruzar dados — a linguagem universal de quem trabalha com dados.
- Conceitos: tabela, linha, coluna, chave · `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `JOIN`.
- **Material grátis (faça na ordem):**
  - [SQLBolt](https://sqlbolt.com/) — interativo, o melhor pra começar.
  - [Mode — SQL Tutorial](https://mode.com/sql-tutorial/) — do básico ao intermediário.
  - [W3Schools SQL](https://www.w3schools.com/sql/) — referência de consulta.
- **Tarefa:** baixar um dataset de manufatura no [Kaggle](https://www.kaggle.com/datasets?search=manufacturing) → abrir no DB Browser → escrever 5 consultas (ex.: produção total por linha, top 3 turnos com mais refugo, média de lead time por produto). Commitar os `.sql` na pasta `M1/`.
- **Pronto quando:** você consegue responder uma pergunta de negócio com uma consulta, sem copiar.

### M2 — Power BI essencial (~3–4 semanas)
**Objetivo:** transformar dado cru em dashboard — a ferramenta que as vagas pedem.
- Blocos: **Power Query** (limpar/transformar) → **Modelo** (relacionar tabelas, star schema básico) → **DAX** (medidas: `SUM`, `CALCULATE`, `DIVIDE`) → **Visuais** (gráficos certos pro dado certo).
- **Material grátis:**
  - [Microsoft Learn — Trilha PL-300](https://learn.microsoft.com/pt-br/training/courses/pl-300t00) (oficial, gratuito — a mesma cert que o Israel está tirando).
  - [Microsoft — Power BI in a Day](https://learn.microsoft.com/pt-br/power-bi/fundamentals/desktop-what-is-desktop).
  - [Guy in a Cube (YouTube)](https://www.youtube.com/@GuyInACube) — canal referência.
  - [SQLBI](https://www.sqlbi.com/) — quando chegar em DAX.
- **Tarefa:** pegar o CSV do M1 → Power Query pra limpar → 1 medida em DAX → 3 visuais numa página. Salvar o `.pbix` (ou `.pbip`) na pasta `M2/`.
- **Pronto quando:** você monta um dashboard simples do zero, sozinha.

### M3 — Análise aplicada à produção (~1 semana) — *seu superpoder*
**Objetivo:** conectar dado a decisão usando o que você JÁ sabe de produção.
- KPIs: **OEE** (Disponibilidade × Performance × Qualidade), refugo/scrap, PCP (planejado × realizado), lead time, aderência ao plano.
- Estatística descritiva: média, mediana, desvio, tendência (o essencial, sem academicismo).
- **Tarefa:** montar um painel com 4 KPIs de produção reais (OEE, refugo %, aderência PCP, lead time médio) com semáforo verde/vermelho. Pasta `M3/`.
- **Pronto quando:** o painel conta uma história ("onde estamos perdendo eficiência?"), não só mostra números.

### M4 — 🏆 Projeto de portfólio (~2 semanas) — *o que te contrata*
**Objetivo:** 1 projeto fim-a-fim, publicado, com narrativa — o diferencial na entrevista.
- Escolha um problema de produção (ex.: "Dashboard de Eficiência de Linha" ou "Controle de Qualidade & Refugo").
- Entregue: dados → modelo → dashboard → **README explicando problema → solução → insight.**
- Publique no seu GitHub (e, se quiser, no Power BI Service público).
- **Pronto quando:** você consegue apresentar em 3 min: "o problema era X, eu modelei Y, o insight foi Z." Isso é o que o entrevistador quer ouvir.

### M5 — Python & Eng. de Dados *(opcional, só depois de conseguir a vaga ou se a vaga pedir)*
- Python + pandas (manipulação de dados) · noções de ETL/pipeline. Não comece por aqui — é armadilha de escopo.

---

## ❓ Como pedir ajuda (o canal oficial)
Travou? **Abra uma [Issue](../../issues/new/choose)** — não some pra retomar depois. Diga: qual módulo, o que tentou, print/erro. Eu respondo por lá (async — quando eu conseguir, mas sempre respondo). É de propósito: aprender a **descrever um problema com clareza** é metade do trabalho de dados.

## ✅ Progresso
Marque seu avanço em [`PROGRESSO.md`](./PROGRESSO.md).

---
_Trilha viva — vai sendo lapidada conforme você avança. Bom começo! 🚀_
