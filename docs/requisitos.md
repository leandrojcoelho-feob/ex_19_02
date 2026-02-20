# 💻 Documento de Requisitos do Sistema

## 📖 Visão Geral do Sistema
O **[PCP - Planejamento e controle de produção]** é uma plataforma desenvolvida para **[resolver o problema X / facilitar a tarefa Y]**, permitindo que **[público-alvo]** consiga **[objetivo principal]**.

---

## 🖥️ Requisitos de Ambiente e Infraestrutura
### Para Usuários (Requisitos Mínimos)
* **Navegadores Suportados:** Chrome (v100+), Firefox (v90+), Safari (v15+)
* **Sistema Operacional:** Windows 10+, macOS 11+, Android 10+, iOS 14+
* **Resolução Mínima:** 1024x768 (Desktop) / 360x640 (Mobile)

### Para Desenvolvimento / Servidor
* **Linguagem / Framework:** [ex: Node.js v18.0+, Python 3.10+]
* **Banco de Dados:** [ex: PostgreSQL 14+, MongoDB 5.0+]
* **Hardware Mínimo (Servidor):** [ex: 2 vCPUs, 4GB RAM, 20GB SSD]
* **Dependências Externas:** [ex: API do Google Maps, Stripe para pagamentos]

---

## 📌 Índice de Requisitos Funcionais (RF)
| ID | Título | Status | Issue |
|---|---|---|---|
| **RF01** | Login do usuário | 🟢 Concluído | [#1](link) |
| **RF02** | Recuperação de senha | 🟡 Em Progresso | [#2](link) |
| **RF03** | Cadastro de produto | 🔴 Pendente | [#3](link) |

---

## ⚖️ Índice de Regras de Negócio (RN)
| ID | Título | Status | Issue |
|---|---|---|---|
| **RN01** | Bloqueio de conta após 3 tentativas de login | 🟢 Concluído | [#4](link) |
| **RN02** | Cálculo de frete grátis acima de R$ 100 | 🔴 Pendente | [#5](link) |

---

## ⚙️ Índice de Requisitos Não Funcionais (RNF)
| ID | Título | Status | Issue |
|---|---|---|---|
| **RNF01** | Tempo de resposta do login inferior a 300ms | 🟡 Em Progresso | [#6](link) |
| **RNF02** | Criptografia de senhas usando Bcrypt | 🟢 Concluído | [#7](link) |
