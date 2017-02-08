# kpl-ui-tookit

## Installation

```bash
npm install
npm rebuild node-sass
npm run dummy
```

## Collaboration

ver as diretrizes de desenvolvimento em:
https://github.com/mercadolibre/kpl-ui-toolkit/wiki/Diretrizes-de-componentes

## Publish

A lib está sendo publicado no NPM Registry privado do Meli - [registry.npm.ml.com/kpl-ui-toolkit](http://registry.npm.ml.com/kpl-ui-toolkit).

### Antes de publicar

Para publicar novas versões no NPM é necessário fazer a configuração de usuário. Em um terminal digite:

```
cd /pasta/da/lib
npm add user
Usuário: admin
Senha: QmeNC5OFlts
```

### Publicando novas versões

Em um terminal digite:

```
cd /pasta/do/hub
npm run update-next
```

Esse comando gera um novo build, atualiza a versão da aplicação (patch) e publica na tag next.

### Tags de publicação

Para cada versão, atualizamos a tag next. Essa tag é usada como tag de preview ou beta. Quando gerarmos um release completo e testado, podemos publicar na tag comum chamada latest. Para isso, basta rodar o comando npm publish

### License

Copyright © 2016, MercadoLibre

