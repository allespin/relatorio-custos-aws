# Relatório de implementação de serviços AWS

Data: 29 de Maio de 2026

Empresa: Zippy Farma

Responsável: Iury Guedes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Zippy Farma, realizado por Iury Guedes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- AWS Cost Explorer & AWS Budgets
- Monitoramento e Controle Orçamentário Avançado
- Implementação de painéis visuais para monitorar os custos diários e configuração de alertas automatizados via e-mail. Caso os gastos com serviços ultrapassem 80% do teto estimado para o mês, a equipe de TI é notificada imediatamente para mitigar desperdícios.

Etapa 2: 
- Amazon EC2 Auto Scaling
- Dimensionamento Elástico de Infraestrutura Computacional
- Configuração de políticas de escalonamento dinâmico para os servidores de aplicação. O sistema reduz automaticamente o número de instâncias EC2 activas durante períodos de baixa demanda (como madrugadas e finais de semana), garantindo que a empresa pague apenas pelo poder computacional estritamente necessário.

Etapa 3: 
- Amazon S3 Lifecycle Policies
- Otimização Automatizada de Ciclo de Vida de Armazenamento
- Criação de regras automatizadas para mover arquivos de logs e backups antigos (com mais de 30 dias de inatividade) da classe S3 Standard para o S3 Glacier Deep Archive. Isso reduz o custo do Gigabyte armazenado em até 75% para dados que raramente precisam ser acessados.

## Conclusão
A implementação de ferramentas na empresa Zippy Farma tem como esperado uma redução estimada de 25% a 35% nos gastos de infraestrutura em nuvem já no primeiro mês, eliminando gargalos de recursos ociosos e trazendo previsibilidade financeira. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
- Documentação de Boas Práticas do AWS Cost Optimization Pillar.
- Links de referência do AWS Architecture Center.

Assinatura do responsável pelo projeto:

Iury G. Guedes
