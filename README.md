Sistema de loja simples desenvolvido em Java, com interface de console, que permite executar operações básicas de gerenciamento de produtos e vendas.

Funcionalidades:

- Cadastro de produtos (nome, preço, quantidade)
- Consulta/lista de produtos disponíveis
- Realizar venda / subtrair estoque
- (Opcional: adicionar ao carrinho, calcular total da compra)
- (Opcional: remoção ou edição do produto)

Estrutura do projeto:
- Menu.java - Controle o fluxo principal e as opções exibidas ao usuário
- Produto.java - Representa os produtos com nome, preço e quantidade
- Loja.java - Gerencia o estoque e as operações de venda
- Carrinho.java - Controle os itens comprados pelo cliente
- Configuracoes.java - Mostra as opções de configuração como suporte, perfil, sobre a apresa
- Main.java - Ponto de entrada do sistema

Tecnologias usadas:
- JDK 17
- `Scanner` - para entrada e saida de dados
