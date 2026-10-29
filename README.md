<h1 align="center">Olá, eu sou a Ester Neves 👋</h1>

<p align="center">
  <b>Desenvolvedora Júnior e QA</b> · APIs REST em Java e Spring Boot · Automação de testes · Bacharel em Direito
</p>

<p align="center">
  <a href="https://linkedin.com/in/esterneves"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ester.charm@hotmail.com"><img src="https://img.shields.io/badge/E--mail-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="E-mail"></a>
</p>

---

### 🔎 Sobre mim

Sou desenvolvedora júnior com foco em qualidade: construo APIs REST em Java e Spring Boot e interfaces em React, e testo o que faço em várias camadas, então sei **como o sistema é feito, o que pode quebrar e onde investigar**. Meu foco é **desenvolvimento com qualidade e automação de testes**.

- ☕ **API REST em Java e Spring Boot** com PostgreSQL, Docker, perfis de acesso e testes unitários, de integração e de API, com cobertura mínima exigida no build
- 🧪 Automação de testes de **API** (pytest + requests) e **Web** (Playwright + Page Object Model)
- 🥒 **BDD** com pytest-bdd: cenários em Gherkin escritos em português, que o negócio lê e a automação executa
- ⚡ **Testes de performance** com k6: fumaça, carga e estresse, com limites de aceitação que fazem o CI falhar quando estourados
- 📱 **Automação mobile** com Maestro: fluxos declarativos em YAML sobre apps Android, executando em emulador no CI, incluindo um app React Native com testes unitários (Jest) e de ponta a ponta
- 📊 **Relatórios públicos**: Allure e k6 publicados no GitHub Pages a cada execução, com histórico de tendência e evidência anexada nas falhas
- 📝 Teste manual e exploratório: **plano de teste, casos de teste e relatório de bugs** com severidade e evidência
- 🔁 Integração contínua com **GitHub Actions**
- 🤖 Residência em **IA Generativa e RAG** (Instituto ECOA / PUC-Rio)
- 🎯 **Teste e avaliação de sistemas de IA**: benchmark com rubrica de aceitação, avaliação separada de recuperação e geração, e casos adversariais de vazamento de dado
- ⚖️ Bacharel em Direito: leitura crítica de requisitos, atenção a detalhes e conhecimento de **LGPD**
- 🎓 Estudante de **Análise e Desenvolvimento de Sistemas**

---

### 🚀 Projetos em destaque

| Projeto | O que é | Tecnologias |
|---|---|---|
| 🧪 [**QA Automation – ServeRest**](https://github.com/EsterNevess/qa-automation-serverest) | 35 testes automatizados de API e Web, com validação de contrato, Page Object Model e CI · [📊 relatório Allure](https://esternevess.github.io/qa-automation-serverest/) | Python · pytest · Playwright · GitHub Actions |
| 🥒 [**BDD com pytest-bdd – Saucedemo**](https://github.com/EsterNevess/qa-bdd-saucedemo) | Os 13 cenários Gherkin acima, agora **executando**: o mesmo texto em português que o negócio lê é o que a automação roda. Page Object Model, evidência em print quando um cenário falha e CI · [📊 relatório Allure](https://esternevess.github.io/qa-bdd-saucedemo/) | Python · pytest-bdd · Playwright · GitHub Actions |
| ⚡ [**Performance com k6 – ServeRest**](https://github.com/EsterNevess/qa-performance-serverest) | Testes de fumaça, carga e estresse com limites de aceitação explícitos e métricas por operação. Carga de 10 usuários: 1.339 requisições, 0% de erro, p(95) de 6 ms. Estresse até 100 usuários: 123 req/s — e o README explica por que **não** achei o ponto de ruptura · [📊 relatório](https://esternevess.github.io/qa-performance-serverest/) | k6 · JavaScript · GitHub Actions |
| 📲 [**Loja Demo – React Native com testes**](https://github.com/EsterNevess/rn-loja-demo) | App Android em React Native (Expo) com login, lista de produtos, detalhe e carrinho, e a suíte que o testa: **29 testes unitários** em Jest e **5 fluxos de ponta a ponta** com Maestro, rodando em **emulador dentro do CI**, com relatório Allure · [📊 relatório](https://esternevess.github.io/rn-loja-demo/) | React Native · Expo · Jest · Maestro · GitHub Actions |
| 📱 [**Automação mobile com Maestro**](https://github.com/EsterNevess/qa-mobile-maestro) | Testes de aplicativo Android nativo em fluxos declarativos de YAML, rodando em **emulador dentro do CI**: login válido, login inválido e carrinho. Os seletores saíram da leitura da fonte do app — no Android ele usa `accessibilityLabel`, não `testID` · [📊 relatório Allure](https://esternevess.github.io/qa-mobile-maestro/) | Maestro · Android · YAML · GitHub Actions |
| 🤖 [**VendeFácil – Assistente RAG**](https://github.com/EsterNevess/rag-vendefacil) | Camada de qualidade de um assistente de IA: **130 testes automatizados**, benchmark de 24 casos com rubrica de aceitação, teste adversarial de vazamento de credenciais e teste de regressão para dado sensível. Investigar um defeito na própria validação levou o resultado de 58,3% para **71,9%** | Python · pytest · LangChain · FAISS |
| ☕ [**API de Tarefas – Java e Spring Boot**](https://github.com/EsterNevess/api-tarefas-spring) | API REST de gestão de tarefas com fluxo de status, três perfis de acesso e prazo calculado em dias úteis. PostgreSQL com Flyway e Docker Compose. **71 testes JUnit** (o build falha abaixo de 85% de cobertura), **23 testes de API** em pytest e um smoke de desempenho com k6, tudo no CI · [📊 relatório Allure](https://esternevess.github.io/api-tarefas-spring/) · [cobertura](https://esternevess.github.io/api-tarefas-spring/cobertura/) | Java · Spring Boot · PostgreSQL · Docker · JUnit · pytest · k6 |
| 🐞 [**Plano de Teste e Relatório de Bugs – ServeRest**](https://github.com/EsterNevess/qa-plano-de-testes-bugs) | Plano de teste, 30 casos executados e 10 bugs reais registrados como issues, com severidade, passos e evidência | Teste manual de API · Casos de teste · Bug report · GitHub Issues |
| 🧾 [**Teste Manual de E-commerce – Saucedemo**](https://github.com/EsterNevess/qa-saucedemo-teste-manual) | 25 cenários e casos de teste (Gherkin e passo a passo), análise de riscos, sugestão de automação e bugs registrados como issues | Teste manual de interface · Gherkin · Casos de teste · GitHub Issues |
| 📋 [**Tarefiz**](https://github.com/EsterNevess/tarefiz-portfolio) | Sistema de gestão de tarefas para uma demanda real da Alterdata (Residência SERRATEC) | React · Vite · JavaScript |
| 📐 [**RAG Jurídico – Arquitetura**](https://github.com/EsterNevess/rag-juridico-arquitetura) | **Projeto de arquitetura, sem código:** dois sistemas RAG jurídicos (due diligence de M&A e jurisprudência), com chunking por cláusula e por seção, comparação de modelos de embedding e análise de quando RAG **não** é a resposta | Arquitetura · RAG · Embeddings |

---

### 🛠️ Ferramentas e tecnologias

**Qualidade e testes**

![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![pytest-bdd](https://img.shields.io/badge/pytest--bdd-23D96C?style=for-the-badge&logo=cucumber&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Maestro](https://img.shields.io/badge/Maestro-6C4CF1?style=for-the-badge&logo=android&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit%205-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-4000BF?style=for-the-badge&logo=insomnia&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![k6](https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Desenvolvimento**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**IA e métodos ágeis**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Scrum](https://img.shields.io/badge/Scrum-0052CC?style=for-the-badge&logo=scrumalliance&logoColor=white)

---

### 📚 Formação e trilha

- 🎓 Tecnólogo em Análise e Desenvolvimento de Sistemas – Gran Faculdade (2026 – 2029, em andamento)
- 🤖 Residência em IA Generativa e RAG – Instituto ECOA / PUC-Rio (2026)
- 💻 Residência em TIC/Software, Desenvolvedora Full Stack – SERRATEC / FIRJAN / SENAI (2025, 790 h)
- ✅ Introdução à Qualidade de Software – FEST / T2M (2026)
- 🏅 Scrum Fundamentals Certified (SFC) – SCRUMstudy (2026)
- ⚖️ Bacharelado em Direito – Universidade Estácio de Sá (2021)

---

<p align="center"><i>"Qualidade não é uma etapa no fim do projeto: é um cuidado em cada parte dele."</i></p>
