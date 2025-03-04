## Como criar React Native localmente

Passo 1: Instalando as ferramentas necessárias

1.1 Instalar o Node.js

O Node.js é necessário para rodar o Expo CLI, que é a ferramenta que vamos usar para criar o projeto React Native.

Baixe o Node.js: Acesse aqui e baixe a versão recomendada (LTS)- https://nodejs.org/pt/download
Instalação: Após o download, siga as instruções do instalador para finalizar a instalação.
Para confirmar que o Node.js foi instalado corretamente, abra o terminal/linha de comando (dependendo do seu sistema operacional) e execute:

  node -v

Isso vai retornar a versão do Node.js instalada.


1.2 Instalar o Expo CLI

O Expo CLI é a ferramenta que cria o projeto React Native de maneira simples.

Instalar o Expo CLI: No terminal, execute o seguinte comando para instalar o Expo CLI globalmente:

  npm install -g expo

Para confirmar que o Expo foi instalado corretamente, execute:


  expo --version


1.3 Instalar o Git

O Git é essencial para gerenciar o seu código e fazer o upload para o GitHub.

Baixar o Git: Acesse aqui e baixe o Git para o seu sistema operacional- https://git-scm.com/downloads
Instalação: Após o download, siga as instruções para instalar o Git.
Para confirmar a instalação, abra o terminal e execute:


  git --version

obs.: Feche e abra novamente o terminal se não encontrar a versão do git


1.4 Instalar o VS Code

O VS Code é um editor de código que você pode usar para editar seu código de forma fácil.

Baixar o VS Code: Acesse aqui e baixe o VS Code para o seu sistema operacional- https://code.visualstudio.com/download
Instalar: Após o download, siga as instruções do instalador para finalizar a instalação.



Passo 2: Criar o projeto com o Expo CLI
Agora que todas as ferramentas estão instaladas, vamos criar o projeto!


2.1 Criar o projeto

Abra o terminal/linha de comando e navegue até a pasta onde você quer criar o projeto (por exemplo, Desktop).
exemplo: cd C:\Users\seu_usuario\Desktop

Execute o seguinte comando para criar o projeto:

    npx create-expo-app@latest nome-do-seu-projeto

Substitua nome-do-seu-projeto por qualquer nome que você queira dar ao seu projeto (como react-native-app).

O Expo CLI vai começar a criar o projeto e instalar as dependências necessárias. Isso pode levar um tempo, dependendo da sua internet.

Após terminar, entre na pasta do projeto:

    cd nome-do-seu-projeto

Passo 3: Acessar seu projeto

3.1 Abrir o VS Code

Abra o VS Code e dentro dele abra a pasta do seu projeto:

No VS Code, vá em File > Open Folder e escolha a pasta do seu projeto (nome-do-seu-projeto) ou simplesmente digite, no terminal:

  code .

## Como rodar o projeto React Native

1. Instale o Expo CLI globalmente:
No terminal:
   npm install -g expo

Clone este repositório e entre na pasta do projeto:

  git clone <URL_DO_REPOSITORIO>
  cd nome-do-seu-projeto

Instale as dependências:

 npm install

Para iniciar o projeto, execute o comando:

 npx expo start

Abra o Expo Go no seu celular e escaneie o QR code que aparecerá no terminal se desejar testar no seu celular 

Nome do estudante: João Pedro Couto de Oliveira
