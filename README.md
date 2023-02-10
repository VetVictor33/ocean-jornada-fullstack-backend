# Entendendo express

## [express] npm install express

Comando para instalar o express

## [nodemon] npm install --save-dev || npm install -D nodemon

Pacote [biblioteca] que permite atualizar a page do express enquanto ela está sendo desenvolviva, sem necessidade de parar a execução

### Detalhes

Quando o express foi instalado, o node instalou a pasta node_modules, que possui uma série de pastas que representam pacotes node, além disso, também adicionou o express no packge.json como uma dependency do projeto

A pasta node_modules existe para que os arquivos necessários para o express também sejam baixados, sendo a árvore de dependências

A instalação do express trouxe o arquivo package-lock.json, que é o raio-x do projeto, que tem as dependências do projeto e suas respectivas dependências, os pacotes baixados e onde foram baixados

### Detalhes [nodemon]

Ao ser instalado, deve-se modificar o script do json alterando a linha de código:
```"dev": "nodemon index.js"```
