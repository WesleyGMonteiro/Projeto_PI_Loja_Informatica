# Projetinho

Projeto realizado com Interfaces em Java, programado com base nos conceitos de Orientação a Objeto, utilizando classes, métodos, exceptions, e banco de dados.

O projeto se resume em 2 Cruds completos envolvendo Java, Interface Gráfica(criada com a IDE Netbeans) e JDBC, no qual, o source com arquivos views(telas) conversavam com os arquivos models(classes de objetos) que conversavam com a classe DAO(Conexão com o banco de dados). Assim é formado nosso CRUD.

O primeiro é o CRUD de cadastro de clientes, no qual o usuário digita os dados, que são válidados com um método criado na classe DAO que recebe os CPF's cadastrados e confrontam com o CPF digitado, assim, se o CPF já for cadastrado surge uma JOptionPane informando que aquele CPF já possui cadastro, nesse CRUD também são necessários que todos os campos obrigatórios(marcados com * ) estejam preenchidos, caso não, aparecerá um aviso pedindo que preencha todos os campos obigatórios, foi inserido também algumas validações como, apenas letras no nome e sobrenome ou apenas números no campo número da casa.

O segundo CRUD é referente aos Produtos, foram reaproveitados muitos métodos, principalmente de validação nesse CRUD, mas também incluí métodos como, dar baixa no estoque, ou acrescentar no estoque, métodos esses cruciais para a tela de vendas.

A tela digamos principal do projeto(Tela de Vendas), foi criada reutilizando alguns métodos de validações já existentes, mas incluindo a validação de não vender produto sem estoque, não digitar quantidade de produto negativa na venda, não vender para cliente sem cadastro, ao adicionar os produtos no carrinho, temos a tela de pagamento, nela é trazido o total da venda com os campos de formas de pagamento, com uma validação que não deixa ser finalizada a compra caso o pagamento seja menor que o valor da venda e que calcula o troco.
