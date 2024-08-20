1. Execução
Foi utilizado o comando ‘git clone’ no repositório do professor, na qual havia os
scripts para realizar a atividade. Então com os scripts foi monitorado o comando
‘nano’, que é simples e utilizado frequentemente. A chamada de sistema
durou 10 segundos e gerou o arquivo ‘log_ls’ contendo todas as chamadas de
sistema realizadas pelo processo ‘nano’ durante o período monitorado.

2. Análise
Na identificação das System Calls foi observado que as chamadas de sistema
mais comuns são as ‘open’, ‘read’, ‘write’ e ‘close’, a maioria estava relacionada
à entrada/saída de arquivos e algumas chamadas relacionadas a rede foram
encontradas.

3. Comparação
Em um sistema multiprogramável, a capacidade de multitarefa permite que várias
operações de I/O ocorram simultaneamente, aumentando o número de
chamadas de sistema observadas.
Em sistemas monoprogramáveis, o gerenciamento de processos é mais simples,
mas menos eficiente, resultando em menos chamadas de sistema, porém com
maior tempo de espera para a conclusão de tarefas.

4. Conclusão
Com esta atividade, foi possível compreender melhor o funcionamento de system
calls e a diferença entre sistemas monoprogramáveis e multiprogramáveis, além
de explorar o impacto de sistemas multiprocessadores na execução de
processos. A atividade foi uma excelente oportunidade para aplicar conceitos
teóricos em um ambiente prático, consolidando o conhecimento sobre o
gerenciamento de processos e recursos em diferentes tipos de sistemas
operacionais.
