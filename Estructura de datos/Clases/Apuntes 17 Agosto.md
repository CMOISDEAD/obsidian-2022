# Tablas Hash

## Métodos

### Como usarlo

```java
// Instanciar la tablahash.
Hashtable<Integer, String> ht = new Hashtable<Integer, String>();

// Guardar un valor.
ht.put(key, value);

// Obtener un valor.
ht.get("105");

// Eliminar elementos.
ht.remove(key);

// Remplazar un elemento.
ht.put(keyToReplace, value);

// Obtener el tamano.
ht.size();

// Obtener las llaves de un hash.
sout("Claves: " + ht.keys());

// Verificar si una tabla contiene una llave.
if (ht.containsKey(key)) doSomething;
```

### Como recorrerlo

```java
ht.forEach((key, value) 
			-> sout(key + ", " + value));
```