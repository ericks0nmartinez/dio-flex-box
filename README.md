# dio-flex-box

Aula 1 - Introdução Flex box

Flex Container
displey: flex;
![alt "Flex Container"](../dio-flex-box/public/img/flex-container.png)

propriedades flex container que envolve os itens, transforma os seus filhos:
flex-direstion, flex-wrap,flex-flow, justify-content, aling-items, aling-content.

Flex Item

![alt "Flex Item"](../dio-flex-box/public/img/flex-item.png)

Filhos direto do flex container, podem se tornar flex container
propriedades flex item: 
flex-grow: definir fator de crescimento,
flex-basis: definir tamanho inicial antes da distribuição,
flex-shrink: definir fator de redução,
flex: abriviação 3 anteriores,
order: relacionado a orde de distribição,
aling-self: definir o alinhamento especifico de um elemento.

Aula 2 - Fundamentos

extensões:

    HTML Snippests    
    Live HTML Previewer

Qualquer tag que o style "display:flex;", se torna um flex container.

flex-direction:

    Padrão de orientação horizontal.
    Alterar orientação para vertical.

Dois eixos principais do container, definindo direção que os flex item são colocados:

    linha - row - direita para esquerda
    linha reversa - row-reverse - esquerda para direita
    Coluna - column - cima para baixo
    Coluna reversa- column-reverse - baixo para cima

Flex wrap

Define se os item deve ou não quebrar a linha:

    nowrap - padrão não quebrar linha
    wrap - alteração para quebra de linha
    wrap-reverse linha que se completara para baixo quebrando pra cima.

problema espaçamento para organizar.

Flex flow

Atalho para duas propiedades fle-direction e flex-wrap.

Justify Content

Alinhar os itens dentro do container distribuindo o espaçamento restante

    flex-start: início do container
    flex-end: fim do container
    center: ao centro do container
    space-between: separa com espaçamentos iguais entre os elementos
    space-around: separa os espaçamentos do meio, duas vezes maior que o espaçamento inicial e final nas bordas
    space-evenly: separa os espaçamentos do meio

Align Items

Trata alinhamento dos flex itens de acordo com o eixo do container

    center: alinhando ao centro
    stretch: padrão, itens crescem igualmente
    flex-start: alinhamento dos itens no inico
    flex-end: alinha os itens no final
    baseline: alinhamento de acordo com a linha base da tipografiados itens


Align Content

Tratar o alinhamento das linhas do container do eixo verticaldo contanir, altura do container tem que ser maior que a soma das linhas dos itens.

    flex-start: início do container
    flex-end: fim do container
    center: ao centro do container
    space-between: separa com espaçamentos iguais entre os elementos
    space-around: separa os espaçamentos do meio, duas vezes maior que o espaçamento inicial e final nas bordas
    space-evenly: separa os espaçamentos do meio