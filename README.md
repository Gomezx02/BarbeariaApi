# 💈 Gerenciador de Agendamentos de Barbearia

Sistema web desenvolvido para gerenciar agendamentos de uma barbearia, permitindo que clientes realizem reservas de horários e que barbeiros administrem sua agenda de forma prática e organizada.

O projeto está sendo desenvolvido com foco em aprendizado de desenvolvimento Full Stack, utilizando tecnologias modernas como **C#**, **.NET**, **ASP.NET**, **Node.js** e **React**, seguindo boas práticas de programação e arquitetura de software.

---

## 📋 Sobre o Projeto

O objetivo deste sistema é permitir que clientes realizem agendamentos de forma simples, enquanto o barbeiro pode visualizar, organizar e gerenciar todos os horários disponíveis.

Além das funcionalidades principais, o projeto foi desenvolvido com foco em:

* Clean Code
* Organização em camadas
* Testes Unitários
* Observabilidade básica
* Boas práticas utilizadas no mercado

---

## 🚀 Tecnologias Utilizadas

### Front-end

* React
* HTML5
* CSS3
* JavaScript


### Back-end

* Node.js
* Express.js
* .Net
* ASP.NET

### Banco de Dados

* MongoDB

### Testes

* Jest

### Ferramentas

* Git
* GitHub
* Visual Studio Code
* Postman

---

## 📂 Estrutura do Projeto

```text
barbearia/
│
├── backend/
│   ├── src/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   └── tests/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── assets/
│
└── README.md
```

---

## ⚙️ Funcionalidades

* Cadastro de clientes
* Cadastro de barbeiros
* Criação de agendamentos
* Cancelamento de agendamentos
* Consulta de horários disponíveis
* Atualização do status do atendimento
* Interface intuitiva para gerenciamento dos horários
* Sistema básico de logs
* Testes unitários das principais regras de negócio

---

## 📅 Cronograma de Desenvolvimento

O projeto foi desenvolvido seguindo um cronograma de 14 dias.

| Dia   | Atividade                                       |
| ----- | ----------------------------------------------- |
| 1-2   | Configuração do ambiente e estrutura do projeto |
| 3-4   | Modelagem do banco de dados                     |
| 5-7   | Desenvolvimento das regras de negócio           |
| 8-9   | Desenvolvimento da interface em React           |
| 10-11 | Implementação de testes unitários               |
| 12    | Observabilidade e sistema de logs               |
| 13    | Debug e análise da aplicação                    |
| 14    | Deploy e documentação                           |

---

## 🗄️ Modelo de Dados

### Cliente

* Nome
* Telefone

### Barbeiro

* Nome
* Especialidade

### Agendamento

* Cliente
* Barbeiro
* Data
* Horário
* Status

---

## 🧪 Testes

Foram implementados testes unitários para validar as principais regras de negócio da aplicação, garantindo maior confiabilidade durante o desenvolvimento.

Entre os cenários testados:

* Criação de agendamentos
* Cancelamento de agendamentos
* Validação de horários disponíveis
* Regras de disponibilidade

---

## 📊 Observabilidade

A aplicação possui um sistema básico de logs para registrar:

* Inicialização do servidor
* Requisições realizadas
* Erros da aplicação
* Eventos importantes do sistema

Esses registros auxiliam na identificação de problemas durante a execução da aplicação.

---

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/barbearia.git
```

### 2. Entre na pasta

```bash
cd barbearia
```

### 3. Instale as dependências

Back-end

```bash
cd backend
npm install
```

Front-end

```bash
cd frontend
npm install
```

### 4. Execute o projeto

Back-end

```bash
npm start
```

Front-end

```bash
npm start
```

---

## 🎯 Objetivos de Aprendizagem

Durante o desenvolvimento deste projeto foram praticados os seguintes conceitos:

* Organização de projetos Full Stack
* Desenvolvimento com Node.js
* Desenvolvimento com React
* Consumo de APIs REST
* Integração com banco de dados
* Boas práticas de programação
* Testes automatizados
* Versionamento utilizando Git e GitHub
* Deploy de aplicações web

---

## 👨‍💻 Autor

Projeto desenvolvido como atividade prática para aprendizado de desenvolvimento Full Stack utilizando Node.js e React.

---

## 📄 Licença

Este projeto possui finalidade exclusivamente educacional.
