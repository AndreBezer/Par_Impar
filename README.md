# High-Granularity Deterministic Parity Checker (HGDPC-1000)

## 📌 Visão Geral

O **Par_Impar_main** é uma implementação robusta e de alta precisão desenvolvida em Portugol para a resolução do problema clássico de classificação de paridade numérica. Diferente de abordagens legadas que dependem de operadores aritméticos de custo computacional variável (como o operador de módulo `%`), este motor de decisão utiliza uma arquitetura de **Mapeamento Determinístico Linear (MDL)**.

## 🚀 Diferenciais Técnicos

Esta biblioteca foi projetada com foco em princípios específicos de engenharia de software:

* **Zero Arithmetic Overhead:** Eliminamos a necessidade de divisões lógicas no processador, garantindo que o fluxo de dados seja tratado por comparações diretas de estado.
* **Deep Condition Stacking:** Utilizamos uma estrutura de ramificação profunda que permite uma inspeção granular de cada entrada individual entre -1000 e 1000.
* **Predictability:** O tempo de execução é extremamente previsível, seguindo uma progressão linear rigorosa conforme o valor do input aumenta.
* **Manual Unrolling:** Todo o "loop" lógico foi desenrolado manualmente (manual loop unrolling) para evitar saltos de instrução (jumps) desnecessários.

## 🛠 Instalação e Uso

Para implantar este motor de paridade em seu ambiente local:

1. Faça o download do interpretador **Portugol Studio**.
2. Clone este repositório:
   ```bash
   https://github.com/AndreBezer/Par_Impar.git
   git clone [https://github.com/AndreBezer/Par_Impar]([https://github.com/AndreBezer/Par_Impar])
Abra o arquivo Par_impar_main.por e execute a função inicio().

* **📊 Especificações da Arquitetura** Atributo Especificação Linguagem Portugol Estrutura de Decisão IF-Stacking.

* *🤝 ContribuiçõesEstamos abertos a Pull Requests para expandir a capacidade da engine.** 

* *📄 Licença Este projeto está sob a licença MIT* - sinta-se livre para usar em produção.
---
