# ⚡ Resolução Warmup: updater.bin

- **Alvo:** `updater.bin`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/updater.bin`[cite: 2]
- **Ambiente:** Binário ELF IndusCom / Estação TN-FIN[cite: 7]
- **Status:** Em resolução

---

### 22. Updater ELF - 10 pts
- **Enunciado:** Este updater.bin veio do path de vendor da IndusCom na estação de finanças da Transnorte na Campanha Relé, o binário que a estação de trabalho executou como se fosse o agente de update do ICG-4200. Qual o primeiro token de file -b?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Arch updater - 10 pts
- **Enunciado:** Qual a arquitetura do processador para a qual o binário foi compilado?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. C2 updater - 10 pts
- **Enunciado:** Qual o endereço/URL de C2 embutido nas strings do binário?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. UA updater - 10 pts
- **Enunciado:** O UA visível em strings é o mesmo agente do heartbeat e do updater. Qual o UA visível em strings?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Host updater - 10 pts
- **Enunciado:** O Host visível em strings amarra o binário à estação do caso Relé. Qual o Host visível em strings?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:** 

---

### 27. Versão updater - 10 pts
- **Enunciado:** Qual a versão do produto ou build declarada no binário?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Produto updater - 10 pts
- **Enunciado:** Qual o nome do produto ou software associado ao updater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Seção QR - 10 pts
- **Enunciado:** Qual o nome da seção do executável ELF que armazena a estrutura do QR code?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Off seção QR - 10 pts
- **Enunciado:** Qual o offset em hexadecimal/bytes onde se inicia a seção do QR code?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. Tam. seção QR - 10 pts
- **Enunciado:** Qual o tamanho em bytes da seção onde o QR code está alocado?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. Flag QR - 10 pts
- **Enunciado:** Qual a flag obtida a partir da decodificação do QR code embutido no executável?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`