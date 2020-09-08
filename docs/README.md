# SYA - Documentação
**Número do Grupo**: 11<br>
**Código da Disciplina**: FGA0208-T01<br>

## Alunos
|Matrícula | Aluno |
| 17/0008371 | [Daniel Sousa Melo](https://github.com/dansousamelo) |
| 17/0016811 | [Lucas Leite Maduro](https://github.com/lucasqmc) |
| 17/0039803 | [Lucas Medeiros](https://github.com/medeiroslucas) |
| 14/0169695 | [Luis Bruno Fidelis](https://github.com/lbrunofidelis) |
| 15/0144474 | [Pedro Queiroz Miranda](https://github.com/pedroMiranda7410) |
| 17/0046176 | [Tiago Miguel](https://github.com/tmcstiago) |

## Instalação 

#### Criando ambiente virtual

```bash
$ virtualenv env
```

#### Instalação Mkdocs

```bash
$ source env/bin/activate	# acessando o ambiente virtual
(env)$ pip install mkdocs
```

## Comandos

#### Iniciar o servidor do Mkdocs

```bash
(env)$ mkdocs serve
```

#### Buildar a documentação

```bash
(env)$ mkdocs build
```

#### Realizar o deploy da documentação

```bash
(env)$ mkdocs gh-deploy
```
