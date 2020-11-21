# DAS - Documento de Arquitetura De Software
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/das/icon.png">
</div>
<br>

<p align="justify">&emsp;Este documento tem como objetivo registrar a estrutura arquitetural do aplicativo SYA, desenvolvido como produto final da disciplina de ADS (Arquitetura e Desenho de Software), no campus do Gama, da Universidade de Brasília.</p>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
20/11/2020 | 1.0 | Adicionando tópico 6 | Daniel Sousa ([@dansousamelo](http://github.com/dansousamelo))
20/11/2020 | 1.1 | Adicionando Introdução | Lucas Leite ([@lucasqmc](http://github.com/lucasqmc))
20/11/2020 | 1.2 | Adicionando Tópicos 2 e 9 | Pedro Miranda ([@pedroMiranda7410](http://github.com/pedroMiranda7410))
20/11/2020 | 1.3 | Adicionando Tópico 3 | Luis Bruno ([@lbrunofidelis](http://github.com/lbrunofidelis))

## **1. Introdução**

### **1.1. Finalidade**

<p align="justify">&emsp;Este documento tem como finalidade descrever, especificar e documentar as decisões arquiteturais relevantes na realização do projeto SYA. Descreve de forma clara e organizada os aspectos do sistema, procurando explanar de forma objetiva seus principais pontos. </p>

### **1.2. Escopo**

<p align="justify">&emsp;Este documento se aplica ao processo de desenvolvimento do SYA, um sistema desenvolvido conforme pede a disciplina de Desenho e Arquitetura de software na Universidade de Brasília. </p>

## **2. Representação Arquitetural**
### **2.1 Tecnologias**
#### **2.1.1 Front End**
<br>

##### **React**
<p align="justify">&emsp;
    O React (também denominado React.js ou ReactJS) é uma biblioteca JavaScript de código aberto com foco em criar interfaces de usuário (frontend) em páginas web. É mantido pelo Facebook, Instagram, outras empresas e uma comunidade de desenvolvedores individuais. Em nosso caso, buscamos utilizar a linguagem typescript, acoplado no framework, que é um superconjunto de JavaScript desenvolvido pela Microsoft que adiciona tipagem e alguns outros recursos a linguagem, trazendo padronização de código e agilidade.
</p>
<p align="justify">&emsp;
    A escolha do React se deve pelo objetivo, em conjunto, da equipe de se desafiar e aprender uma nova tecnologia. Contendo 2 integrantes com maior nível de conhecimento que os demais, que se proporam a ajudar.
</p>

#### **2.1.2 Back End**
<br>

##### **Node**
<p align="justify">&emsp;
    Node é um ambiente de execução Javascript server-side. Com ele é possível criar aplicações Javascript para rodar como uma aplicação standalone em uma máquina, não dependendo de um browser para a execução.
</p>
<br>

##### **Express**
<p align="justify">&emsp;
    Express é um popular framework web estruturado, escrito em JavaScript que roda sobre o ambiente node.js em tempo de execução. Este módulo explica alguns dos principais benefícios deste framework, como configurar o seu ambiente de desenvolvimento e como executar tarefas comuns de desenvolvimento e implantação da web.
</p>
<br>

#### **2.1.2 Banco de Dados**
<br>

##### **Postgresql**
<p align="justify">&emsp;
    Um sistema de Gerência de Bancos de dados Relacional estendido e livre que utiliza, como interface, a linguagem SQL.
</p>

## **3. Requisitos e Restrições Arquiteturais**

### Requisitos

|  Requisito |                                          Descrição                                         |
|:----------:|:------------------------------------------------------------------------------------------:|
|  Segurança | A aplicação deve tratar e armazenar os dados do usuário de forma segura, com criptografia. |
| Desempenho |       O sistema deve possuir um tempo de resposta e navegação entre as telas rápida.       |

### Restrições

|  Restrição |                                                                                                         Descrição                                                                                                         |
|:----------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Plataforma | O sistema terá suporte para navegadores modernos, como Chrome, Firefox, Opera, Safari, Edge. Para mobile, apenas a funcionalidade de Agendamento terá suporte, pois esta é destinada ao Cliente do prestador de serviços. |
|   Conexão  |                                                                              Para interação com o sistema é necessária conexão com internet.                                                                              |
|   Idioma   |                                                                                  Todo o sistema será desenvolvido em Português (Brasil).                                                                                  |
|   Público  |                                                                                O sistema é destinado à brasileiros prestadores de serviços.                                                                               |
|   Equipe   |                                                                                     A equipe de desenvolvimento possui 5 integrantes.                                                                                     |
|   Entrega  |                                                                                   O prazo de entrega do sistema é ao fim da disciplina.                                                                                   |

## **4. Visão de Casos de Uso**

## **5. Visão lógica**

## **6. Visão de implementação**
<p align="justify">&emsp;A Visão de Implementação mostra como, de fato, o sistema proposto será implementado. Uma de suas principais características é a visão geral do Diagrama de Classes final do projeto.</p>

<img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/das/classes.png">

## **7. Visão de dados (banco)**

## **8. Visão de implantação (banco)**

## **9. Visão de processos (banco)**
<p align="justify">&emsp;A Visão de Processos mostra como será feito o modelo de projeto, tendo como base uma visualização em sequência.</p>

<img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/das/Diagrama_Sequencia.png">

<p align="justify">
    <strong>Autor:</strong> <a href="http://github.com/pedroMiranda7410">Pedro Miranda</a>
</p>

## **10. Qualidade (banco)**


## **Referências**

 * <p align="justify">DEVMEDIA. Orientações básicas na elaboração de um diagrama de classes. [S. l.], 2019. Disponível em: https://www.devmedia.com.br/orientacoes-basicas-na-elaboracao-de-um-diagrama-de-classes/37224. Acesso em: 23 set. 2020.</p>




