# SyntaxWear

Landing page de e-commerce voltada para venda de tênis e sneakers, com visual moderno, premium e foco em conversão. O projeto foi desenvolvido em HTML e CSS puro, com estrutura responsiva e seções para hero, categorias, destaques de produtos e newsletter.

## Visão geral

A SyntaxWear é uma marca fictícia de calçados esportivos e urbanos. O objetivo do site é apresentar a identidade visual da marca, destacar coleções e criar uma experiência de compra moderna e atrativa em uma página estática.

### Principais seções

- Header com navegação e ícones de acesso rápido
- Hero banner com call-to-action principal
- Cards de categorias por estilo
- Grid de destaques com modelos de sneakers
- Área de newsletter e redes sociais
- Footer com navegação e informações gerais

## Tecnologias utilizadas

- HTML5
- CSS3
- Google Fonts
- Imagens locais em SVG e assets do projeto

## Estrutura do projeto

```text
.
├── css/
│   ├── base.css
│   ├── reset.css
│   ├── variables.css
│   ├── layout.css
│   └── components/
│       ├── footer.css
│       ├── header.css
│       ├── hero.css
│       ├── product-category.css
│       └── product-grid.css
├── images/
│   ├── banners/
│   ├── favicons/
│   ├── icons/
│   ├── logo/
│   └── products/
├── index.html
├── README.md
└── .git/
```

## Como executar localmente

Como o projeto é uma landing page estática, não há dependências de instalação. Você pode abrir o arquivo `index.html` diretamente no navegador ou iniciar um servidor local.

### Opção 1: abrir diretamente

- Abra o arquivo `index.html` no navegador

### Opção 2: servidor local

No terminal, na pasta do projeto:

```bash
python -m http.server 8000
```

Depois acesse:

```text
http://localhost:8000
```

Se preferir, também é possível usar extensões como Live Server no VS Code.

## Arquivos principais

### `index.html`
Arquivo principal da página, contendo a estrutura do layout e os componentes visuais do site.

### `css/base.css`
Define os estilos gerais do corpo, layout principal e botões reutilizáveis.

### `css/variables.css`
Contém a fonte principal configurada via CSS variables.

### `css/components/`
Arquivos específicos para cada parte da interface:

- `header.css`: navegação e topo do site
- `hero.css`: banner principal e ações estratégicas
- `product-category.css`: categorias de produtos
- `product-grid.css`: grid de destaques de calçados
- `footer.css`: rodapé, newsletter e redes sociais

## Personalização

Para adaptar a marca ou o front-end, você pode alterar:

- Cores e tipografia em `css/variables.css`
- Layout geral em `css/base.css`
- Componentes específicos em `css/components/*.css`
- Texto e conteúdo em `index.html`
- Imagens e logos em `images/`

## Design e identidade visual

A marca leva uma estética moderna com:

- paleta em roxo, branco e tons de cinza
- elementos de destaque com bordas e contraste
- foco em premiumização visual
- linguagem mais urbana e tecnológica

## Melhorias futuras sugeridas

- adicionar página de catálogo com filtros
- incluir carrinho de compras
- criar página de produto individual
- implementar responsividade avançada para todos os dispositivos
- integrar com backend para checkout e gerenciamento de pedidos

## Licença

Este projeto foi desenvolvido como exemplo de landing page e-commerce para fins de estudo e demonstração.

## Autor

Projeto fictício de marca e-commerce SyntaxWear.

## Observações

O site atual é uma implementação front-end estática e funciona como protótipo visual. Ele pode ser expandido para uma aplicação completa com dinâmica de produtos, autenticação e checkout.
