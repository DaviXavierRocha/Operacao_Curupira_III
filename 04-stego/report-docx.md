# 🖼️ Resolução Stego: report.docx

- **Alvo:** `report.docx`[cite: 3]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/report.docx`[cite: 3]
- **Ambiente:** Relatório de Incidente OCC / SE-03[cite: 4]
- **Status:** Em resolução

---

### 38. Relatório DOCX - 10 pts
- **Enunciado:** Este DOCX é o relatório de incidente do OCC da Transnorte sobre a subestação SE-03 na Campanha Relé, redigido quando o despacho ainda classificava a escrita anômala como falha de campo. Qual o dc:title em docProps/core.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 38](caminho/para/imagem.png)
- **Resposta:** 

---

### 39. Autor DOCX - 10 pts
- **Enunciado:** Qual o dc:creator em docProps/core.xml?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 39](caminho/para/imagem.png)
- **Resposta:** 

---

### 40. Assunto DOCX - 10 pts
- **Enunciado:** Qual o dc:subject presente nos metadados core.xml?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 40](caminho/para/imagem.png)
- **Resposta:** 

---

### 41. Keywords DOCX - 10 pts
- **Enunciado:** Quais as cp:keywords declaradas em core.xml?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 41](caminho/para/imagem.png)
- **Resposta:** 

---

### 42. Identificador - 10 pts
- **Enunciado:** Qual o dc:identifier registrado no documento?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 42](caminho/para/imagem.png)
- **Resposta:** 

---

### 43. Categoria DOCX - 10 pts
- **Enunciado:** Qual o valor de cp:category nos metadados do documento?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 43](caminho/para/imagem.png)
- **Resposta:** 

---

### 44. Criação DOCX - 10 pts
- **Enunciado:** Qual a data/hora UTC de dcterms:created?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 44](caminho/para/imagem.png)
- **Resposta:** 

---

### 45. Empresa DOCX - 10 pts
- **Enunciado:** Qual a Company informada em docProps/app.xml?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 45](caminho/para/imagem.png)
- **Resposta:** 

---

### 46. App DOCX - 10 pts
- **Enunciado:** Qual o Application gerador registrado em docProps/app.xml?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 46](caminho/para/imagem.png)
- **Resposta:** 

---

### 47. Setpoint DOCX - 10 pts
- **Enunciado:** O corpo do relatório ainda cita o Setpoint: anômalo da SE-03 no document.xml. Qual o valor na linha Setpoint: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 47](caminho/para/imagem.png)
- **Resposta:** 

---

### 48. Gateway DOCX - 10 pts
- **Enunciado:** A linha Gateway: no corpo nomeia o ICG que o OCC associou ao incidente. Qual o hostname na linha Gateway: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 48](caminho/para/imagem.png)
- **Resposta:** 

---

### 49. Origem cmd DOCX - 10 pts
- **Enunciado:** A linha Src: no corpo aponta o IP que o OCC registrou como origem da escrita. Qual o IP na linha Src: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 49](caminho/para/imagem.png)
- **Resposta:** 

---

### 50. C2 DOCX - 10 pts
- **Enunciado:** A linha C2: no relatório leva a URL do canal que o OCC já tinha visto. Qual a URL na linha C2: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 50](caminho/para/imagem.png)
- **Resposta:** 

---

### 51. Firmware DOCX - 10 pts
- **Enunciado:** A linha Firmware: no corpo fecha a versão do gateway no relato do OCC. Qual o valor na linha Firmware: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 51](caminho/para/imagem.png)
- **Resposta:** 

---

### 52. Estação DOCX - 10 pts
- **Enunciado:** A linha Station: nomeia a estação ou subestação neste relato do OCC. Qual o hostname na linha Station: do document.xml?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 52](caminho/para/imagem.png)
- **Resposta:** 

---

### 53. Comentário zip - 10 pts
- **Enunciado:** Qual o comentário do contêiner ZIP deste arquivo .docx?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 53](caminho/para/imagem.png)
- **Resposta:** 

---

### 54. Arquivo oculto - 10 pts
- **Enunciado:** Qual arquivo oculto/adicional foi inserido dentro da estrutura compactada do DOCX?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 54](caminho/para/imagem.png)
- **Resposta:** 

---

### 55. Flag hint DOCX - 10 pts
- **Enunciado:** Qual a flag ou dica contida no arquivo oculto/mídia dentro do DOCX?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 55](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`