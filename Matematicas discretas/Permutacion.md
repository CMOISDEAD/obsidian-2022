# Permutacion

Ejemplos de permutacion y otros procedimientos en python.
$$
P(n,r) = \frac{n!}{(n-r)!}
$$
*Ejemplo*
Mostrar todos las posibles combinaciones de 3 para una serie 5 de números donde:

1. No importa el _orden_.
2. No se puede repetir _elementos_.

```python
def permutation(data: list[int]):
	counter = 1
	for i in data:
		for j in data:
			if j != i:
				for k in data:
					if k != i and k !=j:
						print("{}: {}{}{}".format(counter, i, j, k))

def main():
	data: list[int] = [1, 2, 3 ,4 ,5]
	permutation(data)

```

- Si se pudieran repetir elementos, eliminaríamos los `if`.
- Para crear una colección de números mas grande agregaríamos mas `for`.