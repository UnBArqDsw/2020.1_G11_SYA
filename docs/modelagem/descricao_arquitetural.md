# Descrição Arquitetural

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/arch.png">
</div>

<p align="justify">&emsp;Este documento tem como objetivo principal especificar de forma clara e concisa tópicos referentes ao Documento de Arquitetura que será desenvolvido durante a disciplina.</p>

## **1. Introdução**

## **1.1 Finalidade**

<p align="justify">&emsp;Este documento possui o objetivo de especificar e documentar decisões arquiteturais no desenvolvimento da aplicação SYA, descrevendo os aspectos do sistema de forma pragmática e estruturada.</p>

## **1.2 Escopo**

<p align="justify">&emsp;Aplica-se ao processo de desenvolvimento do sistema SYA, desenvolvido para  a disciplina Arquitetura e Desenho de Software, na Universidade de Brasília.</p>

## **2. Representação Arquitetural**

## **2.1 Tecnologias**

## **2.1.1 Front End**

### ReactJS

<p align="justify">&emsp;Por definição React é uma biblioteca para criar interfaces. Resolve toda aquele amontoado de código com jQuery que tínhamos para manipular o DOM. Podemos criar coisas performáticas e reutilizáveis de verdade.</p>

## **2.1.2 Back End**

### Express

<p align="justify">&emsp;O ExpressJS é um framework para aplicações web em Node.js que resolve um leque isolado de problemas comuns em todas aplicações como gerenciamento de rotas, requisição, resposta e views.</p>

## **2.1.3 Banco de dados**

### PostgreSQL

<p align="justify">&emsp;O PostgreSQL é um sistema de gerenciamento de banco de dados objeto-relacional baseado no POSTGRES Versão 4.2 desenvolvido pelo Departamento de Ciência da Computação da Universidade da Califórnia em Berkeley. Suporta grande parte do padrão SQL e oferece muitas funcionalidades modernas, como: comandos complexos, chaves estrangeiras, gatilhos, visões, integridade transacional e controle de simultaneidade multiversão.</p>

## **2.2 Motivação Arquitetural**

<p align="justify">&emsp;Por se tratar de um sistema com apenas duas interfaces (cliente, servidor) foi selecionado uma padrão arquitetural que não impusesse uma dificuldade em sua implementação sem o devido retorno, logo, escolhemos uma arquitetura simples mas que atende todas as necessidades do projeto.</p>

## **2.3 Abordagem Arquitetural**

<p align="justify">&emsp;Arquitetura cliente-servidor com dois apenas dois serviços e um banco de dados.</p>

## **2.4 Diagrama de Contexto**

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/modelagem/abordagem_arquitetural.jpeg">
</div>


## **3. Restrições e Metas Arquiteturais**

### Metas

| Meta | Descrição |  
| ---- | ------ | 
| Escalabilidade | A aplicação deve ser escalável de maneira viável |
| Segurança | A aplicação deve prover segurança aos dados sensiveis dos usuários |

### Restrições

| Meta | Descrição |  
| ---- | ------ | 
| Público | A aplicação terá seu foco no púlico brasileiro |
| Linguagem | A aplicação será desenvolvida em português do Brasil |
| Equipe | A equipe conta com somente 6 integrantes |
| Prazo | A aplicação tem o prazo de um semestre letivo para ser desenvolvida |
| Conectividade | A aplicação necessita de conexão com a internet para ser utilizada |

## **4. Visão de Casos de Uso**

## **5. Referências**

 * <p align="justify">AdonisJS vs ExpressJS: Quando utilizar cada um? . Disponível em: https://blog.rocketseat.com.br/adonis-vs-express/#:~:text=A%20melhor%20utiliza%C3%A7%C3%A3o%20do%20ExpressJS,conectarem%20formam%20a%20aplica%C3%A7%C3%A3o%20completa.. Acesso em: 27 de Setembro de 2020.
</p>

 * <p align="justify">Entenda de uma vez por todas o que é React, Vue e Angular. Disponível em: https://medium.com/by-vinicius-reis/o-que-e-react-ng2-auleria-vue-e34b0c77b5a1 .. Acesso em: 27 de Setembro de 2020.
</p>

 * <p align="justify">O que é o PostreSQL. Disponível em: http://pgdocptbr.sourceforge.net/pg82/intro-whatis.html .. Acesso em: 27 de Setembro de 2020.
</p>

## **6. Histórico de revisões**

| Data | Autor | Versão | Alteração |   
| ---- | ------ | ------ | ------ |
| 28/09/2020 | Daniel Sousa ([@dansousamelo](https://github.com/dansousamelo)), Lucas Leite ([@lucasqmc](https://github.com/lucasqmc)), Lucas Medeiros ([@medeiroslucas](https://github.com/medeiroslucas)), Luis Bruno ([@lbrunofidelis](https://github.com/lbrunofidelis), Pedro Queiroz Miranda ([@pedroMiranda7410](https://github.com/pedroMiranda7410)), Tiago Miguel([@tmcstiago](https://github.com/tmcstiago)) | 1.0 | Criando documento de arquitetura |
