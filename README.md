Rick & Morty Characters List

Aplicativo desenvolvido em React Native + Expo, consumindo a API pública de Rick and Morty para exibir uma lista de personagens com nome, imagem, status, espécie e ID.

Este projeto foi feito como exercício prático para trabalhar:

useState

useEffect

FlatList

Consumo de API real

Boas práticas de renderização e layout

Tecnologias utilizadas

React Native

Expo

Hooks (useState, useEffect)

Fetch API

FlatList

Funcionalidades implementadas
Requisitos obrigatórios

Consumo da API: https://rickandmortyapi.com/api/character

Lista de personagens usando FlatList

Cada card exibe:

Imagem

Nome

Status

Espécie

#️ID

Armazena dados com useState

Busca dados no useEffect

Cards estilizados com espaçamento

Extras Implementados (Bônus)

Indicador de carregamento (ActivityIndicator)

Tratamento de erro (mensagem + opção de tentar novamente)

Botão “Recarregar lista”

Campo de pesquisa por nome

Paginação simples (carregar próxima página da API)

Screenshot do App

Print do app funcionando (substitua pelo seu arquivo):

Estrutura do Projeto
/
├── app
├── components
├── hooks
├── assets
├── package.json
├── app.json
├── README.md
└── screenshots
    └── app-running.png

Como rodar o projeto
1. Instale as dependências
npm install

2. Execute o app
npx expo start


Depois, abra no:

Expo Go (Android/iOS)

Emulador Android

Simulador iOS

API utilizada

https://rickandmortyapi.com/api/character

Autor

Douglas Amorim
GitHub: https://github.com/douglasamorim13
