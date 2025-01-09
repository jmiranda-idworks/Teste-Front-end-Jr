
# 🚀 Teste Front-End Júnior - CRUD de Produtos  

## 📌 Sobre o Teste  
O objetivo deste teste é desenvolver uma interface simples para um pequeno sistema de gerenciamento de produtos. Você precisará criar um front-end que consuma uma API fake baseada em `json-server`, permitindo listar, adicionar, editar e excluir produtos.  

## 🎯 O Que Você Deve Fazer  
1. Criar uma interface para exibir uma lista de produtos com as seguintes colunas: ID, Nome, Quantidade, Localização e Ações (Editar/Excluir).  
2. Implementar a funcionalidade de **adicionar** um novo produto.  
3. Permitir que um produto seja **editado**.  
4. Implementar a funcionalidade de **excluir** um produto.  
5. Consumir a API fake gerada pelo `json-server`.  

## 📂 Estrutura do Banco de Dados (`db.json`)  
Os dados já estão prontos no arquivo `db.json`. Eles possuem a seguinte estrutura:  

```json
{
  "products": [
    { "id": 1, "name": "Teclado Mecânico", "quantity": 10, "location": "A1" },
    { "id": 2, "name": "Monitor 27'", "quantity": 5, "location": "B3" }
  ]
}
```

## 🔧 Como Configurar o JSON Server
1.  Instale o json-server (caso ainda não tenha):
```bash
// instalar globalmente
npm install -g json-server

// ou localmente
npm install json-server --save-dev
```
2. Para rodar a API fake, dentro do diretório onde está o `db.json`, execute:
```bash
json-server --watch db.json --port 3001
```

Isso iniciará uma API REST em http://localhost:3001, com os seguintes endpoints:

•  **GET** /products → Retorna todos os produtos

•  **GET** /products/1 → Retorna o produto com ID 1

•  **POST** /products → Adiciona um novo produto

•  **PUT** /products/1 → Atualiza o produto com ID 1

•  **DELETE** /products/1 → Remove o produto com ID 1

## 📌 Requisitos do Projeto

•  Utilizar **React** para construir a interface

•  Consumir os dados da API fake utilizando **fetch** ou **Axios**

•  Criar uma interface responsiva e usável

•  O design não precisa ser sofisticado, mas deve ser organizado

•  Opcional: Utilizar a biblioteca Ant Design para construir a interface

## 🎯 Critérios de Avaliação
•  Código limpo e organizado, seguindo as boas práticas de desenvolvimento React.

•  Uso adequado de componentes e gerenciamento de estado.

•  Capacidade de consumir e manipular dados da API fake.

•  Interface intuitiva e responsiva.

•  Diferencial: uso do Ant Design e boas práticas de UI/UX.

## 📤 Como enviar o teste?

1.  Desenvolva a aplicação seguindo os requisitos mencionados.

2.  Envie o link do repositório para nós quando finalizar o teste.

  
##
Se tiver dúvidas, fique à vontade para perguntar. Boa sorte! 💙
