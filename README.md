# AV2 - Programação Estruturada

## APS1
Faça um programa, utilizando o Dev-C++, para armazenar os dados de um aluno(a), contendo os seguintes dados:

- matricula: inteiro

- nome: caractere

- sexo: caractere

- idade: inteiro

- av1, av2, av3 e media: real          (UTILIZE UMA MATRIZ PARA ARMAZENAR AS NOTAS)

 

O usuário poderá armazenar no máximo 50 alunos. O programa terá a opção de adicionar, exibir ou salvar/carregar os dados. O programa deverá ter as seguintes condições:

### Adicionar:

- Efetuar uma pesquisa para saber se o aluno(a) existe ou não no vetor através da matrícula do mesmo

  - Se existir, informar que o aluno(a) já se encontra presente e não adicione

  - Caso não exista, verifique se o sistema está ou não lotado antes de inserir

- Ao armazenar as notas utilize o mesmo critério de avaliação da UniCarioca para calcular a média, está não deve ser informada pelo aluno (Soma das 2 maiores notas divididos pela quantidade)

### Exibir:

- O usuário poderá exibir os alunos(as) com os seguintes critérios de média:

  - Alunos reprovados com média inferior a 5

  - Alunos reprovados com média inferior a 7

  - Alunos reprovados

  - Alunos aprovados com média superior ou igual a 7

  - Alunos aprovados com média superior ou igual a 9

  - Alunos aprovados

  - Todos os alunos

### Salvar/Carregar:

- O usuário irá escolher entre salvar ou carregar um arquivo externo

  - Colocar um campo para o usuário informar o nome do arquivo externo, tanto na opção de salvar quanto carregar

  - Ao selecionar a opção de carregar dados, o sistema deve ler todas as informações do arquivo externo e adicionar no programa

## APS2
Faça um programa, utilizando o Dev-C++, para armazenar os dados de um funcionário(a), contendo os seguintes dados:

- CPF: inteiro

- nome: caractere

- sexo: caractere

- idade: inteiro

- horas trabalhadas: real

- valor hora trabalhada: real

- salário líquido: real (DEVE SER CALCULADO ATRAVÉS DA QUANTIDADE DE HORAS, VALOR DA MESMA E TABELA DO INSS)

 

O usuário poderá armazenar no máximo 50 funcionários. O programa terá a opção de adicionar, buscar, exibir ou salvar/carregar os dados. O programa deverá ter as seguintes condições:

### Adicionar:

- Efetuar uma pesquisa para saber se o funcionário(a) existe ou não no vetor através do CPF do mesmo

  - Se existir, informar que o funcionário(a) já se encontra presente e não adicione

  - Caso não exista, verifique se o sistema está ou não lotado antes de inserir

- Para calcular o salário líquido utilize os valores informados na quantidade de horas trabalhadas, o valor da hora e a tabela de desconto de INSS que se encontra abaixo:

 

### SALÁRIO DE CONTRIBUIÇÃO (R$)                     ALÍQUOTA INSS

até 1.751,81                                                                                         8%

de 1.751,82 até 2.919,72                                                                      9%

de 2.919,73 até 5.839,45                                                                     11%

 

### Pesquisar:

- A pesquisa será realizada utilizando o CPF do funcionário(a)

  - Caso não exista, informe que o funcionário não está matriculado e pergunte se o usuário deseja adicionar no sistema.

### Exibir:

- O usuário poderá exibir os funcionários(as) com os seguintes critérios de salário:

  - Funcionários com salário inferior a R$ 500

  - Funcionários com salário inferior a R$ 1000

  - Funcionários com salário superior a R$ 4000

  - Funcionários com salário superior ou igual a R$ 5000

  - Funcionários com salário superior ou igual a R$ 7000

  - Funcionários com salário superior ou igual a R$ 10000

  - Todos os funcionários

### Salvar/Carregar:

- O usuário irá escolher entre salvar ou carregar um arquivo externo

  - Colocar um campo para o usuário informar o nome do arquivo externo, tanto na opção de salvar quanto carregar

  - Ao selecionar a opção de carregar dados, o sistema deve ler todas as informações do arquivo externo e adicionar no programa

 
