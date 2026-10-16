# 📦 Resolução Dropper: icg4200.iso

- **Alvo:** `icg4200.iso`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/icg4200.iso`[cite: 3]
- **Ambiente:** Mídia ISO de update IndusCom / Estação TN-FIN[cite: 6]
- **Status:** Em resolução

---

### 01. ISO ICG-4200 - 10 pts
- **Enunciado:** Este icg4200.iso é a mídia de update IndusCom montada na estação de finanças da Transnorte na Campanha Relé, o disco que a estação de trabalho tratou como firmware oficial do ICG-4200. Qual o Volume id?[cite: 6]
- **Análise / Resolução:**
  <!-- Documente sua análise, ferramentas de inspeção de ISO e prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. System id ISO - 10 pts
- **Enunciado:** Qual o System id registrado no cabeçalho/metadados da imagem ISO?[cite: 3, 6]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Publisher ISO - 10 pts
- **Enunciado:** Qual o Publisher id declarado nos metadados do volume ISO?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Preparer ISO - 10 pts
- **Enunciado:** O Data preparer id desta ISO aponta quem a mídia diz ter preparado o volume. Qual o Data preparer id?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Application ISO - 10 pts
- **Enunciado:** O Application id desta ISO é o agente que o disco declara, o mesmo do updater da Relé. Qual o Application id?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Autorun - 10 pts
- **Enunciado:** O open do autorun.inf é o binário que a ISO tentaria disparar ao montar. Qual o open do autorun.inf?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Hash ISO - 10 pts
- **Enunciado:** O SHA256 do update.bin fecha o dropper que a ISO carrega na raiz. Qual o SHA256 do update.bin?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. C2 ISO - 10 pts
- **Enunciado:** Qual a URL/endereço de C2 apontado internamente nos artefatos da ISO?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Flag ISO - 10 pts
- **Enunciado:** Qual a flag localizada dentro dos arquivos presentes na mídia ISO?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`