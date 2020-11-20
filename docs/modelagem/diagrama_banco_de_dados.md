# Diagrama de Banco de Dados

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/diagram.png">
</div>

<p align="justify">&emsp;Com a intenção de modelar o banco de dados, seguindo os requisitos exigidos pelo Backlog, utilizaremos de três documentos que precedem a criação do banco e guiam sua correta estruturação, são eles: Modelo Entidade-Relacionamentos (ME-R) , Diagrama Entidade-Relacionamentos (DE-R) e Diagrama Lógico (DL).</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
25/09/2020 | 1.0 | Adicionando diagrama de banco de dados| Lucas Leite ([@lucasqmc](http://github.com/lucasqmc)) |
26/09/2020 | 1.1 | Adicionar DER e Diagrama lógico | Lucas Medeiros ([@medeiroslucas](http://github.com/medeiroslucas)) |
19/11/2020 | 1.1 | Atualizando ME-R e Entidades | Lucas Leite ([@lucasqmc](http://github.com/lucasqmc)) |
 
<p align="justify">&emsp;Abaixo encontra-se a representação em diagramas de banco de dados da aplicação.</p>

## **Modelo Entidade-Relacionamento(ME-R)**

### **Entidades**

* USER
* EMPLOYEE
* WORK
* APPOINTMENT


### **Atributos**

* APPOINTMENT (id , date, user_id, work_id, employee_id,client_name,client_email) 
* EMPLOYEE (user_id, id, name)
* WORK (id, name, price, duration)
* USER (id, name, email, password, avatar, business_name, business_area)

### **Relacionamentos**

* WORK - has many - APPOINTMENT
 * Um WORK pode possuir vários APPOINTMENTS e um APPOINTMENT é de somente um WORK.
 * Cardinalidade **1 : N**
* EMPLOYEE - has many - APPOINTMENT
 * Um EMPLOYEE pode possuir vários APPOINTMENTS e um APPOINTMENT é de somente um EMPLOYEE.
 * Cardinalidade **1 : N**.
* USER - has many - APPOINTMENT
 * Um USER pode possuir vários APPOINTMENTS e um APPOINTMENT é de somente um USER.
 * Cardinalidade **1 : N**.
* USER - has many - EMPLOYEE
 * Um USER pode possuir vários EMPLOYEE e um EMPLOYEE é de somente um USER.
 * Cardinalidade **1 : N**.
* EMPLOYEE - works - WORK
 * Um EMPLOYEE trabalha com um ou vários WORK(s) e um WORK pode pertencer a vários EMPLOYEE(s)
 * Cardinalidade **N : M**.

## **Diagrama Entidade-Relacionamento (DE-R)**

[![](https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/DER_PYA.png)](https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/DER_PYA.png)
<p align="center"><i>Clique na imagem para ampliar</i></p>


## **Diagrama Lógico**

[![](https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/Logico_SYA.png)](https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/Logico_SYA.png)
<p align="center"><i>Clique na imagem para ampliar</i></p>


## **Referências**
 * <p align="justify">Introdução ao Modelo de Dados e seus Níveis de Abstração. Disponível em: http://spaceprogrammer.com/bd/introducao-ao-modelo-de-dados-e-seus-niveis-de-abstracao/. Acesso: 25 set. 2020.</p>
