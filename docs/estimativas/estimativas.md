# Estimativas

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="../assets/estimativas/cost.svg">
</div>

## Histórico de Versões

| Data | Versão | Descrição | Autor(es) |
| ---- | ------ | --------- | --------- |
| 08/09/2020 | 1.0 | Criação do documento | Lucas Medeiros ([@medeirosLucas](https://github.com/medeiroslucas)) e Tiago Miguel ([@tmcstiago](https://github.com/tmcstiago)) |
| 10/09/2020 | 1.1 | Formatando documento | Daniel Sousa ([@dansousamelo](https://github.com/dansousamelo))  e Luis Bruno ([@lbrunofidelis](https://github.com/lbrunofidelis)) |

## Estimativa de Custo
<p align="justify">&emsp;
  Valores fixos mensais se alongam por 4 meses que é o prazo do projeto.
</p>

### Custo de Mão de Obra
<p align="justify">&emsp;
  Para a mão de obra foi levado em consideração as 6 pessoas que estão participando do projeto, sendo contratadas como Desenvolvedores Júnior dentro do projeto. Com o levantamento dentro do Site Glassdoor, chegou-se a um valor médio de R$ 2.588,00 como salário médio dessa categoria em Brasília. Foi considerado 4 meses de projeto que é o tempo que irá levar a disciplina.
</p>

| Papel                  | Salário             | Quantidade de pessoas | Tempo (meses) | Preço total  |
|------------------------|---------------------|-----------------------|---------------|--------------|
| Desenvolvedores Júnior | R$ 2.588,00 mensais | 6                     | 4             | R$ 62.112,00 |

### Logística e Aquisições

<p align="justify">&emsp;
  Para o levantamento de custos foram considerados computadores com a especificação de um processador i7, 1 Tb de Espaço de Armazenamento, 8 Gb de memória RAM, todos os notebooks da marca Lenovo com o custo até o dia 21/03/2020 de R$ 3.894,05.
</p>

<p align="justify">&emsp;
  Além disso, o espaço de Coworking considerado foi calculado para o uso em 86 dias úteis por 6 horas por dia de trabalho, internet e luz estão inclusos no valor da hora do uso do Coworking.
</p>

<p align="justify">&emsp;
  Já o Marketing Digital foi levado em consideração em 4 meses, nas plataformas do Facebook, Twitter e Instagram.
</p>

| Recurso                          | Preço Unitário    | Quantidade      | Preço total  |
|----------------------------------|-------------------|-----------------|--------------|
| Notebooks                        | R$ 3.894,05       | 6               | R$ 23.364,30 |
| Espaço Coworking para 10 pessoas | R$ 36,00 hora     | 6 horas por dia | R$ 18.576,00 |
| Marketing digital                | R$ 441,15 mensais | 4 meses         | R$ 1.765,80  |

### Infraestrutura

<p align="justify">&emsp;
  Considerando uma cultura de DevOps, popular atualmente, e tecnologias populares para deploy e orquestração de aplicações conteinerizadas, como o Kubernetes, faz-se necessário uma infraestrutura capaz de sustentar diferentes ambientes e que seja tolerante a falhas.
</p>

<p align="justify">&emsp;
  Vamos considerar então três máquinas virtuais, em um serviço de computação em nuvem e com uma configuração mínima capaz de rodar serviços e conteiners docker.
</p>

<p align="justify">&emsp;
  No site da Digital Ocean uma máquina com 2Gb de mémoria RAM, 1 núcleo de CPU e 50Gb de armazenamento está custando $5 dólares, considerando o dólar custando R$5,36 reais, o custo final de uma máquina seria R$ 26,80 reais mensais.
</p>

| Recurso         | Preço Unitário | Quantidade | Preço total |
|-----------------|----------------|------------|-------------|
| Máquina virtual | R$ 30,00       | 3          | R$ 90,00    |

<p align="justify">&emsp;
  Obs: esta sendo considerado o cotação de 1 dólar a R$ 6,00 devido a previsão que está sendo realizada do docker + taxas do cartão de crédito.
</p>

### Custos Totais

<p align="justify">&emsp;
  Fazendo as somas de todos os tipos de custos, chegamos aos custos de todo o projeto ao longo dos 4 meses de execução.
</p>

| Tipo de custo          | Valor         |
|------------------------|---------------|
| Custo de mão de obra   | R$ 62.112,00  |
| Logística e Aquisições | R$ 43.706,10  |
| Infraestrutura         | R$ 90,00      |
| TOTAL                  | R$ 105.908,10 |

## Riscos de Alto nível

| Risco                                       | Impacto                    | Ação preventiva                                                           | Ação corretiva                                                                                     |
|---------------------------------------------|----------------------------|---------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Defeito no Equipamento                      | Atraso                     | Manutenção periódica                                                      | Pareamento na equipe                                                                               |
| Equipe não adaptada com tecnologia          | Produto não ser concluído  | Treinamentos                                                              | Pareamento e disposição de ajuda externa, se necessário, limitando-se apenas a encontrar a solução |
| Abandono da disciplina por membro da equipe | Sobrecarga da equipe       | Estar sempre em comunicação ativa para que os membros se sintam motivados | Revisão do projeto e replanejamento da entrega                                                     |
| Problemas de comunicação                    | Problemas de gerenciamento | Estar sempre alinhado à equipe quanto às atividades e dificuldades        | Verificar o que causou a falha de comunicação para efetivamente integrar a equipe                  |
| Produto não atende necessidade do cliente   | Baixa adesão de usuários   | Avaliar sempre as métricas de valor para tomar decisões rapidamente       | Refinar o entendimento de valor do cliente                                                         |
| Membro faltante nas reuniões semanais       | Falha de comunicação       | Definir datas que a maioria dos membros estão disponíveis                 | Alinhar o membro sobre a reunião                                                                   |