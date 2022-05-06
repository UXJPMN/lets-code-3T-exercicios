# Exercício de Controle de Estoque
O intuito do exercício a seguir é treinar e fixar os conceitos de classes, métodos e acesso.

## O Exercício
Você deve implementar um sistema básico de fluxo de estoque no terminal usando Java que vai seguir algumas regras. Este sistema vai possibilitar que o usuário realize todas as operações básicas relativas a este serviço.

### Regras de Implementação

 - Um estoque deve ter um nome, uma lista de produtos e um identificador único.
 - A única variável do estoque que o usuário conseguirá acessar e modificar livremente será o nome.
 - O identificador único é criado no momento da instância do estoque, ele não é definido pelo usuário e só pode ser lido.
 - O usuário também não deve conseguir acessar diretamente a lista de produtos, somente através de métodos.
 - Um produto deve ter um nome, uma sessão, um tipo, uma quantidade em estoque, uma marca e um identificador único.
 - O identificador único do produto também deve ser criado em conjunto com o produto e não deve ser definido pelo usuário, após ele somente poderá ser lido.
 - O usuário deve conseguir fazer o fluxo de **CRUD** *(create, read, update, delete)* de um produto pelo estoque.
 - Um usuário deve conseguir listar os produtos de um estoque.
 - Um usuário deve conseguir ler os dados de um produto do estoque.
 - Um usuário deve conseguir editar os dados de um produto do estoque (com exceção de seu identificador único).
 - Um usuário deve conseguir deletar um produto específico do estoque.
 - Ao tentar inserir um produto no estoque se houver outro com mesmo nome e de mesma marca ele deve modificar o produto original no estoque, incrementando a quantidade de produtos que seria inserida em vez de criar um novo.
 - O usuário não deve ter acesso a nenhum método que não execute uma das funcionalidades listadas.

## Dicas finais

 - Apesar de o usuário não poder ter acesso, utilize métodos de apoio dentro das classes para facilitar seu trabalho, limpeza e manutenção do seu código!
 - Crie quantas classes, variáveis e métodos achar necessários para executar  exercício.
 - Tente ser declarativo em relação ao nome dos métodos, classes e variáveis.
 - Não guarde as dúvidas para você, compartilhe com os professores e a turma, as vezes mais colegas estão com o mesmo problema, ou é uma questão que não foi pensada inicialmente pelos professores.
 - Aproveite o exercício para fixar os conceitos ensinados em aula.