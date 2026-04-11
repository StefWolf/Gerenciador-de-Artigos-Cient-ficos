# Gerenciador-de-Artigos-Cient-ficos
Trabalho 01 da disciplina de Desenvolvimento Web II do Mestrado PPGTI. Aqui, temos o back-end de um gerenciador de artigos para pesquisadores, desenvolvido em Java Spring Boot.

# Minha Justificativa para o Domínio

## Qual é o domínio mesmo??

O domínio **"Gerenciador de Artigos"** foi escolhido para estar diretamente relacionado às atividades acadêmicas desenvolvidas durante o mestrado. A aplicação tem como objetivo auxiliar no controle e organização de artigos científicos, permitindo o gerenciamento de informações como autores, áreas de pesquisa, periódicos e status de leitura.

## Por que eu quis escolher esse?

Esse domínio foi considerado adequado por possibilitar a aplicação de diversas regras de negócio relevantes, como:

* Restrição de exclusão de entidades que possuem vínculos (ex: autores com artigos associados)
* Validação de dados de entrada
* Controle de estados do artigo (para leitura, lendo, finalizado)

Além disso, o sistema simula um cenário real de gerenciamento acadêmico, contribuindo tanto para a prática de desenvolvimento backend quanto para a organização pessoal de estudos científicos.

## Aspectos Técnicos Aplicados

A aplicação permite explorar conceitos fundamentais de desenvolvimento backend, incluindo:

* Separação de camadas (Controller, Service, Repository)
* Uso de DTOs (Data Transfer Objects)
* Validação de dados com anotações
* Implementações múltiplas de serviços com uso de `@Qualifier`
* Persistência em memória utilizando estruturas como `Map`


ps, para ser sincera, eu queria ter feito algum domínio voltado para minha área que é VR, mas vi que iria ficar complexo talvez então decidir fazer algo mais relevante academicamente. :p
