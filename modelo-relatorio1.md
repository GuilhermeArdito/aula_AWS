
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 09/08/2024
Empresa: Abstergo Industries 
Responsável: Guilherme Ardito

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Guilherme Ardito. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Nome da ferramenta: Amazon EC2 Spot Instances
- Foco da ferramenta: Redução de custos com computação em nuvem
- Descrição de caso de uso: A empresa optou por utilizar Amazon EC2 Spot Instances, que permitem a execução de instâncias ociosas da AWS a preços reduzidos em comparação com as instâncias sob demanda. Este recurso é particularmente útil para cargas de trabalho flexíveis e tolerantes a interrupções, como processamento em lote, análise de big data e renderização. Ao aproveitar os preços dinâmicos das Spot Instances, a Abstergo Industries conseguiu reduzir significativamente os custos com computação, mantendo a eficiência operacional.

Etapa 2: 
- Nome da ferramenta: AWS Lambda
- Foco da ferramenta: Otimização de custos com execução de código
- Descrição de caso de uso: AWS Lambda permite que a Abstergo Industries execute código em resposta a eventos sem a necessidade de gerenciar servidores. Este serviço foi utilizado para automatizar processos internos, como gerenciamento de logs e processamento de dados, com o benefício de pagar apenas pelo tempo de execução do código. Essa abordagem de "serverless" reduziu a necessidade de manter servidores ativos constantemente, gerando economia de custos.

Etapa 3: 
- Nome da ferramenta: Amazon S3 com política de ciclo de vida
- Foco da ferramenta: Redução de custos com armazenamento
- Descrição de caso de uso: Amazon S3 foi utilizado para armazenamento de dados com a aplicação de políticas de ciclo de vida, que permitem mover automaticamente os dados para classes de armazenamento de custo mais baixo à medida que envelhecem. Por exemplo, dados raramente acessados foram movidos para S3 Glacier, resultando em uma redução considerável nos custos de armazenamento, sem comprometer a disponibilidade e durabilidade dos dados necessários para as operações da empresa.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries gerou benefícios imediatos, como a redução significativa dos custos operacionais e maior flexibilidade nas operações de TI. A adoção de Amazon EC2 Spot Instances, AWS Lambda e Amazon S3 com políticas de ciclo de vida aumentou a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[lista de anexos, como manuais, documentos, planilhas, entre outros]

Assinatura do Responsável pelo Projeto:

[Nome do Responsável pelo Projeto]