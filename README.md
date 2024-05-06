﻿# Projeto de Engenharia de dados - NorthWinddb

 ## Introdução

 O presente artigo é referente a um dos projetos disponíveis no curso do [Fernando Amaral](https://www.linkedin.com/in/fernando-amaral/) no curso [Formação Engenharia de Dados: Domine Big Data!](https://www.udemy.com/course/engenheiro-de-dados/learn/lecture/15289778?start=0) disponível na Udemy. O projeto consiste na criação de um pipeline utilizando ferramentas da nuvem AWS e responder a cinco perguntas de negócio utilizando SQL.

 Para isso usaremos as seguintes ferramentas:

 - Um bucket na AWS S3
 - Um banco de dados no AWS Redshift
 - linguagem SQL para criar as tabelas, inserir as informações e criar as consultas
 - Visualizar as informações em um dataViz

O projeto é bem simples, porém uma dica que eu recebi e que gosto de passar a frente é sempre escreva sobre o que aprendeu. Se possível escreva a mão. Isso ajuda a manter os conceitos aprendidos vivos.

## Materiais

Os materiais utilizados foram todos disponibilizados no curso. Mas basicamente faremos um estudo sobre informações de vendas e produtos de um conjunto de dados salvos no CSV chamado Northwinddd. Os materiais se encontram disponíveis nesse repositório caso tenham curiosiadade de aprender um pouco e se desenvolver. As perguntas que iremos responder serão as seguintes:

1. Temos realizado vendas com valor abaixo do preço de tabela?
2. Como está perfomance dos vendedores em relaçao ao ano anterior?
3. Quais os produtos mais caros?
4. Avaliar a diferença de perfomance dos produtos por fornecedor nos ultimos dois anos
5. Quais os 5 produtos mais venderam em cada ano?

Essas perguntas nos permitirão abordar vários conceitos tanto de engenharia quanto em análise.

O esquema a seguir será o que nos basearemos para resolver cada questão.

###colocar imagem aqui###

