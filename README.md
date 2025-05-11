# Walker-Fall-Detection-Dataset
Pesquisa em detecção de quedas e reconhecimento de atividades de usuários de andadores ortopédicos
Este dataset foi desenvolvido para a pesquisa em detecção de quedas e reconhecimento de atividades de usuários de andadores ortopédicos. Ele contém dados de um sensor IMU (Inertial Measurement Unit) coletados de um andador em quatro atividades distintas:

Idle: O andador está parado, sem movimento.
Motion: O andador está sendo movido, mas não por um usuário andando.
Step: Movimento do andador durante o passo de um usuário.
Fall: O andador caindo ao chão.    
O dataset foi criado para auxiliar no desenvolvimento e avaliação de algoritmos de machine learning para sistemas de detecção de quedas em tempo real para usuários de andadores.    

Conteúdo:
O dataset inclui dados de aceleração (XYZ) e giroscópio (XYZ) amostrados a 80 Hz. Cada amostra é composta por 160 leituras de cada um dos seis canais (aceleração X, Y, Z e giroscópio X, Y, Z), totalizando 960 features. Os dados foram pré-processados conforme descrito no artigo, incluindo downsampling, cálculo de RMS, normalização e filtragem.    

Uso:
Este dataset pode ser usado para treinar e avaliar modelos de machine learning para detecção de quedas e reconhecimento de atividades em usuários de andadores. Ele é adequado para tarefas de classificação e pode ser utilizado em diversas aplicações, como sistemas de alerta de quedas, monitoramento de atividades e análise de padrões de movimento.    

Observações:
O dataset foi coletado com um sensor IMU fixado a um andador ortopédico.
O artigo original fornece detalhes adicionais sobre o processo de coleta de dados, pré-processamento e desenvolvimento do sistema.
Sinta-se à vontade para utilizar e adaptar este dataset para suas próprias pesquisas e projetos.
