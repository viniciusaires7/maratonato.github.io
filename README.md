# ACM ICPC at Tocantins [![Build Status](https://travis-ci.org/maratonato/maratonato.github.io.svg)](https://travis-ci.org/maratonato/maratonato.github.io) [![Join the chat at https://gitter.im/maratonato/maratonato.github.io](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/maratonato/maratonato.github.io?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Este é o repositório oficial do site da Maratona de Programação no estado do Tocantins.

## Como funciona?

Este projeto utiliza [Jekyll](http://jekyllrb.com/), que é um gerador de páginas estáticas em Ruby.

<p align="center"><img src="images/screenshot-home.png" /></p>

<caption>Website MaratonaTO</caption>

## Primeiros passos

1. Instale o [Git](http://git-scm.com/downloads) e [Ruby](http://www.ruby-lang.org/pt/downloads/), se você ainda não tiver instalado.

2. Primeiramente, fork o repositório em [MaratonaTO](https://github.com/maratonato/maratonato.github.io).

<p align="center"><img src="images/fork.png" /></p>

3. Após isso, abra um terminal e instale o [Jekyll](http://jekyllrb.com/) com o seguinte comando:

  ```sh
  $ gem install jekyll
  ```

4. Agora clone o projeto:

  ```sh
  $ git clone git@github.com:YOUR_USER_NAME/maratonato.github.io.git
  ```

5. Vá até a pasta do projeto:

  ```sh
  $ cd maratonato.github.io/
  ```

6. E finalmente execute:

  ```sh
  $ jekyll server --watch
  ```

Você terá acesso ao site no endereço `localhost:4000` :smile:

## Navegadores suportados

![IE](https://cloud.githubusercontent.com/assets/398893/3528325/20373e76-078e-11e4-8e3a-1cb86cf506f0.png) | ![Chrome](https://cloud.githubusercontent.com/assets/398893/3528328/23bc7bc4-078e-11e4-8752-ba2809bf5cce.png) | ![Firefox](https://cloud.githubusercontent.com/assets/398893/3528329/26283ab0-078e-11e4-84d4-db2cf1009953.png) | ![Opera](https://cloud.githubusercontent.com/assets/398893/3528330/27ec9fa8-078e-11e4-95cb-709fd11dac16.png) | ![Safari](https://cloud.githubusercontent.com/assets/398893/3528331/29df8618-078e-11e4-8e3e-ed8ac738693f.png)
--- | --- | --- | --- | --- |
IE 8+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Estrutura de arquivos

A estrutura básica dos arquivos deste projeto é organizada da seguinte maneira:

```
.
|-- _includes
|-- _layouts
|-- _posts
|-- _site
|-- _images
|-- _public
|-- _config.yml
`-- index.html
```

### [_includes](https://github.com/maratonato/maratonato.github.io/tree/master/_includes)

São blocos de código usados para gerar a página principal do site ([index.html](https://github.com/maratonato/maratonato.github.io/blob/master/index.html)).

### [_posts](https://github.com/maratonato/maratonato.github.io/tree/master/_posts)

Aqui você encontrará uma lista de arquivos para cada post.

### [_layouts](https://github.com/maratonato/maratonato.github.io/tree/master/_layouts)

Aqui você encontrará o template padrão da aplicação

### [_site](https://github.com/maratonato/maratonato.github.io/tree/master/_site)

Aqui você encontrará todos os arquivos estáticos gerados pelo jekyll após a sua execução. No entanto, este diretório é desnecessário neste projeto, portanto ele é ignorado em ([.gitignore](https://github.com/maratonato/maratonato.github.io/blob/master/.gitignore)).

### [_config.yml](https://github.com/maratonato/maratonato.github.io/blob/master/_config.yml)

Contém a maioria das configurações da aplicação.

### [index.html](https://github.com/maratonato/maratonato.github.io/blob/master/index.html)

Contém todas as seções da aplicação.

## Sincronizando seu fork

Caso você já tenha feito fork a algum tempo você tem duas opções para garantir que estará trabalhando com as ultimas alterações, que pode ser simplesmente deletar seu fork e fazer um novo ou sincronizar seu fork com o repositório de origem usando as [instruções contidas na wiki](https://github.com/maratonato/maratonato.github.io/wiki/Sincronizando-seu-fork-com-o-reposit%C3%B3rio-principal)

## Autores

Este projeto foi idealizado por [@herodrigues](https://www.github.com/herodrigues)

## Lista completa de [colaboradores](https://github.com/maratonato/maratonato.github.io/graphs/contributors).

- [@herodrigues](https://www.github.com/herodrigues) - Herinson Rodrigues
- [@viniciusaires7](https://www.github.com/viniciusaires7) - Vinícius Aires

## Licença

[MIT License](http://mit-license.org/) © Maratona TO

Visite o site [https://maratonato.github.io](https://maratonato.github.io).

_Este projeto utiliza o tema [Hyde](http://hyde.getpoole.com/)._
