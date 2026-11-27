# Portfólio — Ulisses Moraes

Site estático e responsivo sobre cutelaria e forja, feito com HTML, CSS e JavaScript sem framework nem dependências de instalação. Apresenta a primeira faca de Ulisses — aço 1080 e cabo feito com ponta de galhada de cervo —, uma galeria da coleção Castel e um resumo da história da empresa baseado em informações publicadas pela própria Castel.

## Estrutura

- `index.html`: página inicial, apresentação pessoal, primeira faca e história institucional da Castel.
- `colecao.html`: galeria com os 11 modelos Castel confirmados por Ulisses.
- `css/style.css`: identidade visual e estilos responsivos compartilhados pelas duas páginas.
- `js/main.js`: menu móvel e atualização automática do ano no rodapé.
- `images/primeira-faca.jpg`: fotografia enviada por Ulisses.
- `manus-routes.json`: manifesto das páginas estáticas do site.

## Galeria e fontes

As fotos dos produtos são imagens oficiais de referência do catálogo da [Facas Castel](https://facascastel.com/). Elas são creditadas na galeria e cada modelo tem um link para sua respectiva página na loja. As imagens de catálogo não são registros fotográficos dos exemplares físicos de Ulisses. A história da empresa também é resumida a partir das informações institucionais que ela publica no site oficial.

## Publicar no GitHub Pages

1. Envie os arquivos do projeto para a branch `main` do repositório.
2. No GitHub, acesse **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)` e clique em **Save**.
4. Aguarde a conclusão do deploy; o endereço do site aparecerá na seção Pages.

O GitHub Pages lê os arquivos diretamente da raiz; não é necessário build. Os caminhos são relativos e funcionam tanto em site de projeto quanto na raiz do domínio. Se publicar a partir de `/docs`, copie para lá as duas páginas e as pastas `css`, `js` e `images`.

## Personalizar

Edite os textos e metadados em `index.html` e `colecao.html`. Para substituir uma imagem de produto, troque o `src` no cartão correspondente e mantenha a identificação de foto de referência e o crédito à Castel; imagens próprias dos exemplares podem ser adicionadas quando estiverem disponíveis. Preserve ou atualize o link do produto que dá crédito à imagem. Os estilos comuns ficam em `css/style.css`.
