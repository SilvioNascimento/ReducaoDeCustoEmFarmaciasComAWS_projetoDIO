# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/02/2026
Empresa: Abstergo Industries
Responsável: Silvio Nascimento Ribeiro

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por Silvio Nascimento Ribeiro. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- **EC2 - Elastic Computer Cloud**
- Oferece capacidade computacional segura e redimensionável através da definição do uso e modalidades específicas de instâncias (compõe CPU, memória, rede, armazenamento e sistema operacional) conforme a necessidade
- Utilizar o EC2 da AWS para desenvolver um servidor virtual pessoal da empresa Abstergo Industries, o configurando tanto para aceitar aplicações da própria empresa quanto a segurança e as redes e gerenciar o armazenamento da mesma. Desta forma pode evitar de realizar gastos astronômicos de criar um próprio servidor, evitando as despesas de espaço físico e equipamentos conforme a evolução das demandas.

Etapa 2:

- **Amazon EC2 AutoScaling**
- Provê escalabilidade horizontal para seus serviços e melhora a tolerância a falhas com identificação de instâncias, gerenciando melhor os gastos dos serviços contratados da AWS
indisponíveis e implantação multi-AZ
- Definir a quantidade mínima e máxima das coleções de instâncias, chamadas de grupos de Auto Scaling. Assim, a sua aplicação nunca use menos e mais instâncias que foi configurado como mínimo e máximo, respectivamente.
Além disso, pode especificar várias zonas de disponibilidade, proporcionando para sua aplicação contra falhas em um único local.

Etapa 3:

- **EBS – Elastic Block Store**
- Fornece recursos de armazenamento em blocos escaláveis ​​e de alto desempenho que podem ser usados ​​com instâncias do Amazon Elastic Compute Cloud (Amazon EC2). Pode usufruir do armazenamento e backups pontuais dos dados.
- Configurar o tipo de armazenamento como HDD devido ao uso intensivo de throughput, armazenando dados da empresa como produtos em estoque e produtos que já foram comprados por exemplo. E também pode realizar backups nos dados com fins de restauração do volume ou migrar dados entre contas da AWS, regiões da AWS ou zonas de disponibilidade.

---

## Conclusão

A implementação de ferramentas na empresa *Abstergo Industries elimina a necessidade de altos investimentos em infraestrutura física própria (Data Center local), utilizar instâncias necessárias para aplicação e ter a possibilidade de armazenamento de dados para uso intensivo e realização de backups*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- O que é o Amazon EC2? Disponível em: <https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html>

- Computação em AWS. Disponível em: <https://hermes.dio.me/files/assets/b4141d39-8072-4853-a589-b9fa7721fe2a.pdf>

- O que é o Amazon EC2 Auto Scaling? Disponível em: <https://docs.aws.amazon.com/pt_br/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html>

- O que é o Amazon Elastic Block Store? Disponível em: <https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html>

- Armazenamento e Banco de Dados. Disponível em: <https://hermes.dio.me/files/assets/f240fada-ad63-4d56-871a-cded3e51b308.pdf>

---

Assinatura do Responsável pelo Projeto:

<ins>Silvio Nascimento Ribeiro</ins>
