# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17/10/2023
Empresa: Abstergo Industries
Responsável: Paulo André Carriço Santos

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Paulo André Carriço Santos. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- S3
- Armazenamento e bacup dos dados da Industria
- Garantir a segurança e backup dos arquivos, restrigindo e monitorando o acesso.
  Pretendemos utilizar o S3 como solução de backup dos arquivos. Também utilizaremos criptografia na transporte dos dados tanto no envio como na leitura, e restingiremos o acesso aos documentos de fato apenas as pessoas precisam deles.

Etapa 2:

- EC2
- Servidor para publicação do sistema da empresa
- Hospedar o sistema da empresa de forma escalável e com balanceamento de carga, para garantir a disponibilidade, estabilidade e desempenho do sistema.
  Desta forma não precisaremos ter custos com hardware ou preocupação em termos um local adequado para montagem e manutenção de servidores. Neste cenário aconselhamos a utilização de duas instâncias para efetuar o balanceamento

Etapa 3:

- RDS
- Configuração do Banco de dados do sistema
- Utilizaremos o RDS para publicação do banco de dados postgresql do sistema. Com o intúito de garantir a segurança, replicação e backup dos dados.
  Tento um garantia da integridade das informação em caso de desastre bem como um monitoramento de utilização e permormance das sql que são executadas no sistema.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado segurança dos dados, desempenho e escalabilidade dos sistemas bem como integridade e disponibilidade dos dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa. Podemos citar aqui algumas ferramentas de monitoramento como o CloudTrail, CloudWatch

## Anexos

Estimativa Preço - https://drive.google.com/file/d/10oE1BBelUjTGYqPKmg_LXg9PybR6ukya/view?usp=sharing
Arquitetura S3, EC2, RDS - https://docs.google.com/document/d/1shyq15A5oosqCwa4xyujz6zDlxuvnyJKTOcw6KW-aoE/edit?usp=sharing

Assinatura do Responsável pelo Projeto:

Paulo André Carriço Santos
