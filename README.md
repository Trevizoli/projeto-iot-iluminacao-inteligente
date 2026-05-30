# Sistema de Iluminação Inteligente com IoT

## Descrição

Este projeto apresenta uma solução de iluminação inteligente baseada em Internet das Coisas (IoT). O sistema utiliza um ESP32 para monitorar a luminosidade do ambiente por meio de um sensor de luminosidade baseado em LDR e controlar a iluminação através de um módulo relé.

A comunicação entre os dispositivos é realizada utilizando o protocolo MQTT, com o broker MQTT Mosquitto.

## Componentes Utilizados

* ESP32
* Sensor de luminosidade (LDR)
* Módulo relé
* Protoboard
* Jumpers

## Funcionamento

O sensor monitora continuamente a luminosidade do ambiente. Quando a intensidade luminosa fica abaixo do valor configurado, o ESP32 aciona o módulo relé para ligar a iluminação. Quando a luminosidade aumenta, o relé é desligado.

Os dados podem ser enviados para um broker MQTT, permitindo monitoramento remoto e integração com aplicações IoT.

## Protocolo de Comunicação

* TCP/IP
* MQTT
* Broker MQTT Mosquitto

## Autor

Luis Renato Fonseca Trevizoli Neves
Universidade Presbiteriana Mackenzie
