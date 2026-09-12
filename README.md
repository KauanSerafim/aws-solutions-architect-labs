# AWS Solutions Architect – Associate | Laboratórios e Notas de Estudo

Documentação técnica dos laboratórios práticos realizados durante minha preparação para a certificação **AWS Certified Solutions Architect – Associate**, organizados sequencialmente na ordem em que foram realizados.

Cada laboratório documenta os serviços utilizados, as decisões de configuração tomadas e o que cada decisão demonstra em termos de competência técnica. Não é um guia de "como fazer" — é um registro de arquitetura e raciocínio técnico.

## Laboratórios

<!-- LABS_TABLE_START -->

| # | Laboratório | Domínio do SAA | Principais Serviços |
|---|---|---|---|
| 01 | [Observabilidade e Alertas com CloudTrail](labs/01-observabilidade-e-alertas-com-cloudtrail/README.md) | Domínio 1 - Design de Arquiteturas Seguras | CloudTrail, Amazon S3, CloudWatch Logs, IAM, Amazon SNS |
| 02 | [Aplicação WordPress em Alta Disponibilidade](labs/02-aplicacao-wordpress-em-alta-disponibilidade/README.md) | Domínio 2 - Arquiteturas de Alto Desempenho e Resiliência | Amazon VPC, AWS CloudFormation, Amazon RDS Aurora, Amazon EFS, Application Load Balancer, EC2 Auto Scaling |

<!-- LABS_TABLE_END -->

## Estrutura do repositório

```
.
├── labs/                        # um diretório por laboratório, numerado sequencialmente
│   └── NN-nome-do-laboratorio/
│       └── diagrams/            # diagrama (arquitetura.png)
│       ├── README.md            # documentação técnica do laboratório
```

## Sobre

- Certificação em andamento: **AWS Certified Solutions Architect – Associate (SAA-C03)**
- Certificação concluída: **AWS Certified Cloud Practitioner (CLF-C02)**
