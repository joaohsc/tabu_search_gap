1. Descrição do problema.
  O Generalized Assignment Problem (GAP) envolve um conjunto de tarefas I, e um conjunto de máquinas J, onde cada tarefa deve ser atribuída a exatamente uma máquina. A atribuição de uma tarefa a uma máquina acarreta um determinado custo e consome parte da capacidade da máquina. Além disso, nenhuma máquina pode ultrapassar sua capacidade total disponível, o que impõe restrições adicionais ao processo de alocação (PIGATTI et al., 2004).
   
3. Qual metaheurística foi utilizada.
   - Tabu Search
    
4. Bibliotecas necessárias para rodar.
  - matplotlib

6. Como executar o projeto (passo a passo).
  Só é necessário instalar as biliotecas necessárias e rodar o notebook. Uma outra opção é acessar o link do collab disponibilizado e acessar o notebook.

7. Resultados
  Para cada experimento foi montado um gráfico de linha que ilustra o melhor, pior e média do custo. Além disso, foi construído uma variação do gráfico de Gantt para ilustrar as atribuições das máquinas. Para exemplificação dos resultados obtidos só foram selecionados os principais gráficos para visualizar o estudo.

	A figura 1 apresenta o gráfico de custo do experimento 1. Para um caso com poucas máquinas e tarefas, a convergência do gráfico é rápida, aproximadamente 45 iterações. As linhas dos piores custos geralmente são as soluções com a penalidade aplicada, esse cenário se repete nos outros experimentos. Vale ressaltar que houve uma queda considerável no custo, assim como o esperado. Esse resultado da queda de custo é uma característica que permaneceu em todos os experimentos.

![image](https://github.com/user-attachments/assets/ce985d7e-1dbd-4fb6-bce5-4b01daed3b5f)
Figura 1 - Gráfico de custo do experimento 1 (fonte: Autoria própria).

5. Comentários e Conclusões
	Com a aplicação do tabu search, foi possível visualizar nos experimentos a execução da metaheurística para resolver o problema proposto. O impacto da definição dos parâmetros corretos também foi observado. Portanto, pode-se concluir que os objetivos deste trabalho foram atingidos. Uma observação sobre a execução do TS é que de acordo com o aumento do número de tarefas e máquinas o tempo de execução do algoritmo também cresceu. Para os experimentos com 300 tarefas a execução levou aproximadamente 30 minutos. Isso abre possibilidades para pensar em alternativas para otimizar o código ou a abordagem. De um modo geral, o TS apresentou bons resultados para resolver um problema como o GAP. Nos resultados de cada experimento se observou quedas consideráveis no custo, que numa aplicação real seria bastante relevante.
