# Controller
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
25/10/2020 | 1.0 | Adicionando Controller | [@lucasqmc](http://github.com/lucasqmc) 

## **Controller/Controlador**
<p align="justify">&emsp; O padrão controlador atribui a responsabilidade de manipular eventos do sistema para uma classe que não seja de interface do usuário (UI). O controlador é o primeiro objeto fora da camada de interface com o
usuário a receber ou tratar uma mensagem para o sistema. </p>

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/grasps/controller.png">
</div>

<p align="justify">&emsp;Um caso de uso controlador deve ser usado para lidar com todos os eventos de casos de uso e pode ser usado para mais de um caso de uso (por exemplo, para casos de uso como Criar usuário (como no exemplo acima) e Excluir usuário, pode ter um único UserController, em vez de dois casos de uso controllers separados). O controlador  não deve fazer muito trabalho por si próprio,ele deve delegar o trabalho que precisa ser feito para outros objetos,coordenando ou controlando as atividades </p>









