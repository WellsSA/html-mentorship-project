# Projeto de HTML da Mentoria com o Wells

Este projeto tem o objetivo de recriar a página de palestrantes da Campus Party, para entendermos como funciona HTML, CSS e Javascript na prática.

Página de referência: [Palestrante - Wellington Almeida - Campus Party](https://app.4.events/palestrante-wellington-almeida-4937-c18443)

Dentro da pasta `/mentors` tem o código do mentor, que será o código feito em aula. Com o `MENTOR-README.md` que mantém o progresso do professor.

Na raiz do projeto, você iniciará o seu projeto e manterá o acompanhamento no seu `README.md`.

Para começar, crie um fork do repositório

## Cronograma de aulas práticas

- Aula 01:

  - [ ] Iniciar o projeto com o arquivo HTML
  - [ ] Adicionar e referenciar os estilos criando um arquivo CSS
  - [ ] Adicionar o normalize.css para padronização dos estilos entre browsers
  - [ ] Mudar o título da página para "Palestrante - Wellington Almeida"
  - [ ] Começar criação do header da página
    - [ ] Criar estrutura básica da página usando divs e classes
    - [ ] Usar inspecionar elementos e/ou extensão para ver as cores da página
    - [ ] Usar inspecionar elementos e/ou sources para identificar as fontes da página (tipografia)
      - [ ] Alterar fonte da página para usar a fonte Inter
    - [ ] Usar display flex para posicionamento dos elementos
    - [ ] Converter divs para tags semânticas como, por exemplo, `<header>` e `<strong>`
    - [ ] Usar `box-sizing: border-box` para mudar o comportamento padrão dos elementos e adicionar padding

- Aula 02:

  - [ ] Iniciar a implementação da Section Hero
    - [ ] Criar uma section com id "hero"
    - [ ] Analizar a estrutura da página referencia para definir as 3 divs principais: `hero-image`, `hero-info`, `hero-actions`
    - [ ] `hero-image` deve conter uma imagem usando como source a imagem: [link](https://vp2uploads.s3.amazonaws.com/18443/65/palestrantes/d0658d9008c7237409ef4e4fa8cbca654b3f5fbc.png)
    - [ ] `hero-info` deve ter duas divs: `name-section`, contendo: h1 -> nome e h2 -> profissão; e `socialmedia-section`, contendo 4 spans com os respectivos textos: LinkedIn, Twitter, Facebook, Telegram
    - [ ] `hero-actions` deve ter um botão escrito "Baixar artes de divulgação"
  - [ ] Aplicar estilização necessária para seguir o layout da referência:
    - [ ] usar display flex na section `#hero`, e definir propriedades como cor de fundo, padding e afins
    - [ ] `hero-image` deve ter altura e largura de 222px cada e aplicar o border radius na imagem
    - [ ] `hero-info` deve ter altura fixa para suportar o layout, e deve colocar o nome mais acima e as redes sociais mais abaixo. Também, essa section deve estar 32px a direita da section do lado

- Aula 03:

  - [ ] Implementar ícones na aplicação usando [Material Icons](https://fonts.google.com/icons) e [Font Awesome](https://fontawesome.com/icons)

    - [ ] Importe os estilos do Material Icons importando [este stylesheet](https://fonts.googleapis.com/icon?family=Material+Icons).
    - [ ] use os ícones `vpn_key` e `download` do Material de acordo com a referência, seguindo a estrutura `<i class="material-icons">nome_do_icone</i>`
    - [ ] Importe os estilos do Font Awesome importando [este stylesheet](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css).
    - [ ] use os ícones `linkedin-in`, `twitter`, `facebook-f` e `telegram` do Font Awesome de acordo com a referência, seguindo a estrutura `<i class="fa-brands fa-nome_do_icone"></i>`

  - [ ] Estilize a sessão de informações do palestrante na Hero section
    - [ ] Estilize a sessão de `socialmedia-section` para que os ícones tenham a cor `#A1A5A9`, margem à direita de `15px` e tamanho da fonte de `26px`
    - [ ] Estilize o subtítulo contendo o cargo do palestrante para que o `font-weight` fique `normal`
  - [ ] Começar estilização dos botões da aplicação
    - [ ] No botão do topo da página (dentro do `header`), centralizar o ícone e o texto do botão utilizando o `display: flex` e as devidas propriedades
    - [ ] Use as propriedades CSS `color, background, padding, border-radius, border` para estilizar o botão de acordo com a referência (radius: `36px`, padding: `6px 14px`, border: `1px solid white`)
    - [ ] Configure o estilo da borda para que usemos a propriedade `hover` para trocar o `border-style` para `outset`; e utilize também `transform: scale(1.02); transition: all 0.1s ease-in-out;`
    - [ ] Adicione estilos para que o ícone dentro do botão tenha uma margem à direita de `8px`
    - [ ] Defina estilos globais para que todo `button` tenha `cursor: pointer` e configure um `:disabled` global, com estilos à escolha e usando `cursor: not-allowed`
    - [ ] Configure a sessão `hero-actions` para que ela use o `flex: 1` e posicione o botão de ações no centro da sessão
    - [ ] Configure o botão dentro de `hero-actions` para que ele tenha um `border-radius` de `36px` e aplique um gradiente linear no `background`, partindo da esquerda para a direita, e partindo da cor `rgb(47, 162, 255)` para a cor `rgb(0, 255, 47)`. O ícone e o texto devem ser centralizados e o padding deve ser de `6px 14px 6px 10px`.
    - [ ] Adicione também estilos para que o ícone do botão dentro de `hero-actions` tenha um `margin-right` de `4px`
