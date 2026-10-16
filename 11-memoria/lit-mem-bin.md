# 🧠 Resolução Memória: lit-mem.bin

- **Alvo:** `lit-mem.bin`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/lit-mem.bin`[cite: 2]
- **Ambiente:** Litoral Telecom (`LIT-NMS-02`)[cite: 3]
- **Status:** Em resolução

---

# 🧠 Resolução Memória: lit-mem.bin

- **Alvo:** `lit-mem.bin`
- **Link do Alvo:** `[https://download.gohacking.com.br/curupira3/lit-mem.bin](https://download.gohacking.com.br/curupira3/lit-mem.bin)`
- **Ambiente:** Snapshot RMEM do processo curl.exe / Litoral Telecom (`LIT-NMS-02`)
- **Status:** Em resolução

---

### 11. RMEM LIT - 10 pts
- **Enunciado:** Este lit-mem.bin é o snapshot RMEM do curl.exe no LIT-NMS-02 depois do LNK DNS na Campanha Relé, o dump de memória do download que o atalho disparou no NMS. Qual o Computer no cabeçalho?
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. PID RWX LIT - 10 pts
- **Enunciado:** O PID da linha Image=curl.exe com Prot=RWX é o processo que o RMEM marca como região executável gravável. Qual o PID da linha Image=curl.exe com Prot=RWX?
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Off RWX LIT - 10 pts
- **Enunciado:** O Off da região Prot=RWX do curl.exe é onde este snapshot começa o blob gzip do download. Qual o Off da regiao Prot=RWX do curl.exe?
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Len RWX LIT - 10 pts
- **Enunciado:** O Len da região Prot=RWX do curl.exe fecha o tamanho desse blob no RMEM da Litoral. Qual o Len da regiao Prot=RWX do curl.exe?
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. Hash RWX LIT - 10 pts
- **Enunciado:** O SHA256 da região RWX depois de gzip -dc é o hash do PE descomprimido neste dump do NMS. Qual o SHA256 da regiao RWX depois de gzip -dc?
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Off MZ LIT - 10 pts
- **Enunciado:** O offset do MZ dentro da região decodificada aponta onde o PE real começa depois do padding. Qual o offset do MZ dentro da regiao decodificada?
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. C2 PE LIT - 10 pts
- **Enunciado:** A URL C2 no PE a partir do MZ é o portal DNS verdadeiro, não o decoy deste dump. Qual a URL C2 no PE a partir do MZ (não o decoy)?
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. IP socket LIT - 10 pts
- **Enunciado:** Qual o endereço IP do record de socket associado à comunicação externa do processo no dump da Litoral?
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Porta socket LIT - 10 pts
- **Enunciado:** A porta desse record de socket fecha o mesmo registro f4130000 na tabela de rede. Qual a porta desse record de socket?
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Flag RMEM LIT - 10 pts
- **Enunciado:** A Flag no PE a partir do MZ é a marca deste snapshot da Litoral, não o decoy. Qual a Flag no PE a partir do MZ (não o decoy)?
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`