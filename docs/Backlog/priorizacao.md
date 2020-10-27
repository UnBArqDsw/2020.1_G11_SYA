# Priorização

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/diagramas/elementos.png">
</div>

<p align="justify">&emsp;O MoSCoW é uma técnica de priorização de requisitos, onde todos os requisitos são analisados e, a cada um é mensurado um grau de importância, dado por uma letra das 4 palavras que compõem o MoSCoW:</p>

* <p align="justify"><b>Must:</b> são as funcionalidades mais importantes do projeto, aquelas que mais agregam valor e que, sem elas, o projeto não pode ser entregue.</p>

* <p align="justify"><b>Should:</b> funcionalidades que também são importantes, mas não necessárias para entrega (pelo menos inicialmente).</p>

* <p align="justify"><b>Could:</b> funcionalidades desejáveis, que agregam valor ao produto e melhoram a experiência com o cliente.</p>

* <p align="justify"><b>Would:</b> todas as funcionalidades que não serão desenvolvidas no momento pois não agregam valor ao produto.</p>

<p align="justify">&emsp;Essa técnica será utilizada para checar a importância de cada requisito levantado da aplicação Rico. A metodologia utilizada para o levantamento de priorização de requisitos é análoga à técnica de Planning poker onde cada integrante dá um valor à um requisito e então é comparado com o valor de prioridade dos outros membros da equipe. O valor do requisito é definido quando todos os integrantes da equipe entram em consenso.
</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
22/09/2020 | 1.0 | Adicionando priorização | [@dansousamelo](http://github.com/dansousamelo), [@lbrunofidelis](https://github.com/pedroMiranda7410), [@tmcstiago](https://github.com/tmcstiago)|

## **Requisitos Funcionais**
Identificador | Descrição | MOSCOW
---- | ----------- | ------ |
RF01 | O prestador de serviço deve ser capaz de criar uma conta | M |
RF02 | O prestador de serviço  deve ser capaz de logar em sua conta | M |
RF03 | O prestador de serviço  deve ser capaz de excluir sua conta | w |
RF04 | O prestador de serviço  deve ser capaz de editar sua conta | S |
RF05 | O prestador de serviço deve ser capaz de alterar sua senha | S |
RF06 | O prestador de serviço deve ser capaz de recuperar a senha, caso esqueça | C |
RF07 | O prestador de serviços deve ser capaz cadastrar um agendamento | M |
RF08 | O prestador de serviços deve ser capaz de cancelar os agendamentos ativos | S |
RF09 | O sistema deve ser capaz de adicionar o horário de funcionamento do estabelecimento | M |
RF10 | O sistema deve ser para empresas ou prestadores de serviços maiores de 18 anos. | W |
RF11 | O sistema deve ser capaz de mostrar o calendário do estabelecimento. | M |
RF12 | O prestador de serviços deve ter a possibilidade de cadastrar o valor do serviço | S |
RF13 | O prestador de serviços deve ser capaz de inserir a descrição de um serviço | C |
RF14 | O sistema deve ser capaz de listar, cadastrar e excluir um funcionário | S |
RF15 | O sistema deve ser capaz de listar, cadastrar e excluir um serviço | M |
RF16 | O sistema deve ser capaz de mostrar para um funcionário a agenda diária, semanal e mensal. | S |
RF17 | O sistema deve possuir realizar restrição de acesso para funcionários. | S |
RF18 | O sistema deve informar o tempo de duração de um determinado serviço para o usuário. | M |
RF19 | O sistema deve gerar um link com os horários disponíveis para agendamento de um prestador de serviços| M |

## **Requisitos Não Funcionais**
Identificador | Descrição | MOSCOW
---- | ----------- | ------ |
RF01 | O link gerado deve ter uma validade. | W |

## Referências
 * <p align="justify">SERRANO, Maurício; SERRANO, Milene. Aula de elicitação, modelagem e análise de requisitos. Requisitos de Software Aula 7, [S. l.], p. 31-40, 28 set. 2020.
</p>
