# Card de Resumo do Pedido

Fiz esse projeto pra praticar HTML e CSS. É um card de resumo de pedido de um plano anual de música, baseado no desafio "Order Summary Component" do Frontend Mentor.

O card tem uma imagem no topo, um título, um texto explicando o serviço, o plano escolhido ($59.99/year) com um link "Change", e dois botões: "Proceed to Payment" e "Cancel Order".

## O que usei

- HTML
- CSS (flexbox, grid, variáveis e media query)

## Como abrir

Baixa os arquivos e abre o `index.html` no navegador. Precisa ter a pasta `images` do lado do `index.html` e do `style.css`, senão as imagens não aparecem.

## Sobre o código

As cores ficam todas nas variáveis lá no começo do `style.css`, então dá pra mudar o visual mexendo só ali.

Pra centralizar o card na tela usei flexbox no `body`. Já a parte do plano (ícone, nome, preço e o "Change") fiz com grid, porque ficou mais fácil de alinhar.

O fundo com o padrão fica fixo atrás de tudo. No celular (até 600px) ele troca pela versão mobile usando a tag `<picture>`. E em telas de até 420px o card gruda embaixo da tela, com a borda arredondada só em cima.

