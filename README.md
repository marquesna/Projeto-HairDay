# 💇‍♀️ Hair Day

<p align="center">
  <img src="src/assets/logo.svg" alt="Hair Day Logo" width="200px">
</p>

<p align="center">
  Uma aplicação web moderna e intuitiva para o gerenciamento e agendamento de horários em salões de beleza e barbearias.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-concluído-brightgreen?style=for-the-badge" alt="Status Concluído">
  <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black" alt="Webpack">
  <img src="https://img.shields.io/badge/day.js-000000?style=for-the-badge&logo=javascript&logoColor=white" alt="Day.js">
</p>

---

## 📋 Sobre o Projeto

O **Hair Day** foi desenvolvido para solucionar a organização diária de agendamentos de cortes de cabelo e serviços estéticos. O sistema permite que o usuário selecione uma data, visualize os horários disponíveis (divididos entre manhã, tarde e noite) de forma dinâmica, filtre horários passados ou já ocupados, e registre o atendimento de forma rápida e integrada com uma API local (`json-server`).

---

## ✨ Funcionalidades

- **Agendamento Dinâmico:** Seleção de datas a partir do dia atual com carregamento automático dos horários livres.
- **Divisão por Períodos:** Organização visual clara dos horários em **Manhã**, **Tarde** e **Noite**.
- **Validação Inteligente:** Bloqueio automático de horários que já passaram ou que já possuem agendamento confirmado.
- **Cadastro de Clientes:** Inclusão do nome do cliente atrelada ao horário escolhido.
- **Painel de Acompanhamento:** Visualização em tempo real dos agendamentos marcados para o dia selecionado.
- **Cancelamento de Atendimentos:** Opção para remover agendamentos cadastrados de forma simples e segura.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias e ferramentas:

- **HTML5 & CSS3** (com variáveis customizadas, Flexbox e Grid)
- **JavaScript (ES6+)**
- **Day.js** (manipulação e formatação de datas e horários em português)
- **Webpack** (empacotador de módulos, Babel e Webpack Dev Server)
- **JSON Server** (simulação de API REST para persistência dos agendamentos)

---

## 📁 Estrutura do Projeto

hairday/
├── src/
│   ├── assets/         # Ícones, imagens e logotipos
│   ├── libs/           # Configuração de bibliotecas (ex: Day.js)
│   ├── modules/        # Regras de negócio e manipulação do DOM (form, schedules)
│   ├── services/       # Comunicação com a API (fetch)
│   ├── styles/         # Arquivos de estilização modularizados (global, form, schedule)
│   └── main.js         # Ponto de entrada da aplicação
├── index.html          # Interface principal
├── server.json         # Banco de dados simulado para o JSON Server
├── package.json        # Dependências e scripts do projeto
└── webpack.config.js   # Configuração do Webpack



🚀 Como Executar o Projeto
Certifique-se de ter o Node.js instalado em sua máquina.

Clone o repositório:

Bash
git clone [https://github.com/marquesna/hairday.git](https://github.com/marquesna/hairday.git)
cd hairday
Instale as dependências:

Bash
npm install
Inicie o JSON Server (API simulada):
(O servidor rodará na porta 3333)

Bash
npm run server
Inicie o ambiente de desenvolvimento (Webpack Dev Server):
(Em outro terminal, abra o projeto e execute o comando abaixo. A aplicação abrirá automaticamente no navegador na porta 3000)

Bash
npm run dev
👩‍💻 Autora
Desenvolvido por Natalia Marques.
