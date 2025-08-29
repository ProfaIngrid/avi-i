# Cardápio Digital da Lanchonete

Uma lanchonete vende os seguintes produtos:

| Código | Produto        | Preço (R$) |
|--------|----------------|------------|
| 1      | X-Salada       | 15.00      |
| 2      | Refrigerante   | 7.00       |
| 3      | Batata Frita   | 10.00      |

O programa deve:

1. Declarar três pedidos fixos no código, cada um com código do produto e quantidade:  
```java
int cod1 = 1, qtd1 = 2;  // 2 X-Salada
int cod2 = 2, qtd2 = 1;  // 1 Refrigerante
int cod3 = 3, qtd3 = 1;  // 1 Batata

```
Usar um laço while para percorrer os pedidos.

Em cada passo, usar um switch para somar ao total o valor correspondente.

Ao final, imprimir exatamente:
Total: R$XX.00
