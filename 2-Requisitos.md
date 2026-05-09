# 2. Documentação de Requisitos

**Projeto:** Vai Ficar Tudo Bem – Plataforma Virtual de Apoio Emocional  
**Aluno:** Carlos Eduardo Araújo da Silva  
**Instituição:** Gran Faculdade  
**Versão:** 1.0

## 1. Introdução

Este documento apresenta os requisitos funcionais e não funcionais do sistema "Vai Ficar Tudo Bem", uma plataforma virtual humanizada de apoio emocional.

## 2. Requisitos Funcionais

**RF01** - O sistema deve permitir que o usuário realize cadastro utilizando e-mail e senha.  
**RF02** - O sistema deve permitir login e recuperação de senha.  
**RF03** - O sistema deve permitir o uso de forma anônima (sem necessidade de cadastro).  
**RF04** - O sistema deve permitir que o usuário registre seu estado emocional do dia (emojis + escala).  
**RF05** - O sistema deve oferecer um Diário Emocional com prompts guiados para reflexão.  
**RF06** - O sistema deve possuir salas de conversa temática em tempo real (moderadas).  
**RF07** - O sistema deve ter uma seção de conteúdos educativos sobre saúde mental (artigos e exercícios).  
**RF08** - O sistema deve possuir um botão de "Preciso de ajuda urgente" com recursos de emergência.  
**RF09** - O sistema deve permitir ao usuário editar seu perfil (nome, avatar, bio).  
**RF10** - O sistema deve ter feed de mensagens positivas e histórias inspiradoras (moderadas).

## 3. Requisitos Não Funcionais

**RNF01 - Usabilidade**  
A interface deve ser simples, intuitiva e acolhedora, com design emocional (cores suaves).

**RNF02 - Acessibilidade**  
O sistema deve seguir os princípios básicos de acessibilidade (WCAG), com bom contraste, textos alternativos e navegação por teclado.

**RNF03 - Desempenho**  
O sistema deve carregar as páginas em menos de 3 segundos e suportar pelo menos 100 usuários simultâneos no MVP.

**RNF04 - Segurança**  
- Proteção de dados pessoais (LGPD).  
- Armazenamento seguro de senhas (hash).  
- Opção de navegação anônima.

**RNF05 - Confiabilidade**  
O sistema deve ter backup automático dos dados e tratamento de erros amigável.

**RNF06 - Tecnologia**  
- Frontend: React.js + Tailwind CSS  
- Backend: Node.js / Python (a definir)  
- Banco de dados: PostgreSQL ou SQLite  
- Chat em tempo real: Socket.io ou Firebase

**RNF07 - Compatibilidade**  
Deve funcionar nos principais navegadores (Chrome, Firefox, Edge) e ser responsivo (celular, tablet e desktop).

## 4. Regras de Negócio

- Todas as conversas em salas devem ser moderadas.  
- Conteúdos publicados passam por aprovação.  
- Em caso de detecção de risco (ideação suicida), o sistema deve acionar mensagem de apoio + contatos de emergência.

---

**Pronto!**

Agora faça o mesmo processo anterior:

1. Crie o arquivo **`2-Requisitos.md`** no repositório
2. Cole o conteúdo acima
3. Faça o Commit

---

Quando terminar de subir, me avise com **“Subi”** ou **“Pronto”**.

Depois disso, vamos para o passo seguinte (que geralmente é um dos mais importantes para avaliação):

- Diagramas UML (Casos de Uso, Classes, etc.)  
ou  
- Protótipo de telas (Figma)

Me avise quando subir este documento! 🚀
