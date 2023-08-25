# GAS
Objetivo:
Este projeto visa criar um sistema eficiente de detecção de vazamentos de gás em ambientes residenciais, como apartamentos e casas, utilizando o sensor de gás MQ-9, um microcontrolador ESP32 e um buzzer. O objetivo é alertar os residentes sobre possíveis vazamentos de gases inflamáveis e tóxicos, garantindo a segurança das pessoas e prevenindo acidentes.

Componentes do Sistema:

Sensor MQ-9:
O sensor MQ-9 é um sensor de gás que detecta gases como monóxido de carbono (CO) e hidrogênio (H2) no ambiente. Ele mede a concentração desses gases e fornece leituras analógicas que indicam a presença de vazamentos potenciais.

Microcontrolador ESP32:
O ESP32 é um microcontrolador poderoso e versátil com conectividade Wi-Fi e Bluetooth integrada. Ele atua como o cérebro do sistema, coletando dados do sensor MQ-9, processando as leituras e controlando a ativação do alarme.

Buzzer:
O buzzer é um componente sonoro que emite um som audível quando energizado. Neste caso, o buzzer será ativado para alertar os ocupantes sobre a detecção de um vazamento de gás.

Funcionamento:

O sensor MQ-9 faz medições regulares da concentração de gases no ambiente.
As leituras analógicas do sensor são lidas pelo ESP32.
O ESP32 processa as leituras e verifica se a concentração de gases excede um limite de segurança predefinido.
Se a concentração ultrapassar o limite seguro, o ESP32 aciona o buzzer para emitir um som audível de alarme.
O alarme sonoro alerta imediatamente os ocupantes sobre a presença de um vazamento de gás.
