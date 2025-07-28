# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 15/07/2025
Empresa: Abstergo Industries
Responsável: Wesley Silveira dos Santos

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Wesley Silveira dos Santos. O objetivo do projeto foi elencar e implementar 3 serviços da AWS com foco na redução de custos imediatos, sem comprometer a performance e a segurança da infraestrutura tecnológica da empresa.

## Descrição do Projeto
O projeto de implementação foi dividido em 3 etapas principais, cada uma com foco em uma ferramenta específica da AWS voltada para economia e otimização de recursos.

Etapa 1:
Nome da ferramenta: Amazon S3 Intelligent-Tiering

Foco da ferramenta: Armazenamento automático com otimização de custos

Descrição de caso de uso:
A empresa possuía grandes volumes de dados armazenados em camadas padrão do Amazon S3, gerando altos custos. Foi implementado o S3 Intelligent-Tiering para migrar automaticamente objetos não acessados com frequência para camadas de armazenamento mais baratas, sem impacto na performance. A medida representou uma economia estimada de 30% nos custos de armazenamento.

Etapa 2:
Nome da ferramenta: AWS Lambda

Foco da ferramenta: Execução de código sob demanda (Serverless)

Descrição de caso de uso:
Diversas funções automatizadas estavam sendo executadas em instâncias EC2 subutilizadas. Elas foram migradas para o AWS Lambda, permitindo que o código fosse executado apenas sob demanda, eliminando custos fixos com servidores e otimizando o consumo de recursos.

Etapa 3:
Nome da ferramenta: AWS Compute Optimizer

Foco da ferramenta: Otimização de instâncias EC2

Descrição de caso de uso:
Com o auxílio do Compute Optimizer, foi realizada uma análise completa das instâncias EC2 em produção, identificando recursos superdimensionados. Com base nas recomendações, as instâncias foram redimensionadas, resultando em uma redução média de 25% nos custos mensais com computação.

## Conclusão
A implementação dos serviços da AWS na empresa Abstergo Industries resultou em redução imediata de custos operacionais, além de trazer mais eficiência, flexibilidade e escalabilidade à infraestrutura da organização. Recomenda-se a continuidade da utilização dessas ferramentas, bem como a exploração contínua de novos serviços da AWS voltados para automação, segurança e economia.

## Anexos
[Manual de migração S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html?utm_source=chatgpt.com)

[Relatório de uso pré e pós-Lambda](https://docs.aws.amazon.com/compute-optimizer/latest/ug/view-lambda-recommendations.html?utm_source=chatgpt.com)

[Relatório do Compute Optimizer com recomendações aplicadas](https://docs.aws.amazon.com/compute-optimizer/latest/ug/what-is-compute-optimizer.html?utm_source=chatgpt.com)

### Responsável
Wesley Silveira dos Santos
