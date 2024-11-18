# Atividade-10

Esse código demonstra a criação de duas threads com diferentes prioridades em Java, a classe BaixaPrioridade cria uma thread que executa com a prioridade mínima, enquanto a classe AltaPrioridade cria uma thread com prioridade máxima, fazendo pausas de 10 ms. No método main, as threads são iniciadas, e a thread principal cede a execução às outras. Um ShutdownHook é adicionado para garantir que as threads sejam interrompidas corretamente ao encerrar o programa. O código simula um atraso de 50 segundos antes de interromper explicitamente as threads e finalizar a execução. O exemplo ilustra o uso de prioridades de threads e a gestão do ciclo de vida das mesmas.