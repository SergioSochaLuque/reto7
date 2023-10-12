# reto7
1. Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
  + Definí la variable i que es igual a 1 porque la lista inicia desde 1 y la lista vacia.
  + Inicié con while que funciona siempre y cuando i sea menor o igual a 100, por dentro del while se calcula el cuadrado del numero.
  + A la variable se le suma 1 para que el codigo siga realizando el while con el siguiente numero
   ```mermaid
   flowchart TB;
    A(Inicia)--> B["i=0 ; Lista=[]"]
    B -->C{while i<=100}
    C -- SI --> D["cuadrado = i**2"]
    D --> E["Lista.append(cuadrado)"]
    E --> F["i+=1"]
    F ---> C
    C --- NO ---> G[/"Lista"/]
    G --> H(Final)
   ```
![image](https://github.com/SergioSochaLuque/reto7/assets/141857054/ac3ec429-ba2d-44e2-b946-575511ea2022)

2. Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
  +
