# Projeto de Monitoramento Global de Vinherias: PoC Smart Lamp

**Autores**: Ulisses Ribeiro, Arthur Ferreira, Luigi Borghi, Levi de Jesus

## Descrição

Este projeto visa desenvolver uma **PoC (Prova de Conceito)** para o monitoramento global de vinherias, utilizando um **DOIT ESP32 DEVKIT 1** com sensores **DHT11** (temperatura e umidade) e **LDR** (luminosidade). A solução integra os dados coletados em um **dashboard no Thingspeak**, permitindo o monitoramento em tempo real das condições ambientais.

## Objetivos

- Criar uma solução de monitoramento para vinherias.
- Utilizar um **ESP32** para coletar dados de **temperatura**, **umidade** e **luminosidade**.
- Enviar esses dados para o **Thingspeak**, proporcionando visualizações em tempo real.
- Prototipar o sistema no **Wokwi** e realizar o hands-on com a montagem real do hardware.

## Materiais Utilizados

- **DOIT ESP32 DEVKIT 1**
- **Sensor DHT11** (Temperatura e Umidade)
- **Sensor LDR** (Luminosidade)
- **Plataforma Wokwi** (Simulação)
- **Thingspeak** (Dashboard)

## Funcionalidade

O sistema coleta as seguintes variáveis ambientais:

- **Temperatura**: Medida através do sensor **DHT11**.
- **Umidade**: Também coletada pelo **DHT11**.
- **Luminosidade**: Obtida via **LDR**.

Esses dados são enviados para a plataforma **Thingspeak**, onde podem ser visualizados em tempo real.

## Como Rodar o Projeto

### 1. Clonando o Repositório

Clone este repositório para o seu computador:

```bash
git clone https://github.com/SeuUsuario/SmartLamp.git
