# 🔐 Resolução Crypto: heartbeat.xor

- **Alvo:** `heartbeat.xor`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/heartbeat.xor`[cite: 2]
- **Ambiente:** Pulso C2 periódico / Estação de finanças (TN-FIN)[cite: 7]
- **Status:** Em resolução

---

### 15. Beacon XOR - 10 pts
- **Enunciado:** Este arquivo é o blob XOR do heartbeat capturado na estação de finanças da Transnorte na Campanha Relé, o mesmo pulso periódico que o pcap já tinha mostrado sem decifrar. Qual a Key no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Estação XOR - 10 pts
- **Enunciado:** Qual o hostname da estação no cabeçalho em claro?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Operador XOR - 10 pts
- **Enunciado:** Qual o Operator registrado no cabeçalho em claro?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. Cifra XOR - 10 pts
- **Enunciado:** O Cipher no cabeçalho diz qual cifra este blob de heartbeat declara usar. Qual o Cipher no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. UA XOR - 10 pts
- **Enunciado:** Depois do XOR, o UA no plaintext é o mesmo agente periódico visto no pcap da Transnorte. Qual o UA no plaintext depois do XOR?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. C2 XOR - 10 pts
- **Enunciado:** A URL C2 no plaintext é o canal que este heartbeat descreve. Qual a URL C2 no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. Path XOR - 10 pts
- **Enunciado:** O Path no plaintext é o URI do heartbeat que o blob descreve. Qual o Path no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. Intervalo XOR - 10 pts
- **Enunciado:** O Interval no plaintext é o período do pulso do implante. Qual o Interval no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Dominio XOR - 10 pts
- **Enunciado:** O Beacon no plaintext nomeia o tipo ou o canal deste pulso. Qual o Beacon no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Origem XOR - 10 pts
- **Enunciado:** O Src no plaintext é o IPv4 de origem do heartbeat na estação de trabalho de finanças. Qual o Src no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. Destino XOR - 10 pts
- **Enunciado:** O Dst no plaintext é o IPv4 de destino deste heartbeat. Qual o Dst no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Flag XOR - 10 pts
- **Enunciado:** A Flag no plaintext decifrado é a marca deste blob XOR do heartbeat. Qual a Flag no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`