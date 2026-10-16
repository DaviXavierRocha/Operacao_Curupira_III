# 💻 Resolução Endpoint: sysmon_clm.jsonl

- **Alvo:** `sysmon_clm.jsonl`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/sysmon_clm.jsonl`
- **Ambiente:** CLM (Câmara de Liquidação Mercantil / `CLM-MESA-014`)
- **Status:** Em resolução

---

### 21. Sysmon CLM - 10 pts
- **Enunciado:** Qual o hostname ou evento raiz do host CLM registrado no Sysmon?
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. User mshta - 10 pts
- **Enunciado:** O User do mshta.exe aponta a conta da CLM que abriu o HTA depois da captura do kit. Qual o User do mshta.exe?
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. CmdLine HTA - 10 pts
- **Enunciado:** O CommandLine do mshta.exe é a linha que dispara o HTA a partir do Downloads da estação de trabalho. Qual o CommandLine do mshta.exe?
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Guid mshta - 10 pts
- **Enunciado:** O ProcessGuid do mshta.exe amarra o HTA ao clm-agent.bin e aos EventID 11 e 13. Qual o ProcessGuid do mshta.exe?
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. Pai agente - 10 pts
- **Enunciado:** O ParentImage do clm-agent.bin confirma que o agente saiu do mshta, não de outro pai. Qual o ParentImage do clm-agent.bin?
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Nome interno CLM - 10 pts
- **Enunciado:** O OriginalFileName do clm-agent.bin denuncia o nome interno do cliente da CLM. Qual o OriginalFileName do clm-agent.bin?
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:** 

---

### 27. Host Event 3 CLM - 10 pts
- **Enunciado:** O DestinationHostname do EventID 3 do clm-agent.bin é o host do heartbeat que o agente chamou. Qual o DestinationHostname do EventID 3 do clm-agent.bin?
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Arquivo HTA - 10 pts
- **Enunciado:** O TargetFilename do EventID 11 do mshta.exe é o path em que o HTA gravou o clm-agent.bin. Qual o TargetFilename do EventID 11 do mshta.exe?
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Run HTA - 10 pts
- **Enunciado:** O TargetObject do EventID 13 do mshta.exe é a chave Run em que o HTA persistiu o cliente. Qual o TargetObject do EventID 13 do mshta.exe?
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Flag Sysmon CLM - 10 pts
- **Enunciado:** Qual a flag final de comprometimento registrada nos eventos do Sysmon da CLM?
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`