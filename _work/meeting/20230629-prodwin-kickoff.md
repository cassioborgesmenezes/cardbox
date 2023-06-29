---
id: 202306291005
alias: 
tags: meeting erp/producao erp/mes

created: 2023-06-29, 10:05
modified: 2023-06-29, 10:05
---
# 20230629-prodwin-kickoff

Data: 2023-06-29
Participantes: Fernando Salum, Wilson, Leandro

---

## Pauta

1. Reunião Inicial

## Notas

- Vamos tratar agora somente TI
- Não há informação sobre Lote a ser produzido
	- Poderemos utilizar o campo `cdOperacao`
- Integração
	- Como vamos integrar os cadastros (?)
		- Existe um tratamento que é feito a partir da própria OP
		- Mandante do cadastro é o ERP
	- Importante fazermos o tratamento de máquinas
	- Transferência de OP entre máquinas é uma questão complexa
	- Necessidade do PCP: sem este módulo não está sequenciada; abertura de OP vai depender de informação externa; 
		- necessário informar `dtInicio`
		- Prodwin irá avaliar
- Testar leitores de código de barras
- Ambiente Homologação
	- Será interno
- Implantação
	- 1o. passo: comunicação
	- 2o. passo: cadastros (com possibilidade de importação)

## Ações

- [ ] Disponibilizar um servidor Windows Server
- [ ] Disponibilizar um servidor de Banco de Dados SQL Server
- [ ] Verificar se temos um ponto de rede para Linha 1
- [ ] Designar um IP fixo
- [ ] Desenvolver integração via _webservice_