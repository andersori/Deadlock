# Deadlock
####Simulador para a detecção de impasses.

O simulador deve receber como entrada um arquivo padronizado de
acordo com o exemplo abaixo:

3 4

4 2 3 1

2 1 0 0

0 0 1 0

2 1 0 1

0 1 2 0

2 0 0 2

1 0 1 0

2 1 0 0
```
Primeira linha deve conter o número de processos e o número de recursos.
As duas linhas seguintes devem conter um vetor com a quantidade de recursos existentes e disponiveis.
As linhas restantes devem conter duas matrizes, uma matriz de alocados e outra de requisitados.
```

Como resultado o simulador mostrar uma das três opções a seguir:

1. Existe processos em Deadlock (2 processos ou mais);

* Imprimir quais os processos que estão em deadlock;
* Imprimir as linhas de alocação e requisição de cada processo que está em Deadlock;

2. Não existe processo em DeadLock (Todos Foram finalizados);

3. Existe um único processo esperando por recursos externos;

* Imprimir qual o processo que está em espera;
* Imprimir as linhas de alocação e requisição do processo em espera;
