# 📊 Trilha de Dados — de Engenharia de Produção para Analista de Dados / BI

> Trilha prática e enxuta pra quem **já entende de negócio/produção** e quer **entrar em dados** (análise + Power BI) e conquistar uma **vaga melhor** — sem enrolação, orientada a **um projeto real que você constrói do começo ao fim**.
>
> **Autor/mentor:** Israel Rebouças · **Formato:** você segue os módulos, constrói o projeto, e me chama quando travar.

---

## 🆘 Travou? **Me chama no WhatsApp.**

Sério: é o canal oficial de dúvida desta trilha. Sem formulário, sem cerimônia, sem precisar saber explicar. Pode ser literalmente *"travei, não sei o que fazer"* — de preferência **com um print da tela**.

> **Pergunta idiota não existe aqui.** Toda dúvida que você tiver, outra pessoa vai ter — e vira material da trilha. Você está me ajudando a melhorar isso.
>
> **Não some pra "voltar quando entender".** Travar faz parte; ficar travada sozinha, não. É exatamente aí que eu entro.

*(Se em algum momento você preferir registrar por escrito, dá pra [abrir uma Issue aqui](https://github.com/Israelar/trilha-dados/issues/new/choose) — mas é opcional, não um pré-requisito.)*

---

## 🎯 A estratégia (leia primeiro — 2 min)

**Seu objetivo não é virar "cientista de dados" em 1 ano.** É ficar **empregável em análise de dados/BI o mais rápido possível.** As vagas pedem "análise de dados, Power BI, SQL" — então é nisso que a gente foca.

**Seu superpoder:** você é **engenheira de produção.** Você já entende OEE, refugo, PCP, lead time, qualidade, indicadores. A maioria de quem entra em dados **não entende o negócio** — você entende. Seu portfólio vai ser em **domínio de produção/manufatura**, e isso te coloca na frente de qualquer bootcamp genérico numa entrevista.

**Como aprender:** construindo **uma coisa só**, que cresce a cada módulo.

---

## 🏗️ O projeto que você vai construir (a espinha da trilha)

Você **não vai fazer exercícios soltos.** Do M1 ao M4, você constrói **um único projeto**, que ganha uma camada nova a cada módulo:

```
   M1              M2                  M3               M4
 ┌──────┐      ┌─────────┐        ┌──────────┐     ┌──────────┐
 │ BASE │  →   │ ETL +   │   →    │  KPIs    │  →  │DASHBOARD │
 │ DE   │      │ MODELO  │        │ (OEE,    │     │PUBLICADO │
 │DADOS │      │         │        │ refugo…) │     │+ README  │
 └──────┘      └─────────┘        └──────────┘     └──────────┘
  "os dados     "dado limpo e      "os números      "a história
   existem"      relacionado"       que importam"    que convence"
```

**No fim você tem UM projeto completo, de ponta a ponta** — dos dados crus até o painel publicado. É isso que você mostra na entrevista, não uma pasta de exercícios.

> 💡 **Escolha o tema agora, no M0.** Sugestões: *"Dashboard de Eficiência de Linha"*, *"Controle de Qualidade & Refugo"*, *"Aderência ao PCP"*. Escolher cedo faz cada módulo ter propósito.

---

## 🗺️ O mapa: onde você está pisando

Trabalhar com dados é uma cadeia. Vale saber a cadeia inteira — mesmo que você não domine tudo agora:

```
 fonte → ingestão → armazenamento → transformação → modelagem → visualização → decisão
                                    └──────────── VOCÊ VAI DOMINAR ISTO ────────────┘
         └──── você vai SABER QUE EXISTE (e conversar sobre) ────┘
```

**Por que isso importa:** numa entrevista você não precisa ser especialista em tudo — mas precisa **não parecer ingênua**. Saber que existe ingestão, pipeline e engenharia de dados (e onde seu trabalho encaixa) te faz soar sênior mesmo sendo júnior.

**A regra:** profundidade onde emprega, mapa no resto. Isso se chama perfil **T** — e é o que o mercado quer.

---

## 🚦 A trilha (4 módulos + 1 opcional)

| Módulo | O que você sai sabendo | Tempo | Camada do projeto |
|---|---|---|---|
| **M0** — Setup | ambiente pronto, GitHub, como pedir ajuda | 1 dia | escolher o tema |
| **M1** — SQL & pensar em dados | consultar dados (SELECT, filtro, JOIN, agrupamento) | ~2 sem | **a base de dados** |
| **M2** — Power BI essencial | ETL, modelo, DAX, visuais **+ boas práticas** | ~3–4 sem | **ETL + modelo** |
| **M3** — Análise aplicada à produção | KPIs (OEE, refugo, PCP), estatística descritiva | ~1 sem | **os indicadores** |
| **M4** — 🏆 Projeto de portfólio | dashboard publicado + narrativa **+ UI/UX** | ~2 sem | **o produto final** |
| **M5** *(opcional)* | Python/pandas + noções de eng. de dados | — | automação |

> **Meta realista:** M0→M4 em **~8–10 semanas** num ritmo leve. No fim: **1 projeto de portfólio completo** + fundamentos de SQL/Power BI = perfil de **Analista de Dados/BI Jr. com pegada de produção.**

---

## 📚 Os módulos

### M0 — Setup (1 dia)
**Objetivo:** ambiente pronto e o tema escolhido. **Nada de GitHub por enquanto.**
- [ ] Instalar **Power BI Desktop** (grátis, Microsoft Store) e **DB Browser for SQLite** (grátis).
- [ ] **Escolher o tema do seu projeto** — anote no `PROGRESSO.md` (baixe este arquivo ou copie pra um bloco de notas seu).
- [ ] **Tarefa:** me manda no WhatsApp o **tema que você escolheu**. Só isso. É o "oi, cheguei" da trilha. 🙂

> ℹ️ **Por que ainda não tem GitHub aqui?** Porque ele só faz sentido quando você tiver algo pra guardar — e isso acontece no M1. Aprender ferramenta antes de ter necessidade é o jeito mais rápido de desanimar. Uma coisa de cada vez.

### M1 — SQL & pensar em dados (~2 semanas)
**Camada do projeto:** 🗄️ **a base de dados**
**Objetivo:** buscar e cruzar dados — a linguagem universal de quem trabalha com dados.

> 🐙 **Agora sim, o GitHub** — porque agora você tem algo pra guardar.
> - Crie sua conta no GitHub e depois **crie um repositório SEU** (botão verde **New**), com o nome do seu projeto (ex.: `projeto-eficiencia-linha`).
> - ⚠️ **Não use o botão "Fork" neste repositório aqui.** Fork faz uma cópia congelada — você deixaria de ver as melhorias da trilha, e já deu confusão antes. Este repo aqui é seu **material de leitura**; o seu repo é onde mora **o seu projeto**.
> - Vantagem: esse repositório **é o seu portfólio**. É o link que vai no seu LinkedIn e na entrevista.
> - Material (opcional): [GitHub Skills — Introduction to GitHub](https://skills.github.com/) (grátis, 30 min).

- Conceitos: tabela, linha, coluna, chave · `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `JOIN`.
- **Material grátis (na ordem):**
  - [SQLBolt](https://sqlbolt.com/) — interativo, o melhor pra começar.
  - [Mode — SQL Tutorial](https://mode.com/sql-tutorial/) — básico → intermediário.
  - [W3Schools SQL](https://www.w3schools.com/sql/) — referência de consulta.
- **Tarefa:** baixar um dataset de manufatura no [Kaggle](https://www.kaggle.com/datasets?search=manufacturing) → abrir no DB Browser → escrever 5 consultas que respondam perguntas de negócio (ex.: produção total por linha, top 3 turnos com mais refugo, lead time médio por produto). Salvar os `.sql` numa pasta `M1/` **no seu repositório**.
- **Pronto quando:** você responde uma pergunta de negócio com uma consulta, sem copiar.

> 🔥 **Modo hard (opcional — só se quiser puxar mais):** em vez de SQLite, subir um **PostgreSQL** (local ou grátis no [Neon](https://neon.tech)) e carregar os dados lá. Ganho: experiência com banco de verdade. Custo: instalação/configuração. **Não faça isso na primeira passada** — SQLite é arquivo, zero instalação, e ensina o mesmo SQL.

### M2 — Power BI essencial (~3–4 semanas)
**Camada do projeto:** ⚙️ **ETL + modelo**
**Objetivo:** transformar dado cru em modelo confiável.
- Blocos: **Power Query** (limpar/transformar) → **Modelo** (relacionar tabelas, star schema) → **DAX** (medidas: `SUM`, `CALCULATE`, `DIVIDE`) → **Visuais**.
- **Material grátis:**
  - [Microsoft Learn — Trilha PL-300](https://learn.microsoft.com/pt-br/training/courses/pl-300t00) (oficial, gratuito).
  - [Microsoft — Power BI in a Day](https://learn.microsoft.com/pt-br/power-bi/fundamentals/desktop-what-is-desktop).
  - [Guy in a Cube (YouTube)](https://www.youtube.com/@GuyInACube) — canal referência.
  - [SQLBI](https://www.sqlbi.com/) — quando chegar em DAX.

> #### ✅ Boas práticas (o que separa júnior de "júnior que parece pleno")
> - **Star schema:** tabelas de fato (o que aconteceu: produção, refugo) no centro, dimensões (produto, turno, linha, data) ao redor. **Não jogue tudo numa tabela só** — é o erro nº1.
> - **Tabela de datas própria** — e desligue o *Auto Date/Time* (Opções → Carregar Dados). Ele cria dezenas de tabelas ocultas e incha o modelo.
> - **Nomes que um humano entende:** `Refugo (%)`, não `col_ref_pct_v2`. Seu eu do futuro agradece.
> - **Medida DAX > coluna calculada** sempre que der (mais leve).
> - **Documente:** um `README.md` na pasta dizendo de onde vêm os dados e o que cada medida significa.

- **Tarefa:** pegar a base do M1 → limpar no Power Query → montar o modelo (star schema) → 1 medida em DAX → 3 visuais. Salvar em `M2/` no seu repositório.
- **Pronto quando:** você monta um modelo do zero, sozinha, e sabe explicar por que separou as tabelas.

### M3 — Análise aplicada à produção (~1 semana) — *seu superpoder*
**Camada do projeto:** 📈 **os indicadores**
**Objetivo:** conectar dado a decisão usando o que você JÁ sabe.
- KPIs: **OEE** (Disponibilidade × Performance × Qualidade), refugo/scrap, PCP (planejado × realizado), lead time, aderência ao plano.
- Estatística descritiva: média, mediana, desvio, tendência (o essencial, sem academicismo).
- **Tarefa:** 4 KPIs de produção no seu modelo (OEE, refugo %, aderência PCP, lead time) com semáforo verde/vermelho. Pasta `M3/` no seu repositório.
- **Pronto quando:** o painel responde *"onde estamos perdendo eficiência?"* — não só mostra números.

### M4 — 🏆 Projeto de portfólio (~2 semanas) — *o que te contrata*
**Camada do projeto:** 🎨 **o produto final**
**Objetivo:** o projeto publicado, com cara profissional e narrativa.

> #### 🎨 UI/UX de dashboard — onde 90% dos juniores perdem a vaga
> O recrutador julga seu painel em **3 segundos**, antes de ler qualquer número. Estes princípios valem mais que 10 medidas DAX:
>
> 1. **O teste dos 5 segundos.** Mostre pra alguém e pergunte: *"o que isso está te dizendo?"* Se a pessoa não souber, o painel falhou — não importa quão certo esteja o dado.
> 2. **Hierarquia visual.** O número mais importante é o maior e fica em cima à esquerda (é onde o olho começa). O resto é apoio.
> 3. **Menos é mais.** Uma página com 6 visuais bem escolhidos vence uma com 30. Se tudo grita, nada é ouvido.
> 4. **Cor tem significado, não decoração.** Escolha 1 cor de destaque + tons neutros. Vermelho/verde **só** para status (ruim/bom) — nunca pra "ficar bonito". Cuidado: ~8% dos homens não distingue vermelho de verde — use também ícone ou texto.
> 5. **O gráfico certo pro dado certo.** Comparar categorias → barras. Evolução no tempo → linhas. Parte do todo → evite pizza (barra empilhada é mais legível). Um número único → cartão.
> 6. **Contexto sempre.** "Refugo: 4,2%" não diz nada. "Refugo: 4,2% ▲ vs meta de 3%" diz tudo.
> 7. **Respire.** Espaço em branco não é desperdício — é o que deixa o olho descansar e encontrar o que importa.

- **Entregue:** dados → modelo → dashboard → **README com problema → solução → insight**.
- Finalize **o seu repositório** (aquele do M1) — ele agora é o seu portfólio. É este link que vai no LinkedIn e na entrevista. (Se quiser, publique também no Power BI Service público.)
- **Pronto quando:** você apresenta em 3 min: *"o problema era X, eu modelei Y, o insight foi Z."* É exatamente o que o entrevistador quer ouvir.

### M5 — Python & Eng. de Dados *(opcional — só depois da vaga, ou se a vaga pedir)*
- Python + pandas · noções de ETL/pipeline · agendamento.
- **Não comece por aqui** — é armadilha de escopo. A vaga de BI Jr. não pede.

---

## ✅ Progresso
Marque seu avanço em [`PROGRESSO.md`](./PROGRESSO.md).

---
_Trilha viva — vai sendo lapidada conforme você avança. Cada dúvida sua melhora ela pra próxima pessoa. Bom começo! 🚀_
