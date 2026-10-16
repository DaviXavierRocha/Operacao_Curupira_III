# 💻 Resolução Endpoint: sysmon_lit

- **Alvo:** `sysmon_tn.jsonl` (recorte Litoral)
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/sysmon_tn.jsonl`
- **Ambiente:** Litoral Telecom (`LIT-NMS-02`)
- **Status:** Em resolução

---

### 11. Sysmon LIT - 10 pts
- **Enunciado:** Qual o hostname ou evento raiz do NMS registrado neste export de endpoint?
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. User cmd lure - 10 pts
- **Enunciado:** O User desse cmd.exe aponta a conta da Litoral que disparou o lure no NMS. Qual o User desse cmd.exe?
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. CmdLine lure - 10 pts
- **Enunciado:** O CommandLine desse cmd.exe é a linha que baixa o dns-update.bin a partir do portal falso. Qual o CommandLine desse cmd.exe?
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Guid cmd - 10 pts
- **Enunciado:** O ProcessGuid desse cmd.exe amarra o lure aos filhos curl e ao EventID 13. Qual o ProcessGuid desse cmd.exe?
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. Pai curl - 10 pts
- **Enunciado:** O ParentImage do curl.exe confirma que o download DNS saiu do cmd do lure, não de outro pai. Qual o ParentImage do curl.exe?
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Host Event 3 LIT - 10 pts
- **Enunciado:** O DestinationHostname do EventID 3 do curl.exe é o host do portal que o NMS resolveu. Qual o DestinationHostname do EventID 3 do curl.exe?
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. IP Event 3 LIT - 10 pts
- **Enunciado:** O DestinationIp dessa conexão é o IPv4 do mesmo EventID 3 do curl.exe. Qual o DestinationIp dessa conexão?
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. Arquivo curl - 10 pts
- **Enunciado:** O TargetFilename do EventID 11 do curl.exe é o path em que o dns-update.bin caiu no NMS. Qual o TargetFilename do EventID 11 do curl.exe?
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Run DNS - 10 pts
- **Enunciado:** O TargetObject do EventID 13 do cmd.exe da campanha é a chave Run do DNS da IndusCom. Qual o TargetObject do EventID 13 do cmd.exe da campanha?
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Flag Sysmon LIT - 10 pts
- **Enunciado:** Qual a flag registrada nos eventos da Litoral Telecom neste export?
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`