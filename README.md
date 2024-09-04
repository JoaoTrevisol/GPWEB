No código HTML criamos 3 DIV pai e dentro de cada uma delas, uma DIV filho.
As divs pai atuam como contêiners para os elementos internos, cada um com uma classe (class) diferente: 'pai", "pai2", pai3".
As classes (class) associadas a esses div estão sendo usadas para aplicar estilos CSS diferentes, utilizando Flexbox para posicionar os retângulos: "Center", "Left" e "right" através do CSS.

Agora, no código em CSS:
Elementos Pai (.pai, .pai2, .pai3)

-Todos os contêineres pais (.pai, .pai2, .pai3) compartilham um fundo de cor plum (Roxo claro) e uma borda sólida preta de 5px.

-A altura é definida em 100px para todos.

-Todos utilizam display: flex, o que permite a organização dos elementos filhos de maneira flexível dentro dos containers.

.pai:
Centraliza horizontalmente o conteúdo com justify-content: center.

.pai2:
Alinha o conteúdo à esquerda com justify-content: left.
Tem uma margem superior de 100px para criar espaço em relação ao conteúdo acima.

.pai3:
Alinha o conteúdo à direita com justify-content: right.
Utilizando também uma margem superior de 100px.

Elementos Filhos (.filho, .filho2, .filho3):

-Todos os elementos filhos dentro dos containers pais compartilham um fundo de cor orange e têm uma borda preta pontilhada de 3px.

-A altura é de 80px e a largura de 300px para todos.

-Usam display: flex para organizar o conteúdo interno (center, left e right), centrando-o tanto horizontalmente (justify-content: center) quanto verticalmente (align-items: center).

-Todos têm uma margem de 5px ao redor para criar espaço entre os elementos.
