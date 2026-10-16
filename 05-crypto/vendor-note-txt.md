# 🔐 Resolução Crypto: vendor_note.txt

- **Alvo:** `vendor_note.txt`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/vendor_note.txt`[cite: 2]
- **Ambiente:** Estação de finanças (TN-FIN) / Nota do fornecedor IndusCom[cite: 7]
- **Status:** Em resolução

---

### 01. Nota hex - 10 pts
- **Enunciado:** Este arquivo é a nota cifrada da IndusCom recolhida na estação de finanças da Transnorte na Campanha Relé, o recado do vendor que só fecha depois de hex e Base64. Qual o Host no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**
  <!-- Documente sua análise, etapas de decodificação e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Operador hex - 10 pts
- **Enunciado:** Qual o Operator no cabeçalho em claro da nota?[cite: 2, 7]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Canal hex - 10 pts
- **Enunciado:** Qual o Channel/Canal no cabeçalho ou metadado em claro?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Camadas hex - 10 pts
- **Enunciado:** O Encoding no cabeçalho diz como o plaintext foi empacotado antes da cifra. Qual o Encoding no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Gateway hex - 10 pts
- **Enunciado:** Depois de hex e Base64, o plaintext ainda nomeia o gateway da SE-03. Qual o Gateway no plaintext depois de hex e base64?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Firmware hex - 10 pts
- **Enunciado:** Qual a versão de Firmware indicada no plaintext decifrado?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Modelo hex - 10 pts
- **Enunciado:** Qual o Model/Modelo do dispositivo no plaintext decifrado?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. C2 hex - 10 pts
- **Enunciado:** A URL C2 no plaintext é o canal que a nota mandava a estação de trabalho usar. Qual a URL C2 no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. IP C2 hex - 10 pts
- **Enunciado:** O C2_IP no plaintext fecha o IPv4 do canal citado nesta nota. Qual o C2_IP no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Setpoint hex - 10 pts
- **Enunciado:** Qual o valor do Setpoint operacional revelado no plaintext?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. Origem hex - 10 pts
- **Enunciado:** Qual o endereço IP de origem registrado no plaintext?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Build hex - 10 pts
- **Enunciado:** O Build no plaintext fecha a revisão do pacote citado nesta nota. Qual o Build no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Caso OCC hex - 10 pts
- **Enunciado:** O Case no plaintext é o código IR que o vendor ou o operador colou neste recado. Qual o Case no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Flag hex - 10 pts
- **Enunciado:** A Flag no plaintext decifrado é a marca do caso nesta nota da IndusCom. Qual a Flag no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`