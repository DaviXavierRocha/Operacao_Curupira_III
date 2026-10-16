# 💾 Resolução Disco: lit-disk.img

- **Alvo:** `lit-disk.img`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/lit-disk.img`[cite: 3]
- **Ambiente:** Volume ext4 Linux / Litoral Telecom (`LIT-NMS-02`)[cite: 4]
- **Status:** Em resolução

---

### 13. Disco LIT - 10 pts
- **Enunciado:** Este lit-disk.img é o volume ext4 do NMS Linux LIT-NMS-02 depois do pacote DNS da Campanha Relé, a imagem em que o RPM deixou cron, unit e um notes apagado. Qual o Volume Name?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Hostname ext4 - 10 pts
- **Enunciado:** Qual o hostname registrado na configuração de rede do sistema ext4?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. User UID 1000 - 10 pts
- **Enunciado:** Qual o nome do usuário associado ao UID 1000 no arquivo /etc/passwd da imagem?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Cron IndusCom - 10 pts
- **Enunciado:** O comando no cron IndusCom, último campo da linha que não é comentário, é o binário que o pacote agendou. Qual o comando no cron IndusCom (último campo da linha que não é comentário)?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Unit DNS - 10 pts
- **Enunciado:** Qual o nome do serviço/unit systemd associado ao pacote DNS no sistema?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. C2 dns.conf - 10 pts
- **Enunciado:** Qual a URL/endereço de C2 apontada no arquivo dns.conf dentro da imagem?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Hash disco LIT - 10 pts
- **Enunciado:** O SHA256 do dns-update.bin no disco fecha o dropper que o RPM deixou em usr. Qual o SHA256 do dns-update.bin no disco?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Hosts CDN - 10 pts
- **Enunciado:** O IPv4 de update.induscom-cdn.net no etc/hosts é o pin que o NMS usou para o canal. Qual o IPv4 de update.induscom-cdn.net no etc/hosts?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. Inode notes - 10 pts
- **Enunciado:** Qual o número do inode associado ao arquivo notes apagado/recuperável?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. C2 apagado - 10 pts
- **Enunciado:** Qual a URL de C2 contida dentro do arquivo de notas que foi apagado?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Flag apagado - 10 pts
- **Enunciado:** A Flag no arquivo apagado é a marca deste volume ext4 da Litoral. Qual a Flag no arquivo apagado?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`