# 💻 Projeto Backend - API com JavaScript, Express, Bcrypt e React

Este é o repositório do backend de um projeto full stack que utiliza **JavaScript** no servidor, com **Express** para criação da API, **Bcrypt** para segurança de senhas e **Axios** para integração com o frontend feito em **React**.

---

## 🚀 Tecnologias Utilizadas

- **JavaScript (ES6+)** – linguagem principal do backend
- **Node.js** – ambiente de execução
- **Express** – framework para criação da API REST
- **Bcrypt** – criptografia de senhas
- **Axios** – comunicação entre frontend (React) e backend
- **React** – interface do usuário (frontend separado)

---

## 📁 Estrutura do Projeto

/backend
├── controllers/
│ └── userController.js
├── routes/
│ └── userRoutes.js
├── models/
│ └── userModel.js
├── config/
│ └── db.js
├── app.js
└── package.json

markdown
Copiar
Editar

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/) ou outro banco (caso aplicável)

### Instalação:

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
cd backend
2. Instale as dependências:

bash
Copiar
Editar
npm install
3. Inicie o servidor:

bash
Copiar
Editar
npm start
4. O servidor estará rodando em http://localhost:3000 (ou na porta configurada).

🔐 Funcionalidades Implementadas
Registro de usuários com senha criptografada (Bcrypt)

Login/autenticação de usuários

Integração com frontend React via API (Axios)

Rotas protegidas (caso JWT esteja implementado)

Respostas em JSON

📦 Dependências Principais
json
Copiar
Editar
"dependencies": {
  "express": "^4.x",
  "bcrypt": "^5.x",
  "axios": "^1.x"
}
🌐 Integração com o Frontend
O frontend do projeto foi desenvolvido em React e se comunica com esta API utilizando Axios. As rotas da API devem estar funcionando corretamente para que o frontend acesse dados, autenticação e outras funcionalidades.

🧠 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

📄 Licença
Este projeto está sob a licença MIT.

✨ Desenvolvido por
Maria Julia – Projeto acadêmico | Turma 0151