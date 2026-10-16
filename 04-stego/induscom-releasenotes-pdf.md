# 🖼️ Resolução Stego: IndusCom_ReleaseNotes.pdf

- **Alvo:** `IndusCom_ReleaseNotes.pdf`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/IndusCom_ReleaseNotes.pdf`[cite: 3]
- **Ambiente:** Boletim de Release IndusCom / Estação TN-FIN[cite: 4]
- **Status:** Em resolução

---

### 01. Boletim PDF - 10 pts
- **Enunciado:** Este PDF é o boletim de release da IndusCom baixado na estação de finanças da Transnorte na Campanha Relé, o documento que a estação de trabalho abriu como update legítimo do ICG-4200. Qual o Title do documento?[cite: 4]
- **Análise / Resolução:**
  <!-- Documente sua análise e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Autor PDF - 10 pts
- **Enunciado:** Qual o Author no metadado do PDF?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Operador PDF - 10 pts
- **Enunciado:** Qual o operador ou autor registrado nos campos adicionais do boletim?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Estação PDF - 10 pts
- **Enunciado:** O Station no metadado amarra o boletim à estação ou subestação citada no caso Relé. Qual o Station do PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Gateway PDF - 10 pts
- **Enunciado:** O Gateway no metadado nomeia o ICG que este boletim dizia atualizar. Qual o Gateway do PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Firmware PDF - 10 pts
- **Enunciado:** A versão de firmware no metadado é a que o boletim vendia como update da SE-03. Qual o Firmware no metadado do PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Build PDF - 10 pts
- **Enunciado:** O Build no metadado fecha a revisão do pacote que a estação de trabalho de finanças baixou. Qual o Build no metadado do PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Páginas PDF - 10 pts
- **Enunciado:** Qual o total de páginas registrado no documento?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Versão PDF - 10 pts
- **Enunciado:** Qual a versão de formato de arquivo PDF declarada no cabeçalho?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. PDF cifrado - 10 pts
- **Enunciado:** O arquivo indica criptografia ativa (campo Encrypted no metadado)?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. Largura página - 10 pts
- **Enunciado:** Qual a dimensão de largura da página do PDF?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Modelo no PDF - 10 pts
- **Enunciado:** O texto extraído ainda traz a linha Model: do ICG citado no boletim. Qual o modelo na linha Model: do texto extraido?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Site no PDF - 10 pts
- **Enunciado:** A linha Site: no texto aponta a subestação que o boletim mencionava. Qual o site na linha Site: do texto extraido?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. C2 no PDF - 10 pts
- **Enunciado:** Qual a URL de canal C2 mencionada no corpo do texto extraído?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. IP C2 PDF - 10 pts
- **Enunciado:** Qual o endereço IPv4 associado à infraestrutura do C2 no PDF?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Setpoint PDF - 10 pts
- **Enunciado:** A linha Setpoint: no texto é o valor que o boletim já antecipava para a SE-03. Qual o valor na linha Setpoint: do texto extraido?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Anexo PDF - 10 pts
- **Enunciado:** Há um arquivo embutido neste PDF, listado pelo pdfdetach, fora das páginas visíveis. Qual o nome do arquivo embutido listado pelo pdfdetach?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. Conteúdo anexo - 10 pts
- **Enunciado:** O embutido não é só nome: por dentro ainda tem a URL do canal da IndusCom. Qual a URL gravada no arquivo embutido?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Zip pos-EOF PDF - 10 pts
- **Enunciado:** Além do embutido, há um ZIP colado neste PDF com um arquivo relay. Qual o nome do arquivo relay dentro do zip colado no PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Flag zip PDF - 10 pts
- **Enunciado:** O relay.txt nesse ZIP colado carrega a marca do caso do boletim. Qual a flag dentro de relay.txt no zip colado no PDF?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`