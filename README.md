# 📊 Smart Monitor para Futebol Feminino  

Este projeto implementa um sistema de **monitoramento inteligente** utilizando o **ESP32** para captar dados ambientais e fisiológicos durante atividades esportivas, com foco no **futebol feminino**.  

## Componentes utilizados
- **ESP32 (DOIT DEVKIT V1)**  
- **DHT22** → Sensor de temperatura e umidade  
- **Potenciômetro** → Simulação de sensor de batimento cardíaco  
- **Wi-Fi (Wokwi Guest)** para envio dos dados à nuvem  

## Integração com ThingSpeak
Os dados coletados são enviados para o **ThingSpeak**, permitindo análise em tempo real dos seguintes parâmetros:  
1. **Temperatura ambiente**  
2. **Umidade relativa do ar**  
3. **Batimento cardíaco (simulado)**  

## Aplicação no Futebol Feminino
O sistema pode ser utilizado para:  
- Monitorar as condições ambientais de treino e jogo.  
- Avaliar a carga física das atletas por meio do acompanhamento do batimento cardíaco.  
- Apoiar treinadores e preparadores na **prevenção de fadiga e lesões**.  

## Simulação
O projeto pode ser testado no **Wokwi Simulator**, com dados sendo enviados diretamente para o **ThingSpeak Dashboard**.  

<img width="1048" height="716" alt="Gráficos do ThingSpeak" src="https://github.com/user-attachments/assets/7666a056-59f1-4b7d-8ddb-3d8b19d128b9" />


