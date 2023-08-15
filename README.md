# Tópicos Importantes

- O que é o Node.js? 
- Para que serve o NPM?
- Para que serve o Nodemon?
<br>Monitor para usarmos no modo Dev para quando fizer qualquer alteração ele restartar e manter atualizado
- O que é o express? (um framework para construir e gerenciar APIs)
- O que é API? (Sigla para Application Programming Interface, é uma interface de aplicação, um conjunto de rotas que sua aplicação vai se comunicar com aquele sistema)

# Comandos

### NPM (Node Package Manager)

Verifica a versão do npm instalada
```
npm -v
```

Inicializa o gerenciador de pacotes em um novo projeto.
```
npm init
```

Instala um novo pacote
```
npm i [nome-do-pacote]
```

Instala um novo pacote como dependencia de dev
```
npm i [nome-do-pacote] -D
```
Rodar os scripts do package json
```
npm run [nome do script]
```

### GIT

Configura o nome de usuario para commitar as mudanças
```
- git config --global user.name "Nome Usuario"
```

Configura o email do usuario para commitar as mudanças
```
- git config --global user.email "Email usuario"
```
---
```
- git config --list
```
---
```
- git init
```
---
```
- git remote add origin https://github.com/Shiibo/api_node_express.git