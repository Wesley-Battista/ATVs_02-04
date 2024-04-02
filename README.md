# ATVs_02-04

##### EXERCÍCIO 03

## Code

UPDATE Alunos

SET Favoritos = 'SIM'

WHERE PessoaID IN (1, 5, 8, 12, 25, 26, 29, 30, 16, 28);

UPDATE Alunos

SET Favoritos = 'NÃO'

WHERE PessoaID IN (2, 3, 4, 6, 7, 9, 10, 11, 13, 14, 15, 17, 18, 19, 20, 21, 22, 23, 24, 27, 31, 32, 33, 34);

#### EXERCÍCIO 04

## Code

SELECT * FROM `Alunos` WHERE  Favoritos = 'SIM'
