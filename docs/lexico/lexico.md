# **Léxico**

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/lexico/lexico.png">
</div>


<p align="justify">
    Aqui estão listados os léxicos, sendo estes termos específicos do contexto do domínio da aplicação. Dito isso, algumas das definições a seguir diferem significativamente das definições para as mesmas palavras que poderiam ser encontradas em um dicionário, pois aqui estão definidas no contexto do aplicativo.
</p>

## Histórico de Versões

<table>
    <thead>
        <th>Data</th>
        <th>Versão</th>
        <th>Descrição</th>
        <th>Autor(es)</th>
    </thead>
    <tbody>
        <td>10/09/2020</td>
        <td>1.0</td>
        <td>Criação do documento sobre Léxicos e subindo léxicos 1, 2, 3, 4 e 5</td>
        <td>
            <a href="https://github.com/pedroMiranda7410">Pedro Miranda</a>
        </td>
    </tbody>
</table>
<br>

Para cada termo estão listadas as seguintes definições:

- Nome: Nome do Léxico;
- Sinônimo(s): outros termos que possuem os mesmos atributos deste;
- Sujeito: se o termo se refere a um sujeito, objeto, verbo ou estado. Sujeito para os que se referem a atores que podem realizar ações, verbo para os termos que indicam ações, estado para os que indicam alguma condição temporária, e objeto para aqueles que não se encaixam em nenhum dos dois casos anteriores;
- Noção: significado do termo e contexto do mesmo;
- Impacto: ações que podem ser realizadas pelo sujeito referenciado pelo termo ou sobre ele.

Para facilitar a visibilidade de cada uma dessas informações para cada termo, será usado o seguinte template tabular:

## Template

<table>
    <thead>
        <th>Nome: </th>
        <th>...{ Nome } ...</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td>...{ Sinônimo(s) } ...</td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td>...{ Sujeito } ...</td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>...{ Noção } ...</td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>...{ Impacto } ...</td>
        </tr>
    </tbody>
</table>

## Léxico 1

<table id="agendar">
    <thead>
        <th>Nome: </th>
        <th>Agendar</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td>Verbo</td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>
                <ul>
                    <li>
                        O <a href="#/lexico/lexico?id=usuario">usuário</a> da plataforma possui capacidade de criar um novo evento na agenda da plataforma, informando a data/hora, <a href="#/lexico/lexico?id=funcionario">funcionário</a> responsável, <a href="#/lexico/lexico?id=servico">serviço</a> proposto e o nome do <a href="#/lexico/lexico?id=cliente">cliente</a> designado.
                    </li>
                    <li>
                        O <a href="#/lexico/lexico?id=cliente">cliente</a> de um respectivo dono de um negócio, ou <a href="#/lexico/lexico?id=usuario">usuário</a>, poderá efetuar seu próprio agendamento, verificando os horários e <a href="#/lexico/lexico?id=funcionario">funcionários</a> disponíveis, através de um link.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>
                <ul>
                    <li>
                        O <a href="#/lexico/lexico?id=usuario">usuário</a> pode agendar um <a href="#/lexico/lexico?id=servico">serviço</a>.
                    </li>
                    <li>
                        O <a href="#/lexico/lexico?id=cliente">cliente</a> pode agendar um <a href="#/lexico/lexico?id=servico">serviço</a>.
                    </li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

## Léxico 2

<table id="cliente">
    <thead>
        <th>Nome: </th>
        <th>Cliente</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td>Objeto</td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>
                Aquele que busca pagar por um <a href="#/lexico/lexico?id=servico">serviço</a> proposto por um devido <a href="#/lexico/lexico?id=usuario">usuário</a>.
            </td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>
                O cliente realiza uma troca de serviço e dinheiro entre um <a href="#/lexico/lexico?id=usuario">usuário</a>.
            </td>
        </tr>
    </tbody>
</table>

## Léxico 3

<table id="funcionario">
    <thead>
        <th>Nome: </th>
        <th>Funcionário</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td>Objeto</td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>
                Aquele que está responsabilizado de realizar um determinado <a href="#/lexico/lexico?id=servico">serviço</a> a que vos foi designado com seus respectivos <a href="#/lexico/lexico?id=cliente">clientes</a>.
            </td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>
                O funcionário realiza o <a href="#/lexico/lexico?id=servico">serviço</a> para um <a href="#/lexico/lexico?id=cliente">cliente</a> e recebe seu valor monetário.
            </td>
        </tr>
    </tbody>
</table>

## Léxico 4

<table id="servico">
    <thead>
        <th>Nome: </th>
        <th>Serviço</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td> Verbo </td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>
                <ul>
                    <li>
                        Tarefa realizada pelo <a href="#/lexico/lexico?id=funcionario">funcionário</a> sob um <a href="#/lexico/lexico?id=cliente">cliente</a>.
                    </li>
                    <li>
                        Um <a href="#/lexico/lexico?id=funcionario">funcionário</a> realiza um serviço para um <a href="#/lexico/lexico?id=cliente">cliente</a> recebendo um valor monetário em troca negociado com o <a href="#/lexico/lexico?id=usuario">usuário</a>.
                    </li>
                </ul>
             </td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>
                <ul>
                    <li>
                        O <a href="#/lexico/lexico?id=cliente">cliente</a> paga o <a href="#/lexico/lexico?id=usuario">usuário</a> e recebe o serviço.
                    </li>
                    <li>
                        O <a href="#/lexico/lexico?id=funcionario">funcionário</a> realiza o serviço para o <a href="#/lexico/lexico?id=cliente">cliente</a>.
                    </li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

## Léxico 5

<table id="usuario">
    <thead>
        <th>Nome: </th>
        <th>Usuário</th>
    </thead>
    <tbody>
        <tr>
            <td>Sinônimo(s)</td>
            <td> - </td>
        </tr>
        <tr>
            <td>Sujeito</td>
            <td>Objeto</td>
        </tr>
        <tr>
            <td>Noção</td>
            <td>
                Aquele que é dono de um negócio e tiver efetuado o pagamento da plataforma, para desfrutar de todas suas funcionalidades propostas.
            </td>
        </tr>
        <tr>
            <td>Impacto</td>
            <td>
                O usuário possui conta na Plataforma SYA e ganha direitos de uso das suas funcionalidades.
            </td>
        </tr>
    </tbody>
</table>






# Referência
- PAX. <b>Léxicos</b>.Disponível em: https://pax-app.github.io/Wiki/#/docs/DS/dinamica-e-seminario-2/lexico. Acesso em: 10 set. 2020.
- REQUISITOS DO APP RICO, REQUISITOS DE SOFTWARE UNB, FGA. <b>Léxicos</b>.Disponível em: https://requisitos-de-software.github.io/2019.2-Rico/Modelagem/lexicos. Acesso em: 10 set. 2020.
- SERRANO, Maurício; SERRANO, Milene. Requisitos - Vídeo Aula 02g. 2020. 34 slides. Material apresentado para a disciplina de Arquitetura e Desenho de Software da UnB, FGA.