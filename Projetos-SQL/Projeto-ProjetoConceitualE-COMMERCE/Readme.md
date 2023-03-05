# Projeto Esquema conceitual de banco de dados.

**Projeto:** Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE
  
**Disponibilizado:** Geração Tech Unimed-BH - Ciência de Dados - Digital Innovation One.
  
 **Autor**: Juliana Mascarenhas

# Sobre 

Este projeto tem o objetivo abordar os conceitos aprendidos nas aulas de banco de dados na prática. Para isso iremos fazer um projeto de um banco de dados para E-Commerce.

## Informações: 

O projeto feito é de um e-commerce de venda de produtos online. Suas entidade, informações e atributos são:

### Cliente: 
* O cliente pode se cadastrar no site com o CPF ou CNPJ 
* Um cliente pode comprar mais de um pedido. Este tem um período de arência para devolução do produto.
* Atributos: Nome, ID, email e endereço.
* O cliente pode ser PJ ou PF

### Fornecedor:
* Atributos: CNPJ e Razão social

### Estoque
* Atributos: ID e Local 

### Entrega:
* Atributos: Status, código de rastreio, data limite e local

### Produto: 
* São vendidos por uma unica plataforma online, contudo, estes podem ter vendedores distintos
* Cada produto possui apenas um fornecedor
* Um pedido pode ser composto por um ou mais produtos.
* Atributos: Id e status

# Diagrama conceitual: 
![image](https://user-images.githubusercontent.com/84606803/222935630-745203c8-8575-4c73-9552-17f813795796.png)



