# Ejemplo 01

En este primer ejemplo vamos a realizar nuestro primer ejecucion de codigo python. Para ello vamos a iniciar el interprete de python para luego usar la funcion `print()` para imprimer un `Hello world`


## Pasos 1. Abrir interprete de python dentro de docker.

### Ejecucion

```sh
docker run -ti python:3.9 python
```

### Resultado

```sh
Unable to find image 'python:3.9' locally
3.9: Pulling from library/python
5e0b432e8ba9: Pull complete 
a84cfd68b5ce: Pull complete 
e8b8f2315954: Pull complete 
0598fa43a7e7: Pull complete 
83098237b6d3: Pull complete 
b92c73d4de9a: Pull complete 
d8175d86ad38: Pull complete 
a2c9bf0d5eac: Pull complete 
b254bd014afa: Pull complete 
Digest: sha256:6c79ffec74d8284f21dfeb415124151d925e7476fa98d0bb59b0ef8ab91cad02
Status: Downloaded newer image for python:3.9
Python 3.9.9 (main, Dec  3 2021, 01:15:49) 
[GCC 10.2.1 20210110] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

## 2. Imprimimos mensaje

### Ejecucion

```python
print("Hello World!")
```

### Resultado

```python
Hello World!
```

# Ejemplo 02

En este ejemplo vamos a jugar un poco con los tipos de datos `boolean`

## Paso 1. creo variables

### Ejecucion

```python
a = True
b = False
d = True
C = False
```

## Paso 2. Operaciones basicas

### Ejecucion

```python
a and b
```

### Resultado
```python
False
```

### Ejecucion

```python
a or b
```

### Resultado
```python
True
```

### Ejecucion

```python
not a
```

### Resultado
```python
False
```

## Paso 3. Operaciones que devuelven `Boolean`

### Ejecucion

```python
2 < 5
```

### Resultado
```python
True
```

### Ejecucion

```python
5 < 2
```

### Resultado
```python
False
```

### Ejecucion

```python
lista = [2, 4, 6, 7, 8, 9]

3 in lista

```

### Resultado
```python
False
```

# Ejemplo 03

En este ejemplo vamos a jugar un poco con los tipos de datos `numericos`

## Paso 1. creo variables

### Ejecucion

```python
a = 2.4234
b = 1
c = 6
d = 8+3i

```

## Paso 2. Operaciones basicas

### Ejecucion

```python
a + b
```

### Resultado
```python
3.4234
```

### Ejecucion

```python
b + c
```

### Resultado
```python
7
```

### Ejecucion

```python
b % c
```

### Resultado
```python
1
```

```python
b / d
```

### Resultado
```python
(0.1095890410958904-0.0410958904109589j)
```


