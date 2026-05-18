SEGUINDO NORMAS (IEC 61851)

Painel Geral Schneider toma decisões em milissegundos:

Início (Grid Connection): O sistema boota e verifica a estabilidade da rede elétrica vinda da concessionária. Se houver oscilação, ele se protege e não inicia.

Detecção (Vehicle Detection): Ao plugar o cabo, o protocolo IEC 61851 entra em ação. O carregador "conversa" com o carro para saber quanto ele pode receber (ex: 7.4kW ou 22kW).

O Grande Decisor (Total Load > Limit?):

Caminho da Esquerda (Não): Se há energia sobrando no prédio, o sistema libera a Potência Total (ex: 7.4kW) para aquele carro carregar o 
mais rápido possível.

Caminho da Direita (Sim): Se ligar esse carro vai estourar o limite do disjuntor geral, o sistema ativa o Algoritmo de Balanceamento.

Algoritmo Inteligente:

Ele calcula quem tem prioridade (ex: quem chegou primeiro ou quem está com bateria mais baixa).

Ajusta os limites de corrente via PWM (modulação de largura de pulso) nos carregadores.

Distribui uma Potência Reduzida (ex: 3.7kW para cada um), garantindo que todos carreguem sem derrubar a luz do condomínio.

Monitoramento (Cloud Telemetry): Tudo é registrado na nuvem para o síndico ver no app e para cobrança automática por apartamento.

<img width="979" height="542" alt="Captura de tela 2026-05-18 202931" src="https://github.com/user-attachments/assets/55de54c8-f63e-4943-92de-7a6fddbecd3e" />

<img width="979" height="542" alt="image" src="https://github.com/user-attachments/assets/a683fd1d-3829-4128-848f-8ba79bc92515" />

by k.

