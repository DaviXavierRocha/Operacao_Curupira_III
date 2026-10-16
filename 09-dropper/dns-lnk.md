# 📦 Resolução Dropper: dns.lnk

- **Alvo:** `dns.lnk`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/dns.lnk`[cite: 3]
- **Ambiente:** Atalho malicioso do Windows / Litoral Telecom (NMS)[cite: 4]
- **Status:** Em resolução

---

### 10. Dropper LNK DNS - 10 pts
- **Enunciado:** Qual a linha de comando completa (Target / Arguments) disparada pelo atalho?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. Dropper MachineID - 10 pts
- **Enunciado:** Qual o MachineID ou NetBIOS name registrado nos metadados do arquivo .lnk?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Dropper WorkingDir - 10 pts
- **Enunciado:** Qual o Working Directory configurado nas propriedades do atalho?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Dropper Description LNK - 10 pts
- **Enunciado:** Qual o campo de descrição (Comment/Description) embutido no arquivo LNK?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Dropper Serial LNK - 10 pts
- **Enunciado:** Qual o número de série do volume (Drive Serial Number) gravado no LNK?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. Dropper Portal LNK - 10 pts
- **Enunciado:** A URL no CommandLineArguments é o portal DNS falso que o LNK baixa ao executar. Qual a URL no CommandLineArguments?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Dropper Saida LNK - 10 pts
- **Enunciado:** O nome do arquivo de saída no CommandLineArguments é o dropper que o LNK grava depois do download. Qual o nome do arquivo de saida no CommandLineArguments?[cite: 6]
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Dropper Flag LNK - 10 pts
- **Enunciado:** Qual a flag encontrada na análise das propriedades ou payload embutido do atalho?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`