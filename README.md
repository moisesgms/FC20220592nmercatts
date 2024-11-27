### Descrição Geral do Sistema

Este sistema foi desenvolvido para gerenciar as operações de uma loja, controlando o estoque, registrando produtos, realizando vendas e administrando o caixa. Ele simula todo o processo de vendas, desde a entrada de produtos até a finalização das transações, facilitando a consulta, adição e remoção de itens, além de monitorar produtos com vencimento próximo ou estoque baixo.

### Funcionalidades do Sistema

**Gerenciamento de Caixa:** O sistema permite abrir o caixa com um saldo inicial e fechá-lo, mostrando o saldo final após as vendas realizadas.

**Administração de Produtos:** O sistema permite registrar novos produtos no estoque, incluindo detalhes como código, nome, preço, categoria, validade e garantia. Também é possível consultar produtos por código, remover produtos do estoque, verificar os produtos com vencimento próximo e identificar aqueles com estoque baixo (menos de 5 unidades).

**Realização de Vendas:** O sistema registra as vendas, calcula o total da transação e atualiza tanto o estoque quanto o caixa.

**Operação do Sistema:** O usuário pode acessar o menu principal, que oferece opções para gerenciar o caixa e a administração de produtos.

### Melhorias no Código

O código foi reestruturado para separar claramente as funcionalidades de gerenciamento de caixa e administração de produtos, promovendo maior organização. Foi introduzida a validação de processos, como verificar se o caixa está aberto antes de realizar vendas e se o estoque é suficiente. A classe de produtos agora inclui mais detalhes, como validade e garantia, oferecendo maior controle sobre itens com características específicas. Além disso, foram adicionadas funcionalidades para verificar produtos com vencimento próximo e estoque baixo, facilitando o gerenciamento do inventário. Os menus também foram ajustados para melhorar a navegação e a experiência do usuário.

### Conclusão

O sistema oferece uma solução prática e eficiente para o gerenciamento de lojas, com funcionalidades que garantem o controle de estoque, vendas e caixa. As melhorias no código aumentaram sua flexibilidade e usabilidade, tornando-o ideal para pequenos e médios comerciantes.
