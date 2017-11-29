# Python Level 0
## Exemplos de códigos da linguagem Python.

## Em comum na lista

```py
# Lista numéricas A e B
a = [1, 2, 3, 4, 5, 1]
b = [6, 7, 8, 9, 10, 1, 2, 11, 22]

# Verifica a quantidade de elementos que existem em comum entre as duas listas
comum = len(set(a).intersection(b))
print(comum)
```

### Output
`2`

* * *

## Tupla Par

```py
def tupla_par(tupla):
    
  '''
  tupla: uma tupla
  
  retorna: nova tupla formada pelos elementos que possuem índices pares
  '''
  return tupla[0::2]

tupla  = ('segunda', 'terça', 'quarta', 'quinta', 'sexta', 'sábado', 'domingo')
tupla_par(tupla)

```

### Retorna
`('segunda', 'quarta', 'sexta', 'domingo')`

