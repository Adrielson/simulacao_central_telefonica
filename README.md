# simulacao_central_telefonica
TRABALHO DE SIMULAÇÃO Descrição: O trabalho tem o objetivo de avaliar a capacidade de implementação de um simulador para um problema de pequeno porte.


METODO DE TRÊS FASES (definições)
1: método de três fases para elaborar o pseudocódigo que representam os eventos da simulação. O método das três fases é uma abordagem que mescla a estratégia de evento com a de atividade. Fases "A", "B" e "C" são introduzidas. A fase "B" checa pelo fim de atividades e a fase "C", as condições para as atividades ocorrerem. A fase "A", por sua vez, atualiza o tempo, avançando-o para o próximo evento.

2: Um técnica conhecida para execução de simulações de eventos discretos é o "Método das três fases". Nesta abordagem, a primeira fase sempre avança o relógio para o próximo evento a ocorrer, respeitando a ordem cronológica de eventos (chamados de eventos do tipo A). A segunda fase é a execução de todos os eventos que incondicionalmente ocorrem no instante atual (chamados de eventos do tipo B). A terceira fase é a execução de todos os eventos que condicionalmente ocorrem no tempo atual (chamados eventos do tipo C). O método das três fases é um refinamento da abordagem baseada em eventos, na qual os eventos simultâneos são ordenados de modo a tornar mais eficiente o uso dos recursos computacionais. O método das três fases é utilizado por diversos pacotes comerciais de simulação, mas do ponto de vista do usuário, tais especificidades técnicas do método de execução são geralmente ocultas

IMPLEMENTAÇÃO
Na Fase A, o relógio da simulação é avançado para o próximo evento a ocorrer, respeitando a ordem cronológica dos eventos. Isso significa que o tempo da simulação é atualizado para o momento em que o próximo evento está programado para ocorrer.

Na Fase B, são executados todos os eventos que ocorrem incondicionalmente no instante atual. Esses eventos são chamados de eventos do tipo B, e eles ocorrem sem depender de nenhuma condição adicional. Essa fase lida com atividades que devem ser executadas sempre que ocorrerem, independentemente de outras condições.

Na Fase C, são executados todos os eventos que condicionalmente ocorrem no tempo atual. Esses eventos são chamados de eventos do tipo C, e sua ocorrência depende de condições específicas que devem ser satisfeitas. Essa fase lida com atividades que podem ocorrer apenas se determinadas condições forem atendidas.

O método das três fases é uma abordagem refinada da estratégia de evento, na qual os eventos simultâneos são ordenados de forma a otimizar o uso dos recursos computacionais. Embora os detalhes técnicos da execução do método possam ser ocultos em pacotes comerciais de simulação, essas especificidades são relevantes para entender o funcionamento do método das três fases.
