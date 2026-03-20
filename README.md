<<
Projeto Backend Geração Tech
=======
# 🛒 Digital Store - Back-end API

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-api-badge&logo=javascript&logoColor=%23F7DF1E)

Esta é a API de gerenciamento da **Digital Store**, um ecossistema de e-commerce completo. O projeto foca em fornecer uma base sólida para operações de produtos, usuários e categorias, seguindo os padrões REST.

---

## 🚀 Funcionalidades

* **Autenticação de Usuários**: Registro e login seguros.
* **Gestão de Produtos**: CRUD completo (Criar, Ler, Atualizar e Deletar).
* **Categorias**: Organização de produtos por tipos.
* **Carrinho e Pedidos**: Lógica de backend para processamento de compras.

## 🛠 Tecnologias e Ferramentas

* **Runtime:** Node.js
* **Framework:** Express.js
* **Persistência (Sugestão):** MongoDB / MySQL (via Prisma ou Sequelize)
* **Documentação:** Swagger (opcional)
* **Testes:** Jest (opcional)

---

## 📦 Como instalar e rodar

### 1. Clonar o repositório
```bash
git clone [https://github.com/Mickaellysilva/Projeto-Digital-Store-Backend.git](https://github.com/Mickaellysilva/Projeto-Digital-Store-Backend.git)
```
### 2. Instalar as dependênciasNavegue até a pasta raiz e execute:Bashnpm install
### 3. Configurar variáveis de ambiente

Crie um arquivo .env na raiz do projeto (se houver necessidade de banco de dados ou portas específicas):Snippet de códigoPORT=3000
DATABASE_URL=seu_link_aqui
 ### 4. Iniciar a aplicação Bash# Para desenvolvimento com atualização automática (nodemon)
npm run dev

# Para produção
npm start 
## 📁 Estrutura do Projeto

```bash
.
├── src
│   ├── config
│   ├── controllers
│   ├── database
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── services
│   ├── app.js
│   └── server.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md

---

## 👩‍💻 Autoria

Desenvolvido por Kássia, Mickaelly e Tatiana

- 💼 Projeto acadêmico - Geração Tech  
- 🚀 Foco em desenvolvimento Back-end  


Desenvolvido por Kássia, Mickaelly e Tatiana
© 2026 Todos os direitos reservados.
