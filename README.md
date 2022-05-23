# Métodos Formais - T1

Disciplina: Métodos Formais

Prof. Júlio Machado

Alunos: Marco Goedert e Matheu Góes

## Trabalho 1

A nota do trabalho consiste no trabalho aqui especificado, cujo objetivo é construir especificações e verificações formais na linguagem Dafny para algoritmos sobre estruturas de dados. O trabalho será realizado em grupos de até 5alunos. O trabalho deve ser entregue via Moodle até a data de 25/05/2022.

O grupo deve entregar um arquivo (.dfy) contendo todo o código-fonte em Dafny.

### Enunciado:

Estamos interessados em implementar o tipo abstrato de dados Pilha (sem limite de tamanho) através da implementação concreta utilizando arrays.

Para tal será necessário criar uma classe Pilha em Dafny e representar os atributos e método de acordo com as seguintes instruções. Para fins de simplificação, considere a declaração de pilhas contendonúmeros inteiros e não se preocupe em implementar uma coleção genérica.

Representação abstrata (via ghost):

- Representar a coleção de elementos da pilha.

Invariante de classe (via predicate):

- Utilizar um predicado adequado para a invariante da representação abstrata associada à coleção do tipo pilha.

Autocontratos:

- Utilizar o suporte de autocontratos para simplificar a especificação em Dafny.

Operações:

- Construtor deve instanciar uma pilha vazia.
- Adicionar um novo elemento no topo da pilha.
- Remover um elemento do topo da pilha, caso ela não esteja vazia.
- Ler o valor do topo da pilha, sem removê-lo.
- Verificar se a pilha está vazia ou não, retornando verdadeiro ou falso.
- Informar o número de elementos armazenados na pilha.
- Inverter a ordem dos elementos da pilha.

Todas as pré-condições, pós-condições, invariantes e variantes devem ser corretamente especificadas. Faz parte da avaliação do trabalho o completo entendimento de quais asserções devem fazer parte da especificação das operações solicitadas.
Por fim, construa um pequeno método “Main” demonstrando o uso das operações implementadas e verificando asserções (no estilo de teste unitário) para um número de casos que garantam uma cobertura razoável.

Observações:

- **LEMBRETE**: cópia de trabalhos é plágio, sujeito a processo disciplinar. Os trabalhos envolvidos em fraudes receberão nota 0,0 (zero).
- Dúvidas devem ser esclarecidas com o professor.
- Não serão aceitos trabalhos entregues além da data limite.
- Não serão aceitos trabalho entregues via correio eletrônico
