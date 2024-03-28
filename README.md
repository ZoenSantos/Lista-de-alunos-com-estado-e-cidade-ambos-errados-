# Lista-de-alunos-com-estado-e-cidade-ambos-errados-

Côdigo utilizado por mim para definir estado e cidade
UPDATE alunos
SET cidade = 'Chapecó'
WHERE id IN (19, 20, 21, 22, 23, 24);

UPDATE alunos
SET estado = 'SC'
WHERE id IN (19, 20, 21, 22, 23, 24);
