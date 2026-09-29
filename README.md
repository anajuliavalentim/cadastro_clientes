# 🛒 Cadastro de Produtos com Validação

Atividade desenvolvida em **PHP** com integração ao **MySQL**, com o objetivo de praticar a criação de formulários, validação de dados e cadastro de produtos em um banco de dados.

## 📋 Sobre a atividade

O desafio foi desenvolvido seguindo as instruções do arquivo **10a_desafio2.md**.

O sistema possui um formulário para cadastrar produtos, solicitando:

* **Nome do Produto**
* **Preço**

Antes de realizar o cadastro, os dados são validados pelo PHP.

## ⚙️ Funcionalidades

* Criação da tabela `produtos` no banco de dados `exercicio`;
* Formulário para cadastro de produtos;
* Validação do nome do produto;
* Validação do preço;
* Verificação para garantir que o preço seja maior que zero;
* Inserção dos dados no banco de dados;
* Mensagem de sucesso após o cadastro;
* Mensagens de erro quando os dados são inválidos.

## 🗄️ Banco de Dados

O projeto utiliza o banco de dados:

```sql
exercicio
```

E a tabela:

```sql
produtos
```

A tabela deve ser criada no **MySQL** antes de executar o código PHP.

## 💻 Tecnologias utilizadas

* PHP
* MySQL
* HTML
* Visual Studio Code

## ✅ Resultado esperado

Quando os dados forem válidos, o sistema apresenta:

> **Produto cadastrado com sucesso!**

Caso os dados sejam inválidos, uma mensagem de erro é exibida, por exemplo:

> **Erro: O preço deve ser um número positivo.**

## 📁 Arquivo principal

```text
10a_desafio2.php
```

## 🚀 Como executar

1. Criar o banco de dados `exercicio` no MySQL.
2. Criar a tabela `produtos`.
3. Colocar o arquivo PHP no servidor local, como o XAMPP.
4. Iniciar o Apache e o MySQL.
5. Acessar o arquivo pelo navegador.
6. Preencher o formulário e testar o cadastro.

## 🎯 Objetivo

Praticar conceitos básicos de **PHP, HTML, validação de dados e integração com banco de dados MySQL**, realizando um cadastro simples e seguro de produtos.

---

👩‍💻 **Atividade prática — Desenvolvimento de Sistemas**

🚀 **PHP + MySQL**
