# 🔐 Resolução Crypto: recovery.pem

- **Alvo:** `recovery.pem`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/recovery.pem`[cite: 2]
- **Ambiente:** Chaves de recuperação / Kit RSA do fornecedor[cite: 7]
- **Status:** Em resolução

---

### 38. Kit RSA - 10 pts
- **Enunciado:** Este PEM é o kit RSA de recuperação da IndusCom recolhido com o sync do vendor na Campanha Relé, a chave que o operador do Obsidian deixou junto do canal de sync. Qual o Host no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 38](caminho/para/imagem.png)
- **Resposta:** 

---

### 39. Operador RSA - 10 pts
- **Enunciado:** Qual o Operator no cabeçalho em claro do kit RSA?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 39](caminho/para/imagem.png)
- **Resposta:** 

---

### 40. Tipo chave - 10 pts
- **Enunciado:** Qual o tipo ou formato de chave declarado no arquivo PEM?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 40](caminho/para/imagem.png)
- **Resposta:** 

---

### 41. Padding RSA - 10 pts
- **Enunciado:** O Padding no cabeçalho diz como o RSA deste kit foi aplicado. Qual o Padding no cabeçalho em claro?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 41](caminho/para/imagem.png)
- **Resposta:** 

---

### 42. Gateway RSA - 10 pts
- **Enunciado:** Depois do RSA, o plaintext ainda nomeia o gateway da SE-03. Qual o Gateway no plaintext depois do RSA?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 42](caminho/para/imagem.png)
- **Resposta:** 

---

### 43. Firmware RSA - 10 pts
- **Enunciado:** O Firmware no plaintext decifrado é a versão do ICG citada neste kit de recuperação. Qual o Firmware no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 43](caminho/para/imagem.png)
- **Resposta:** 

---

### 44. C2 RSA - 10 pts
- **Enunciado:** A URL C2 no plaintext é o canal que este kit RSA descreve. Qual a URL C2 no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 44](caminho/para/imagem.png)
- **Resposta:** 

---

### 45. Origem RSA - 10 pts
- **Enunciado:** O Src no plaintext aponta o IP interno que o kit associava à escrita na SE-03. Qual o Src no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 45](caminho/para/imagem.png)
- **Resposta:** 

---

### 46. Estação RSA - 10 pts
- **Enunciado:** A Station no plaintext amarra o kit RSA à estação ou subestação do caso. Qual o Station no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 46](caminho/para/imagem.png)
- **Resposta:** 

---

### 47. Flag RSA - 10 pts
- **Enunciado:** A Flag no plaintext decifrado é a marca deste kit RSA da IndusCom. Qual a Flag no plaintext decifrado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 47](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`