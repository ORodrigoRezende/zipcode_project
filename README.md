# Busca CEP - Projeto de Estudo JavaScript

Um projeto simples desenvolvido com HTML, CSS e JavaScript puro para aprender conceitos fundamentais da linguagem e como integrar APIs externas.

![Busca CEP](./img/img1.png)

## Objetivo

Criar uma aplicação prática para estudar e praticar:
- Manipulação do DOM
- Tratamento de eventos
- Programação assíncrona (fetch)
- Validação de dados
- Organização de código com módulos ES6

## Funcionalidades

- Busca de CEP usando a API ViaCEP
- Preenchimento automático de rua e cidade
- Se a rua não for encontrada, o campo fica habilitado para digitação
- Validação de campos obrigatórios
- Listagem dos endereços salvos
- Design responsivo

## Tecnologias

- HTML5
- CSS3
- JavaScript ES6
- API ViaCEP

## Estrutura do Projeto

```
zipcode_project/
├── index.html
├── README.md
├── css/
│   ├── styles.css
│   └── modal.css
└── js/
    ├── zipcode.js
    ├── controllers/
    │   ├── form-controller.js
    │   ├── list-controller.js
    │   ├── modal-controller.js
    │   └── page-controller.js
    ├── models/
    │   └── address.js
    └── services/
        ├── address-service.js
        ├── request-service.js
        └── exceptions/
            └── request-exception.js
```

## Como Usar

1. Abra o arquivo `index.html` no navegador
2. Digite um CEP válido (ex: 01310100)
3. A rua e cidade serão preenchidas automaticamente
4. Digite o número do endereço
5. Clique em "Salvar" para adicionar à lista

## Aprendizados

Neste projeto foram colocados em prática conceitos como:

- **Seleção de elementos**: Usando querySelector e propriedades de formulário
- **Event listeners**: Capturando eventos de input e click
- **Fetch API**: Requisições HTTP assincronas com async/await
- **Modularização**: Separação de código em módulos ES6
- **Validação**: Verificação de campos obrigatórios
- **DOM manipulation**: Criação e atualização de elementos

## Próximos Passos

Possíveis melhorias para o projeto:
- Salvar endereços em LocalStorage
- Adicionar testes
- Melhorar validação de CEP
- Adicionar mais campos de endereço

## Contato

rezendeeesilva@gmail.com

---

Projeto desenvolvido como estudo de JavaScript.
