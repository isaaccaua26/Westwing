# Teste MySQL para Desenvolvedor

## Objetivo:
Fazer uma query que retorne o relatório abaixo:
- Todos os clientes, cor de suas casas, seus bairros, seus carros

SELECT cli.nome, cli.sobrenome, cs.cor, br.nome, cr.id_carro, cr.modelo 
FROM cliente  cli,
     casa     cs,
     bairro   br,
     carro   cr
WHERE cli.id_cliente = cs.fk_cliente
  AND cli.id_cliente = br.fk_cliente
  AND cli.id_cliente = cr.fk_cliente



## Requisitos:
- Utilizar o dump desse projeto;
