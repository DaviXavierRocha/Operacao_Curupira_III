# 🗄️ Resolução SQLite: historian.db

- **Alvo:** `historian.db`
- **Ambiente:** SCADA / Historian SE-03 (Subestação Transnorte)
- **Status:** Em resolução

---

### 27. Historian SE-03 - 10 pts
- **Enunciado:** Este arquivo é o export SQLite do historian da subestação SE-03 da Transnorte, ligado ao gateway IndusCom da Campanha Relé, onde o setpoint anômalo ficou gravado como se fosse operação de campo. Qual value em meta tem key host?
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Site historian - 10 pts
- **Enunciado:** A meta.site identifica a subestação neste historian da SE-03. Qual value em meta tem key site?
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Produto historian - 10 pts
- **Enunciado:** A meta.product nomeia o produto que gerou este SQLite de campo. Qual value em meta tem key product?
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Fornecedor hist - 10 pts
- **Enunciado:** Qual o fornecedor (vendor) registrado nos metadados deste banco historian?
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. Modelo historian - 10 pts
- **Enunciado:** Qual o modelo do equipamento registrado na tabela de metadados do historian?
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. Firmware hist - 10 pts
- **Enunciado:** A meta.firmware é a versão que o historian registrou para o ICG da SE-03. Qual value em meta tem key firmware?
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta:** 

---

### 33. Mestre historian - 10 pts
- **Enunciado:** A meta.master é o IPv4 do mestre OCC neste historian. Qual value em meta tem key master?
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Escravo hist - 10 pts
- **Enunciado:** A meta.slave é o IPv4 do gateway ou slave na SE-03. Qual value em meta tem key slave?
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta:** 

---

### 35. Tag setpoint - 10 pts
- **Enunciado:** O mapa de tags deste historian nomeia o holding 40081 além do setpoint. Qual name da tag com address 40081?
- **Análise / Resolução:**

  ![Evidência 35](caminho/para/imagem.png)
- **Resposta:** 

---

### 36. Unit setpoint - 10 pts
- **Enunciado:** Qual o unit ID associado ao ponto de medição ou controle do setpoint?
- **Análise / Resolução:**

  ![Evidência 36](caminho/para/imagem.png)
- **Resposta:** 

---

### 37. Origem telemetria - 10 pts
- **Enunciado:** Qual o endereço de origem registrado para os envios rotineiros de telemetria no historian?
- **Análise / Resolução:**

  ![Evidência 37](caminho/para/imagem.png)
- **Resposta:** 

---

### 38. Origem cmd hist - 10 pts
- **Enunciado:** Qual o endereço IP de origem registrado para a emissão de comandos de escrita no historian?
- **Análise / Resolução:**

  ![Evidência 38](caminho/para/imagem.png)
- **Resposta:** 

---

### 39. Setpoint ruim hist - 10 pts
- **Enunciado:** Qual o valor anômalo gravado na alteração indevida de setpoint?
- **Análise / Resolução:**

  ![Evidência 39](caminho/para/imagem.png)
- **Resposta:** 

---

### 40. Setpoint anterior - 10 pts
- **Enunciado:** O old_value da primeira escrita de 10.50.10.88 mostra o setpoint que estava válido antes do ensaio. Qual old_value da primeira escrita do 10.50.10.88?
- **Análise / Resolução:**

  ![Evidência 40](caminho/para/imagem.png)
- **Resposta:** 

---

### 41. 1a escrita hist - 10 pts
- **Enunciado:** O ts da primeira escrita de 10.50.10.88 neste historian deve cruzar com o log Modbus da SE-03. Qual ts da primeira escrita do 10.50.10.88?
- **Análise / Resolução:**

  ![Evidência 41](caminho/para/imagem.png)
- **Resposta:** 

---

### 42. Transação hist - 10 pts
- **Enunciado:** O txn dessa primeira escrita amarra o comando no historian ao pedido no momento. Qual txn da primeira escrita do 10.50.10.88?
- **Análise / Resolução:**

  ![Evidência 42](caminho/para/imagem.png)
- **Resposta:** 

---

### 43. Volume hist - 10 pts
- **Enunciado:** Qual o total de registros de eventos ou escritas armazenados na tabela principal de histórico?
- **Análise / Resolução:**

  ![Evidência 43](caminho/para/imagem.png)
- **Resposta:** 

---

### 44. FC escrita hist - 10 pts
- **Enunciado:** Qual o código de função (function code) utilizado nas escritas registradas no historian?
- **Análise / Resolução:**

  ![Evidência 44](caminho/para/imagem.png)
- **Resposta:** 

---

### 45. Bobina hist - 10 pts
- **Enunciado:** Qual valor ou estado foi atribuído na alteração da bobina registrada no historian?
- **Análise / Resolução:**

  ![Evidência 45](caminho/para/imagem.png)
- **Resposta:** 

---

### 46. Tag bobina - 10 pts
- **Enunciado:** Qual o identificador ou nome da tag correspondente à bobina alterada?
- **Análise / Resolução:**

  ![Evidência 46](caminho/para/imagem.png)
- **Resposta:** 

---

### 47. Probe C2 hist - 10 pts
- **Enunciado:** Qual endereço IP suspeito de C2 realizou probe ou tentativa de comunicação na base?
- **Análise / Resolução:**

  ![Evidência 47](caminho/para/imagem.png)
- **Resposta:** 

---

### 48. Qualidade ruim - 10 pts
- **Enunciado:** Qual registro ou valor de leitura apresentou flag de qualidade ruim (bad quality) no monitoramento?
- **Análise / Resolução:**

  ![Evidência 48](caminho/para/imagem.png)
- **Resposta:** 

---

### 49. Volume tags - 10 pts
- **Enunciado:** A contagem de tags fecha o mapa de pontos que este historian da SE-03 conhecia. Quantas linhas existem na tabela tags?
- **Análise / Resolução:**

  ![Evidência 49](caminho/para/imagem.png)
- **Resposta:** 

---

### 50. Endereço tensão - 10 pts
- **Enunciado:** O address de SE03_V_AB é o holding de tensão que o OCC de fato polava. Qual address da tag SE03_V_AB?
- **Análise / Resolução:**

  ![Evidência 50](caminho/para/imagem.png)
- **Resposta:** 

---

### 51. Hora bobina - 10 pts
- **Enunciado:** Qual o timestamp da gravação do evento que modificou o estado da bobina?
- **Análise / Resolução:**

  ![Evidência 51](caminho/para/imagem.png)
- **Resposta:** 

---

### 52. Alarme critico - 10 pts
- **Enunciado:** Qual a mensagem ou flag associada ao registro de alarme de nível crítico?
- **Análise / Resolução:**

  ![Evidência 52](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`