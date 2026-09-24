"O usuário precisa acompanhar o pedido depois de fazer a compra"
User story -> Como comprador quero acompanhar a rota de entrega para estar preparado para recebe-lo
Critérios de aceitação:
    1: Dado que o pedido foi feito, quando ele estiver em preparação, então não será gerado um código de envio (COULD)
    2: Dado que o pedido está a caminho, quando ele dar entrada em outro estabelecimento, então será atualizada sua localização para o usuário (SHOULD)
    3: Dado que o pedido foi entregue, quando confirmada a entrega pelo cliente, então a demanda deve ser finalizada internamente no sistema (MUST)

"O restaurante precisa avisar quando um item do cardápio fica indisponível"
User story -> Como atendente, quero saber quando um item do cardápio fica indisponível para avisar o cliente que requisita-lo
Critérios de aceitação:
    1: Dado que o item esteja marcado como indisponível, quando o mesmo voltar ao cardápio, então ele deve voltar a ser listado como disponível (SHOULD)
    2: Dado que o item esteja marcado como indisponivel, quando o mesmo estiver no cadapio, então ele não pode ser processado em uma venda (MUST)
    3: Dado que o estoque do item estaja incorreto, quando for encontrada outra unidade o mesmo, então sua quantidade deve ser alterada no sistema (COULD)

 "O entregador precisa reportar um problema durante a entrega"
User story -> Como entregador, quero avisar que aconteceu um imprevisto para aletar tanto cliente quanto restaurante que o pedido pode atrasar
Critérios de aceitação:
    1: Dado que o entregador tenha um problema mecânico ou pessoal, quando estiver em rota de entrega, então ele poderá alertar o cliente que seu pedido irá atrasar (MUST)
    2: Dado que o entregador tenha um problema mecanico ou pessoal, quando estiver em rota de entrega, então ele poderá solicitar passar a entrega para outro entregador (COULD)
    3: Dado que o cliente receba o alerta de imprevisto do entregador, quando o pedido exceder o tempo limite de entrega, então ele poderá solicitar o cancelamento e reembolso do pedido (SHOULD)
