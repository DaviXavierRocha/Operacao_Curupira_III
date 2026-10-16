# 🔐 Resolução Crypto: update.enc

- **Alvo:** `update.enc`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/update.enc`[cite: 2]
- **Ambiente:** Pacote de atualização malicioso / ObsidianUpdater[cite: 7]
- **Status:** Em resolução

---

### 27. Pacote AES - 10 pts
- **Enunciado:** Este arquivo é o pacote AES do updater da IndusCom recolhido na estação de finanças da Transnorte na Campanha Relé, a receita do drop que o Defender classificou como ObsidianUpdater. Qual o Pass no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Estação AES - 10 pts
- **Enunciado:** O Host no cabeçalho em claro identifica a estação de onde este pacote AES do updater saiu. Qual o Host no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Operador AES - 10 pts
- **Enunciado:** O Operator no cabeçalho em claro aponta quem o vendor associou a este updater. Qual o Operator no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Cifra AES - 10 pts
- **Enunciado:** O Cipher no cabeçalho diz qual cifra este pacote do updater declara usar. Qual o Cipher no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. KDF AES - 10 pts
- **Enunciado:** O KDF no cabeçalho diz como a senha vira chave neste pacote AES. Qual o KDF no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. URL updater AES - 10 pts
- **Enunciado:** Depois do AES, a URL no plaintext é de onde o updater deveria se puxar. Qual a URL no plaintext depois do AES?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta:** 

---

### 33. Drop AES - 10 pts
- **Enunciado:** O Drop no plaintext é o path em que o updater deveria cair no disco da estação de trabalho. Qual o Drop no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Hash AES - 10 pts
- **Enunciado:** O Hash no plaintext fecha o binário que este pacote AES descreve. Qual o Hash no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta:** 

---

### 35. UA AES - 10 pts
- **Enunciado:** O UA no plaintext é o agente que o updater usaria na saída. Qual o UA no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 35](caminho/para/imagem.png)
- **Resposta:** 

---

### 36. C2 AES - 10 pts
- **Enunciado:** A URL C2 no plaintext é o canal que o updater da IndusCom deveria usar. Qual a URL C2 no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 36](caminho/para/imagem.png)
- **Resposta:** 

---

### 37. Flag AES - 10 pts
- **Enunciado:** A Flag no plaintext decifrado é a marca deste pacote AES do updater. Qual a Flag no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 37](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`