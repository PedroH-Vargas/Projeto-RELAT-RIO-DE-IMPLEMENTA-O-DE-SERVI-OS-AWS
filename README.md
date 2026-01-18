# Projeto-RELAT-RIO-DE-IMPLEMENTA-O-DE-SERVI-OS-AWS
O projeto de implementação de ferramentas foi dividido em 3 etapas, focadas em armazenamento, computação e banco de dados.

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 17 de Janeiro de 2026
Empresa: Abstergo Industries 
Responsavel: [nome do responsÃ¡vel pelo projeto]

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsavel pelo projeto]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuiçãoo de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (com foco em Intelligent-Tiering)
- Otimização de custos de armazenamento.
- Armazenamento dos arquivos de vídeo editados da empresa (60-80GB). A utilização da classe Intelligent-Tiering permite que arquivos não acessados por mais de 30 dias sejam movidos automaticamente para camadas de custo menor, sem necessidade de intervenção manual ou taxas de recuperação, ideal para padrões de acesso desconhecidos.

Etapa 2: 
- Amazon EC2 Spot Instances
- Redução de custos em processamento de logs e renderização.
- Utilização de instâncias Spot para as tarefas de processamento de logs e renderização de vídeo. Como essas tarefas podem ser interrompidas e retomadas, o uso de instâncias Spot oferece uma economia de até 90% em comparação ao preço de instâncias On-Demand.

Etapa 3: 
- Amazon RDS (Relational Database Service)
- Automação e redução de overhead operacional.
- Migração dos bancos de dados MySQL/PostgreSQL locais para o RDS. A ferramenta reduz custos indiretos ao automatizar backups, patches de segurança e redundância (Multi-AZ), permitindo que a equipe de TI foque em inovação e não em manutenção de hardware e software básico.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado uma redução significativa na fatura mensal da AWS e o aumento da durabilidade dos dados. O uso de armazenamento inteligente e instâncias de baixo custo aumentará a eficiência e a produtividade da empresa, garantindo escalabilidade para os grandes volumes de vídeo processados.

## Anexos

Planilha de estimativa de custos (AWS Pricing Calculator).
Diagrama de arquitetura da solução.
Guia de boas práticas para gerenciamento de Snapshots EBS.

Assinatura do ResponsÃ¡vel pelo Projeto: Pedro Henrique

Pedro Henrique Vargas