---
id: {{date:YYYYMMDD}}{{time:HHmm}}
type: meeting
company: 
summary: " "
alias: 
tags: [[_MeetingsMoc]] meeting 

created: {{date}}, {{time}}
modified: {{date}}, {{time}}
---


# [[2024-02-06 Atualizacao Versao Sankhya]]

Data: {{date}}
**Attendees**:
-

---

## Pauta

1. 

## Notas

![[Pasted image 20240206143729.png]]

### 4.20b208 -> 4.20b214

```sql
**Mensagem de erro:**ORA-06550: linha 4, coluna 13: PL/SQL: ORA-00947: não há valores suficientes ORA-06550: linha 4, coluna 2: PL/SQL: SQL Statement ignored ORA-06550: linha 8, coluna 13: PL/SQL: ORA-00947: não há valores suficientes ORA-06550: linha 8, coluna 2: PL/SQL: SQL Statement ignored ORA-06550: linha 12, coluna 13: PL/SQL: ORA-00947: não há valores suficientes ORA-06550: linha 12, coluna 2: PL/SQL: SQL Statement ignored  
**Número do script:**815  
**Nome do script:**DML2_TGFNRR  
**Conteúdo:**
BEGIN MERGE INTO TGFNRR NRR USING DUAL ON (NRR.CODNATREND = 12052) WHEN NOT MATCHED THEN INSERT VALUES (12052, 'Juros sobre o Capital Próprio cujos beneficiários não estejam identificados no momento do registro contábil', 'S', 'N', 'N', NULL, NULL, 'IR', 'A', '01/12/2022', NULL, 'S','4010,4020'); MERGE INTO TGFNRR NRR USING DUAL ON (NRR.CODNATREND = 11006) WHEN NOT MATCHED THEN INSERT VALUES (11006, 'Rendimentos pagos sem retenção do IR na fonte – Lei 10.833/2003}', 'N', 'N', 'N', NULL, NULL, NULL, 'A', '01/12/2022', NULL, 'S','4010,4020'); MERGE INTO TGFNRR NRR USING DUAL ON (NRR.CODNATREND = 15052) WHEN NOT MATCHED THEN INSERT VALUES (15052, 'Demais comissões, corretagens, ou qualquer outra importância paga/creditada pela representação comercial ou pela mediação na realização de negócios civis e comerciais', 'N', 'N', 'N', NULL, NULL, 'IR', 'A', '01/12/2022', NULL, 'S','4010,4020'); END; /
```

![[Pasted image 20240206150803.png]]
## Ações

- [ ] Meeting Notes Distributed to the Team
- [ ] Tasks & Projects Completed, Processed or Delegated
- [ ] Key Dates Completed or Scheduled