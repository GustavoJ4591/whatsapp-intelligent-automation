# Estrutura do Banco de Dados

## Tabela: clientes
id
nome
numero
primeira_interacao
ultima_interacao

## Tabela: atendimentos
id
cliente_id
status
setor
data_abertura
data_fechamento

## Tabela: orcamentos
id
cliente_id
descricao
arquivo
historico

## Tabela: logs
id
cliente_id
mensagem
horario
