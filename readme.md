# Projeto Lojinha de Dona Marlene

Este é um projeto para uma lojinha virtual da Dona Marlene, que é conhecida pelas frutas de altíssima qualidade que vende em seu bairro. O objetivo deste projeto é criar um site para expandir o alcance das suas vendas e atingir um público maior.

## Tecnologias utilizadas

    Node.js
    TypeScript
    Jest (para testes automatizados)

## Estrutura do projeto:

A estrutura do projeto é composta por vários componentes, cada um responsável por uma parte específica da aplicação. Aqui está a estrutura geral do projeto:\

.\
├── src\
│   ├── controllers\
│   │   └── fruits-controller.ts\
│   ├── middlewares\
│   │   └── schemaValidatorMiddleware.ts\
│   ├── schemas\
│   │   └── fruit-schema.ts\
│   ├── services\
│   │   └── fruits-service.ts\
│   └── routers\
│       └── fruits-router.ts\
└── tests\
    ├── controllers\
    │   └── fruits-controller.test.ts\
    ├── middlewares\
    │   └── schemaValidatorMiddleware.test.ts\
    └── schemas\
        └── fruit-schema.test.ts

        
## Como executar o projeto

### 1. Clone este repositório para sua máquina local:
    git clone https://github.com/ThaisFReis/lojinha-dona-marlene // mudar
    
### 2. Acesse a pasta do projeto:
    cd lojinha-dona-marlene
    
###  3. Instale as dependências:
    npm install
    
### 4. Execute o projeto:
    npm start
    
### 5. Para executar os testes, utilize o seguinte comando:
    npm test // mudar
