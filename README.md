# Relatório de Implementação de Serviços AWS

Data: 11/08/2025<br>
Empresa: Abstergo Industries<br>
Responsável: Carmen Oliveira

## Introdução
Este relatório apresenta uma análise estratégica para a adoção de três serviços fundamentais da Amazon Web Services (AWS) com o objetivo principal de gerar uma redução de custos significativa e imediata para a Abstergo Industries. A proposta consiste na migração de cargas de trabalho de computação, armazenamento de objetos e bancos de dados relacionais para os serviços Amazon EC2, Amazon S3 e Amazon RDS, respectivamente.

A implementação destes serviços permitirá que a empresa substitua despesas de capital (CAPEX) com hardware por despesas operacionais (OPEX) variáveis, aumente a eficiência operacional, a escalabilidade e a segurança da infraestrutura de TI.

## Descrição do Projeto
Este documento detalha a recomendação técnica para a implementação de serviços da AWS na infraestrutura da Abstergo Industries. O objetivo é otimizar a alocação de recursos de TI, com foco na redução de custos operacionais e na modernização do ambiente tecnológico. Para isso, foram selecionados três serviços que oferecem o maior impacto inicial.

## Etapa 1: 
- Amazon EC2 (Elastic Compute Cloud)

Foco do Serviço: Oferecer capacidade computacional flexível, com destaque para elasticidade, escalabilidade, alta disponibilidade, confiabilidade e controle de custos.

Descrição do Caso de Uso: Inicialmente, a adoção do EC2 na empresa possibilitará uma redução de custos imediata com o provisionamento de hardware (servidores, equipamentos de rede). A medida é eficaz tanto para a demanda comum quanto, principalmente, para demandas excepcionais, como períodos promocionais, picos sazonais ou processamentos internos pontuais.

A escalabilidade e a elasticidade automáticas permitem não só economizar em períodos de baixa atividade, mas também aumentar a capacidade de forma instantânea. A alta disponibilidade e a confiabilidade, por sua vez, garantem que os serviços estarão sempre operacionais, com um tempo de inatividade ínfimo se comparado ao risco de uma infraestrutura privada.

A redução de custos é uma consequência direta do modelo pay-as-you-go (pague pelo que usar), pois a empresa pagará apenas pelos recursos e pelo tempo que efetivamente os utilizar.

## Etapa 2
- Amazon S3 (Simple Storage Service)

Foco do Serviço: O S3 é focado no armazenamento de objetos, sendo ideal para dados que não exigem acesso em tempo real. Os casos de uso incluem o armazenamento de: documentos, backups, dados de pesquisas, imagens, logs, arquivos de mídia e dados de aplicações.

Descrição do Caso de Uso: A adoção do S3 pela nossa empresa possibilitará eliminar outra parte da infraestrutura física, ao mesmo tempo que reforça a segurança contra acessos indevidos.

Com seus recursos de backup automático e recuperação de desastres, o S3 reduz a necessidade de um profissional dedicado exclusivamente a essa tarefa. Além disso, sua alta confiabilidade o torna excelente para o armazenamento de dados com fins regulatórios. Por exemplo, podemos guardar dados de medicamentos desenvolvidos em diferentes países, mantendo a conformidade com as legislações locais e acessando facilmente o histórico de versões de cada arquivo.

## Etapa 3
- Amazon RDS (Relational Database Service)

Foco do Serviço: O foco do RDS é simplificar a configuração, a operação e a escalabilidade de bancos de dados relacionais. Ele oferece suporte aos mais diversos sistemas, como MySQL, PostgreSQL, Oracle e SQL Server, enquanto automatiza rotinas de administração (configuração, atualizações de segurança e backups), com a clara vantagem da escalabilidade e da alta disponibilidade.

Descrição do Caso de Uso: Ao migrar para o Amazon RDS, o benefício imediato é a redução de custos com a infraestrutura de servidores, suas manutenções e o licenciamento de software. Outro fator que agrega grande valor é a segurança, pois os bancos de dados operam em redes privadas e possuem criptografia para dados em trânsito e em repouso.


## Conclusão e Próximos Passos
A adoção dos serviços Amazon EC2, S3 e RDS representa um passo estratégico fundamental para a Abstergo Industries alinhar sua infraestrutura de TI com os objetivos de negócio, promovendo agilidade, segurança e uma drástica otimização de custos.

## Fontes
https://aws.amazon.com/pt/s3/?did=ft_card2&trk=ft_s3
https://aws.amazon.com/pt/ec2/?did=ft_card2&trk=ft_ec2
https://aws.amazon.com/pt/rds/?did=ft_card2&trk=ft_rds
