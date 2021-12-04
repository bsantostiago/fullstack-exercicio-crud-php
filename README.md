# Orientações para o exercício

## 1. SQL
- Crie um banco de dados chamado **fullstack_escola**
- Crie no phpMyAdmin uma tabela chamada **alunos** com os seguintes campos:

    - id (inteiro pequeno, não nulo, com chave primária e auto incrementado)
    - nome (string com tamanho 30) não nulo
    - primeira (decimal tamanho total 3, 1 dígito depois da vírgula) não nulo
    - segunda (decimal tamanho total 3, 1 dígito depois da vírgula) não nulo
    - media (decimal tamanho total 3, 1 dígito depois da vírgula) não nulo
    - situacao (string com tamanho 15) não nulo
  
---

## 2. PHP e SQL

*Obs.: você pode usar a abordagem que preferir (estruturada ou orientada a objetos)*

- Programe os scripts PHP necessários para acessar o Banco de Dados usando PDO.
- Programe os scripts PHP/SQL necessários para realizar as operações CRUD para o aluno


---


## 3. PHP

*Obs.: você pode usar a abordagem que preferir (estruturada ou orientada a objetos)*

- Na página **inserir.php**, programe os recursos necessários para fazer INSERT no banco

**Obs.:** os campos de média e situação devem ser preenchidos com o resultado de operações.
Média: é a soma da primeira e da segunda nota e a divisão delas por 2.
Situação: se média maior ou igual a 7, será "aprovado". Senão, "reprovado".

- Na página **visualizar.php**, programe os recursos necessários para fazer SELECT no banco

- Na página **atualizar.php**, programe os recursos necessários para fazer SELECT e UPDATE no banco

**Obs.:** somente os campos nome, primeira e segunda poderão ser preenchidos manualmente.
Média será atualizada de acordo com os valores dos campos das notas.
Situação será atualizada de acordo com o valor da média.

- Na página **excluir.php**, programe os recursos necessários para fazer DELETE no banco

---

## DESAFIO 🔥
- Em **visualizar.php**, mostre em azul quando aprovado, e em vermelho quando reprovado.

## DESAFIOS TURBINADOS 🔥💥💯

- Em **visualizar.php**, usando JavaScript, programe recursos que possibilitem que ao clicar em um link de exclusão, seja perguntado ao usuário se ele realmente deseja apagar aquele registro. Apenas se ele confirmar, a exclusão será feita. 

- Em **atualizar.php**, usando JavaScript, programe recursos que permitam atualizar em tempo real os campos de média e situação.











