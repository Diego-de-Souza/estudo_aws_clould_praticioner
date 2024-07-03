# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: [03/07/2024]
Empresa: Abstergo Industries 
Responsável: Diego de Souza Lima

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Diego de Souza Lima. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- AWS Identity and Access Management (IAM) 
### Descrição medida 1:
O AWS IAM é um serviço que permite gerenciar com segurança o acesso aos serviços e recursos da AWS. Com o IAM, é possível criar e gerenciar usuários e grupos, bem como usar permissões para permitir ou negar o acesso aos recursos da AWS.

### Caso de Uso medida 1:
Uma empresa pode usar o IAM para criar políticas detalhadas que garantem que apenas os usuários autorizados tenham acesso a determinados recursos. Por exemplo, um desenvolvedor pode ter permissões para acessar e modificar os recursos de um ambiente de desenvolvimento, enquanto um administrador de sistemas pode ter permissões para acessar e gerenciar recursos em ambientes de produção. Além disso, o uso de autenticação multifator (MFA) pode ser implementado para aumentar a segurança dos acessos, exigindo não apenas uma senha, mas também um segundo fator de autenticação.

Medida 2: 
- AWS Key Management Service (KMS)
### Descrição medida 2:
O AWS KMS é um serviço que permite criar e gerenciar chaves de criptografia para proteger os dados armazenados nos serviços da AWS. O KMS integra-se a muitos outros serviços da AWS para facilitar o uso de criptografia de dados em repouso e em trânsito.

### Caso de Uso medida 2:
Uma empresa pode usar o KMS para criptografar dados sensíveis armazenados em bancos de dados como o Amazon RDS ou em objetos no Amazon S3. Por exemplo, informações financeiras ou dados de clientes podem ser protegidos usando chaves gerenciadas pelo KMS. Além disso, as chaves podem ser rotacionadas automaticamente para cumprir políticas de segurança internas ou regulamentares.

Medida 3: 
- AWS CloudTrail
### Descrição medida 3:
O AWS CloudTrail é um serviço que permite monitorar e registrar a atividade da conta da AWS. Ele oferece um histórico de ações realizadas por um usuário, função ou serviço da AWS, ajudando na auditoria e na conformidade com normas de segurança.

### Caso de Uso medida 3:
Uma empresa pode usar o CloudTrail para acompanhar todas as atividades realizadas nos seus recursos AWS. Por exemplo, se houver uma tentativa de acesso não autorizado a um recurso sensível, o CloudTrail pode registrar essa atividade e alertar os administradores. Além disso, a empresa pode usar esses registros para investigar incidentes de segurança, realizar auditorias de conformidade e melhorar a visibilidade sobre as operações de TI.


## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries* tem como esperado *AWS Identity and Access Management, AWS Key Management Service, AWS CloudTrail*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Amazon Web Service, AWS. Documentação Gerencie com segurança as identidades e o acesso a serviços e recursos da AWS: AWS Identity and Access Management.2024.
Disponivel em: https://aws.amazon.com/pt/iam/

Amazon Web Service, AWS. Documentação Crie e controle chaves usadas para criptografar ou assinar digitalmente seus dados: AWS Key Management Service.2024.
Disponivel em: https://aws.amazon.com/pt/kms/

Amazon Web Service, AWS. Documentação Acompanhe a atividade do usuário e o uso da API na AWS e em ambientes híbridos e multinuvem: AWS CloudTrail.2024.
Disponivel em: https://aws.amazon.com/pt/cloudtrail/

Assinatura do Responsável pelo Projeto:

Diego de Souza Lima