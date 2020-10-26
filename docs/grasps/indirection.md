# Indirection
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
25/10/2020 | 1.0 | Adicionando Indireção | [@lucasqmc](http://github.com/lucasqmc) 

## **Indirection/Indireção**
<p align="justify">&emsp; A ideia do padrão indirection é utilizar uma classe intermediária como uma proteção para o objeto cliente de futuras variações no objeto que está sendo utilizado. Esse padrão busca diminuir o acoplamento entre as camadas de domínio e de serviços. </p>



<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/grasps/indirection1.png">
</div>

<p align="justify">&emsp;No exemplo, as classes EmployeeRepository e UserRepository são responsáveis por estabelecer uma comunicação entre os objetos de dominio e o banco de dados, procura-se diminuir o acoplamento entre as camadas de domínio e de serviços.</p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/grasps/indirection2.png">
</div>

<p align="justify">&emsp;Na classe intermediária EmployeeRepository são implementados os métodos que são responsáveis pela comunicção direta com o banco de dados, utilizando um objeto que utiliza as interfaces do banco.</p>

## Referências
 * <p align="justify"> SERRANO, Milene. Slides de GRASP'S. Módulo Padrões de Projeto GRASP(s) Material Complementar  (Parte II), [S. l.], p. 25-30, 26 out. 2020.
</p>






