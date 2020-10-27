# Políticas de Git

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/politicas/git.png">
</div>

## Histórico de Versões

| Data | Versão | Descrição | Autor(es) |
| ---- | ------ | --------- | --------- |
| 29/09/2020 | 1.0 | Criação do documento | Luis Bruno ([@lbrunofidelis](https://github.com/lbrunofidelis)) |

## Guia de contribuição

<div style="display: flex; justify-content: center; align-items:center;">
    <img src="https://unbarqdsw.github.io/2020.1_G11_SYA/assets/politicas/contribuindo.png">
</div>

## Política de Issues
<p align="justify">&emsp;
Seguindo o template, cada Issue deve ser aberta neste repositório, mesmo que seja relacionada ao Front-end ou Back-end. Deve ser adicionado uma label referente à issue, a milestone (Sprint de entrega), os responsáveis e uma descrição da issue com as tarefas a serem realizadas.
</p>

## Política de Commits
<p align="justify">&emsp;
O padrão de commits do repositório seguem em Inglês no seguinte formato:
</p>

    👽 Fix login error

<p align="justify">&emsp;
A mensagem de commit deve ser em inglês e no modo indicativo ou imperativo, e deve conter uma descrição detalhada acerca do commit, se necessário, como o que ele adiciona/remove/edita, o que ele corrige e o porquê.
</p>

<p align="justify">&emsp;
Para atribuir os membros que contribuíram para este commit utilize o Co-authored:
</p>

    Co-authored-by: Nome do membro 1 <email do membro 1>
    Co-authored-by: Nome do membro 2 <email do membro 2>

## Política de Branches
<p align="justify">&emsp;
Tipos de branches:
</p>

* **master** - Branch principal de cada repositório que contém o código mais estável da aplicação. Todo código antes de ir para a master passa pela branch **development** para testar com as outras integrações do sistema.

* **development** - Branch que abriga as novas features implementadas durante a sprint. Aqui as features são testadas para então irem para a **master**.

* **feature** - Branch que possui as features que estão sendo implementadas durante a sprint, e devem conter o número da Issue/Feature que esta resolver, como por exemplo: **#41**.

## Política de Pull Request

<p align="justify">&emsp;
Os Pull Requests devem ser feitos para a branch <b>master</b> seguindo o template de Pull Request. O Pull Request deve seguir o template e ser descrito de forma clara o que foi feito e o que resolve. Devem também serem revisados por membros não vinculados ao PR.
</p>


