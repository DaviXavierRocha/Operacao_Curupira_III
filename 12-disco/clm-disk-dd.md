# 💾 Resolução Disco: clm-disk.dd

- **Alvo:** `clm-disk.dd`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/clm-disk.dd`[cite: 3]
- **Ambiente:** Imagem raw MBR/NTFS / CLM (`CLM-MESA-014`)[cite: 4]
- **Status:** Em resolução

---

### 24. Disco CLM - 10 pts
- **Enunciado:** Este clm-disk.dd é o disco MBR da estação de trabalho CLM-MESA-014 depois do HTA da Campanha Relé. O wiper ainda não rodou, e o plantão precisa do start da partição NTFS antes de listar o agente. Qual o Start em setores da partição NTFS?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. Tipo 0x07 - 10 pts
- **Enunciado:** O tipo da partição NTFS no mmls (hex) fecha a entrada MBR desta estação de trabalho da Câmara. Qual o tipo da partição NTFS no mmls (hex)?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Volume NTFS - 10 pts
- **Enunciado:** O Volume Name do NTFS em offset 2048 identifica o volume depois de pular o MBR. Qual o Volume Name do NTFS em offset 2048?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:** 

---

### 27. Perfil CLM - 10 pts
- **Enunciado:** Qual o nome do diretório de perfil de usuário principal identificado na pasta Users?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. HTA Downloads - 10 pts
- **Enunciado:** Qual o nome ou identificador do arquivo HTA localizado no diretório Downloads?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Path agente - 10 pts
- **Enunciado:** O path NTFS do clm-agent.bin é onde o HTA gravou o agente neste disco. Qual o path NTFS do clm-agent.bin?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Hash disco CLM - 10 pts
- **Enunciado:** O SHA256 do clm-agent.bin no disco fecha o agente que restou na estação de trabalho da CLM. Qual o SHA256 do clm-agent.bin no disco?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. Pass desk.cred - 10 pts
- **Enunciado:** O Pass no desk.cred da estação de trabalho é a credencial que o kit colheu e deixou neste disco. Qual o Pass no desk.cred da estação de trabalho (credencial colhida)?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. State wiper - 10 pts
- **Enunciado:** O State do clm-wipe.bin, ainda não executado, diz em que estágio o wiper está neste dd. Qual o State do clm-wipe.bin (ainda não executado)?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta:** 

---

### 33. Trigger wiper - 10 pts
- **Enunciado:** O Trigger do wiper é o gatilho que o binário espera antes de apagar o lote. Qual o Trigger do wiper?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Target wiper - 10 pts
- **Enunciado:** O Target do wiper é o lote de liquidação que o binário aponta. Qual o Target do wiper?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta:** 

---

### 35. Flag wiper - 10 pts
- **Enunciado:** A Flag no clm-wipe.bin é a marca deste disco MBR da Câmara. Qual a Flag no clm-wipe.bin?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 35](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`