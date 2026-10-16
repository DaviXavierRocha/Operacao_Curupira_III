# 💾 Resolução Disco: tn-disk.img

- **Alvo:** `tn-disk.img`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/tn-disk.img`[cite: 3]
- **Ambiente:** Volume NTFS / Estação de Finanças (`TN-FIN-WS042`)[cite: 4]
- **Status:** Em resolução

---

### 01. Disco TN - 10 pts
- **Enunciado:** Este tn-disk.img é o volume NTFS da estação TN-FIN-WS042 depois do dropper ICG-4200 na Campanha Relé, a imagem de disco em que o plantão ainda acha o update.bin, a lixeira e o ADS do relatório. Qual o Volume Name?[cite: 4]
- **Análise / Resolução:**
  <!-- Documente sua análise, etapas de montagem/inspeção do NTFS e prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Perfil TN - 10 pts
- **Enunciado:** O diretório de perfil em /Users além de Public é a conta da estação de trabalho de finanças neste NTFS. Qual o diretório de perfil em /Users além de Public?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Startup TN - 10 pts
- **Enunciado:** O arquivo no Startup do ops.cardoso é o .cmd que o updater deixou para subir no logon. Qual o arquivo no Startup do ops.cardoso?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Alvo Startup - 10 pts
- **Enunciado:** O path dentro do ObsidianUpdater.cmd aponta o update.bin que o Startup dispara. Qual o path dentro do ObsidianUpdater.cmd?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Path dropper NTFS - 10 pts
- **Enunciado:** O path NTFS do update.bin no volume é onde o dropper ficou gravado neste disco da Transnorte. Qual o path NTFS do update.bin no volume?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Hash disco TN - 10 pts
- **Enunciado:** O SHA256 do update.bin no disco deve cruzar com o hash da ISO e do Sysmon. Qual o SHA256 do update.bin no disco?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Firmware icg.cfg - 10 pts
- **Enunciado:** O Firmware em ProgramData/IndusCom/icg.cfg é a versão que o vendor colou no config do ICG. Qual o Firmware em ProgramData/IndusCom/icg.cfg?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Setpoint Desktop - 10 pts
- **Enunciado:** O Setpoint no occ-note.txt da Desktop é o valor da SE-03 que a estação de trabalho anotou em claro. Qual o Setpoint no occ-note.txt da Desktop?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. SID lixeira - 10 pts
- **Enunciado:** O SID sob $Recycle.Bin identifica a lixeira desta conta no NTFS da TN-FIN. Qual o SID sob $Recycle.Bin?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Path $I - 10 pts
- **Enunciado:** Qual o caminho original do arquivo apagado registrado nos metadados da lixeira ($I)?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. C2 $R - 10 pts
- **Enunciado:** A URL C2 no $R da lixeira é o heartbeat que restou no arquivo apagado. Qual a URL C2 no $R da lixeira (arquivo apagado)?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Flag ADS - 10 pts
- **Enunciado:** A Flag no ADS hidden de Q3-report.txt é a marca deste volume NTFS da Transnorte. Qual a Flag no ADS hidden de Q3-report.txt?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`