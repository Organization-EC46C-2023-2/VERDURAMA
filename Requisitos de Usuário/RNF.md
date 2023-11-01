# 1. Requisitos Não Funcionais

<p align="justify">A <i>Tabela 2</i> a seguir contém os <b>Requisitos Não Funcionais (RNF)</b> elicitados utizando a técnica de Brainstorm.</p>

| ID   |  Requisito NF | Categoria/Tipo | Prioridade | Requisitos Relacionados |
| :---:| :-----------: |:-------------: | :--------: | :---------------------: |
| RNF01 |  O usuário poderá criar sua carteira digital de pagamento dentro para finalizar as compras. | Produto/Usabilidade |Alta  |     |
| RNF02 |  O usuário deve ser capaz de realizar o pagamento via saldo na carteira (com os cupons) ou via pix, cartão de crédito, cartão de débito e dinheiro. | Produto/Usabilidade |Alta | RNF01 |
| RNF03 |  O usuário podera adicionar saldo via deposito PIX, carteira virtual (Apple Pay, Samsung Pay, Google Pay etc.), ou por cartões presentes (Gift Cards). | Produto/Usabilidade |Alta | RNF01 |
| RNF04 |  Os itens adicionados as sacola/carrinho deverão ser apenas de um produtor/vendedor. | Produto |Alta  |     |
| RNF05 |  A sacola não deve aceitar adicionar produtos de outros vendedores caso na estejam vazios. | Produto/Usabilidade |Alta  |  RNF04 |
| RNF06 |  A sacola deve ter um tamanho mínimo e máximo de itens adicionados. | Produto |Média  |     |
| RNF07 |  O cadastro do usuário será feito por third-party authentication service, via APIs de integração do Google e do Facebook. | Produto/Sistema |Alta  |     |
| RNF08 |  O cadastro do produtor será feito através de um formulário CRUD no nosso banco de dados. | Produto/Sistema |Alta  |     |
| RNF09 |Evitar a criação de vendedores fantasmas/bots.| Sistema |Alta  | RNF08    |
| RNF10 |  Deverá existir uma validação de cadastro de vendedores/produtores.|Sistema|Alta  |   RNF08  |
| RNF11 |As transações deverão ser realizadas por uma empresa terceirizada contratada, como: PagSeguro.|Sistema |Alta  |   RNF01/RNF02/RNF03  |
| RNF12 |As APIs de consulta e listagem deverão ser paginadas para melhor filstros de pesquisa da plataforma.|Sistema/Produto/Usabilidade | Média  |   |

<p style="text-align: center">Tabela 2: Requisitos Não Funcionais</p>

# 2. Referências

<a href="../README.md">VOLTAR INÍCIO</a>
