# Documento de arquitetura

| Data | Versão | Descrição | Autor |
|--|--|--|--|
| 03/12/2020 | 0.1 | Tópicos 1, 2| Brian Pina |


# 1 Introdução

## 1.1 Finalidade

<p align="justify"> &emsp;&emsp;
Esse documento de arquitetura tem como função mostrar uma visão geral sobre a arquitetura utilizada pelo software EmDia, ela é uma descrição do sistema que auxilia na compreensão de como o sistema irá se comportar. Portanto, especifica decisões relevantes na produção e implementação do projeto Dorime em relação a como acontecerá a comunicação dos diversos serviços contidos no software como um todo.
</p>

## 1.2 Escopo
**WIP**

## 1.3 Referências

* [Como documentar a Arquitetura de Software](http://www.linhadecodigo.com.br/artigo/3343/como-documentar-a-arquitetura-de-software.aspx)
* [Documento de Arquitetura Aix](https://fga-eps-mds.github.io/2019.1-Aix/projeto/2019/03/29/documento-de-arquitetura/)

## 1.4 Visão Geral

<p align="justify"> &emsp;&emsp;
Nesse documento de Arquitetura de Software, serão exploradas todas as informações relacionadas à arquitetura do projeto. Na primeira parte será apresentada a arquitetura da aplicação, na segunta parte uma explicação das metas e restrições da arquitetura. Na terceira parte, expressa a visão de casos de uso e, em seguida, a visão lógica.
</p>

## 1.5 Definições, Acrônimos e Abreviações

* API - Application Programming Interface: uma série de procedimentos que permite a criação de aplicações que fazem uso de dados e funcionalidades de um outro sistema, aplicação ou serviço.
* REST - Representational State Transfer: Estilo de arquitetura de software que define um conjunto de restrições a serem usadas para a criação de APIs.

# 2 Representação da arquitetura

_Inserir imagem_

[![Diagrama de relações]()]()

## 2.1 Flutter

Flutter é um framework de desenvolvimento mobile criado pela Google. Tem como seus objetivos facilitar o desenvolvimento de belas interfaces, alta performance de seus aplicativos, melhor tempo de desenvolvimento e base verdadeiramente única de código.

## 2.2 Flask

Microframework em Python baseado em Jinja 2, Werkzeug e good intentions. Como Flask não possui uma ferramenta padrão para comunicação com o banco de dados, será utilizado a extensão Flask-MongoEngine.  
Para garantir as boas práticas de padrão de APIs RESTful, será utilizado a extensão Flask-RESTful para a criação de uma API em Flask que seja consistente.

## 2.3 MongoDB

Banco de dados NoSQL, baseado em documentos e escrito em C++. Faz uso de documentos similares ao JSON, o que permite alta performance porém mantendo a simplicidade.

## 2.4 ReactJS

Biblioteca de desenvolvimento Front-End criado pelo Facebook. Tem como princípio a componentização através do uso da linguagem conhecida com JSX.

## 2.5 Nginx

Proxy reverso e servidor http feito em C. Tem como grande vantagem o fato de lidar com requisições através de uma pipeline baseada em projetos.

# 3 Metas e restrições de arquitetura

_WIP_

# 4 Visões de caso de uso

# 4.1 Mapa de histórias de usuário

_Inserir imagem_

![User Story Map]()

## 4.2 Especificações dos Casos de Uso

_WIP_

# 5. Visão Lógica

## 5.1 Diagrama de pacotes

 - Web

_Inserir imagem_

[![Diagrama de pacotes web]()]()

 - Mobile

_Inserir imagem_

[![Diagrama de pacotes mobile]()]()

## 5.2 Diagrama de banco de dados

_Inserir imagem_

[![Diagrama de banco de dados]()]()

## 5.3 Diagrama de classes

_Inserir imagem_

[![Diagrama de classes]()]()

