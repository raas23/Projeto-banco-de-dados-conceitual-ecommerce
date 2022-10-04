# Projeto-banco-de-dados-conceitual-ecommerce
Entrega do projeto referente ao Desafio - Refinando um banco de dados conceitual E-Commerce.
Entrega do desafio de projeto de Banco de Dados conceitual - E-Commerce.

Neste sentido, foi criado um diagrama no modelo entidade relacionamento, no qual apresento,
através do contexto da minha loja online Praiana Store:

Entidades fortes:
Produto
Fornecedor
Estoque
Cliente 
Pedido

Entidades fracas:
Pagamento
Entrega

Visto que para ativar o pagamento e a entrega, é necessário que tenha sido realizado um 
pedido por parte do cliente. Assim, trata-se de um relacionamento fraco entre o pedido,
o pagamento e a entrega, visto estes últimos estarem como uma espécie de atributos deri-
vados da entidade Pedido.

Obs: Dentro de fornecedor, há o atributo CNPJ pois os produtos são comprados em lojas
na cidade de Fortaleza, no Ceará.
Contudo, como as vendas são realizadas em Aveiro-Portugal, dentro de Cliente, há a identi-
ficação como NIF (equivalente ao CPF) ou NIPC (equivalente ao CNPJ).
Assim como também no Pagamento, há as opções dinheiro, "MBWAY" e transferência bancária, 
pois são as formas de pagamento comumente utilizadas em Portugal.
