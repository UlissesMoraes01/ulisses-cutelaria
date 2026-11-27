# Portfólio — Ulisses Moraes

Site pessoal estático sobre cutelaria e forja, feito com HTML, CSS e JavaScript sem framework ou dependências de instalação. A página inclui a primeira faca do autor — aço 1080, cabo feito de ponta de galhada de cervo — e a formação em curso de Cutelaria na UnB, informações fornecidas pelo próprio autor.

## Estrutura

- `index.html`: conteúdo da página e metadados.
- `css/style.css`: identidade visual e regras responsivas.
- `js/main.js`: menu móvel e ano automático no rodapé.
- `images/primeira-faca.jpg`: fotografia enviada pelo autor.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie os arquivos deste projeto para a branch `main`.
2. Na página do repositório, acesse **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)` e clique em **Save**.
4. Aguarde a conclusão do deploy. O endereço do site aparecerá na seção Pages.

Não é necessário build: o `index.html` está na raiz. Os caminhos para CSS, JavaScript e fotos são relativos, compatíveis com repositório de projeto no Pages. Se preferir, configure publicação a partir de `/docs` copiando para lá a página e as pastas `css`, `js` e `images`.

## Personalizar

Edite o texto, título e descrição em `index.html`. Substitua `images/primeira-faca.jpg` pela sua fotografia mantendo o nome do arquivo (ou altere `src` no HTML). No `css/style.css`, ajuste cores e tipografia declaradas no início do arquivo. Se adicionar peças, insira cartões/seções antes de `#processo` e coloque as fotos em `images/`.

A foto da faca enviada por Ulisses está incorporada localmente ao projeto e também é usada na abertura do site.
