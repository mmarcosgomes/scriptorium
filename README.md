# meusite

Site pessoal em HTML puro.

## Estrutura

- `index.html`: home
- `sobre/index.html`: sobre
- `projetos/index.html`: listagem de projetos
- `projetos/<projeto>/index.html`: página individual do projeto
- `blog/index.html`: listagem de posts com filtro CSS puro
- `blog/<post>/index.html`: página individual do post

## Como manter

- Para criar um post novo:
  1. Copie uma pasta existente em `blog/` e renomeie para o novo slug.
  2. Edite o `index.html` do post.
  3. Ajuste o título, a data e o texto.
  4. Adicione o card do post em `blog/index.html`.
  5. Se o post pertencer a um projeto, adicione o link também em `projetos/<projeto>/index.html`.

- Para criar ou atualizar um projeto:
  1. Copie uma pasta existente em `projetos/` e renomeie para o novo slug.
  2. Edite o `index.html` do projeto.
  3. Ajuste o título, o progresso e a lista de posts ligados.

- Não existe mais build automático, `package.json`, `build.mjs` ou `blog/posts.json`.
- No Cloudflare Pages, publique como site estático, sem build command.
