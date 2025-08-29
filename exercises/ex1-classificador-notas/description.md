# Controle de Estacionamento

Um estacionamento precisa de um sistema para verificar vagas.

- Existem **5 vagas numeradas de 1 a 5**, e cada vaga já está definida como **ocupada** ou **livre**.  
- O programa deve declarar variáveis no código para representar cada vaga:
```java
boolean vaga1 = true;   // ocupada
boolean vaga2 = false;  // livre
boolean vaga3 = true;
boolean vaga4 = false;
boolean vaga5 = true;
```

O sistema deve percorrer todas as vagas usando um laço (for) e, com auxílio de um switch, selecionar a vaga correspondente.

Para cada vaga, use if/else para imprimir:

"Vaga X: Livre"

"Vaga X: Ocupada"

No final, mostre o total de vagas livres e ocupadas.

Saída esperada (com os valores acima)

Vaga 1: Ocupada
Vaga 2: Livre
Vaga 3: Ocupada
Vaga 4: Livre
Vaga 5: Ocupada
Livres: 2
Ocupadas: 3


