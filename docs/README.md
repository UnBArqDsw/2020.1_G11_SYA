# SYA - Documentação
**Número do Grupo**: 11<br>
**Código da Disciplina**: FGA0208-T01<br>

## Alunos
| Matrícula | Aluno |
| --------- | ----- |
| 17/0008371 | [Daniel Sousa Melo](https://github.com/dansousamelo) |
| 17/0016811 | [Lucas Leite Maduro](https://github.com/lucasqmc) |
| 17/0039803 | [Lucas Medeiros](https://github.com/medeiroslucas) |
| 14/0169695 | [Luis Bruno Fidelis](https://github.com/lbrunofidelis) |
| 15/0144474 | [Pedro Queiroz Miranda](https://github.com/pedroMiranda7410) |
| 17/0046176 | [Tiago Miguel](https://github.com/tmcstiago) |


## Histórico de Versões da wiki

<table>
    <thead>
        <th>Data</th>
        <th>Versão</th>
        <th>Descrição</th>
        <th>Autor(es)</th>
    </thead>
    <tbody>
        <tr>
            <td>09/09/2020</td>
            <td>1.0</td>
            <td>Realizando configuração da wiki com o plugin docsify</td>
            <td>
                <a href="https://github.com/medeiroslucas">Lucas Medeiros</a>
            </td>
        </tr>
        <tr>
            <td>09/09/2020</td>
            <td>2.0</td>
            <td>Desenvolvendo HTML e CSS customizado para ficar de acordo com o guia de estilo do SYA</td>
            <td>
                <a href="https://github.com/pedroMiranda7410">Pedro Miranda</a>
            </td>
        </tr>
    </tbody>
</table>


## Instalação 

### Criando ambiente virtual

```bash
$ nodeenv env
```

### Instalação Docsify

```bash
$ source env/bin/activate	# acessando o ambiente virtual
(env)$ npm i docsify-cli -g
```

## Comandos

### Iniciar o servidor Docsify

```bash
(env)$ docsify serve docs
```

Para realizar o deploy basta commitar as modificações
