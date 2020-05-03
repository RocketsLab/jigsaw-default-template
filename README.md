# Jigsaw Default Template

This is a default template (without any customization) to build a site with Jigsaw.

## Instalation

* Install [**Jigsaw**](https://jigsaw.tighten.co/docs/installation/)

After install jigsaw, run the following command from your project directory:

```shell script
./vendor/bin/jigsaw init rocketslab/jigsaw-default-template
```

## Composer scripts

This template comes with 2 scripts to "shortcut" jigsaw commands:

**Build** project:

```shell script
composer run build
```

**Run a server** to preview:

```shell script
composer run serve
```

## Building and Previewing your site

If you want build your JS and CSS assets and preview your site with Hot-Reload, 
just install NPM dependencies with following command:

```shell script
npm run install
``` 

After install run:

```shell script
npm run watch
```

The command above starts a [**BrowserSync**](https://www.browsersync.io/) and keep
watching for files modifications and reloads the page automatically.

**Thanks!**

By [**Jorge Gonçalves**](https://github.com/jjsquady)

[RocketsLab](https://rocketslab.com.br)

---

### For Brazilian Users

Este é um template padrão (sem modificações) pra criar sites com Jigsaw.

## Instalação

* Instale [**Jigsaw**](https://jigsaw.tighten.co/docs/installation/)

Depois de instalado, rode o comando abaixo de dentro do diretório do seu projeto:

```shell script
./vendor/bin/jigsaw init rocketslab/jigsaw-default-template
```

## Composer scripts

Este template vem com 2 scripts do composer como "atalhos" para comandos do jigsaw:

**Gerar** o projeto:

```shell script
composer run build
```

**Rodar um servidor** para visualizar:

```shell script
composer run serve
```

## Gerando e visualizando seu site

Se você quer gerar seus arquivos JS e CSS e prever o site com recarregamento automático,
instale as dependências NPM com o comando abaixo:

```shell script
npm run install
``` 

Para ter o recarregamento automático:

```shell script
npm run watch
```

O comando acima inicia uma instância do [**BrowserSync**](https://www.browsersync.io/) e fica
de olho em mudanças nos arquivos do projeto e recarrega o site automaticamente toda vez que um arquivo
foi modificado.

**Obrigado!**

Criado por [**Jorge Gonçalves**](https://github.com/jjsquady)

[RocketsLab](https://rocketslab.com.br)
