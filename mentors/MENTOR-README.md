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
    - [x] `hero-actions` deve ter um botão escrito "Baixar artes de divulgação"
  - [x] Aplicar estilização necessária para seguir o layout da referência:
    - [x] usar display flex na section `#hero`, e definir propriedades como cor de fundo, padding e afins
    - [x] `hero-image` deve ter altura e largura de 222px cada e aplicar o border radius na imagem
    - [x] `hero-info` deve ter altura fixa para suportar o layout, e deve colocar o nome mais acima e as redes sociais mais abaixo. Também, essa section deve estar 32px a direita da section do lado

- Aula 03:

  - [x] Implementar ícones na aplicação usando [Material Icons](https://fonts.google.com/icons) e [Font Awesome](https://fontawesome.com/icons)

    - [x] Importe os estilos do Material Icons importando [este stylesheet](https://fonts.googleapis.com/icon?family=Material+Icons).
    - [x] use os ícones `vpn_key` e `download` do Material de acordo com a referência, seguindo a estrutura `<i class="material-icons">nome_do_icone</i>`
    - [x] Importe os estilos do Font Awesome importando [este stylesheet](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css).
    - [x] use os ícones `linkedin-in`, `twitter`, `facebook-f` e `telegram` do Font Awesome de acordo com a referência, seguindo a estrutura `<i class="fa-brands fa-nome_do_icone"></i>`

  - [x] Estilize a sessão de informações do palestrante na Hero section
    - [x] Estilize a sessão de `socialmedia-section` para que os ícones tenham a cor `#A1A5A9`, margem à direita de `15px` e tamanho da fonte de `26px`
    - [x] Estilize o subtítulo contendo o cargo do palestrante para que o `font-weight` fique `normal`
  - [x] Começar estilização dos botões da aplicação
    - [x] No botão do topo da página (dentro do `header`), centralizar o ícone e o texto do botão utilizando o `display: flex` e as devidas propriedades
    - [x] Use as propriedades CSS `color, background, padding, border-radius, border` para estilizar o botão de acordo com a referência (radius: `36px`, padding: `6px 14px`, border: `1px solid white`)
    - [x] Configure o estilo da borda para que usemos a propriedade `hover` para trocar o `border-style` para `outset`; e utilize também `transform: scale(1.02); transition: all 0.1s ease-in-out;`
    - [x] Adicione estilos para que o ícone dentro do botão tenha uma margem à direita de `8px`
    - [x] Defina estilos globais para que todo `button` tenha `cursor: pointer` e configure um `:disabled` global, com estilos à escolha e usando `cursor: not-allowed`
    - [x] Configure a sessão `hero-actions` para que ela use o `flex: 1` e posicione o botão de ações no centro da sessão
    - [x] Configure o botão dentro de `hero-actions` para que ele tenha um `border-radius` de `36px` e aplique um gradiente linear no `background`, partindo da esquerda para a direita, e partindo da cor `rgb(47, 162, 255)` para a cor `rgb(0, 255, 47)`. O ícone e o texto devem ser centralizados e o padding deve ser de `6px 14px 6px 10px`.
    - [x] Adicione também estilos para que o ícone do botão dentro de `hero-actions` tenha um `margin-right` de `4px`
