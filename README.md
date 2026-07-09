# Projeto: Testes de Aplicativos Móveis (Mobile) com Emulador Android (Sprint 5)

## 📌 Sobre o Projeto
Este projeto prático foi desenvolvido durante o bootcamp de Analista de QA da TripleTen Brasil. O foco central foi realizar a garantia de qualidade do aplicativo móvel "Urban Lunch", validando fluxos completos do usuário (End-to-End) — desde a seleção do local de coleta no mapa até a finalização e feedback do pedido — utilizando um ambiente emulado de smartphone. Todas as falhas críticas encontradas foram integradas e reportadas no Jira.

## 🛠️ Escopo Técnico e Atividades Executadas
* **Configuração de Ambiente Mobile:** Uso e configuração de emuladores móveis (Android Studio / dispositivo emulado Google Pixel 5) para simular o comportamento real do usuário em um smartphone.
* **Design de Testes para Mobile (Checklists):** Estruturação e execução de checklists detalhados focados nas particularidades de interfaces móveis, gestos de toque (taps) e comportamentos de rolagem de tela (scroll).
* **Validação de Fluxos Críticos (E2E):** 
  * **Seleção e Geolocalização:** Testes na lógica do mapa interativo, seleção e cancelamento de pontos de coleta e comportamento do sistema caso o acesso à geolocalização seja negado.
  * **Escolha de Pratos e Carrinho:** Validação de incrementos/decrementos de itens, telas de informações de pratos e comportamento dos botões operacionais como "Avançar".
  * **Checkout e Rastreamento:** Teste das telas de confirmação de pedido, cálculo de custos totais (pratos + entrega), temporizadores da tela de acompanhamento e telas de conclusão ("Receber o pedido").
* **Gestão e Rastreabilidade de Bugs no Jira:** Identificação de bugs visuais e lógicos na interface móvel, com abertura e documentação formal de Bug Reports vinculados à ferramenta de gestão (Tickets `CAM-91` a `CAM-96`).

## 🧰 Ferramentas Utilizadas
* **Ambiente de Emulação:** Android Emulator (Dispositivo Pixel 5)
* **Estruturação de Testes:** Google Sheets
* **Gerenciamento e Bug Tracking:** Jira / Atlassian Ecosystem

## 🔗 Artefatos e Entregáveis deste Projeto
* [Acesse aqui a Planilha Completa do Checklist de Testes Mobile e Links do Jira](https://docs.google.com/spreadsheets/d/1cUJ4u5qLRrAordbjTqcHIThGLls6527vYo-vuNUKWAg/edit?gid=287334773#gid=287334773)
