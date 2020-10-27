# Comportamentais
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

<p align="justify">&emsp;A sigla GoF vem do inglês "<i>Gang of Four</i>" por ser uma didática vinda do livro Design Pattern que descreve padrões de projeto, com 4 autores diferentes e dai "<i>Gang of Four</i>".</p>

<p align="justify">&emsp;Os GoF's comportamentais são padrões voltados para as alterações do nível do comportamentos dos nossos objetos.</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
26/10/2020 | 1.0 | Adicionando padrões comportamentais | [@medeiroslucas](http://github.com/medeiroslucas), [@pedroMiranda7410](https://github.com/pedroMiranda7410) e [@tmcstiago](http://github.com/tmcstiago)

## **1. Template Method**
<p align="justify">&emsp;O padrão **Template Method** define que o esqueleto de
um algoritmo deve ser feito em na superclasse e as especificidades do objeto
devem ser definidas em suas subclasses.</p>

<p align="justify">&emsp;Utilizamos esse conceito na construção de uma interface
que define as operações que podem ser realizadas por uma classe, posteriormente
esses métodos são definidos independentemente.</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/template_method.png">
</div>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/template_method_2.png">
</div>

## **2. Mediator**
<p align="justify">&emsp;O papel do padrão **Mediator** é definir um objeto que
agrega e acopla outros objeto garantindo que a as interações entre as entidades
sejam realizadas apenas através do mediator.</p>

<p align="justify">&emsp;No caso do nosso projeto o mediator é utilizado para
concatenar todas as rotas em apenas um objeto, garantindo que o usuário não
possa acessar nenhuma separadamente. </p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/mediator.png">
</div>

## **3. State**
<p align="justify">&emsp;É um padrão de design comportamental no qual o um objeto altera seu comportamento de acordo com o estado.</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/state1.jpg">
</div>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/state2.jpg">
</div>
