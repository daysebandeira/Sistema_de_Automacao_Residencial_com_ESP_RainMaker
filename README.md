# Sistema_de_Automacao_Residencial_com_ESP_RainMaker
Sistema de automação residencial utilizando a Franzininho WiFi LAB01 e o ESP RainMaker, permitindo o controle remoto de iluminação e monitoramento de ambiente, integrando recursos de IoT.

## Descrição
Sistema de automação residencial utilizando ESP RainMaker para controle remoto de iluminação e monitoramento ambiental.

## Funcionalidades
- Controle de luz (liga/desliga, brilho)
- Monitoramento de temperatura e umidade
- Automação por sensor de presença
- Simulação de ar-condicionado
- Integração com Alexa e Google Assistant

##  Hardware
- Franzininho WiFi LAB01 (ESP32-C3)
- Sensor DHT11
- Sensor PIR
- LED RGB

## Instalação
1. Instale Arduino IDE
2. Instale bibliotecas:
   - ESP RainMaker
   - DHT sensor library
3. Conecte a placa via USB

##  Execução
1. Compile e envie o código
2. Abra o app ESP RainMaker
3. Faça o pareamento via BLE

##  Estrutura

smart-home-iot/
 ├── src/
 │   └── main.cpp
 ├── docs/
 └── README.md

##  Integração
Compatível com Alexa e Google Assistant via ESP RainMaker.

##  Autor
Projeto acadêmico de IoT do Curso Embarcados
