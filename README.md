# Programação de Dispositivos Móveis 2 - Aulas

Como Criar um Projeto PWA:
1. Criar o diretório do projeto;

2. Transformar o diretório em um projeto Node.js:
	2.1. Terminal: "npm init -y";
	2.2. Em "package.json" alterar o valor de "main" para "index.html".

3. Adicionar a dependência "serve":
	3.1. Terminal: "npm i serve --save";
	3.2. Em "package.json", adicionar a seguinte linha em "scripts": "serve": "serve .".
    
4. Criar a estrutura de diretórios do projeto:
	4.1. Pasta "css" contendo o arquivo "styles.css";
    4.2. Pasta "js" para armazenar os scripts referentes ao projeto;
    4.3. Pasta "images" para armazenar as imagens referentes ao projeto;
    4.4. Arquivo "favicon.ico", o ícone que define a imagem presente a aba do navegador;
    4.5. Arquivo "index.html" para ocupar a função de "start" da aplicação;
    4.6. Arquivo "manifest.json" para guardar as configurações referentes à PWA;
    4.7. Arquivo "sw.js" - a.k.a. Service Worker -, o qual dispõe a aplicação offline e permite a instalação/cachê da mesma.

5. Para executar o projeto, rode: "npm run serve".