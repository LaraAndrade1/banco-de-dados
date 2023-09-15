# Comandos SQL - Para CRUD (Referência)

## Resumo 
C -> Create (isere dados)
R -> Read (Ler dados)
U -> Update (Atualizar dados)
D -> Delete (Deletar dados)

<!-- _____________________________________________ -->

## Insert
## Fabricantes

```sql
 INSERT INTO fabricantes (nome) VALUES ('Asus') 
 INSERT INTO fabricantes (nome) VALUES ('Dell') 
 INSERT INTO fabricantes (nome)
 VALUES('Apple'),('LG'),('Samsung'),('Brastemp')

```
<!-- ________________________________________________ -->

## Insert
## Produtos

```sql
 INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Ultrabook', 'Ultrabook Asus Intel Core i9',
 8500.99, 10, 6);

 INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Geladeira', 'Frost-free com acesso a internet' ,
 6500.99, 7, 1);

 INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Tablet Android', '256gb de armazenamento',
 6500.99, 7, 1);

 INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Iphone 14 pro max', 'Processador bionic 15 com 520gb de armagenamento',
 9999.97, 3, 3);
 
 

```

<!-- ________________________________________________ -->

## Insert
## Fabricantes

```sql
 INSERT INTO produtos (nome)
 VALUES('Positivo'),('Microsoft');

```
<!-- ________________________________________________ -->

## Insert
## Fabricantes

```sql
  INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Ultrabook', 'Ultrabook Asus Intel Core i9',
 8500.99, 10, 6);

 INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Geladeira', 'Frost-free com acesso a internet' ,
 6500.99, 7, 1);

 
 
 
```

