# ⚡ Resolução Warmup: firmware.bin

- **Alvo:** `firmware.bin`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/firmware.bin`[cite: 2]
- **Ambiente:** Blob de firmware ICG-4200 / Gateway SE-03[cite: 7]
- **Status:** Em resolução

---

### 33. Firmware ICFW - 10 pts
- **Enunciado:** Este firmware.bin é o blob ICG-4200 recolhido no sync da IndusCom na Campanha Relé, a imagem que a Transnorte puxou como firmware do gateway da SE-03. Qual o Host no cabeçalho ASCII?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Magic ICFW - 10 pts
- **Enunciado:** Qual a assinatura mágica (Magic Bytes/Header ASCII) no início deste arquivo de firmware?[cite: 2, 7]
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta:** 

---

### 35. Modelo ICFW - 10 pts
- **Enunciado:** Qual o modelo do dispositivo declarado no cabeçalho do firmware?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 35](caminho/para/imagem.png)
- **Resposta:** 

---

### 36. Versão ICFW - 10 pts
- **Enunciado:** Qual a versão de firmware declarada no cabeçalho?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 36](caminho/para/imagem.png)
- **Resposta:** 

---

### 37. PayloadOff - 10 pts
- **Enunciado:** Qual o offset do payload indicado no cabeçalho estruturado do firmware?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 37](caminho/para/imagem.png)
- **Resposta:** 

---

### 38. PayloadLen - 10 pts
- **Enunciado:** Qual o comprimento/tamanho total do payload especificado no cabeçalho?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 38](caminho/para/imagem.png)
- **Resposta:** 

---

### 39. Hash declarado - 10 pts
- **Enunciado:** Qual o valor do hash declarado para verificação de integridade no cabeçalho?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 39](caminho/para/imagem.png)
- **Resposta:** 

---

### 40. Hash carve - 10 pts
- **Enunciado:** Qual o hash calculado diretamente sobre o payload extraído (carved) do binário?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 40](caminho/para/imagem.png)
- **Resposta:** 

---

### 41. Gateway ICFW - 10 pts
- **Enunciado:** Qual o nome do gateway de campo referenciado dentro do firmware?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 41](caminho/para/imagem.png)
- **Resposta:** 

---

### 42. Site ICFW - 10 pts
- **Enunciado:** Qual o código do site/subestação associado ao firmware?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 42](caminho/para/imagem.png)
- **Resposta:** 

---

### 43. C2 ICFW - 10 pts
- **Enunciado:** Qual o endereço do canal C2 configurado internamente no payload?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 43](caminho/para/imagem.png)
- **Resposta:** 

---

### 44. Flag ICFW - 10 pts
- **Enunciado:** A Flag no payload decodificado é a marca deste firmware.bin. Qual a Flag no payload decodificado?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 44](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`