---
layout: default
title: Visão Geral
nav_order: 1
has_children: true
---

# Internet of Things – Tópico 3
# Visão Geral

### Tecnologias Habilitadoras
Para que a IoT deixe de ser conceito e vire realidade, é preciso unir hardware (objetos) e software (inteligência). O artigo divide isso em dois grandes blocos:

## A. O Elos Físicos (Hardware)
O foco aqui é tornar o mundo real "legível" e "conectado":

- RFID (Identificação): Etiquetas inteligentes que transmitem IDs únicos. Não precisam de linha de visão e permitem rastrear objetos em tempo real (logística, segurança).

- WSN (Redes de Sensores Sem Fio): Redes de nós inteligentes que cooperam para monitorar variáveis ambientais (temperatura, movimento, etc.). Geralmente operam sob o padrão IEEE 802.15.4.

- RSN (Redes de Sensores RFID): A convergência dos dois. Une a capacidade de identificação (RFID) com a capacidade de processamento/sensoriamento (WSN).

## B. O Elo Lógico (Middleware)
O Middleware é a "camada de tradução". Como o hardware é muito heterogêneo (cada dispositivo fala uma "língua"), o middleware esconde essa complexidade dos programadores.

Arquitetura: Adota-se principalmente o modelo SOA (Service Oriented Architecture), onde tudo é tratado como um "serviço" reutilizável.

Camadas Funcionais:

- Abstração: Traduz comandos específicos de hardware para um formato padrão.

- Gestão de Serviços: Monitora e configura os objetos.

- Composição: Permite criar fluxos complexos unindo serviços simples.

- Segurança: Protege os dados, um desafio crítico devido à natureza invasiva da tecnologia.

### Descubra mais sobre os tópicos específicos clicando na barra lateral... ### 


