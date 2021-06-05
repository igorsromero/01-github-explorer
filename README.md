Projeto em ReactJs desenvolviudo como forma de estudo.

<details>
<summary>Iniciando o projeto</summary>

Criando o projeto:
```
yarn init -y
```

Adicionando o React:
```
yarn add react
```

Adicionando o React DOM:
```
yarn add react-dom
```

Adicionando o Babel:
```
yarn add @babel/core @babel/cli @babel/preset-env -D
yarn add @babel/preset-react -D
yarn add babel-loader -D
```

<details>
<summary>Saiba mais sobre o Babel</summary>

- @babel/core: A biblioteca do babel.
- @babel/cli: Executar o babel através da linha de comando.
- @babel/preset-env: Biblioteca do babel que identifica qual ambiente a aplicação ta sendo executada, para converter o código da melhor maneira possível.
- babel-loader: É responsável pela integração entre o babel e o webpack.

</details>

Adicionando o Webpack:
```
yarn add webpack webpack-cli -D
yarn add webpack-dev-server -D
```

Adicionando o HTML-Webpack-Plugin:
```
yarn add html-webpack-plugin -D
```

Adicionando Cross-Env:
```
yarn add cross-env -D
```

Adicionando Style e CSS Loader:
```
yarn add style-loader css-loader -D
```

Adicionar Sass:
```
yarn add sass-loader -D
yarn add node-sass -D
```

Comando para transpilar:
```
yarn webpack
yarn webpack serve
```

</details>

<details>
<summary>Estrutura de pastas</summary>

- src -> Onde fica todo o código criado por nós, principalmente o código javascript.
- public -> Arquivos públicos, index.html, icone favicon, robot.txt, qualquer arquivo que é acessado diretamente do meio externo.
</details>


<details>
<summary>Dúvidas</summary>

- Qual a diferença entre NPM e YARN?
- O que é o Babel ?

</details>

<details>
<summary>Problemas Enfrentados</summary>

- O Babel não estava executando nem realizando o Webpack, após pesquisa, encontrei um método de solucionar, que é alterar o nome do babel.config.js para .babelrc e adicionar as propriedades do bapel através do método utilizado atualmente. [Link para a questão]

[Link para a questão]: https://stackoverflow.com/questions/66525387/add-babel-preset-react-https-git-io-jfedr-to-the-presets-section-of-your

</details>
