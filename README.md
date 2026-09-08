# Diogo & Bethânia — O universo em detalhes

Álbum afetivo estático em HTML, CSS e JavaScript, compatível com GitHub Pages, sem build.

## Prévia local

Execute `python -m http.server 8000 --bind 127.0.0.1` nesta pasta e abra http://127.0.0.1:8000.

## Organização

- `index.html`: história original, linha do tempo, cartas de um e dois meses e carta da Bethânia, galeria e links de música.
- `styles.css`: identidade visual e layouts para celular e computador.
- `script.js`: abertura das cartas por link, fotos ampliadas e contador no fuso de São Paulo.
- `assets/`: cinco fotografias originais para ampliação e versões WebP de 480 e 960 pixels para carregamento responsivo e cache.

A única dependência visual externa é Google Fonts (Fraunces e DM Sans), com fontes locais de fallback. A leitura e as cartas funcionam sem JavaScript. A música e a playlist abrem no YouTube mediante escolha de quem está lendo.

## Publicação

Envie `index.html`, `styles.css`, `script.js` e `assets/` à branch configurada no GitHub Pages. Não há instalação de pacotes nem etapa de compilação.
