# ERP

Um **sistema ERP (Enterprise Resource Planning)** moderno e modular, desenvolvido para atender empresas de pequeno e médio porte, oferecendo integração de **financeiro, estoque, vendas, compras e relatórios gerenciais**.  
O ERP Echo possui interface frontend desenvolvida em **Next.js (React)**, garantindo uma experiência moderna e responsiva.

---

## 🚀 Tecnologias

### Backend
- [Node.js](https://nodejs.org/) – Ambiente de execução JavaScript
- [TypeScript](https://www.typescriptlang.org/) – Tipagem estática no backend
- [NestJS](https://nestjs.com/) – Framework para APIs modernas e escaláveis
- [Mongoose](https://mongoosejs.com/) – ODM para MongoDB
- [MongoDB](https://www.mongodb.com/) – Banco de dados NoSQL
- [Docker](https://www.docker.com/) – Containerização e ambiente isolado

### Frontend
- [Next.js 14](https://nextjs.org/) – Framework React para web moderna
- [React](https://reactjs.org/) – Biblioteca de UI
- [TypeScript](https://www.typescriptlang.org/) – Tipagem estática
- [Tailwind CSS](https://tailwindcss.com/) + [Shadcn UI](https://ui.shadcn.com/) – Interface moderna
- [Zod](https://zod.dev/) – Validação de dados
- [Notistack](https://iamhosseindhv.com/notistack) – Notificações

### Infraestrutura
- [Docker](https://www.docker.com/) – Containerização
- [Nginx](https://www.nginx.com/) – Proxy reverso e HTTPS
- [MongoDB Atlas](https://www.mongodb.com/atlas) – Banco gerenciado (opcional)

---

## 📦 Estrutura do Projeto

```bash
erp/
├── backend/                # API NestJS
│   ├── src/                # Código fonte do NestJS
│   ├── test/               # Testes automatizados
│   ├── .env                # Variáveis de ambiente
│   ├── Dockerfile          # Imagem da API
│   └── package.json        # Dependências e scripts
├── frontend-nextjs/        # Aplicação Next.js
│   ├── app/                # Páginas e componentes
│   └── package.json
├── docker-compose.yml      # Orquestração de containers
└── README.md
