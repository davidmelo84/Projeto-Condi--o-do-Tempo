# WeatherApp

WeatherApp é um projeto simples que exibe a condição do tempo atual de uma cidade escolhida pelo usuário, utilizando a API OpenWeather. O projeto é desenvolvido com HTML, CSS, JavaScript e TypeScript, e é gerenciado com Node.js e npm.

## Funcionalidades

- Busca a condição do tempo atual de qualquer cidade.
- Exibe informações como temperatura, umidade, velocidade do vento e descrição do tempo.
- Interface de usuário simples e responsiva.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript
- TypeScript
- Node.js
- npm
- Fetch API
- OpenWeather API

## Pré-requisitos

Antes de começar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

- Node.js
- npm (Node Package Manager)

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/weatherapp.git
    cd weatherapp
    ```

2. Instale as dependências:

    ```bash
    npm install
    ```

3. Crie um arquivo `.env` na raiz do projeto e adicione sua chave de API do OpenWeather:

    ```env
    REACT_APP_OPENWEATHER_API_KEY=your_openweather_api_key
    ```

4. Inicie o servidor de desenvolvimento:

    ```bash
    npm start
    ```

## Estrutura de Pastas

```
weatherapp/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Weather.tsx
│   │   └── ...
│   ├── styles/
│   │   ├── App.css
│   │   └── ...
│   ├── App.tsx
│   ├── index.tsx
│   └── ...
├── .env
├── package.json
├── tsconfig.json
└── ...
```

## Uso

1. Abra o navegador e vá para `http://localhost:3000`.
2. Digite o nome de uma cidade no campo de busca e pressione Enter.
3. Veja a condição do tempo atual da cidade escolhida.

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm start`

Inicia o aplicativo em modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

### `npm run build`

Compila o aplicativo para produção na pasta `build`.\
Ele agrupa corretamente o React no modo de produção e otimiza a compilação para o melhor desempenho.

## Contribuição

1. Fork o projeto.
2. Crie uma nova branch (`git checkout -b feature/feature-name`).
3. Faça suas alterações e commite (`git commit -am 'Add some feature'`).
4. Faça push para a branch (`git push origin feature/feature-name`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT 
---

Feito com ♥ por [David Melo](https://github.com/davidmelo84)

