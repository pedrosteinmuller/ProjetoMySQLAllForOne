# Projeto All for One 👥

A partir do Banco de Dados `NorthWind` contendo informações de uma loja. Foi desenvolvido dasafios para selecionar as informações necessárias.

* Projeto desenvolvido com MySQL e Docker

### Instruções

- Para rodar o repositório localmente, realize o clone do projeto e utilize os comandos a seguir para inicializar o Docker:

```
docker-compose up -d
docker attach all_for_one
npm install // para instalar as dependências
docker-compose down // para parar completamente a aplicação
```

### Desafios

| Desafio | Descrição |
|---|---|
| `1` | Query que exiba apenas os nomes dos produtos |
| `2` | Query que exibe todos as informações dos produtos |
| `3` | Query que exiba a primary key da tabela de produtos |
| `4` | Query que mostra a quantidade total de informações presentes na coluna `product_name` |
| `5` | Query que exibe os dados da tabela entre o quarto registro, até o décimo terceiro |
| `6` | Query que exiba as `product_name` e `id` da tabela `products` em ordem alfabética dos nomes |
| `7` | Query que mostra os 5 últimos registros da tabela `products` |
| `8` | Query que retorna 3 colunas, contendo respectivamente os nomes 'A', 'Trybe' e 'eh', e com valores a soma de `5 + 6`, a string `de`, a soma de `2 + 8` |
| `9` | Query que mostra todos os valores não nulos da coluna `notes` da tabela `purchase_orders` |
| `10` | Query que exiba todos os dados da tabela `purchase_orders`, ordenado de forma decrescente de `created_by`, sendo o mesmo maior ou igual a `3` |
| `11` | Query que mostre a coluna `notes` da tabela `purchase_orders`, onde `Purchase generated based on Order` tenha o final contendo valores entre 30 a 39 |
| `12` | Query que mostra `submitted_date` da tabela `purchase_orders` no dia 26 de abril de 2006 |
| `13` | Query que exibe `supplier_id` equivalente a 1 ou 3, referente a tabela `purchase_orders` |
| `14` | Query que mostra os registro onde `supplier_id` esteja entre 1 a 3 |
| `15` | Query que exibe apenas as horas de todos os registros da coluna `submitted_date` da tabela `purchase_orders` |
| `16` | Query que mostra a coluna `submitted_date` da tabela `purchase_orders` que estão entre `2006-01-26 e `2006-03-31` |
| `17` | Query que mostra os registros das colunas `id` e `supplier_id` da tabela `purchase_orders` em que os `supplier_id` seja equivalente a `1`, `3`, `5` ou `7` |
| `18` | Query que exiba todos os registros da tabela `purchase_orders`, onde `supplier_id` igual a `3` e `status_id` igual a `2` |
| `19` | Query que mostra a quantidade de pedidos realizados na `orders` pelo `employee_id` igual a `5` ou `6`, e que foram enviados através da coluna `shipper_id` igual a `2` |
| `20` | Query para adicionar mais um registro a tabela `order_details` |
| `21` | Query para adicionar mais de um registro a tabela `order_details` |
| `22` | Query que atualiza os dados da coluna `discount` da tabela `order_details` para `15` |
| `23` | Query que atualiza os dados da coluna `discount` da tabela `order_details` para `30`, quando o `unit_price` é menor que 10.0000 |
| `24` | Query que atualiza os dados da coluna `discount` da tabela `order_details` para `45`, quando o `unit_price` é maior que 10.0000 e o `id` esteja entre `30` e `40` |
| `25` | Query que deleta todos os dados da tabela `order_details`, quando o `unit_price` é menor que 10.0000 |
| `26` | Query que deleta todos os dados da tabela `order_details`, quando o `unit_price` é maior que 10.0000 |
| `27` | Query que deleta todos os dados da tabela `order_details` |
