Como cliente, quero avaliar o pedido depois da entrega, para ajudar outros clientes a escolherem melhor.
Dado que o pedido foi entregue, quando o cliente abre o app, então aparece a opção de avaliar o pedido.
Dado que o cliente avalia com nota e comentário, quando confirma o envio, então a avaliação aparece no perfil do restaurante
--> RNF 1: A avaliação do usuário terá um limite de 300 caracteres e fará a cesura de termos ofensivos (Segurança)
--> RNF 2: A avaliação deve aparecer em até dois minutos para os outros usuários depois de enviada (Confiabilidade)
--> RNF 3: A nota de um restaurante será a soma de todas as notas recebidas divididas pela quantidade de usuários que avaliaram (Adequação funcional)

Como cliente, quero salvar um cartão de pagamento, para não digitar os dados a cada compra.
Dado que o cliente cadastra um cartão válido, quando confirma o cadastro, então o cartão fica disponível para escolha no checkout.
Dado que o cliente tem um cartão salvo, quando faz um novo pedido, então pode selecionar esse cartão sem redigitar os dados.
--> RNF 1: A confirmação da compra não pode demorar mais do que dois segundos em 95% dos casos (Confiabilidade)
--> RNF 2: O cliente poderá cadastrar de um a cinco cartões, e poderá alternar entre eles com menos de três cliques (Usabilidade)
--> RNF 3: A emissão do comprovante de compra deve ser enviada por e-mail para o comprador em até 5 minutos pós compra (Adequação funcional)

Como dono de restaurante, quero ver um resumo diário de vendas, para acompanhar o desempenho do dia.
Dado que o dia comercial termina, quando o restaurante abre o painel de vendas, então vê o total de pedidos e o faturamento do dia.
Dado que o restaurante seleciona um período diferente, quando aplica o filtro, então o resumo é recalculado para aquele período.
--> RNF 1: Cada alteração no resultado diário deve ser computada em até 1 minuto após o fim da transação (Confiabilidade)
--> RNF 2: O sistema deve armazenar os ultimos seis meses do historico de desempenho (Adequação funcional)
--> RNF 3: O resultado por horário ficará disponível por no maximo 24 horas após o fim do expediente (Adequação funcional)