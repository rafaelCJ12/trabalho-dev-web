# 📘 Documentação do Projeto - Desenvolvimento Web

![Planejamento do Projeto](./pmc.jpeg)

---

## 🧾 Visão Geral

 Desenvolver um sistema Web para uso em caixas de supermercado, permitindo o cadastro de produtos e criação de compras.

---

## ✅ Backlog

| ID    | Prioridade | História de Usuário                                                                 |
|-------|------------|--------------------------------------------------------------------------------------|
| HU-1  | 1️⃣         | **No papel de funcionário**, desejo **cadastrar produtos na base de dados do sistema**. |
| HU-2  | 2️⃣         | **No papel de funcionário**, desejo **listar os produtos do mercado**, para saber o que há no estoque. |
| HU-3  | 3️⃣         | **No papel de funcionário**, desejo **ser adicionado ao sistema**, para usá-lo. |
| HU-4  | 4️⃣         | **No papel de funcionário**, desejo **criar uma compra**, para ser levada por um cliente. |
| HU-5  | 5️⃣         | **No papel de funcionário**, desejo **adicionar produtos a uma compra**, de um cliente. |
| HU-6  | 6️⃣         | **No papel de funcionário**, desejo **excluir um item de uma compra**, caso haja um erro de inserção ou desistência da compra de um produto. |
| HU-7  | 7️⃣         | **No papel de gerente**, desejo **listar as compras feitas no mercado**, para saber como andam as vendas. |
| HU-8  | 8️⃣         | **No papel de gerente**, desejo **listar itens de uma compra**, para consultas de histórico. |
| HU-9  | 9️⃣         | **No papel de funcionário**, desejo **fazer login no sistema**, para usá-lo. |
| HU-10 | 🔟         | **No papel de gerente**, desejo **consultar as compras nas quais um fucnionário foi responsável**, para fins de auditoria. |

---

## 🎨 Protótipo de Telas

Cada funcionalidade descrita no backlog possui ao menos uma tela representando sua interface esperada.

### 🖼️ Protótipo do Requisito HU-9

![Protótipo da tela de login no sistema](tela1.jpeg)
**Figura 1**: Tela de login no sistema — correspondente à história de usuário HU-9.

### 🖼️ Protótipo do Requisito HU-2

![Protótipo da tela de consulta de produtos](tela2.jpeg)
**Figura 2**: Tela de consulta de produtos — correspondente à história de usuário HU-2.

### 🖼️ Protótipo do Requisito HU-5

![Protótipo da tela de adicionar produtos a uma compra](tela3.jpeg)
**Figura 2**: Tela de produtos a uma compra — correspondente à história de usuário HU-5.

### 🖼️ Protótipo do Requisito HU-9 e HU-10

![Protótipo da tela de consulta de compras](tela3.jpeg)
**Figura 2**: Tela de compras feitas — correspondente às histórias de usuário HU-9 e HU-10.

---

## 🏗 Análise e Projeto 

O projeto  do sistema 

### Modelo 

![alt text](image-1.png)

### Esboço da arquitetura geral (cliente-servidor)


![alt text](image.png)


### Autorização  e Autenticação 
A autorização no Strapi (a partir do v4 e mantida no v5) é baseada em perfis de usuários (roles) e permissões atribuídas a esses perfis. Ela define o que cada usuário pode ou não pode fazer ao interagir com os endpoints da API.

1. Tipos de usuários
O Strapi tem dois contextos principais de usuários:

🔹 Usuários Autenticados
Criados via cadastro/login na API pública.

Associados a uma role do tipo “Authenticated” ou outra personalizada.

Usam token JWT para acesso autenticado.

🔸 Usuários Administrativos
Criados via painel de administração do Strapi.

Usam o Strapi Admin Panel.

Gerenciados separadamente e com permissões diferentes.


### Tecnologias a serem utilizadas 
Strapi, HTML, CSS, SQLITE....

---

### Telas do sistema

![alt text](tela1-1.png)
**Figura 2**: Tela de listagem de produtos com imagem, nome e preço — correspondente à história de usuário HU-1.


