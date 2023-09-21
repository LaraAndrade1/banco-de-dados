# comandos SQL - Referência
<!-- _______________________________________________ -->
## Modelagem física

### Criar banco de dados
```sql
CREATE DATABASE vendas CHARACTER SET utf8mb4;

```
<!-- ________________________________________________ -->

### Criar a tabela de fabricantes

```sql

CREATE TABLE filmes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(45) NOT NULL
)

```
<!-- ________________________________________________ -->

### Criar a tabela de fabricantes

```sql

CREATE TABLE filmes(
    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    titulo VARCHAR(45) NOT NULL,
    lancamento DATE(4) NOT NULL,
    genero INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
   
)

```

<!-- ________________________________________________ -->

### Adicionar campo/coluna em uma tabela

```sql

    ALTER TABLE produtos ADD fabricante_id INT NOT NULL
    AFTER quantidade;



```
<!-- ________________________________________________ -->

### Adicionar campo/coluna em uma tabela

```sql

    ALTER TABLE produtos 
        # CONSTRAINT é uma restrição definida no relacionamento
    ADD CONSTRAINT fk_produtos_fabricantes
   
        # A chave estrangeira deve fazer referência a chave primaria
        FOREIGN KEY (fabricante_id) REFERENCES fabricantes(id)


```






