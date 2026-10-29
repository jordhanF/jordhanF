<div align="center">

# Oi, eu sou o Jordhan 👋

### Desenvolvedor · ERP e integrações · Sankhya · TypeScript, Python e Java

Trabalho onde o software encontra a operação: ERP, BI e aplicativos que rodam na mão
de quem vende na rua, confere estoque no galpão e emite nota no fim do dia.

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jordhan-fernandes-727729142/)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jordhannassis@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jordhanF)

</div>

---

## 🧭 No que eu trabalho

**ERP Sankhya para três distribuidoras.** Regras fiscais, faturamento, carteira de
clientes e os relatórios que a operação usa para fechar o mês. Muita consulta SQL,
muita integração e nenhuma tolerância a número errado.

**App de vendas que roda offline.** O vendedor monta o pedido no celular dentro do
cliente, sem sinal, e o pedido sobe quando a rede volta. A parte difícil não é a tela:
é a fila de sincronização, a reconciliação com o ERP e descobrir *por que* um valor
mudou entre o celular e a nota.

**WMS e coletor de código de barras.** Endereçamento, inventário e conferência em
coletor Android. Bipagem errada não pode virar estoque errado.

> A maior parte desse trabalho vive em repositório privado da empresa. O que está
> público aqui são projetos de faculdade, estudos e coisas que eu construí por conta.

---

## 🛠️ Com o que eu construo

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Mobile e front**

![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Infra e testes**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 📌 Projetos

### [sd-2026-2-kit-c2a2](https://github.com/jordhanF/sd-2026-2-kit-c2a2) — RAG distribuído em microsserviços

Sistema de perguntas e respostas sobre documentos próprios, quebrado em três serviços
independentes mais um worker de fila. A chamada ao LLM é protegida por **circuit breaker,
tempo-limite e retentativa** — e a diferença aparece medida: uma falha custa 2,04 s com o
circuito fechado e 0,01 s depois que ele abre.

Tem uma decisão de arquitetura de que eu gosto: a recuperação **não** reconstrói o
vocabulário do índice, ela pede o vetor a quem é dono dele. Duas cópias divergindo dariam
similaridades plausíveis e erradas — sem erro nenhum. Falha silenciosa é pior que falha
ruidosa.

`Python` · `FastAPI` · `Redis` · `Docker` · 47 testes offline, provados por mutação

### [chromesthesia](https://github.com/jordhanF/chromesthesia) — visualizador de música

Navegador visual de presets sobre o libprojectM 4.1.4, com pad de emoção e geração de
preset por LLM. Nasceu de um problema concreto: escolher preset de visualizador no escuro,
no meio da música, é horrível.

`Python` · `libprojectM`

### [Cliente-Bancario](https://github.com/jordhanF/Cliente-Bancario) — gestão de clientes

Teste técnico: sistema de gerenciamento de clientes bancários, com o front inteiro tipado.

`TypeScript` · `React` · `Vite`

### [ProjetoIntegradorIII](https://github.com/jordhanF/ProjetoIntegradorIII) — poluição do ar e doenças respiratórias

Análise do impacto da poluição do ar na incidência de doenças respiratórias: coleta,
limpeza e visualização dos dados até a conclusão.

`Jupyter` · `Python` · `Pandas`

---

## 📊 Números

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jordhanF&theme=github_dark#gh-dark-mode-only" alt="Resumo do perfil" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jordhanF&theme=default#gh-light-mode-only" alt="Resumo do perfil" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=jordhanF&theme=github_dark#gh-dark-mode-only" alt="Linguagens por repositorio" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=jordhanF&theme=github_dark#gh-dark-mode-only" alt="Linguagens por commit" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=jordhanF&theme=default#gh-light-mode-only" alt="Linguagens por repositorio" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=jordhanF&theme=default#gh-light-mode-only" alt="Linguagens por commit" />

</div>

> O gráfico conta só o que é público. O dia a dia é bem mais TypeScript e SQL do que ele mostra.

---

## 🎓 Agora

Terminando a graduação na **FAESA**, com o artigo de TCC sobre automação de divulgação
com IA previsto para novembro. Estudando sistemas distribuídos — consenso, replicação e o
que fazer quando a dependência do outro lado simplesmente não responde.

---

<div align="center">

**Quer conversar?**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jordhan-fernandes-727729142/)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jordhannassis@gmail.com)

</div>
