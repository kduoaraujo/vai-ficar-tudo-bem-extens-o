# 4. Modelo Conceitual e Diagrama de Classes

**Projeto:** Vai Ficar Tudo Bem – Plataforma Virtual de Apoio Emocional  
**Aluno:** Carlos Eduardo Araújo da Silva  
**Versão:** 1.0

## 1. Diagrama de Classes (UML)

### Principais Classes:

- **Usuario**
  - Atributos: id, nome, email, senhaHash, dataNascimento, avatar, bio, anonimo (boolean)
  - Métodos: cadastrar(), login(), editarPerfil(), registrarEmocao()

- **RegistroEmocional**
  - Atributos: id, usuarioId, data, emoji, intensidade (1-10), observacao
  - Métodos: salvar()

- **DiarioEntrada**
  - Atributos: id, usuarioId, titulo, texto, data, promptUsado
  - Métodos: criar(), salvar()

- **SalaConversa**
  - Atributos: id, tema, descricao, ativa (boolean), moderadorId
  - Métodos: entrar(), enviarMensagem()

- **Mensagem**
  - Atributos: id, salaId, usuarioId, texto, dataHora, anonima

- **ConteudoEducativo**
  - Atributos: id, titulo, descricao, tipo (artigo/video/exercicio), url, aprovado

- **AjudaEmergencia**
  - Atributos: id, usuarioId, dataHora, tipoAjuda, status

## 2. Modelo Entidade-Relacionamento (MER)

### Entidades e Relacionamentos:

- **Usuário** 1:N **RegistroEmocional**
- **Usuário** 1:N **DiarioEntrada**
- **Usuário** 1:N **Mensagem**
- **SalaConversa** 1:N **Mensagem**
- **Moderador** (herda de Usuário) 1:N **SalaConversa**
- **Usuário** N:M **SalaConversa** (participação)

### Cardinalidades principais:
- Um usuário pode ter vários registros emocionais.
- Uma sala de conversa pode ter várias mensagens.
- Uma mensagem pertence a uma sala e a um usuário.

## 3. Regras de Integridade

- Todo registro emocional deve estar vinculado a um usuário (mesmo anônimo).
- Mensagens em salas devem ter data/hora automática.
- Conteúdos educativos só aparecem se estiverem aprovados.
