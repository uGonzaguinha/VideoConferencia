# VideoConferencia

## Descrição
Este é um projeto de aplicação de videoconferência desenvolvido em Node.js e Express, utilizando EJS para renderização de páginas. O objetivo deste projeto é fornecer uma plataforma simples e eficaz para realizar videoconferências.

## Funcionalidades
- Criação de salas de videoconferência.
- Participação em salas de videoconferência através de um link único.
- Suporte para múltiplos participantes em uma sala.

## Tecnologias Utilizadas
- Node.js
- Express
- EJS
- Socket.io
- UUID
- PeerJS

## Instalação
Para instalar e executar este projeto localmente, siga os passos abaixo:

1. Clone este repositório:
    ```sh
    git clone https://github.com/uGonzaguinha/VideoConferencia.git
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd VideoConferencia
    ```

3. Instale as dependências:
    ```sh
    npm install express ejs socket.io uuid peer
    ```

4. Inicie o servidor:
    ```sh
    npm start
    ```

5. Acesse a aplicação em seu navegador:
    ```
    http://localhost:3000
    ```

## Uso
1. Abra o navegador e acesse a URL do servidor.
2. Crie uma nova sala de videoconferência.
3. Compartilhe o link da sala com os participantes.
4. Acesse a sala utilizando o link fornecido.

## Estrutura do Projeto
- `public/` - Arquivos estáticos (CSS, JS, imagens)
- `views/` - Templates EJS
- `server.js` - Arquivo principal do servidor
