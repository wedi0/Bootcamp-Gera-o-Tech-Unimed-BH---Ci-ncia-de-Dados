# Projeto Lógico de Banco de Dados

**Projeto:** Construindo seu Primeiro Projeto Lógico de Banco de Dados
  
**Disponibilizado:** Geração Tech Unimed-BH - Ciência de Dados - Digital Innovation One.
  
 **Autor**: Juliana Mascarenhas

# Sobre 

Este projeto tem como objetivo aplicar os conceitos de persistência de dados usando o mysql e utilizando o modelo conceitual de e-commerce feito em um projeto anterior. Aqui vamos criar o banco de dados, inserir dados e fazer queries para consultas. 

# Informações: 

Assim como demonstrado durante o desafio, realize a criação do Script SQL para criação do esquema do banco de dados. Posteriormente, realize a persistência de dados para realização de testes. Especifique ainda queries mais complexas dos que apresentadas durante a explicação do desafio. Sendo assim, crie queries SQL com as cláusulas abaixo:

## Recuperações simples com SELECT Statement
* Filtros com WHERE Statement;
* Crie expressões para gerar atributos derivados;
* Defina ordenações dos dados com ORDER BY;
* Condições de filtros aos grupos – HAVING Statement;
* Crie junções entre tabelas para fornecer uma perspectiva mais complexa dos dados;

## Diretrizes
* Não há um mínimo de queries a serem realizadas;
* Os tópicos supracitados devem estar presentes nas queries;
* Elabore perguntas que podem ser respondidas pelas consultas;
* As cláusulas podem estar presentes em mais de uma query;

# Modelo conceitual: 


![image](https://user-images.githubusercontent.com/84606803/226137701-6cf08824-c0d9-4bed-a815-696e0f8fa107.png)


# Modelo lógico

Cliente(**ID**, endereço, nome, e-mail, tipo, CPF, CNPJ)

Pedido(**ID**, status, pagamento, *Id-cliente*, *codigo-de-rastreio*, *id-produto*)

    Id-cliente ref. Cliente; 
    codigo-de-rastreio ref. Entrega; 
    id-produto ref. produto;

Entrega(**codigo-de-rastreio**, status, data-limite, local)


Pedido(**ID**, nome, *CNPJ*)

    CNPJ ref. Fornecedor

Fornecedor(**CPNJ**, razão social)

Estoque(**ID**, local)

Produto-Estoque(**id-produto**, **id-estoque**, quantidade)

    id-produto ref. produto;
    id-estoque ref. estoque;

    ref. significa referencia.

# Criando o BD


