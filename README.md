# Proto Sistema de Vendas | PHP8.1 e MySQL8

O projeto em desenvolvimento é um ensaio para criação de APIs, Sistema de Vendas (com login e registros) e gerenciamento de estoque.

Os níveis de acesso e responsabilidades apresentam as seguintes regras:

- admin: gerentes, diretoes e demais agentes tomadores de decisões na empresa;
- sysadmin: arquitetos, desenvolvedores, engenheiros de infraestrutura;
- editor: redatores, criativos e mkt;
- user: clientes e leitores;
- guest: convidados 

## Estrutura do Projeto

A aplicação está divida em back-end e front-end, seguindo o padrão de comunicação entre API e ClientApp.

## O banco de dados

O banco de dados é o MySQL 8.0, com o uso de triggers e procedures para gerenciamento de estoque e vendas.    

## O back-end

O back-end é desenvolvido em PHP 8.1, com o uso de Slim Framework 4.8, Eloquent ORM 8.0 e Twig 3.3.

## O front-end

O front-end é desenvolvido em HTML5, CSS3, JavaScript e Bootstrap 5.1.





