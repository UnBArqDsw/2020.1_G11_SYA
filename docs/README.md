# SYA - Documentação
**Número do Grupo**: 11<br>
**Código da Disciplina**: FGA0208-T01<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| xx/xxxxxx  |  xxxx xxxx xxxxx |
| xx/xxxxxx  |  xxxx xxxx xxxxx |

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
