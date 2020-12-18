<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://icon-library.com/images/zombie-icon-png/zombie-icon-png-18.jpg" width="200"></a></p>

<h4 align="center">
API REST LARAVEL <br> CASO APOCALIPSE ZOMBIE ACONTEÇA
</h4>

## Primeiros passos
### RUN:
```
compose install
```
```
php artisan migrate
```
```
php artisan serve
```
## GET
```
/api/survivor
```
```
/api/survivor/{id}
```
## POST
```
/api/survivor
```
## PUT
```
/api/survivor/{id}
```
## DELETE
```
/api/survivor/{id}
```

## RELATORIO
```
[GET]

/api/relatorio
```

## TROCAS
```
Sobreviventes carregam consigo [armas, facas, etc...]
e eles podem fazer trocas desses objetos.
```

```
INVENTARIO DO SOBREVIVENTE:

ITEM
ÁGUA
COMIDA
MEDICAMENTO
MUNIÇÃO
```
### ITEM
```
ENVIE UM [POST] /api/items/trocas contendo:

    {
        "troca": "item",
        "id": ,
        "id_exchange": 
    } 
  
 1. troca = Aqui você deve informar quais dos items do inventario deseja fazer a troca, já que estamos trocando o item do inventario colocamos "item".
 2. id = Aqui você deve informar o id da pessoa que quer fazer a troca.
 3. id_exchange = Aqui deve informar o id da pessoa que aceitou a troca.

```

```
obs: Sobreviventes infectados não podem fazer trocas !
```
### AGUA
```
EM BREVE
```
### COMIDA
```
EM BREVE
```
### MEDICAMENTO
```
EM BREVE
```
### MUNIÇÃO
```
EM BREVE
```


