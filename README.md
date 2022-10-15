# OpenStreetMap GitHub Actions
[![img/github-actions.png](img/github-actions.png)](https://github.com/features/actions)

**Lista para copiar-e-colar de exemplos de [GitHub Actions](https://github.com/features/actions) com uso relacionado ao [OpenStreetMap](https://www.openstreetmap.org/help).**

---

<!-- TOC depthfrom:2 -->

- [Introdução](#introdu%C3%A7%C3%A3o)
    - [Comparação com GitHub pages](#compara%C3%A7%C3%A3o-com-github-pages)
    - [Comparação com "ter um servidor próprio"](#compara%C3%A7%C3%A3o-com-ter-um-servidor-pr%C3%B3prio)
- [Lista de Actions](#lista-de-actions)
    - [Exemplos genéricos de como rodar script de linguagem de programação](#exemplos-gen%C3%A9ricos-de-como-rodar-script-de-linguagem-de-programa%C3%A7%C3%A3o)
        - [Bash](#bash)
        - [Java](#java)
        - [Lua](#lua)
        - [JavaScript NodeJS](#javascript-nodejs)
        - [Perl](#perl)
        - [PHP](#php)
        - [Python](#python)
        - [Ruby](#ruby)
    - [Exemplos genéricos de bando de dados](#exemplos-gen%C3%A9ricos-de-bando-de-dados)
        - [PostgreSQL](#postgresql)
    - [Aplicativos](#aplicativos)
        - [Flutter](#flutter)
- [Lista de Desejos](#lista-de-desejos)
- [Licença](#licen%C3%A7a)

<!-- /TOC -->

---

## Introdução

### Comparação com GitHub pages
O [GitHub Pages](https://pages.github.com/),
uma hospedagem gratuita amplamente usada por anos,
sempre ofereceu hospedagem com funcionalidade restrita usando [Jekyll](https://jekyllrb.com/).
GitHub Actions também também ser usadas para gerar sites estáticos gratuitamente e praticamente sem limitações para projetos código aberto.

### Comparação com "ter um servidor próprio"
> TODO: explicar

## Lista de Actions

### Exemplos genéricos de como rodar script de linguagem de programação

> Decisão é baseada no que é usado em https://github.com/openstreetmap e https://github.com/osmlab.

#### Bash
- [.github/workflows/generic_bash.yml](.github/workflows/generic_bash.yml)
  - [.github/scripts/salve_mundi.sh](.github/scripts/salve_mundi.sh)

#### Java
- [.github/workflows/generic_java.yml](.github/workflows/generic_java.yml)
  - [.github/scripts/salve_mundi.java](.github/scripts/salve_mundi.java)

#### Lua
- [.github/workflows/generic_lua.yml](.github/workflows/generic_lua.yml)
  - [.github/scripts/salve_mundi.lua](.github/scripts/salve_mundi.lua)

#### JavaScript (NodeJS)
- [.github/workflows/generic_nodejs.yml](.github/workflows/generic_nodejs.yml)
  - [.github/scripts/salve_mundi.js](.github/scripts/salve_mundi.js)

#### Perl
- [.github/workflows/generic_perl.yml](.github/workflows/generic_perl.yml)
  - [.github/scripts/salve_mundi.pl](.github/scripts/salve_mundi.pl)

#### PHP
- [.github/workflows/generic_php.yml](.github/workflows/generic_php.yml)
  - [.github/scripts/salve_mundi.php](.github/scripts/salve_mundi.php)

#### Python
- [.github/workflows/generic_python.yml](.github/workflows/generic_python.yml)
  - [.github/scripts/salve_mundi.py](.github/scripts/salve_mundi.py)

#### Ruby
- [.github/workflows/generic_ruby.yml](.github/workflows/generic_ruby.yml)
  - [.github/scripts/salve_mundi.rb](.github/scripts/salve_mundi.rb)

### Exemplos genéricos de bando de dados

#### PostgreSQL
- [.github/workflows/generic_postgresql.yml](.github/workflows/generic_postgresql.yml)

### Aplicativos

#### Flutter
- [.github/workflows/generic_app_flutter.yml](.github/workflows/generic_app_flutter.yml)
  - <https://github.com/OsmPernambuco/ReciBus>

## Lista de Desejos

- [x] Instalador generico de linguages de programação e ambientes mais comuns de:
  - https://github.com/openstreetmap
  - https://github.com/osmlab
- [ ] Exemplo de integração de Bot com Telegram
  - https://github.com/appleboy/telegram-action
- [ ] JOSM cli
  - https://wiki.openstreetmap.org/wiki/JOSM/Plugins/CommandLine
  - https://github.com/Foxhind/JOSM-CommandLine-commands


  <!--
  - Maybe
    - https://github.com/marketplace/actions/workflow-webhook-action
    - https://kontent.ai/blog/how-to-trigger-github-action-using-webhook-with-no-code/
  -->

## Licença

[![Domínio Público](img/dominio-publico.png)](LICENSE)

Na medida do possível segundo a lei, [Emerson Rocha](https://github.com/fititnt)
renunciou a todos os direitos autorais e direitos conexos ou vizinhos a este
trabalho para o [Domínio Público](LICENSE).