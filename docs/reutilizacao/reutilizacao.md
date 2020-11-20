# Reutilização de Software
<br>
<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/gofs/pattern.png">
</div>
<br>

## **Histórico de Versões**
Data | Versão | Descrição | Autor(es) 
---- | ----------- | ------ | ---------
19/10/2020 | 1.0 | Adicionando Frameworks e Bibliotecas | Lucas Leite ([@lucasqmc](http://github.com/lucasqmc))
20/10/2020 | 1.1 | Atualizando Frameworks e Bibliotecas | Lucas Leite ([@lucasqmc](http://github.com/lucasqmc))


## **Introdução**

<p align="justify">&emsp; Neste documento procuramos expor de forma clara e objetiva os pontos candidatos á reutilização no nosso projeto, seja em futuros sistemas com certa similaridade de escopo ou dentro do proprio sistema no desenvolvimento de novas funcionalidades. Para explanar de forma organizada estes pontos dividimos em duas categorias: frameworks e bibliotecas, onde são caracterizadas as ferramentas que são utilizadas de maneira mais genérica e que possuem maior potencial de reutilização.  </p>


## **Frameworks**

### **Express.js**
<p align="justify">&emsp; É um framework para desenvolvimento web que roda na plataforma Node.js que fornece um conjunto robusto de recursos para aplicativos web e móvel. Express é o framework Node mais popular e a biblioteca subjacente para uma série de outros frameworks do Node. Os desenvolvedores que utilizam desse framework têm liberdade para criar pacotes de middleware específicos visando resolver problemas específicos que surgem no desenvolvimento de uma aplicação. Existem bibliotecas para trabalhar com cookies, sessões, login de usuários, parâmetros de URL, dados em requisições POST, cabeçalho de segurança e tantos outros. </p>

### **TypeORM**
<p align="justify">&emsp;TypeORM é um Framework de mapemanto de objeto-relacional(ORM) que pode ser executado em diversas plataformas (NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, e Electron). Mapeamento objeto-relacional (ou ORM, do inglês: Object-relational mapping) é uma técnica de desenvolvimento utilizada para reduzir a impedância da programação orientada aos objetos utilizando bancos de dados relacionais. As tabelas do banco de dados são representadas através de classes e os registros de cada tabela são representados como instâncias das classes correspondentes. O objetivo do TypeORM é sempre oferecer suporte aos recursos JavaScript mais recentes e fornecer recursos adicionais que o ajudem a desenvolver qualquer tipo de aplicativo que utilizem bancos de dados, desde pequenos aplicativos com algumas tabelas até aplicativos corporativos de grande escala com vários bancos de dados. </p>

## **Bibliotecas**
### **Front-End**

#### **React.js**
<p align="justify">&emsp;React é uma biblioteca JavaScript declarativa, eficiente e flexível para a criação de interfaces de usuário (UI). Funciona como uma uma coleção de funcionalidades relacionadas que podem ser chamadas pelo desenvolvedor para a criação de interfaces de usuário reaproveitáveis. O React veio amplamente como uma forma de resolver o problema de uma manipulação custosa do DOM, minimizando a quantidade de manipulação mantendo seu próprio DOM virtual e somente renderizando quando necessário, um feito que permite uma implementação diferente de alto desempenho. Isso significa que raramente manipularemos o DOM diretamente; ao invés, deixaremos o React tratar a manipulação do DOM. Essa funcionalidade é a base para muito do design do React. Isso significa que raramente manipularemos o DOM diretamente; ao invés, deixaremos o React tratar a manipulação do DOM. </p>

#### **Axios**
<p align="justify">&emsp;Axios é uma biblioteca cliente HTTP, que funciona tanto no browser quanto em Node.js. A biblioteca é basicamente uma API que sabe interagir tanto com XMLHttpRequest quanto com a interface http do node. Isso significa que o mesmo código utilizado para fazer requisições ajax no browser também funciona no servidor. Essa biblioteca serve para realizar nossas requisições HTTP para o back-end, sendo fundamental sua utilização no decorrer de evoluções do sistema que necessitem da biblioteca para realizar chamadas. </p>

#### **Materail UI**
<p align="justify">&emsp;Material-UI é um projeto de código aberto que apresenta componentes React que implementam o Material Design do Google. Material-UI fornece um componente CssBaseline opcional. Ele corrige algumas inconsistências entre navegadores e dispositivos, enquanto fornece redefinições um pouco mais opinativas para elementos HTML comuns. </p>


### **Back-End**

#### **Date-fns**
<p align="justify">&emsp;A bilbioteca date-fns fornece o conjunto de ferramentas mais abrangente, porém simples e consistente para manipular datas JavaScript em um navegador e Node.js. </p>

#### **bcryptjs**
<p align="justify">&emsp;A bilbioteca bcryptjs fornece uma maneira segura  de armazenar senhas no banco de dados. Algoritmos de hash são funções unilaterais. Eles transformam qualquer quantidade de dados em uma “impressão digital” de comprimento fixo que não pode ser revertida. Eles também têm a propriedade de que, se a entrada mudar mesmo que seja um pouquinho, o hash resultante será completamente diferente.</p>

#### **jsonwebtoken**
<p align="justify">&emsp;jsonwebtoken é uma biblioteca para Node.js que permite a manipulação e implementação de JSON Web Tokens. JSON Web Token (JWT) é um padrão aberto que define uma maneira compacta e independente para transmitir informações com segurança entre as partes como um objeto JSON. Essas informações podem ser verificadas e confiáveis ​​porque são assinadas digitalmente. Os JWTs podem ser assinados usando um segredo (com o algoritmo HMAC) ou um par de chaves pública / privada usando RSA ou ECDSA. é normalmente utilizado para fabricar tokens de Authorization para as requisições,depois que o usuário estiver conectado, cada solicitação subsequente incluirá o JWT, permitindo que o usuário acesse rotas, serviços e recursos permitidos com esse token.</p>

#### **tsyringe**
<p align="justify">&emsp; É um biblioteca que auxilia na injeção de dependências através de um  construtor, serve para diminuir o acoplamento entre classes. Quando falamos em “injetar” uma dependência, nada mais é do que passar uma classe que será utilizada para uma classe que irá consumi-la. Injeção de Dependência é um é um padrão de projeto usado para evitar o alto nível de acoplamento de código dentro de uma aplicação.</p>

#### **celebrate**
<p align="justify">&emsp; É um biblioteca utilizada para realizar validações nos parametros das requisições que chegam ao Back-end. Celebrate fornece uma função de middleware expressa que envolve a biblioteca de validação joi. Isso permite usar esse middleware em qualquer rota única ou globalmente e garantir que todas as suas entradas estejam corretas antes da execução qualquer função do controlador. O middleware permite validar req.params, req.headers e req.query.</p>

#### **cors**
<p align="justify">&emsp; 
CORS é uma biblioteca para node.js para fornecer um middleware Connect / Express que pode ser usado para habilitar CORS com várias opções.</p>


## Referências
 * <p align="justify"> Colaboradores da MDN.Introdução Express/Node. https://developer.mozilla.org/pt-BR/docs/Learn/Server-side/Express_Nodejs/Introdu%C3%A7%C3%A3o   , [S. l.],  19 nov. 2020.
</p>
 * <p align="justify"> React o que é e como funciona essa ferramenta. https://medium.com/reactbrasil/react-o-que-%C3%A9-e-como-funciona-essa-ferramenta-319922a8371cIntrodu%C3%A7%C3%A3o, [S. l.],  19 nov. 2020.
</p>

 * <p align="justify">Como usar Axios como cliente HTTP. http://codeheaven.io/how-to-use-axios-as-your-http-client-pt/#:~:text=Axios%20%C3%A9%20um%20cliente%20HTTP,browser%20tamb%C3%A9m%20funciona%20no%20servidor. , [S. l.],  19 nov. 2020.
</p>

 * <p align="justify"> EISENMAN Bonnie ; React.js na vida real do Codecademy. https://www.infoq.com/br/articles/reactjs-codecademy/#:~:text=Resumindo%3A%20o%20React%20%C3%A9%20uma,interfaces%20de%20usu%C3%A1rios%20com%20JavaScript.&text=O%20React%20ajuda%20a%20construir,complexas%20sem%20poluir%20o%20c%C3%B3digo., [S. l.],  19 nov. 2020.
</p>

 * <p align="justify">  TypeORM. https://typeorm.io/#/ , [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  date-fns. https://date-fns.org/ , [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  bcrypt.js. https://www.npmjs.com/package/bcryptjs, [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  JSON Web Token. https://jwt.io/introduction/  , [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  Injeção de dependencia. https://medium.com/@eduardolanfredi/inje%C3%A7%C3%A3o-de-depend%C3%AAncia-ff0372a1672  , [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  Celebrate. https://github.com/arb/celebrate  , [S. l.],  20 nov. 2020.
</p>

 * <p align="justify">  CORS. https://expressjs.com/en/resources/middleware/cors.html  , [S. l.],  20 nov. 2020.
</p>






