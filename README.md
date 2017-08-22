# Project R2

Trata-se de um escopo cru para projetos futuros utilizando Drupal 8.3x, contendo módulos essenciais e um sub tema em Bootstrap com Sass, Singularity, Breakpoint, LiveReload, Gulp e Font Awesome (CDN).


## Informações do Projeto

- Repositório de código principal: https://github.com/1ns/project-r2
- Issue tracker: https://github.com/1ns/project-r2/issues


## Responsável
- [Alan Amorim (ins)](mailto:alan.amorim@live.com)


## Instruções de desenvolvimento

O tema principal deste projeto conta como base o Bootstrap, utilizando seu starterkit com Sass.
Para trabalhar no tema, primeiro é necessário ter o nodejs instalado.

```sudo apt-get update && sudo apt-get install nodejs```

Seguir [estas](https://drupal-bootstrap.org/api/bootstrap/starterkits%21sass%21README.md/group/sub_theming_sass/8) instruções em cima do tema *bootstrap_sass_starterkit*
Entre na pasta do tema que você configurou e digite:

```npm install```

Depois de todas as dependências terem sido instaladas com sucesso, instale o gulp globalmente:

```npm install -g gulp```

Agora digite "gulp" e ele irá compilar o que precisar e irá detectar quaisquer mudanças nos arquivos em tempo real.
Você precisa ter seu webserver configurado pra rodar o site em r2.l, pois sem isso você ficará sem acesso ao BrowserSync.


## TODO
- Colocar mais informações práticas de desenvolvimento do projeto.
