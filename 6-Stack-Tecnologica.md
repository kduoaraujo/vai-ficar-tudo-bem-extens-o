# 6. Stack Tecnológica e Arquitetura do Sistema

**Projeto:** Vai Ficar Tudo Bem – Plataforma Virtual de Apoio Emocional  
**Aluno:** Carlos Eduardo Araújo da Silva  
**Versão:** 1.0

## 1. Arquitetura Geral

O sistema será desenvolvido utilizando **arquitetura cliente-servidor** com frontend separado do backend (API REST + WebSocket).

## 2. Tecnologias Escolhidas

### Frontend
- **React.js** + Vite
- **Tailwind CSS** (para design rápido e responsivo)
- **React Router** (navegação)
- **Socket.io-client** (chat em tempo real)

### Backend
- **Node.js** + **Express.js** (ou Python + FastAPI)
- **JWT** para autenticação

### Banco de Dados
- **PostgreSQL** (produção) / **SQLite** (desenvolvimento)

### Tempo Real (Chat)
- **Socket.io**

### Hospedagem (MVP)
- **Frontend**: Vercel
- **Backend**: Render ou Railway
- **Banco de Dados**: Supabase ou Railway

### Outras Ferramentas
- **Git** + GitHub (controle de versão)
- **Figma** (protótipos)
- **Insomnia** ou **Postman** (testes de API)
- **ESLint** + **Prettier** (qualidade de código)

## 3. Justificativa da Stack

- React + Tailwind → Interface moderna, acolhedora e responsiva.
- Node.js → Facilita o uso de Socket.io para chat em tempo real.
- PostgreSQL → Bom para escalabilidade e relacionamentos.
- Vercel + Render → Hospedagem gratuita e fácil para MVP.

## 4. Diagrama de Arquitetura (em texto)
