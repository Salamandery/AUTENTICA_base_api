<div align="center">

# 🔐 AUTENTICA

### API de Autenticação Segura

[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-4.17.1-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Sequelize](https://img.shields.io/badge/Sequelize-5.8.7-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)](https://sequelize.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io/)

[![ESLint](https://img.shields.io/badge/ESLint-Airbnb%20Base-4B32C3?style=for-the-badge&logo=eslint&logoColor=white)](https://eslint.org/)
[![Prettier](https://img.shields.io/badge/Prettier-1.17.1-F7B93E?style=for-the-badge&logo=prettier&logoColor=black)](https://prettier.io/)

> 🚀 **API RESTful** para autenticação de usuários com **JWT**, desenvolvida em **Node.js** com **Express** e **Sequelize**.

[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=for-the-badge)]()

</div>

## 📋 Sumário

- [Sobre o Projeto](#-sobre-o-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura e Padrões](#-arquitetura-e-padrões)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação e Configuração](#-instalação-e-configuração)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Endpoints da API](#-endpoints-da-api)
- [Scripts Disponíveis](#-scripts-disponíveis)

## 🎯 Sobre o Projeto

<div align="center">

![API Authentication](https://img.shields.io/badge/API-Authentication-blue?style=for-the-badge&logo=api&logoColor=white)
![RESTful](https://img.shields.io/badge/RESTful-API-orange?style=for-the-badge)
![Security](https://img.shields.io/badge/Security-JWT%20%2B%20bcrypt-red?style=for-the-badge)

</div>

API de autenticação desenvolvida seguindo **padrões RESTful**, com sistema de autenticação **JWT**, criptografia de senhas com **bcrypt** e validação de dados com **Yup**. O projeto utiliza **PostgreSQL** como banco de dados e **Sequelize** como ORM.

### ✨ **Principais Funcionalidades**
- 🔐 **Autenticação JWT** - Tokens seguros para sessões
- 🔒 **Criptografia bcrypt** - Senhas protegidas com hash
- ✅ **Validação Yup** - Schemas robustos para dados
- 🗄️ **ORM Sequelize** - Gerenciamento eficiente do banco
- 🚀 **Performance** - Otimizado para produção

## 🛠 Tecnologias Utilizadas

<div align="center">

| Categoria | Tecnologia | Versão | Descrição |
|-----------|------------|--------|-----------|
| **🖥️ Core** | ![Node.js](https://img.shields.io/badge/Node.js-16.x-339933?style=flat-square&logo=node.js&logoColor=white) | 16.x | Runtime JavaScript |
| | ![Express](https://img.shields.io/badge/Express-4.17.1-000000?style=flat-square&logo=express&logoColor=white) | 4.17.1 | Framework web |
| | ![Sequelize](https://img.shields.io/badge/Sequelize-5.8.7-52B0E7?style=flat-square&logo=sequelize&logoColor=white) | 5.8.7 | ORM para Node.js |
| | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-336791?style=flat-square&logo=postgresql&logoColor=white) | 13+ | Banco de dados |
| **🔐 Segurança** | ![JWT](https://img.shields.io/badge/JWT-8.5.1-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) | 8.5.1 | Autenticação por tokens |
| | ![bcrypt](https://img.shields.io/badge/bcryptjs-2.4.3-00A3CC?style=flat-square) | 2.4.3 | Criptografia de senhas |
| | ![Yup](https://img.shields.io/badge/Yup-0.27.0-4285F4?style=flat-square) | 0.27.0 | Validação de schemas |
| **🛠️ Dev Tools** | ![ESLint](https://img.shields.io/badge/ESLint-5.16.0-4B32C3?style=flat-square&logo=eslint&logoColor=white) | 5.16.0 | Linter Airbnb |
| | ![Prettier](https://img.shields.io/badge/Prettier-1.17.1-F7B93E?style=flat-square&logo=prettier&logoColor=black) | 1.17.1 | Formatador de código |
| | ![Nodemon](https://img.shields.io/badge/Nodemon-1.19.1-76D04B?style=flat-square&logo=nodemon&logoColor=white) | 1.19.1 | Hot reload |

</div>

## 🏗 Arquitetura e Padrões

<div align="center">

![MVC](https://img.shields.io/badge/Architecture-MVC-blue?style=for-the-badge)
![Repository](https://img.shields.io/badge/Pattern-Repository-orange?style=for-the-badge)
![Middleware](https://img.shields.io/badge/Pattern-Middleware-green?style=for-the-badge)

</div>

### 🎯 **Padrões de Projeto**
- **🏗️ MVC (Model-View-Controller)** - Separação clara de responsabilidades
- **📦 Repository Pattern** - Abstração da camada de dados
- **🔗 Middleware Pattern** - Interceptação de requisições
- **🏛️ Class-based Architecture** - Estrutura orientada a objetos

### 📁 **Estrutura de Pastas**
```
src/
├── 📂 app/
│   ├── 🎮 controllers/    # Controladores da aplicação
│   ├── 🔗 middlewares/    # Middlewares customizados
│   └── 📊 models/         # Modelos do Sequelize
├── ⚙️ config/             # Configurações (DB, Auth)
├── 🗄️ database/           # Migrations e Seeds
└── 🛣️ routes.js          # Definição de rotas
```

## ⚙️ Pré-requisitos

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-16.x+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Yarn](https://img.shields.io/badge/Yarn-1.22+-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white)

</div>

- **🟢 Node.js** 16.x ou superior
- **🐘 PostgreSQL** 13+ instalado e rodando
- **🧶 Yarn** ou **📦 npm** para gerenciamento de dependências

## 🚀 Instalação e Configuração

<div align="center">

![Quick Start](https://img.shields.io/badge/Quick-Start-orange?style=for-the-badge)
![Easy Setup](https://img.shields.io/badge/Setup-Easy-green?style=for-the-badge)

</div>

### 📋 **Passo a Passo**

#### 1️⃣ **Clone o repositório**
```bash
git clone <repository-url>
cd AUTENTICA_base_api
```

#### 2️⃣ **Instale as dependências**
```bash
yarn install
# ou
npm install
```

#### 3️⃣ **Configure o banco de dados**

Crie um banco PostgreSQL chamado `meetapp` e configure as credenciais em `src/config/database.js`:

```javascript
module.exports = {
  dialect: 'postgres',
  host: 'localhost',
  username: 'postgres',
  password: 'docker',
  database: 'meetapp',
  define: {
    timestamps: true,
    underscored: true,
    underscoredAll: true,
  },
};
```

#### 4️⃣ **Execute as migrations**
```bash
yarn sequelize db:migrate
# ou
npx sequelize-cli db:migrate
```

#### 5️⃣ **Inicie o servidor**
```bash
# 🛠️ Desenvolvimento
yarn dev

# 🚀 Produção
yarn start
```

<div align="center">

🎉 **Servidor rodando em:** `http://localhost:3000`

</div>

## 📁 Estrutura do Projeto

<div align="center">

![Project Structure](https://img.shields.io/badge/Structure-Organized-blue?style=for-the-badge)
![Clean Code](https://img.shields.io/badge/Code-Clean-green?style=for-the-badge)

</div>

```
AUTENTICA_base_api/
├── 📂 src/
│   ├── 🎮 app/
│   │   ├── controllers/
│   │   │   ├── SessionController.js
│   │   │   └── UserController.js
│   │   ├── middlewares/
│   │   │   └── auth.js
│   │   └── models/
│   │       └── User.js
│   ├── ⚙️ config/
│   │   ├── auth.js
│   │   └── database.js
│   ├── 🗄️ database/
│   │   ├── migrations/
│   │   └── index.js
│   ├── app.js
│   ├── routes.js
│   └── server.js
├── 🔧 .eslintrc.js
├── 💅 .prettierrc
├── 🗄️ .sequelizerc
├── 🔄 nodemon.json
├── 📦 package.json
└── 📖 README.md
```

## 🔌 Endpoints da API

<div align="center">

![REST API](https://img.shields.io/badge/REST-API-blue?style=for-the-badge)
![JWT Auth](https://img.shields.io/badge/Auth-JWT-green?style=for-the-badge)
![CRUD](https://img.shields.io/badge/CRUD-Operations-orange?style=for-the-badge)

</div>

### 🔐 **Autenticação**

| Método | Endpoint | Descrição | Autenticação |
|--------|----------|-----------|--------------|
| `POST` | `/sessions` | Login de usuário | ❌ |
| `POST` | `/users` | Cadastro de usuário | ❌ |
| `PUT` | `/users` | Atualização de dados | ✅ |

### 💡 **Exemplos de Uso**

#### 📝 **Cadastrar usuário**
```bash
curl -X POST http://localhost:3000/users \
  -H "Content-Type: application/json" \
  -d '{
    "name": "João Silva",
    "email": "joao@email.com",
    "password": "123456"
  }'
```

#### 🔑 **Fazer login**
```bash
curl -X POST http://localhost:3000/sessions \
  -H "Content-Type: application/json" \
  -d '{
    "email": "joao@email.com",
    "password": "123456"
  }'
```

#### ✏️ **Atualizar dados (com token)**
```bash
curl -X PUT http://localhost:3000/users \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer YOUR_JWT_TOKEN" \
  -d '{
    "name": "João Silva Atualizado",
    "email": "joao.novo@email.com"
  }'
```

## 📜 Scripts Disponíveis

```bash
# Desenvolvimento
yarn dev          # Inicia servidor com nodemon

# Produção
yarn start        # Inicia servidor em produção

# Banco de dados
yarn sequelize db:migrate    # Executa migrations
yarn sequelize db:seed:all   # Executa seeds
yarn sequelize db:drop       # Remove banco de dados

# Linting e formatação
yarn lint         # Executa ESLint
yarn lint:fix     # Corrige problemas do ESLint
```

## 🔧 Configurações

### ESLint
Configurado com Airbnb Base + Prettier para manter consistência de código.

### Prettier
Formatador automático de código com configurações otimizadas.

### Nodemon
Hot reload configurado com Sucrase para suporte a ES6+.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👤 Autor
by **Rodolfo M. F. Abreu**


