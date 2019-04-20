# Array

## Funcionamento em memória
A terminar

## Declaração

Para declarar um array em C é possível usar os seguintes formatos:

```c
int b[5];  // declara array
int a[] = {1, 2, 3, 4};  // declara e inicializa array
```

## Atribuiçao

Para adicionar um elemento no array você usa o índice:

```c
a[1] = 5;
```
Para adicionar vários elementos no array você pode usar o for para gerar os
diferentes índices.

```c
for (int i = 0; i <= 100; i++) {
    scanf("%d", &a[i]);
}
for (int j = 0; j <= 50; j++) {
    b[j] = 0;
}
```

## Array multidimensional (Matriz)
