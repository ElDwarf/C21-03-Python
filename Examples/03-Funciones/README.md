# Ejemplo 01

En este ejemplo vamos a jugar con funciones y probarlas


## Pasos 1. crear funcion simple

### Definicion

```python
def print_hello_world() -> None:
    print("Hello world")
```

### Uso

```python
print_hello_world()
```

### Resultado

```python
Hello world
```

## Pasos 2. crear funcion con parametro

### Definicion

```python
def print_hello_name(name: str) -> None:
    print(f"Hello {name}")
```

### Uso

```python
print_hello_name("Pablo")
```

### Resultado

```python
Hello Pablo
```

## Pasos 3. crear funcion con respuesta

### Definicion

```python
def print_hello_name(name: str) -> str:
    return f"Hello {name}"
```

### Uso

```python
msg = print_hello_name("Pablo")
print(msg)
```

### Resultado

```python
Hello Pablo
```

## Pasos 3. crear funcion con valores default

### Definicion

```python
def print_hello_name(name: str, cant: int= 1) -> str:
    return f"Hello {name}, "*cant
```

### Uso 1

```python
msg = print_hello_name("Pablo")
print(msg)
```

### Resultado

```python
Hello Pablo,
```

### Uso 2

```python
msg = print_hello_name("Pablo", 2)
print(msg)
```

### Resultado

```python
Hello Pablo, Hello Pablo,
```
