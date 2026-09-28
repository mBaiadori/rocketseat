---
id: automovel-motor
title: Especificação e Arquitetura do Motor Automotivo
type: spec
version: 1.0.0
status: approved
layer: automovel
path: automovel/motor.md
parent: automovel/carros.md
lifecycle:
  stage: docs
  previous_stage: draft
  next_stage: active
  feedback_loops: {}
---

Este documento define a arquitetura, os componentes principais e o funcionamento canônico do **Motor** no ecossistema automotivo.

## 1. Visão Geral

O motor é o coração do veículo automotivo, responsável por converter energia química (proveniente de combustíveis fósseis, biocombustíveis ou reações elétricas) em energia mecânica, garantindo a tração e o deslocamento do automóvel.

## 2. Componentes Principais

- **Bloco do Motor:** Estrutura fundamental que abriga os cilindros e suporta o virabrequim.
- **Cabeçote:** Parte superior que sela os cilindros e abriga as válvulas de admissão e escape, além das velas de ignição (em motores a combustão).
- **Virabrequim (Árvore de Manivelas):** Converte o movimento linear dos pistões em movimento rotacional.
- **Pistões e Bielas:** Elementos móveis que realizam o ciclo de trabalho dentro dos cilindros através da pressão gerada pela combustão ou campo eletromagnético.

## 3. Tipos de Motorização

1. **Combustão Interna (ICE):** Utiliza ciclos termodinâmicos (Otto ou Diesel) para queima de combustível.
2. **Elétricos:** Utilizam motores de indução eletromagnética alimentados por baterias de alta voltagem.
3. **Híbridos:** Combinam sistemas de combustão interna com propulsão elétrica para maximizar a eficiência energética.