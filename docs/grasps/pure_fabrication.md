# Pure Fabrication
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>



## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
25/10/2020 | 1.0 | Adicionando Fabricação Pura | [@lucasqmc](http://github.com/lucasqmc) 

## **Pure Fabrication**
<p align="justify">&emsp;Consiste na criação de uma classe que não representa nenhum conceito no domínio do problema, ela apenas funciona como uma classe prestadora de serviços, e é projetada para que possamos ter um baixo acoplamento e alta coesão no sistema. Atribuir responsabilidade apenas para as classes do domínio
conceitual pode levar a situações de maior acoplamento e menor
coesão. </p>

<p align="justify">&emsp;Coesão é o conceito que mede quão relacionadas ou focadas estão as
responsabilidades de um elemento. Classes que fazem muitas tarefas não relacionadas são
mais difíceis de entender, de manter e de reusar, além de
mais vulneráveis às mudanças. A solução é atribuir responsabilidades de modo que a coesão da
classe permaneça alta. </p>

<div style="display: flex; justify-content: center; align-items:center;">

    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/grasps/service-class.png">
</div>

<p align="justify">&emsp;Salvar um objeto no Banco de Dados implica em uma série de operações não relacionadas ao conceito de Employee, como verificar se existe o User relacionado a esse Employee e escrever os dados do Employee na tabela correta. </p>

<p align="justify">&emsp;A classe Employee tem de ser associada às interfaces do banco de dados relacional (IEmployeeRepository e ICreateEmployeeDTO)</p>







