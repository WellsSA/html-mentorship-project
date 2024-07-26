# Projeto de HTML da Mentoria com o Wells

Este projeto tem o objetivo de recriar a página de palestrantes da Campus Party, para entendermos como funciona HTML, CSS e Javascript na prática.

Página de referência: [Palestrante - Wellington Almeida - Campus Party](https://app.4.events/palestrante-wellington-almeida-4937-c18443)

## Cronograma de aulas práticas

- Aula 01:

  - [x] Iniciar o projeto com o arquivo HTML
  - [x] Adicionar e referenciar os estilos criando um arquivo CSS
  - [x] Adicionar o normalize.css para padronização dos estilos entre browsers
  - [x] Mudar o título da página para "Palestrante - Wellington Almeida"
  - [x] Começar criação do header da página
    - [x] Criar estrutura básica da página usando divs e classes
    - [x] Usar inspecionar elementos e/ou extensão para ver as cores da página
    - [x] Usar inspecionar elementos e/ou sources para identificar as fontes da página (tipografia)
      - [x] Alterar fonte da página para usar a fonte Inter
    - [x] Usar display flex para posicionamento dos elementos
    - [x] Converter divs para tags semânticas como, por exemplo, `<header>` e `<strong>`
    - [x] Usar `box-sizing: border-box` para mudar o comportamento padrão dos elementos e adicionar padding

- Aula 02:
  - [x] Iniciar a implementação da Section Hero
    - [x] Criar uma section com id "hero"
    - [x] Analizar a estrutura da página referencia para definir as 3 divs principais: `hero-image`, `hero-info`, `hero-actions`
    - [x] `hero-image` deve conter uma imagem usando como source a imagem: [link](https://vp2uploads.s3.amazonaws.com/18443/65/palestrantes/d0658d9008c7237409ef4e4fa8cbca654b3f5fbc.png)
    - [x] `hero-info` deve ter duas divs: `name-section`, contendo: h1 -> nome e h2 -> profissão; e `socialmedia-section`, contendo 4 spans com os respectivos textos: LinkedIn, Twitter, Facebook, Telegram
    - [ ] `hero-actions` deve ter um botão escrito "Baixar artes de divulgação"
  - [ ] Aplicar estilização necessária para seguir o layout da referência:
    - [ ] usar display flex na section `#hero`, e definir propriedades como cor de fundo, padding e afins
    - [ ] `hero-image` deve ter altura e largura de 222px cada e aplicar o border radius na imagem
    - [ ] `hero-info` deve ter altura fixa para suportar o layout, e deve colocar o nome mais acima e as redes sociais mais abaixo. Também, essa section deve estar 32px a direita da section do lado
