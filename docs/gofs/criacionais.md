# Criacionais
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

<p align="justify">&emsp;Os GoF's criacionais aplicam-se em situações que envolvem a criação de objetos e ajudam a fazer um sistema independente de como seus objetos são criados, compostos e representados.</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
15/10/2020 | 1.0 | Adicionando Singleton | [@dansousamelo](http://github.com/dansousamelo) e [@pedroMiranda7410](https://github.com/pedroMiranda7410)

## **1. Singleton**
<p align="justify">&emsp;Padrão comumente utilizado. Seremos incapazes de dar um new para criar um instância podendo acessá-lo apenas por um método estático.</p>

<p align="justify">&emsp;Utilizamos o conceito de singleton no backend para garantir uma instância única da aplicação com o banco de dados.</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/singleton.png">
</div>

<p align="justify">&emsp;Nos arquivos responsáveis pela regra de negócio conseguimos acesso ao banco de dados por meio da injeção de dependência, abaixo temos o código responsável pela autenticação de um usuário. </p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/singleton2.png">
</div>

<p align="justify">&emsp;Em relação ao front-end, utilizaremos o localStorage, que é um recurso da própria Web, variáveis são armazenadas globalmente.</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/singleton3.png">
</div>

## **Referências**

 * <p align="justify">Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides (1994). Design Patterns: Elements of Reusable Object-Oriented Software</p>




