# SOLID
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/01.png">
</div>
<br>

<p align="justify">&emsp;<i>SOLID</i> é um acrônimo criado por Michael Feathers, após observar que cinco princípios da orientação a objetos e design de código — Criados por Robert C. Martin (a.k.a. Uncle Bob) e abordados no artigo The Principles of OOD — poderiam se encaixar nesta palavra.</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
26/10/2020 | 1.0 | Adicionando documento | [@dansousamelo](http://github.com/dansousamelo)

## **SRP — Single Responsibility Principle**
<p align="justify">&emsp;Princípio da Responsabilidade Única — Uma classe deve ter um, e somente um, motivo para mudar. Esse princípio declara que uma classe deve ser especializada em um único assunto e possuir apenas uma responsabilidade dentro do software, ou seja, a classe deve ter uma única tarefa ou ação para executar.</p>
<p align="justify">&emsp;Esse conceito foi amplamente utilizado em nossa aplicação, temos os nossos services, por exemplo, que são responsáveis exclusivamente pelas regras de negócio da aplicação, abaixo podemos ver um exemplo. Cada service possui apenas um único método chamado <i>execute</i>.
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/02.png">
</div>

## **OCP — Open-Closed Principle**
<p align="justify">&emsp;Princípio Aberto-Fechado — Objetos ou entidades devem estar abertos para extensão, mas fechados para modificação, ou seja, quando novos comportamentos e recursos precisam ser adicionados no software, devemos estender e não alterar o código fonte original.</p>

<p align="justify">&emsp;Devemos concentrar nos aspectos essenciais do contexto, abstraindo-os para uma interface. Se as abstrações são bem definidas, logo o software estará aberto para extensão.
</p>

<p align="justify">&emsp;Em nosso projeto utilizamos de interfaces para definir os métodos para conexão com banco de dados assim como para testar os nossos services. Temos:
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/03.png">
</div>

<p align="justify">&emsp;Se quisermos adicionar mais um método relacionado ao usuário basta acrescentá-lo nessa interface e implementá-lo de fato para se conectar ao banco e para possibilitar a execução de testes unitários. Abaixo temos o método findById, por exemplo, implementado em 2 lugares diferentes, ambos implementam a interface acima.
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/04.png">
</div>
<p align="center"><i>Repositório fake, usado para os testes unitários</i></p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/05.png">
</div>
<p align="center"><i>Repositório que se conecta a base de dados</i></p>

## **LSP— Liskov Substitution Principle**
<p align="justify">&emsp;Princípio da substituição de Liskov — Uma classe derivada deve ser substituível por sua classe base.</p>

<p align="justify">&emsp;O princípio da substituição de Liskov foi introduzido por Barbara Liskov em sua conferência “Data abstraction” em 1987. A definição formal de Liskov diz que:
</p>

<p align="justify">&emsp;Se S é um subtipo de T, então os objetos do tipo T, em um programa, podem ser substituídos pelos objetos de tipo S sem que seja necessário alterar as propriedades deste programa.
</p>

<p align="justify">&emsp;Em nosso sistema temos que nosso services não conhecem o formato final da estrutura que armazena os dados. Sendo que a estrutura que armazena os dados pode ser substituído desde que seja implementado os métodos da interface abaixo.
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/06.png">
</div>

## **ISP — Interface Segregation Principle**
<p align="justify">&emsp;Princípio da Segregação da Interface — Uma classe não deve ser forçada a implementar interfaces e métodos que não irão utilizar.
Esse princípio basicamente diz que é melhor criar interfaces mais específicas ao invés de termos uma única interface genérica.
</p>

<p align="justify">&emsp;Em nosso sistema temos 2 interfaces, uma para usuário e outra para funcionários desses usuários, ambas possuem métodos em comum mas possuem diferenças entre si.
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/07.png">
</div>
<p align="center"><i>IUserRepository</i></p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/08.png">
</div>
<p align="center"><i>IEmployeeRepository</i></p>

## **DIP — Dependency Inversion Principle**
<p align="justify">&emsp;Princípio da Inversão de Dependência — Dependa de abstrações e não de implementações.</p>

<p align="justify">&emsp;De acordo com Uncle Bob, esse princípio pode ser definido da seguinte forma:
</p>

  * <p align="justify">Módulos de alto nível não devem depender de módulos de baixo nível. Ambos devem depender da abstração.
  </p>
  * <p align="justify">Abstrações não devem depender de detalhes. Detalhes devem depender de abstrações.
  </p>

<p align="justify">&emsp;Em nosso código fazemos isso para se conectar com o banco de dados através do construtor da classe como podemos ver abaixo:
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/09.png">
</div>
<p align="justify">&emsp;Essas duas variáveis privadas serão utilizadas no decorrer do service, observe abaixo:
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/solid/10.png">
</div>

<p align="justify">&emsp;Estamos criptografando a senha e criando o usuário passando apenas parâmetros, sem instanciar as classes.
</p>

## **Referências**

 * <p align="justify">DA PAIXÃO, João Roberto. O que é SOLID: O guia completo para você entender os 5 princípios da POO. [S. l.], 9 jan. 2019. Disponível em: https://medium.com/desenvolvendo-com-paixao/o-que-%C3%A9-solid-o-guia-completo-para-voc%C3%AA-entender-os-5-princ%C3%ADpios-da-poo-2b937b3fc530. Acesso em: 23 out. 2020.</p>