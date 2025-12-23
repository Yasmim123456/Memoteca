![Thumbnail](./thumbnail.png)

# Memoteca

A Memoteca é um aplicativo organizador de pensamentos e frases que permite cadastrar, listar, editar,  deletar, filtrar e favoritar pensamentos, incluindo informações como conteúdo, autoria e data. Foi desenvolvido durante a formação de JavaScript da Alura, com o objetivo de praticar **CRUD completo** utilizando **requisições HTTP**.

## 🔨 Funcionalidades do projeto

`Cadastro de pensamentos`: Permite adicionar novos pensamentos à lista, inserindo informações como conteúdo e autoria.

`Listagem de pensamentos`: Exibe os pensamentos cadastrados, permitindo visualizar o texto e a autoria.

`Edição de pensamentos`: Permite editar pensamentos existentes, atualizando as informações conforme necessário.

`Exclusão de pensamentos`: Permite remover pensamentos da lista.

`Busca typeahead`: Implementa uma funcionalidade de busca com sugestões automáticas, permitindo filtrar pensamentos conforme a pessoa digita.

`Favoritar pensamentos`: Adiciona a opção de favoritar pensamentos, destacando os favoritos na lista para fácil acesso.

`Validações de formulário com Regex`: Utiliza expressões regulares para validar campos do formulário, garantindo que os dados inseridos estejam no formato correto antes do envio.

`Cadastro e manipulação de data`: Permite registrar a data do pensamento no momento do cadastro, garantindo que cada pensamento esteja associado a um timestamp.

## ✔️ Técnicas e tecnologias utilizadas

`JavaScript`: Linguagem de programação utilizada para desenvolver a lógica do aplicativo.

`Fetch API`: Utilizada para realizar requisições HTTP para comunicação com o servidor.

`Axios`: Biblioteca usada para facilitar e simplificar as requisições HTTP.

`Node.js`: Plataforma utilizada para executar o ambiente de desenvolvimento.

`JSON Server`: Utilizado para simular um backend e facilitar o desenvolvimento e teste das operações CRUD.

`CSS`: Utilizado para estilização da interface do aplicativo.


## 📁 Link do Figma

Você pode [acessar o figma do projeto aqui](https://www.figma.com/design/Sz1gmmemxqcB3amInL4Ndp/Rebrand-Memoteca-%7C-Curso-CRUD?node-id=148-26&t=FpdmfbiM1i1s6REQ-0).

## 🛠️ Como rodar o projeto localmente

Este projeto utiliza **JSON Server** para simular uma API REST.

### 📌 Pré-requisitos

- Node.js (versão utilizada: 20.12.2)
- JSON Server

---

### 1️⃣ Instalar o JSON Server

npm install -g json-server

### 2️⃣ Rodar o backend (API fake)

Abra um terminal na pasta backend e execute:

json-server --watch db.json --port 3000

A API ficará disponível em:

http://localhost:3000/pensamentos

### 3️⃣ Rodar o frontend

Abra o projeto no Visual Studio Code.
Com a extensão Live Server instalada, clique com o botão direito no arquivo index.html e selecione Open with Live Server.

O frontend será acessado em:

http://localhost:5500