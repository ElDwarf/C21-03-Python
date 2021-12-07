# Ejemplo 01

En este ejemplo vamos a realizar acciones sobre estructuras de datos


## Pasos 1. crear variables

### Ejecucion

```python
lista_a = [2, 3, 4, 5, 6, 7]
lista_b = ["a", "b", "c", "d", "e", "f"]
lista_c = [lista_a, lista_b, lista_a, lista_b]
tupla_a = (1, 2, 3, 4, 5, 6, 7, 8, 9, 0)
diccionario = {
  "Nombre": "Pablo",
  "Apellido": "Dalmasso",
  "Edad": 35,
  "Nacionalidad": "Argentino"
}
```

### Resultado

```python

```

## Pasos 2. Iterar (recorrer)

### Ejecucion

```python
for item in lista_a:
    print(item)
```

### Resultado

```python
2
3
4
5
6
7
```

## Pasos 3. Ingreso por indice

### Ejecucion

```python
print(lista_c[1][0])
```

### Resultado

```python
a
```

## Pasos 4. Agregar item

### Ejecucion

```python
lista_a.append(0)
print(lista_a)
```

### Resultado

```python
[2, 3, 4, 5, 6, 7, 0]
```

## Pasos 4. Extraer item

### Ejecucion

```python
item = lista_a.pop()
print(item)
print(lista_a)
```

### Resultado

```python
0
[2, 3, 4, 5, 6, 7]
```

## Pasos 5. Ingresar a la tupla

### Ejecucion

```python
tupla_a.append(2)
```

### Resultado

```python
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
AttributeError: 'tuple' object has no attribute 'append'
```

## Pasos 6. Iterar Diccionario

### Ejecucion

```python
for key in diccionario:
    print(f'{key}: {diccionario[key]}')
```

### Resultado

```python
Nombre: Pablo
Apellido: Dalmasso
Edad: 35
Nacionalidad: [Argentino](Argentino)
```



