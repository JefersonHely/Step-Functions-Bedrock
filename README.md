# Assistente de Delivery com AWS Step Functions e Bedrock

Este projeto demonstra como construir um Assistente de Delivery utilizando AWS Step Functions, AWS Lambda, AWS DynamoDB e AWS Bedrock. O sistema orquestra o fluxo de processamento de pedidos, gerencia o status dos pedidos e fornece um chatbot com inteligência artificial para interações com os clientes.

## Funcionalidades

- **Gerenciamento de Pedidos**: Permite que os clientes criem e acompanhem seus pedidos.
- **Processamento de Pedidos**: Orquestra o processamento de pedidos desde a criação até a entrega usando AWS Step Functions.
- **Assistente com IA**: Utiliza o AWS Bedrock para fornecer um chatbot com inteligência artificial para interações com os clientes.
- **Sistema de Notificações**: Envia atualizações sobre o status dos pedidos para os clientes via AWS SNS.
- **Arquitetura Escalável**: Construído usando componentes serverless que escalam automaticamente conforme a demanda.
