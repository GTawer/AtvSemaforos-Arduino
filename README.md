# 🚦 Sistema Inteligente de Controle de Trânsito: Desafio dos Semáforos Sincronizados 👾

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge&logo=github)
![Platform](https://img.shields.io/badge/Plataforma-Tinkercad%20%2F%20Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)

Esta atividade foi desenvolvida com foco em **Mobilidade Urbana**, simulando uma solução tecnológica para um cruzamento crítico de duas vias de grande circulação. O projeto foi projetado e programado em **C++** utilizando a plataforma **Tinkercad** e componentes físicos do **Arduino UNO**.

O objetivo principal foi aplicar conceitos de eletrônica digital, lógica de programação unida à automação/IoT para organizar o fluxo de veículos de forma segura, eliminando riscos de colisões e atropelamentos.

---

## 📂 Detalhes do Projeto

| Item | Descrição | Status |
| :--- | :--- | :--- |
| `Hardware` | Montagem de 2 semáforos completos (6 LEDs) na Protoboard. | ✅ |
| `Lógica de Sincronismo` | Intertravamento eletrônico que impede sinais verdes simultâneos. | ✅ |
| `Código-Fonte` | Programação em C++ estruturada com controle automático de tempo. | ✅ |
| `Multimídia` | Gravação de vídeo demonstrativo pelo Product Owner (P.O.). | ✅ |

---

## ⚙️ Funcionamento e Lógica do Sistema

Para resolver os problemas de congestionamento e acidentes do cruzamento, a lógica de programação foi estruturada da seguinte forma:

* **Sincronização entre Vias:** Enquanto a **Via A** está com o sinal VERDE acionado, a **Via B** permanece obrigatoriamente no VERMELHO.
* **Transição Segura:** Antes de alternar a preferência de passagem, o sinal AMARELO da via ativa é acionado por um tempo determinado, alertando os motoristas.
* **Ciclo Contínuo:** O sistema roda de forma automatizada em um loop infinito, garantindo a fluidez contínua do trânsito.

> ⚠️ **Segurança em Primeiro Lugar:** O código foi blindado contra falhas lógicas para garantir que em nenhum momento ambos os semáforos fiquem verdes simultaneamente, evitando colisões.

---

## 🔗 Links do Projeto
* [Acesse aqui o projeto no Tinkercad - Gabriel A. Torres](https://www.tinkercad.com/things/iy8Ng7Wr1Ay-semaforo-de-duas-vias?sharecode=7yJMzGKuw8FMifz0JsIby9lAzom6xVKLo_70daSDMpk)

---

## 🛠️ Ferramentas Utilizadas

* **Tinkercad:** Ambiente virtual para simulação e teste do circuito.
* **Arduino UNO:** Microcontrolador base para automação.
* **Linguagem C/C++:** Programação embarcada (`setup` e `loop`).

---

## 👥 Autores

* **Disciplina:** Lógica de Programação (LOPAL) / Internet das Coisas (IoT)
* **Professores:** Raul Porto Lopes e Paulo Cesar Camargo
* **Alunos:** Gabriel de Araujo Torres (Nº 08)
* **Data:** 12/05/2026

#### Projeto desenvolvido no SENAI A. Jacob Lafer.

<p align="">
  <img src="https://media.tenor.com/RoenXI3n-KsAAAAi/wallace-wells-wallace.gif" width="200" height="auto" />
