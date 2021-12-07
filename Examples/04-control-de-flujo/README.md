# Ejemplo 01 `IF`

En este ejemplo vamos a jugar con `if`


## Pasos 1. crear funcion

### Definicion

```python
def par_o_impar(nro: int) -> None:
    resto = nro % 2
    if resto == 0:
        print("Par")
    else:
        print("Impar")
```

### Uso

```python
par_o_impar(2)
Par
```

# Ejemplo 02 `For`

En este ejemplo vamos a jugar con `for`

## Pasos 1. crear funcion

### Definicion

```python
def deletreo(palabra: str) -> None:
    for x in palabra:
        print(x)
```

### Uso

```python
deletreo(hola)
h
o
l
a
```

# Ejemplo 03 `While`

En este ejemplo vamos a jugar con `while`

## Pasos 2. crear funcion

### Definicion

```python
def imprimir_mientras_tenga_algo(lista: list) -> None:
    while len(lista):
        x = lista.pop()
        print(x)
```

### Uso

```python
imprimir_mientras_tenga_algo(["hola", "puerta", "chau"])
hola
puerta
chau
```
