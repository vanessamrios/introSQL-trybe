# All For One: Introdução SQL.

- Este exercício foi realizado durante o modulo de Backend do curso de desenvolvimento de software da Trybe e nele foi praticado conceitos introdutórios de SQL usando o banco de dados `Northwind`. Nele foi desenvolvido o entendimento de bancos de dados e tabelas, como a linguagem de consulta estruturada (SQL) é usada, como usar o MySQL Workbench, o que é uma query SQL e quais são seus tipos de comando.

- Neste projeto foram praticadas habilidades de:

 * Gerar valores com `SELECT`
 * Selecionar colunas individualmente com `SELECT`
 * Renomear e gerar colunas em uma consulta com `AS`
 * Concatenar colunas e valores com `CONCAT`
 * Remover dados duplicados em uma consulta com `DISTINCT`
 * Contar a quantidade de resultados em uma consulta com `COUNT`
 * Limitar a quantidade de resultados em uma consulta com `LIMIT`
 * Pular resultados em uma consulta com `OFFSET`
 * Ordernar os resultados de uma consulta com `ORDER BY`
 * Filtrar resultados de consultas com o `WHERE`
 * Utilizar operadores booleanos e relacionais em consultas
 * Criar consultas mais dinâmicas e maleáveis com `LIKE`
 * Fazer consultas que englobam uma faixa de resultados com `IN` e `BETWEEN`
 * Encontrar e separar resultados que incluem datas.
 * Inserir dados em tabelas com `INSERT`
 * Atualizar dados em tabelas com `UPDATE`
 * Apagar dados em tabelas com `DELETE`
 
- A lista de desafios segue abaixo e os respectivos comando necessários pra executá-los está contido em arquivos separados.

- Desafios Iniciais

- [x] 1. Exiba apenas os nomes dos produtos na tabela `products`.
- [x] 2. Exiba os dados de todas as colunas da tabela `products`.
- [x] 3. Escreva uma query que exiba os valores da coluna que representa a primary key da tabela `products`.
- [x] 4. Conte quantos registros existem na coluna `product_name` da tabela `products`.
- [x] 5. Monte uma query que exiba os dados da tabela `products` a partir do quarto registro até o décimo terceiro.
- [x] 6. Exiba os dados das colunas `product_name` e `id` da tabela `products` de maneira que os resultados estejam em ordem alfabética dos nomes.
- [x] 7. Mostre apenas os ids dos 5 últimos registros da tabela `products` (a ordernação deve ser baseada na coluna `id`).
- [x] 8. Faça uma consulta que retorne três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'.

- Desafios sobre filtragem de dados

- [x] 9. Mostre todos os valores de `notes` da tabela `purchase_orders` que não são nulos.
- [x] 10. Mostre todos os dados da tabela `purchase_orders` em ordem decrescente, ordenados por `created_by` em que o `created_by` é maior ou igual a 3.
- [x] 11. Exiba os dados da coluna `notes` da tabela `purchase_orders` em que seu valor de `Purchase generated based on Order` é maior ou igual a 30 e menor ou igual a 39.
- [x] 12.  Mostre as `submitted_date` de `purchase_orders` em que a `submitted_date` é do dia 26 de abril de 2006.
- [x] 13. Mostre o `supplier_id` das `purchase_orders` em que o `supplier_id` seja 1 ou 3.
- [x] 14. Mostre os resultados da coluna `supplier_id` da tabela `purchase_orders` em que o `supplier_id` seja maior ou igual a 1 e menor ou igual 3.
- [x] 15. Mostre somente as horas (sem os minutos e os segundos) da coluna `submitted_date` de todos registros da tabela `purchase_orders`.
- [x] 16. Exiba a `submitted_date` das `purchase_orders` que estão entre `2006-01-26 00:00:00` e `2006-03-31 23:59:59`.
- [x] 17. Mostre os registros das colunas `id` e `supplier_id` das `purchase_orders` em que os `supplier_id` sejam tanto 1, ou 3, ou 5, ou 7.
- [x] 18. Mostre todos os registros de `purchase_orders` que tem o `supplier_id` igual a 3 e `status_id` igual a 2.
- [x] 19. Mostre a quantidade de pedidos que foram feitos na tabela `orders` pelo `employee_id` igual a 5 ou 6, e que foram enviados através do método(coluna) `shipper_id` igual a 2.

- Desafios de manipulação de tabelas

- [x] 20. Adicione à tabela `order_details` um registro com `order_id`: 69, `product_id`: 80, `quantity`: 15.0000, `unit_price`: 15.0000, `discount`: 0, `status_id`: 2, `date_allocated`: NULL, `purchase_order_id`: NULL e `inventory_id`: 129.
- [x] 21. Adicione com um único `INSERT`, duas linhas à tabela `order_details` com os mesmos dados do requisito 20.
- [x] 22. Atualize os dados de `discount` do `order_details` para 15. (Não é necessário utilizar o SAFE UPDATE em sua query).
- [x] 23.  Atualize os dados da coluna `discount` da tabela `order_details` para 30, onde o valor na coluna `unit_price` seja menor que 10.0000.
- [x] 24. Atualize os dados da coluna `discount` da tabela `order_details` para 45, onde o valor na coluna `unit_price` seja maior que 10.0000 e o id seja um número entre 30 e 40.
- [x] 25. Delete todos os dados em que a `unit_price` da tabela `order_details` seja menor que 10.0000.
- [x] 26. Delete todos os dados em que a `unit_price` da tabela `order_details` seja maior que 10.0000.
- [x] 27. Delete todos os dados da tabela `order_details`.
