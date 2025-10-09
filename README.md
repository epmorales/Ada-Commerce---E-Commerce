# 🛒 Ada E-Commerce

Projeto desenvolvido como parte de um desafio acadêmico, simulando o fluxo de um **E-Commerce**.  
O sistema é todo implementado em **Java** e permite gerenciar clientes, produtos e pedidos, com operações de cadastro, atualização e finalização.

---

## 📌 Funcionalidades

✔️ **Clientes**
- Cadastrar cliente  
- Listar clientes  
- Atualizar informações do cliente  

✔️ **Produtos**
- Cadastrar produto  
- Listar produtos  
- Atualizar produto  

✔️ **Pedidos**
- Criar pedido  
- Adicionar item ao pedido  
- Alterar quantidade de item  
- Remover item do pedido  
- Finalizar pedido (aguardando pagamento)  
- Pagar pedido  
- Entregar pedido  

---

## 🏗️ Estrutura do Projeto

- `model/` → Contém as entidades principais (**Cliente, Produto, Pedido, ItemPedido, StatusPedido**).  
- `notificacao/` → Interface de notificação e implementação de envio por e-mail.  
- `repositorio/` → Interfaces e implementação em memória para armazenamento dos dados.  
- `Main.java` → Ponto de entrada do programa, com menu interativo no console.  

---

🛠️ Tecnologias Utilizadas

Java 17+

Programação Orientada a Objetos (POO)

Estruturas de dados em memória (Map, List)

Princípios de abstração, encapsulamento e interfaces
