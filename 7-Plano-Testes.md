# 7. Plano de Testes

**Projeto:** Vai Ficar Tudo Bem – Plataforma Virtual de Apoio Emocional  
**Aluno:** Carlos Eduardo Araújo da Silva  
**Versão:** 1.0

## 1. Introdução

Este documento descreve os testes que serão realizados no sistema para garantir qualidade, usabilidade e confiabilidade.

## 2. Tipos de Testes

### 2.1 Testes Funcionais
- Verificar cadastro e login de usuários
- Testar modo anônimo
- Validar registro emocional (emoji + escala)
- Testar funcionamento do Diário Emocional
- Verificar envio e recebimento de mensagens no chat em tempo real
- Testar botão de "Preciso de ajuda urgente"

### 2.2 Testes de Usabilidade e Humanização
- Avaliar se a interface é acolhedora e fácil de usar
- Verificar clareza dos textos e empatia na linguagem
- Testar responsividade (celular, tablet e desktop)
- Avaliar acessibilidade (contraste, tamanho de fonte, navegação)

### 2.3 Testes Não Funcionais
- Tempo de carregamento das páginas (< 3 segundos)
- Teste com múltiplos usuários simultâneos no chat
- Teste de segurança (tentativa de acesso indevido)
- Compatibilidade com diferentes navegadores

### 2.4 Testes de Segurança
- Proteção de dados (LGPD)
- Validação de campos (SQL Injection, XSS)
- Autenticação e autorização

## 3. Casos de Teste (Exemplos)

| ID       | Descrição                              | Entrada                     | Resultado Esperado                     | Status |
|----------|----------------------------------------|-----------------------------|----------------------------------------|--------|
| CT01     | Cadastro de usuário                    | Preencher dados válidos     | Cadastro realizado com sucesso         |        |
| CT02     | Registro emocional                     | Selecionar emoji + texto    | Registro salvo e feedback positivo     |        |
| CT03     | Entrar na sala de conversa             | Clicar em uma sala          | Usuário entra e vê mensagens           |        |
| CT04     | Botão de ajuda urgente                 | Clicar no botão flutuante   | Exibir tela com contatos de emergência |        |

## 4. Ferramentas de Teste
- Testes manuais (principais)
- Jest / React Testing Library (frontend)
- Postman (testes de API)
- WAVE / Lighthouse (acessibilidade)
