Descrição Geral do Sistema: 
Este sistema foi projetado para gerenciar as operações de uma loja ou mercado, permitindo o controle de estoque, registro de produtos, vendas e administração do caixa. Ele simula o processo completo de uma venda, desde a entrada de novos produtos no estoque até a finalização das transações de venda. O sistema foi estruturado de forma a facilitar a consulta, adição e remoção de produtos, bem como a verificação de produtos com vencimento próximo ou com estoque baixo.
Funcionalidades do Sistema
Gerenciamento do Caixa:
Abrir Caixa: Permite iniciar o caixa da loja, definindo um saldo inicial.
Fechar Caixa: Encerramento do caixa, mostrando o saldo final após as vendas realizadas.
Administração de Produtos:
Registrar Novo Produto: Adição de novos produtos ao estoque, incluindo detalhes como código, nome, preço, quantidade, categoria, data de validade e garantia.
Consultar Produto: Permite buscar um produto pelo código, exibindo suas informações completas.
Remover Produto: Exclui produtos do estoque com base no código informado.
Verificar Produtos com Vencimento Imediato: Exibe os produtos que estão próximos da data de vencimento, útil para produtos perecíveis.
Verificar Produtos com Estoque Crítico: Identifica produtos cujo estoque está abaixo de um nível crítico (menos de 5 unidades).
Realização de Vendas:
Permite registrar a venda de produtos, calculando o total da venda e atualizando o estoque e o saldo do caixa.
Operação do Sistema:
Menu Principal: Permite ao usuário acessar a administração do caixa e os menus de produtos.

Menu de Administração de Produtos: Oferece opções para gerenciar os produtos no estoque e realizar vendas.
Melhorias no Código
Modularização:
O código foi reestruturado para ter uma separação clara entre as funcionalidades de "Mercado" (gerenciamento de caixa e estoque) e "Produto" (detalhes dos itens), promovendo maior clareza e organização.
Interatividade e Validação:
A introdução de validações básicas (como verificar se o caixa está aberto antes de realizar uma venda e garantir que o estoque seja suficiente para a venda) melhorou a robustez do sistema.
O sistema foi projetado para permitir que o usuário interaja com o sistema de forma sequencial e lógica, melhorando a experiência do usuário.
Detalhamento de Produtos:
A classe Produto agora possui atributos adicionais, como a data de validade e período de garantia, o que aumenta a flexibilidade e o controle sobre o estoque, especialmente em mercados com diferentes categorias de produtos.
Exibição e Relatórios:
  A inclusão de funcionalidades como "verificar produtos com vencimento     próximo" e "estoque crítico" facilita o gerenciamento proativo do inventário, ajudando a evitar perdas e problemas de abastecimento.
Menu Personalizado e Estrutura de Navegação:
Os menus foram ajustados para melhorar a navegação do sistema, facilitando o acesso às funcionalidades e tornando o código mais intuitivo.



Conclusão
Este sistema de gerenciamento de loja é uma solução eficiente para o controle de estoque, vendas e administração do caixa. 
Ele oferece uma interface simples e funcional, permitindo que o usuário gerencie produtos, realize vendas e acompanhe o desempenho do caixa de maneira organizada. 
As melhorias implementadas no código, como a validação de processos, a personalização de menus e a modularização das funcionalidades, proporcionam maior flexibilidade e eficiência no uso diário. 
Esse sistema é ideal para pequenos e médios comerciantes que buscam uma maneira prática e eficiente de administrar suas operações comerciais.
