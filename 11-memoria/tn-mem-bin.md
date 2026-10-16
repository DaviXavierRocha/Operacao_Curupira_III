# 🧠 Resolução Memória: tn-mem.bin

- **Alvo:** `tn-mem.bin`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/tn-mem.bin`[cite: 2]
- **Ambiente:** Transnorte / Estação de Finanças (`TN-FIN-WS042`)[cite: 3]
- **Status:** Em resolução

---

### 01. RMEM TN - 10 pts
- **Enunciado:** Este tn-mem.bin é o snapshot RMEM do processo update.bin na TN-FIN-WS042 depois da ISO ICG-4200 na Campanha Relé, o dump de memória que o plantão tirou do dropper ainda residente. Qual o Computer no cabeçalho?[cite: 3]
- **Análise / Resolução:**
  <!-- Documente sua análise, ferramentas de inspeção de dump/strings e insira prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. PID RWX TN - 10 pts
- **Enunciado:** O PID da linha Image=update.bin com Prot=RWX é o processo que o RMEM marca como região executável gravável. Qual o PID da linha Image=update.bin com Prot=RWX?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Off RWX TN - 10 pts
- **Enunciado:** O Off da região Prot=RWX do update.bin é onde este snapshot começa o blob gzip do dropper. Qual o Off da regiao Prot=RWX do update.bin?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Len RWX TN - 10 pts
- **Enunciado:** O Len da região Prot=RWX do update.bin fecha o tamanho desse blob no RMEM da Transnorte. Qual o Len da regiao Prot=RWX do update.bin?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Hash RWX TN - 10 pts
- **Enunciado:** O SHA256 da região RWX depois de gzip -dc é o hash do PE descomprimido, não do blob cru. Qual o SHA256 da regiao RWX depois de gzip -dc?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Off MZ TN - 10 pts
- **Enunciado:** O offset do MZ dentro da região decodificada aponta onde o PE real começa depois do padding. Qual o offset do MZ dentro da regiao decodificada?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. C2 PE TN - 10 pts
- **Enunciado:** A URL C2 no PE a partir do MZ é o heartbeat verdadeiro, não o decoy que o dump também carrega. Qual a URL C2 no PE a partir do MZ (não o decoy)?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. IP socket TN - 10 pts
- **Enunciado:** Qual o endereço IP remoto da conexão de socket ativa registrada na tabela de rede da TN-FIN?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Porta socket TN - 10 pts
- **Enunciado:** A porta desse record de socket fecha o mesmo registro d4120000 na tabela de rede. Qual a porta desse record de socket?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Flag RMEM TN - 10 pts
- **Enunciado:** A Flag no PE a partir do MZ é a marca deste snapshot, não o decoy. Qual a Flag no PE a partir do MZ (não o decoy)?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`