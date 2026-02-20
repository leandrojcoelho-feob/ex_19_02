---
name: "Caso de Uso (UC)"
about: "Descrever o passo a passo da interação entre o usuário e o sistema"
title: "UC0X — [Nome do Caso de Uso]"
labels: "caso de uso, documentação"
---

## 🎭 Atores
- **Ator Principal:** [ex: Usuário Não Logado]
- **Atores Secundários:** [ex: Sistema de Envio de E-mail]

## 🚦 Pré-condições
- [ ] O usuário deve estar na página inicial.
- [ ] O usuário não pode estar autenticado.

## 🟢 Fluxo Principal (Caminho Feliz)
1. O **[Ator]** clica no botão "Entrar".
2. O **Sistema** exibe a tela de login solicitando e-mail e senha.
3. O **[Ator]** preenche os dados e clica em "Confirmar".
4. O **Sistema** valida as credenciais.
5. O **Sistema** redireciona o usuário para o Painel Principal (Dashboard).

## 🔄 Fluxos Alternativos e Exceções
* **[FA01] E-mail ou Senha Incorretos (Passo 4):**
  1. O **Sistema** identifica que as credenciais são inválidas.
  2. O **Sistema** exibe a mensagem de erro "Usuário ou senha inválidos".
  3. Retorna ao passo 2 do Fluxo Principal.
* **[FA02] Esqueci minha senha (Passo 2):**
  1. O **[Ator]** clica no link "Esqueci minha senha".
  2. O **Sistema** redireciona para o `UC02 - Recuperação de Senha`.

## 🏁 Pós-condições
- O usuário terá uma sessão ativa e terá acesso às rotas protegidas do sistema.

## 🔗 Requisitos e Regras Associadas
- **Requisito Funcional:** # [Issue do RF01 - Login do Usuário]
- **Regras de Negócio:** # [Issue da RN01 - Bloqueio após 3 tentativas]
