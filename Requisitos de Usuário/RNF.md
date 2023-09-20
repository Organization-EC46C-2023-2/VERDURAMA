# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm.</p>

| ID   |  Requisito NF | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :---:| :-----------: |:-------------: | :--------: | :---------------------: |
| RF01 |  O usuário deverá criar sua carteira digital de pagamento dentro para finalizar as compras. | Produto/Usabilidade |Alta  |     |
| RF02 |  O usuário deve ser capaz de realizar o pagamento via saldo na carteira ou via pix. | Produto/Usabilidade |Alta | RF01 |
| RF03 |  O usuário podera adicionar saldo via deposito PIX, carteira virtual (Apple Pay, Samsung Pay, Google Pay etc.), ou por cartões presentes (Gift Cards). | Produto/Usabilidade |Alta | RF01 |
| RF04 |  Os itens adicionados as sacola/carrinho deverão ser apenas de um produtor/vendedor. | Produto |Alta  |     |
| RF05 |  A sacola não deve aceitar adicionar produtos de outros vendedores caso na estejam vazios. | Produto/Usabilidade |Alta  |  RF04 |
| RF06 |  A sacola deve ter um tamanho mínimo e máximo de itens adicionados. | Produto |Média  |     |
| RF07 |Evitar a criação de vendedores fantasmas/bots.| Sistema |Alta  |     |
| RF08 |  Deverá existir uma validação de cadastro de vendedores/produtores.|Sistema|Alta  |   RF07  |
| RF09 |As transações deverão ser realizadas por uma empresa terceirizada contratada, como: PagSeguro.|Sistema |Alta  |   RF01/RF02/RF03  |
| RF10 |As APIs de consulta e listagem deverão ser paginadas para melhor filstros de pesquisa da plataforma.|Sistema/Produto/Usabilidade | Média  |   |

<p style="text-align: center">Tabela 2: Requisitos Não Funcionais</p>

# 2. Referências

<a href="../README.md">VOLTAR INÍCIO</a>