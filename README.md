# Boas vindas ao repositório do projeto de Movie Cards CRUD!

## O que foi desenvolvido

Com base em um projeto anterior, esse projeto teve como objetivo a criação de um CRUD de cartões de filmes em React.

Tendo como funcionalidades:

  - Listar todos os filmes cadastrados, com informações resumidas sobre cada filme;
  - Exibir informações detalhadas de um filme selecionado;
  - Adicionar um novo filme à lista;
  - Editar um filme da lista;
  - E apagar um filme da lista.

Este app tem 4 rotas:

1. A rota raiz (index), no caminho `/`. Esta rota exibirá uma lista com todos os filmes cadastrados. Essa lista contém informações resumidas sobre cada filme.

2. Uma rota para mostrar informações detalhadas de um filme, no caminho `/movies/:id`. Onde o `:id` é o parâmetro da URL que representa id do filme exibido. Por exemplo, ao entrar no caminho `/movies/5`, serão exibidas informações sobre o filme com id 5.

3. Uma rota para criar novos filmes, no caminho `/movies/new`. Essa rota renderizará um formulário para adicionar um novo filme.

4. Uma rota para editar um filme, no caminho `/movies/:id/edit`. Analogamente à rota 2, `:id` é o id do filme a ser editado. Essa rota renderizará um formulário idêntico ao da rota 3. Nesse caso, porém, o formulário virá preenchido com as informações do filme a ser editado. Ao submeter o formulário, ao invés de criar um novo filme, o filme em questão terá seus dados atualizados.

Relacionado a cada rota haverá um componente React responsável por renderizar seu conteúdo. Esse mapeamento entre o caminho da URL, rota e componente é feito pelo `React Router`, a principal biblioteca de roteamento em `React`.

Outra diferença importante neste projeto é que os dados virão de uma API (simulada) essa API irá: ler, criar, atualizar e apagar filmes.