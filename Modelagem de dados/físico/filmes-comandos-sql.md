# Comandos sql - Referência

# Modelagem física

## Criação da tabela

```sql
CREATE DATABASE filmes CHARACTER SET utf8mb4;
```
<!-- __________________________________________________ -->

 # Criar tabela fabricante

```sql
CREATE TABLE fabricantes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL
);
```


<!-- __________________________________________________ -->

# Criar tabela produtos

```sql
CREATE TABLE filmes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR(45) NOT NULL,
    lancamento YEAR(4) NOT NULL,
    genero_id INT NOT NULL 
);

```
<!-- __________________________________________________ -->

# Adicionar campo/coluna em uma tabela

```sql
ALTER TABLE produtos ADD fabricante_id INT NOT NULL
AFTER quantidade;

```
<!-- __________________________________________________ -->

# Criação da chave estrangeira (relacionamento entre as tabelas)

```sql
ALTER TABLE 
    ADD CONSTRAINT fk_filmes_generos

    FOREIGN KEY (genero_id) REFERENCES generos(id)
```

<!-- __________________________________________________ -->

# Apagar uma tabela

```sql
DROP TABLE fabricantes;
```