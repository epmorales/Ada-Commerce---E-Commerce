# 🛒 Ada E-Commerce

Projeto desenvolvido como parte de um desafio acadêmico, simulando o fluxo de um **E-Commerce**.  
O sistema é implementado em **Java** e permite gerenciar clientes, produtos e pedidos, com operações de **cadastro, atualização e finalização**.

---

## 📌 Funcionalidades

### 👤 Clientes
- ➕ Cadastrar cliente  
- 📋 Listar clientes  
- ✏️ Atualizar informações do cliente  

### 📦 Produtos
- ➕ Cadastrar produto  
- 📋 Listar produtos  
- ✏️ Atualizar produto  

### 🧾 Pedidos
- 🆕 Criar pedido  
- ➕ Adicionar item ao pedido  
- 🔄 Alterar quantidade de item  
- ❌ Remover item do pedido  
- ✅ Finalizar pedido (aguardando pagamento)  
- 💳 Pagar pedido  
- 📦 Entregar pedido  

---

## 🏗️ Estrutura do Projeto

📂 **model/** → Entidades principais (`Cliente`, `Produto`, `Pedido`, `ItemPedido`, `StatusPedido`)  
📂 **notificacao/** → Interface de notificação e implementação de envio por e-mail  
📂 **repositorio/** → Interfaces e implementação em memória para armazenamento dos dados  
📄 **Main.java** → Ponto de entrada do programa, com menu interativo no console  

---

## 🎨 Menu Interativo

```text
------------------------------------------
|             Ada E-Commerce              |
|                                         |
|               CLIENTES                  |
| 1 - Cadastrar cliente                   |
| 2 - Listar clientes                     |
| 3 - Atualizar cliente                   |
|                                         |
|               PRODUTOS                  |
| 4 - Cadastrar produto                   |
| 5 - Listar produtos                     |
| 6 - Atualizar produto                   |
|                                         |
|                PEDIDOS                  |
| 7 - Criar pedido                        |
| 8 - Adicionar item ao pedido            |
| 9 - Alterar quantidade de item          |
| 10 - Remover item do pedido             |
| 11 - Finalizar pedido                   |
| 12 - Pagar pedido                       |
| 13 - Entregar pedido                    |
|                                         |
| 0 - Sair                                |
------------------------------------------
🛠️ Tecnologias Utilizadas
☕ Java 17+

🔑 Programação Orientada a Objetos (POO)

🗂️ Estruturas de dados em memória (Map, List)

🧩 Princípios de abstração, encapsulamento e interfaces
