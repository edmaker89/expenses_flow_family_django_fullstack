# 💸 ExpenseFlow Family

## Visão Geral do Projeto
O **ExpenseFlow Family** é um sistema web para gerenciar despesas familiares, inspirado em planilhas financeiras. Ele permite o registro detalhado de gastos familiares, categorizados por pessoa, instituição e categoria, além de funcionalidades como controle de pagamentos, parcelamentos e geração de relatórios visuais. O objetivo é oferecer uma visão clara e organizada das finanças domésticas de forma simples e prática.

---

## 🛠️ Funcionalidades Principais

### Funcionalidades Gerais
- 📝 **Cadastro de despesas:**
  - Descrição, valor, instituição, pessoa responsável, data de vencimento, categoria e detalhes de parcelamento.  

- ✅ **Marcação de status:**
  - Controle dinâmico permitindo marcar despesas como pagas ou pendentes.

- 📊 **Relatórios e dashboards:**
  - Resumos visuais com gráficos para análise de despesas por pessoa, categoria e instituição, integrados ao **Chart.js**.

- 🔍 **Busca e filtros avançados:**
  - Pesquisas detalhadas e filtragem de despesas por datas, categorias ou valores.

- 🔑 **Usuários autenticados:**
  - Sistema seguro de login/logout para cada membro familiar acompanhar suas finanças.

- 📱 **Interface responsiva:**
  - Total adaptação para uso em computadores, tablets e smartphones.

---

## 🏗️ Estrutura do Projeto
O sistema foi modularizado para manter escalabilidade e organização. Cada parte tem responsabilidades específicas:

### Diretórios
- 📂 `familymanager/`: Configurações globais do projeto.
- 📂 `accounts/`: Gerenciamento de usuários (registro, login, autenticação).
- 📂 `expenses/`: CRUD de despesas e geração de relatórios.
- 📂 `static/`: Arquivos estáticos, como CSS e JavaScript.
- 📂 `media/`: Repositório para upload de comprovantes de despesas (se implementado).

---

## ⚙️ Tecnologias Utilizadas

- **Backend:**
  - 🐍 Python com Django (ORM poderoso, segurança nativa e facilidade de escalabilidade).
  
- **Banco de Dados:**
  - SQLite (desenvolvimento) e PostgreSQL (produção).

- **Frontend:**
  - HTML5, CSS3, JavaScript, e **TailwindCSS** para design responsivo.

- **Gráficos:**
  - 📊 Chart.js para visualizações dinâmicas de dados (gráficos de barras, pizza e linhas).

- **Infraestrutura:**
  - Docker para containerização e GitHub Actions para CI/CD.

---

## 🚀 Roadmap de Desenvolvimento

- **Fase 1 (1-2 semanas):**
  - Configurar projeto Django e criar modelos (modelagem de dados).  
  - Adicionar registros iniciais via admin.

- **Fase 2 (2-3 semanas):**
  - Implementar sistema CRUD para despesas.  
  - Configurar autenticação de usuários (login, logout, proteção de rotas).

- **Fase 3 (2-3 semanas):**
  - Criar dashboards e relatórios interativos com **Chart.js**.  
  - Adicionar campos de busca e filtros para listagem de despesas.

- **Fase 4 (1 semana):**
  - Refinar UI/UX, adicionar mensagens de feedback e escrever documentação.

- **Fase 5 (1-2 semanas, opcional):**
  - Realizar deploy em serviços como Heroku, DigitalOcean ou Railway.  
  - Implementar notificações por email para despesas próximas do vencimento.

---

## 🧑‍💻 Melhores Práticas de Desenvolvimento

- **Design Patterns:**
  - Adotar padrões como MVC (MVT no Django) e princípios DRY e KISS.

- **Testes:**
  - Utilizar testes unitários (models, views) e testes de integração simulando interações reais. Ferramentas sugeridas: `unittest` ou `pytest`.

- **Controle de versão:**
  - Commit messages semânticos (ex.: `feat: adiciona funcionalidade X`).
  - GitHub Flow para organização: branches por funcionalidade e PRs para merge seguro.

- **Dockerização:**
  - Isolamento de ambiente para garantir consistência entre dev e produção.

---

## 📜 Estrutura de Documentação

1. 📋 **README.md:**
   - Documentação principal com visão geral, instalação, dependências e uso.

2. 📄 **Docstrings e comentários:**
   - Descritivos nas funções e classes no código para facilitar entendimento.

3. 📦 **`requirements.txt`:**
   - Lista de dependências Python necessárias.

4. 🔒 **LICENSE:**
   - Licença de código aberto escolhida (MIT, GPL, etc.).

---

## 🏷️ Tags Sugeridas

`Python` `Django` `Chart.js` `Full Stack` `Expense Management` `TailwindCSS` `PostgreSQL` `Web Application` `Docker`

---

## 😃 Funcionalidades Futuras

Para ampliar ainda mais a utilidade e o impacto do projeto:
- 🔔 **Notificações de vencimento:**
  - Sistema de alertas para despesas vencidas ou próximas do vencimento.
  
- 📆 **Orçamento mensal:**
  - Controle de limite de gastos por categoria ou instituição.  

- 📷 **Upload de comprovantes:**
  - Anexar imagens de comprovantes às despesas cadastradas.
 
- 📱 **Integração com Whatsapp:**
  - Permitir registros de depesas
  - Permitir consulta de orçamento e valor total das despesas
  - Ter um assistente de finanças com o contexto atualizado

---

**Desenvolvido com ❤️ e foco em organização financeira.**
