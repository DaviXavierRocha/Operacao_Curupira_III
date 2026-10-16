# 🧠 Resolução Memória: clm-mem.bin

- **Alvo:** `clm-mem.bin`
- **Link do Alvo:** `[https://download.gohacking.com.br/curupira3/clm-mem.bin](https://download.gohacking.com.br/curupira3/clm-mem.bin)`
- **Ambiente:** Dump de Memória CLMD / CLM (`CLM-MESA-014`)
- **Status:** Em resolução

---

### 21. CLMD CLM - 10 pts
- **Enunciado:** Este clm-mem.bin é o dump CLMD da estação de trabalho CLM-MESA-014 depois do HTA da Campanha Relé. Não é o formato RMEM, e o plantão precisa do cabeçalho CLMD antes de tratar o SLOT AES. Qual o Station no cabeçalho?
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. User CLMD - 10 pts
- **Enunciado:** Qual o User identificado no cabeçalho ou metadados da estrutura CLMD?
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. KeyHint AES - 10 pts
- **Enunciado:** Qual o KeyHint registrado no cabeçalho para derivar ou localizar a chave AES?
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Salt CLMD - 10 pts
- **Enunciado:** Qual o Salt criptográfico gravado no dump CLMD para o SLOT AES?
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. SockOff - 10 pts
- **Enunciado:** Qual o offset (SockOff) onde começa a tabela ou array de sockets no binário?
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. SockStride - 10 pts
- **Enunciado:** Qual o tamanho/passo de cada entrada da estrutura de socket (SockStride)?
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:** 

---

### 27. Off JSON AES - 10 pts
- **Enunciado:** Qual o offset do bloco cifrado em AES que armazena o JSON interno da aplicação?
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Len JSON AES - 10 pts
- **Enunciado:** Qual o comprimento/tamanho (Len) em bytes do bloco JSON cifrado?
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Path HTA JSON - 10 pts
- **Enunciado:** Qual o caminho completo do arquivo HTA referenciado no JSON após a descriptografia?
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Pass JSON - 10 pts
- **Enunciado:** Qual a senha ou credencial colhida presente nos dados do JSON decifrado?
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. C2 JSON - 10 pts
- **Enunciado:** Qual a URL de comando e controle (C2) configurada dentro do payload JSON?
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. IP socket CLM - 10 pts
- **Enunciado:** Qual o endereço IPv4 registrado na estrutura de socket associada ao agente malicioso?
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta:** 

---

### 33. PID socket CLM - 10 pts
- **Enunciado:** Qual o PID vinculado à conexão de rede ativa no dump de memória?
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Flag CLMD - 10 pts
- **Enunciado:** Qual a flag obtida na análise do dump de memória CLMD da Câmara?
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`