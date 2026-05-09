# 3. Diagramas UML

**Projeto:** Vai Ficar Tudo Bem – Plataforma Virtual de Apoio Emocional  
**Aluno:** Carlos Eduardo Araújo da Silva  
**Versão:** 1.0

## 1. Diagrama de Casos de Uso

### Atores Principais:
- Usuário Anônimo
- Usuário Cadastrado
- Moderador/Voluntário
- Administrador (futuro)

### Casos de Uso Principais:

**Gerenciamento de Conta**
- Realizar Cadastro
- Fazer Login
- Recuperar Senha
- Editar Perfil
- Usar como Anônimo

**Apoio Emocional**
- Registrar Estado Emocional
- Escrever no Diário Emocional
- Ler Conteúdos Educativos

**Interação Social**
- Participar de Sala de Conversa Temática
- Enviar Mensagem em Tempo Real
- Ler Histórias Inspiradoras

**Suporte e Emergência**
- Acionar "Preciso de Ajuda Urgente"
- Visualizar Contatos de Emergência

**Moderação** (ator Moderador)
- Moderar Salas de Conversa
- Aprovar/Rejeitar Conteúdos
- Monitorar Usuários em Crise

## 2. Descrição dos Casos de Uso Principais

**UC01 - Usar como Anônimo**
- Ator: Usuário Anônimo
- Objetivo: Acessar funcionalidades básicas sem criar conta.
- Fluxo Principal: Acessa página inicial → Escolhe "Entrar como Anônimo" → Tem acesso a salas de conversa e conteúdos.

**UC02 - Registrar Estado Emocional**
- Ator: Usuário Cadastrado
- Pré-condição: Usuário logado.
- Fluxo: Clica em "Como estou hoje" → Seleciona emoji + intensidade → Salva registro.

**UC03 - Participar de Sala de Conversa**
- Ator: Usuário Cadastrado / Anônimo
- Fluxo: Escolhe tema → Entra na sala → Participa da conversa (com moderação).

**UC04 - Acionar Ajuda Urgente**
- Ator: Qualquer usuário
- Fluxo: Clica no botão flutuante vermelho → Recebe mensagens de acolhimento + números de apoio (CVV etc.).

## 3. Próximos Diagramas (serão criados em breve)

- Diagrama de Classes
- Diagrama de Sequência
- MER / DER (Modelo de Banco de Dados)
