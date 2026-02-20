---
name: "Regra de Negócio (RN)"
about: "Definir uma política, cálculo, restrição ou fluxo de decisão do negócio"
title: "RN0X — [Título Curto da Regra]"
labels: "RN, documentação, regra de negócio"
---

## 🏛️ Descrição da Regra
> **Exemplo:** O sistema deve bloquear a conta do usuário após 3 tentativas consecutivas de login com a senha incorreta.

## ⚖️ Condições e Lógica de Validação
- [ ] O sistema deve contar o número de falhas consecutivas de login.
- [ ] A contagem deve ser zerada se o login for feito com sucesso antes da 3ª falha.
- [ ] No 3º erro consecutivo, o status da conta deve mudar para "Bloqueada".

## 🚫 Exceções e Tratamento de Erro
- **Cenário de Bloqueio:** Exibir a mensagem *"Sua conta foi bloqueada por excesso de tentativas. Verifique seu e-mail para recuperação."*
- **Recuperação:** O bloqueio só pode ser desfeito através do fluxo de "Esqueci minha senha" ou por um Administrador.

## 🔗 Onde essa regra se aplica? (RFs Associados)
- Aplica-se no **RF01 — Login do Usuário** (Issue # )
- Aplica-se no **RF02 — Recuperação de Senha** (Issue # )

## 📋 Contexto Adicional
