# Dentro da pasta /client e execute o comando:

  npm install

Este comando baixará todas as dependências utilizadas pelo projeto. Depois de baixadas, execute o script:

  npm run watch

Esse script compilará todos os arquivos e travará o terminal aguardando futuras atualizações nos arquivos. Porém, para acessar a aplicação ainda será necessário levantar o servidor. É um servidor disponibilizado com o projeto, mas ao longo dos commits irá ser substituído pelo Webpack Dev Server.

Caso queria veja atraves do primiero commit para levantar o servidor é necessário abrir uma nova aba no terminal ou um novo terminal. Neste novo terminal, acesse a pasta /server. Dentro da pasta, execute o comando:

  npm start

Para acessá-la, basta entrar com o endereço http://localhost:3000

Foi removido o babel-cli e systemjs
  npm unistall babel-cli --save-dev
  npm unistall systemjs --save

E instalado o webpack versão 3.1.0 e babel core para automatizar o processo
npm install webpack@3.1.0 babel-core@6.25.0 --save-dev

Para a minificação do bundles em foi usada um cross plataforme chamando cross-env
  npm install cross-env@5.0.1 --save-dev

Instalação do webpack dev server. Ele faz a build do projeto
  npm install webpack-dev-server@2.5.1 --save-dev  

Usando a plataforma Node.js para gerenciar as dependências de frontend. Nesse sentido, Webpack será o responsável pelo carregamento dessas dependências adicionando-as no bundle da aplicação.
  npm install bootstrap@3.3.7 --save  

Insladando um loader para o webpack ler o arquivo csss como modulo
npm install css-loader@0.28.4 style-loader@0.18.2 --save-dev
npm install url-loader@0.5.9 file-loader@0.11.2 --save-dev