# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 12/08/2024
Empresa: Abstergo Industries 
Responsável: Guilherme Ardito   

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsável pelo projeto]. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: Implementação do AWS Identity and Access Management (IAM)
- Descrição de caso de uso: AWS IAM foi implementado para gerenciar o acesso aos recursos da AWS de forma segura e controlada. Foi criado um conjunto de políticas de acesso baseadas em funções, permitindo que os colaboradores acessem apenas os recursos necessários para suas funções específicas. Além disso, foram configuradas senhas complexas, autenticação multifator (MFA) para acessos privilegiados e a rotação regular das credenciais, mitigando riscos de acesso não autorizado.

Medida 2: Configuração de AWS CloudTrail para Auditoria de Segurança
- Descrição de caso de uso: AWS CloudTrail foi configurado para monitorar e registrar todas as atividades de API na conta da AWS da Abstergo Industries. Essa medida permite que a empresa rastreie ações realizadas pelos usuários, detecte atividades suspeitas e realize auditorias de segurança. As trilhas de auditoria foram configuradas para serem armazenadas em um bucket Amazon S3 com criptografia ativada, garantindo a integridade e a segurança dos logs.

Medida 3: Implementação de AWS Shield e AWS WAF para Proteção contra Ataques DDoS
- Descrição de caso de uso: Para proteger a infraestrutura web da Abstergo Industries contra ataques de negação de serviço (DDoS), foram implementados AWS Shield e AWS WAF. AWS Shield oferece proteção automática contra ataques DDoS, enquanto AWS WAF foi configurado para filtrar tráfego malicioso, bloqueando requisições de IPs suspeitos e protegendo as aplicações web contra vulnerabilidades comuns como injeção de SQL e scripts entre sites (XSS).


## Conclusão
A implementação dessas medidas de segurança na Abstergo Industries resultou em um aumento significativo na proteção dos recursos da empresa, mitigando riscos de acesso não autorizado, garantindo a rastreabilidade das ações e protegendo a infraestrutura contra ataques externos. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais a segurança dos processos da empresa.

## Anexos

Políticas IAM configuradas
Logs de auditoria do CloudTrail
Configurações do AWS WAF e AWS Shield

Assinatura do Responsável pelo Projeto:

Guilherme Ardito