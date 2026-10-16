# 💻 Resolução Endpoint: sysmon_tn.jsonl

- **Alvo:** `sysmon_tn.jsonl`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/sysmon_tn.jsonl`
- **Ambiente:** Transnorte / Estação de Finanças (`TN-FIN-WS042`)
- **Status:** Em resolução

---

### 01. Sysmon TN - 10 pts
- **Enunciado:** Este sysmon_tn.jsonl é o export Sysmon da TN-FIN-WS042 depois da mídia ICG-4200 na Campanha Relé, o EventID 1 em que o update.bin sobe a partir da ISO montada na estação de trabalho de finanças. Qual o ParentImage do processo update.bin?
- **Análise / Resolução:**
  <!-- Documente sua análise, filtros de campos JSON e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Nome interno TN - 10 pts
- **Enunciado:** Qual o OriginalFileName ou nome interno do executável do updater?
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Hash Sysmon TN - 10 pts
- **Enunciado:** Qual o hash (SHA256) do processo update.bin registrado no EventID 1?
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Guid updater - 10 pts
- **Enunciado:** O ProcessGuid do update.bin amarra este processo aos eventos 3, 11 e 13 do mesmo export. Qual o ProcessGuid do update.bin?
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Guid pai - 10 pts
- **Enunciado:** O ParentProcessGuid do update.bin fecha o pai que disparou o dropper na TN-FIN-WS042. Qual o ParentProcessGuid do update.bin?
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. IP Event 3 TN - 10 pts
- **Enunciado:** O DestinationIp da conexão EventID 3 do update.bin é o IPv4 do canal que o dropper abriu. Qual o DestinationIp da conexão EventID 3 do update.bin?
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Porta Event 3 - 10 pts
- **Enunciado:** O DestinationPort dessa conexão é a porta do mesmo EventID 3 do update.bin. Qual o DestinationPort dessa conexão?
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Arquivo Event 11 - 10 pts
- **Enunciado:** O TargetFilename do EventID 11 do update.bin é o path em que o dropper se gravou na estação de trabalho de ops.cardoso. Qual o TargetFilename do EventID 11 do update.bin?
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Run Event 13 - 10 pts
- **Enunciado:** O TargetObject do EventID 13 do update.bin é a chave Run em que o updater persistiu. Qual o TargetObject do EventID 13 do update.bin?
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Flag Sysmon TN - 10 pts
- **Enunciado:** O CampaignId do processo update.bin é a marca deste export Sysmon da Transnorte. Qual o CampaignId do processo update.bin?
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`