# ☁️ AWS Step Functions - Orquestração de Workflows Automatizados

Este repositório foi criado como parte do **laboratório prático da formação AWS Cloud Foundations**, com o objetivo de consolidar o aprendizado sobre **orquestração de serviços e automação de fluxos de trabalho (workflows)** utilizando o **AWS Step Functions**.

---

## Objetivo do Laboratório

O laboratório tem como propósito **compreender e aplicar o conceito de orquestração de serviços** na nuvem AWS.  
O **AWS Step Functions** permite integrar diferentes serviços da AWS (como Lambda, S3, DynamoDB, SNS, SQS etc.) em **fluxos de trabalho automatizados e visuais**, reduzindo a necessidade de código (*Low-Code*).

Este projeto demonstra como o Step Functions pode:
- Coordenar a execução de múltiplos serviços.
- Implementar decisões lógicas (Choice States).
- Automatizar tarefas e rotinas recorrentes.
- Simplificar o monitoramento e a manutenção de processos.

---

##  Conceitos Fundamentais

| Conceito | Descrição |
|-----------|------------|
| **Step Functions** | Serviço de orquestração que conecta componentes de aplicações distribuídas e microserviços. |
| **State Machine (Máquina de Estado)** | Representa o fluxo de trabalho, com etapas (estados) conectadas entre si. |
| **Task (Tarefa)** | Uma ação individual do fluxo (ex: executar Lambda, consultar S3, enviar mensagem SNS). |
| **Choice (Escolha)** | Estado de decisão que direciona o fluxo conforme condições lógicas. |
| **Pass (Passagem)** | Estado que apenas passa dados adiante, sem executar tarefas. |
| **Wait (Espera)** | Introduz um atraso temporário antes da próxima etapa. |
| **Parallel (Paralelo)** | Executa múltiplas ramificações simultaneamente. |
| **Fail / Succeed** | Define a conclusão do fluxo, seja com sucesso ou falha. |

---

## Estrutura do Modelo de Workflow 

O workflow tem como objetivo demonstrar o funcionamento do Map State no AWS Step Functions, permitindo processar múltiplos arquivos armazenados no S3 de forma paralela.

Observação: O workflow foi criado a partir de um modelo da AWS, apenas para estudo e compreensão do funcionamento do Map State e Step Functions, mas tem como criar seu próprio fluxo de trabalho do zero.

## Conclusão

Este laboratório demonstrou o uso prático de **modelos pré-criados do AWS Step Functions**, especificamente o **“Map Distributed”**, para orquestrar **processamento paralelo de dados**.  

O Step Functions provou ser uma ferramenta poderosa para **automação, escalabilidade e monitoramento de workflows serverless**, permitindo integrar facilmente múltiplos serviços da AWS com lógica de decisão e paralelismo controlado.

> “O fluxo de dados ganha vida quando a automação encontra a escalabilidade — e o Step Functions é a ponte entre o código e o resultado.”
