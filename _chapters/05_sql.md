# Capítulo 5 - SQL Básico

O SQL é a linguagem universal dos dados. Permite filtrar, combinar e calcular informações.

## O que aprender
- `SELECT`, `FROM`, `WHERE`, `GROUP BY`, `JOIN`.
- `SUM`, `AVG`, `COUNT`.

**Exemplo:**
```sql
SELECT nome, SUM(bananas) AS total
FROM minions
WHERE mes = 'Março'
GROUP BY nome;
```