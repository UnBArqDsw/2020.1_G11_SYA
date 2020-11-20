# Estruturais
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
22/10/2020 | 1.0 | Adicionando Decorator | [@dansousamelo](http://github.com/dansousamelo)
26/10/2020 | 1.0 | Adicionando Adapter e Facade | [@pedroMiranda7410](http://github.com/pedroMiranda7410) e [@medeiroslucas](http://github.com/medeiroslucas)

## **1. Decorators**
<p align="justify">&emsp;O Decorator é um padrão de projeto estrutural, que permite acrescentar novos comportamentos a métodos de forma dinâmica. Os decorators permitem estender o funcionamento de um método.</p>
<p align="justify">&emsp;O Decorator foi utilizado para a criação de entidades, onde conseguimos conectá-las ao nosso banco de dados, como podemos ver logo abaixo:
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/decorator.png">
</div>

## **2. Adapter**

<p align="justify">&emsp;
    Converter a interface de uma classe em outra interface que os clientes esperam. O adaptador permite que as classes trabalhem em conjunto que de outra forma não poderiam por causa de interfaces incompatíveis.
</p>

### [Algumas aplicabilidades]. Utilize o padrão Adapter quando:

<ul align="justify">&emsp;
    <li>
        Se pretende utilizar uma classe existente, e a sua interface não corresponde à que necessita
    </li>
    <li>
        Se pretende criar uma classe reutilizável que coopere com classes não relacionadas ou imprevistas, ou seja, classes que não têm necessariamente interfaces compatíveis
    </li>
    <li>
        (apenas adaptador) Se precisa de utilizar várias subclasses existentes, mas não é prático adaptar a sua interface subclassificando cada uma delas. Um adapter pode adaptar a interface da sua classe mãe.
    </li>
</ul>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/estrutural_adapter_hash.jpeg">
</div>

<p align="justify">&emsp;
    Os exemplos abaixo, não necessariamente estamos citando um caso de uso de adapter, mas dentro do nosso back-end construimos interfaces para cada objeto possibilitando, futuramente, adaptar suas funções, caso necessário.
</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/estrutural-adapter.png">
</div>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/estrutural-adapter-2.png">
</div>

## **3. Facade**

<p align="justify">&emsp;
    Fornecer uma interface unificada para um conjunto de interfaces num subsistema. Facade define uma interface de nível superior que torna o subsistema mais fácil de utilizar.
</p>

### [Algumas aplicabilidades]. Utilize o padrão Facade quando:

<ul align="justify">&emsp;
    <li>
        Se pretende fornecer uma interface simples para um subsistema complexo. Os subsistemas tornam-se frequentemente mais complexos à medida que evoluem. A maioria dos padrões, quando aplicados, resultam em mais e menores classes. Isto torna o subsistema mais reutilizável e mais fácil de personalizar, mas também se torna mais difícil de usar para clientes que não precisam de o personalizar. Um Facade pode fornecer uma visão por defeito simples do subsistema que é suficientemente boa para a maioria dos clientes. Apenas os clientes que necessitem de mais personalização terão de olhar para além da fachada.
    </li>
    <li>
        há muitas dependências entre clientes e as classes de implementação de uma abstração. Introduzir um facade para desacoplar o subsistema dos clientes e outros subsistemas, promovendo assim a independência do subsistema e portabilidade.
    </li>
    <li>
        quer colocar os seus subsistemas. Use um facade para definir um ponto de entrada para cada nível de subsistema. Se os subsistemas são dependentes, então pode simplificar as dependências entre eles, fazendo-os comunicar com cada outros unicamente.
    </li>
</ul>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/estrutural_facade.jpeg">
</div>

## **Referências**

 * <p align="justify">Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides (1994). Design Patterns: Elements of Reusable Object-Oriented Software</p>