# README - Otimização de Aterrissagem de Aeronaves


Disciplina: GCC118 - Programação Matemática.

## Equipe
- Aluno 1: Guilherme Henrique Silva Barbara - 202120499;
- Aluno 2: (Preencher).

## Introdução
Este projeto consiste em resolver o problema de otimização de aterrissagem de aeronaves em um grande aeroporto brasileiro. O problema visa minimizar penalidades relacionadas ao tempo de pouso fora do intervalo ideal para cada avião, considerando uma única pista principal de voo.

## Descrição do Problema
Diariamente, um conjunto de aviões pousa no aeroporto. Para cada avião, são fornecidas as seguintes informações:
- **Ri:** Tempo de detecção pelo radar.
- **Ei:** Tempo inicial permitido para pouso.
- **Ti:** Tempo ideal de pouso.
- **Li:** Tempo final permitido para pouso.
- **gi:** Penalidade por unidade de tempo caso o avião pouse antes do tempo ideal.
- **hi:** Penalidade por unidade de tempo caso o avião pouse depois do tempo ideal.

Além disso, uma matriz de separação S=[sij] determina o tempo mínimo que deve ser aguardado entre o pouso de dois aviões consecutivos.

## Objetivos
1. **Formulação Matemática:** Formular o problema como um modelo de programa linear ou inteiro.
2. **Resolução com Solver:** Resolver as instâncias propostas utilizando um solver genérico, como GLPK, CPLEX ou outros.
3. **Metaheurística:** Implementar a metaheurística Variable Neighborhood Search (VNS).
4. **Análise e Relatório:** Documentar os experimentos com análise de resultados.

## Requisitos
- O código deve aceitar uma instância de problema pela entrada padrão e imprimir a solução pela saída padrão.
- Os parâmetros principais do método devem ser configuráveis pela linha de comando.
- Valores apresentados para métodos estocásticos devem ser médias de pelo menos 5 replicações com sementes diferentes.
- O projeto deve estar documentado com README, código-fonte, e relatório completo.

## Solver Utilizado
GLPK

## Metaheurística Utilizada
Variable Neighborhood Search (VNS)

### Escolhas Implementadas
- **Representação do Problema:** (Preencher);
- **Função Objetivo:** (Preencher);
- **Solução Inicial:** (Preencher);
- **Estratégia de Busca Local:** (Preencher);
- **Critério de Parada:** (Preencher).

## Resultados Computacionais
Os resultados computacionais serão apresentados com as seguintes informações:
- Valor da Solução Inicial (SI)
- Valor da Solução Final (SF)
- Desvio percentual entre SI e SF
- Desvio percentual entre SF e solução ótima
- Tempo computacional da metaheurística e do solver

## Instâncias Teste
Link para download das instâncias: [https://drive.google.com/file/d/1_FB9c04PjbI6f_qvGQoXyu24Czr55b3R/view?usp=sharing](https://drive.google.com/file/d/1_FB9c04PjbI6f_qvGQoXyu24Czr55b3R/view?usp=sharing)

Valores de referência:
- Instância 1: 700
- Instância 2: 1480
- Instância 3: 820
- Instância 4: 2520
- Instância 5: 3100
- Instância 6: 24442
- Instância 7: 1550
- Instância 8: 1950

## Como Executar
(Preencher)



