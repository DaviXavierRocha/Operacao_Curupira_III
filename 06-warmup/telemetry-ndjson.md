# ⚡ Resolução Warmup: telemetry.ndjson

- **Alvo:** `telemetry.ndjson`[cite: 2]
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/telemetry.ndjson`[cite: 2]
- **Ambiente:** Exportação EDR / SOC Transnorte[cite: 7]
- **Status:** Em resolução

---

### 45. Telemetria EDR - 10 pts
- **Enunciado:** Este telemetry.ndjson é o export EDR da abertura do caso da Campanha Relé na Transnorte, o primeiro objeto JSON em que o SOC amarra host, operador e o sync do vendor. Qual o host no evento case_open?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 45](caminho/para/imagem.png)
- **Resposta:** 

---

### 46. Operador EDR - 10 pts
- **Enunciado:** Qual o operador responsável citado no evento de abertura de caso?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 46](caminho/para/imagem.png)
- **Resposta:** 

---

### 47. Caso EDR - 10 pts
- **Enunciado:** Qual o código/identificador do caso (IR) registrado no evento?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 47](caminho/para/imagem.png)
- **Resposta:** 

---

### 48. Site EDR - 10 pts
- **Enunciado:** Qual o site operacional registrado na telemetria?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 48](caminho/para/imagem.png)
- **Resposta:** 

---

### 49. Objetos JSON - 10 pts
- **Enunciado:** Quantos objetos JSON (linhas) compõem este arquivo telemetry.ndjson?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 49](caminho/para/imagem.png)
- **Resposta:** 

---

### 50. Tipos event - 10 pts
- **Enunciado:** Quantos tipos distintos de eventos (event types) aparecem na telemetria?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 50](caminho/para/imagem.png)
- **Resposta:** 

---

### 51. Heartbeats TN - 10 pts
- **Enunciado:** Quantos eventos de heartbeat foram registrados especificamente para a estação da Transnorte?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 51](caminho/para/imagem.png)
- **Resposta:** 

---

### 52. IP vendor_sync - 10 pts
- **Enunciado:** Qual o endereço IP associado aos eventos do tipo vendor_sync?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 52](caminho/para/imagem.png)
- **Resposta:** 

---

### 53. C2 vendor_sync - 10 pts
- **Enunciado:** Qual a URL/destino de C2 apontada nos eventos vendor_sync?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 53](caminho/para/imagem.png)
- **Resposta:** 

---

### 54. UA vendor_sync - 10 pts
- **Enunciado:** O ua do vendor_sync é o agente que o EDR viu no sync. Qual o ua do evento vendor_sync?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 54](caminho/para/imagem.png)
- **Resposta:** 

---

### 55. Intervalo sync - 10 pts
- **Enunciado:** O interval do vendor_sync é o período do canal neste evento. Qual o interval do evento vendor_sync?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 55](caminho/para/imagem.png)
- **Resposta:** 

---

### 56. Gateway EDR - 10 pts
- **Enunciado:** O gateway do vendor_sync nomeia o ICG associado ao sync. Qual o gateway do evento vendor_sync?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 56](caminho/para/imagem.png)
- **Resposta:** 

---

### 57. Modelo EDR - 10 pts
- **Enunciado:** O model do vendor_sync fecha a família do equipamento neste evento. Qual o model do evento vendor_sync?[cite: 7]
- **Análise / Resolução:**

  ![Evidência 57](caminho/para/imagem.png)
- **Resposta:** 

---

### 58. Flag EDR - 10 pts
- **Enunciado:** Qual a flag registrada nos metadados ou na carga útil do evento da telemetria EDR?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 58](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`