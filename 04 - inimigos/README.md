# Exercício de Inimigos em um Jogo
O intuito do exercício a seguir é treinar e fixar os conceito de polimorfismo.

## O Exercício
Você deve implementar um sistema básico que representa um jogo com 4 tipos de inimigo: genérico, vampiro, cobra e gigante. Todos eles devem ter uma função de atacar, apanhar e interagir. O método de apanhar deve receber um tipo de ataque e seu dano como parâmetro.

### Regras de Implementação

#### Genérico
**Ataque:** deve imprimir *"causou 10 de dano"*
**Apanhar:** deve imprimir *"recebeu [dano recebido] de dano"*
**Interagir:** deve imprimir *"Por que eu responderia meu inimigo???"*
<hr />

#### Vampiro
**Ataque:** deve imprimir *"causou 20 de dano"* e depois *"seu personagem está sangrando"*
**Apanhar:** deve imprimir *"recebeu [dano recebido] de dano"*, se o tipo de dano recebido for *"perfurante"* o dano recebido é dobrado.
**Interagir:** deve imprimir *"O que é um homem?"*
<hr />

#### Cobra
**Ataque:** deve imprimir *"causou 10 de dano"* e depois *"seu personagem está envenenado"*
**Apanhar:** deve imprimir *"recebeu [dano recebido] de dano"*, se o tipo de dano recebido for *"pancada"* o dano recebido é dobrado.
**Interagir:** deve imprimir *"Se você acender a chama a maldição acaba."*
<hr />

#### Gigante
**Ataque:** deve imprimir *"causou 25 de dano"* e depois *"seu personagem está atordoado"*
**Apanhar:** deve imprimir *"recebeu [dano recebido] de dano"*, se o tipo de dano recebido for *"fogo"* o dano recebido é dobrado.
**Interagir:** deve imprimir *"Me desculpe"*


## Dicas finais

 - Apesar de ser um exercício de polimorfismo tente utilizar os demais conceitos aprendidos no exercício.
 - Crie quantas classes, variáveis e métodos achar necessários para executar  exercício.
 - Tente ser declarativo em relação ao nome dos métodos, classes e variáveis.
 - Não guarde as dúvidas para você, compartilhe com os professores e a turma, as vezes mais colegas estão com o mesmo problema, ou é uma questão que não foi pensada inicialmente pelos professores.
 - Aproveite o exercício para fixar os conceitos ensinados em aula.