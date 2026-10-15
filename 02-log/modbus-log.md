# 📋 Resolução LOG: modbus.log

- **Alvo:** `modbus.log`[cite: 2]
- **Ambiente:** Subestação SE-03 / Gateway Modbus ICG-4200[cite: 3]
- **Status:** Em resolução

---

### 79. Gateway SE-03 - 10 pts
- **Enunciado:** Este log é o gateway Modbus TCP da subestação SE-03 da Transnorte, o primeiro evento de campo da Campanha Relé, quando um IP da rede corporativa escreveu o setpoint no lugar do OCC. Qual hostname aparece no campo host=?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 79](caminho/para/imagem.png)
- **Resposta:** 

---

### 80. Produto ICG - 10 pts
- **Enunciado:** O product= identifica o software do gateway Modbus que estava na SE-03 neste log. Qual product= do gateway?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 80](caminho/para/imagem.png)
- **Resposta:** 

---

### 81. Fornecedor ICG - 10 pts
- **Enunciado:** O vendor= do equipamento confirma a IndusCom no hardware ou software da SE-03. Qual vendor= do equipamento?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 81](caminho/para/imagem.png)
- **Resposta:** 

---

### 82. Modelo ICG - 10 pts
- **Enunciado:** O model= fecha a família ICG usada no gateway desta subestação. Qual model= do gateway?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 82](caminho/para/imagem.png)
- **Resposta:** 

---

### 83. Site SE-03 - 10 pts
- **Enunciado:** O site= é o código operacional da subestação neste log de campo da Relé. Qual site= identifica a subestação?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 83](caminho/para/imagem.png)
- **Resposta:** 

---

### 84. Protocolo OT - 10 pts
- **Enunciado:** O proto= das linhas confirma o protocolo industrial usado nos polls e nas escritas. Qual proto= nas linhas do log?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 84](caminho/para/imagem.png)
- **Resposta:** 

---

### 85. Porta 502 - 10 pts
- **Enunciado:** A dport= é a porta de serviço em que o mestre e o IP corporativo falaram com o gateway. Qual dport= do trafego?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 85](caminho/para/imagem.png)
- **Resposta:** 

---

### 86. Mestre OCC - 10 pts
- **Enunciado:** O mestre que mais gerou event=poll_ok é o OCC legítimo neste log da SE-03. Qual src= gerou o maior número de event=poll_ok?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 86](caminho/para/imagem.png)
- **Resposta:** 

---

### 87. Escravo ICG - 10 pts
- **Enunciado:** O dest= dos polls do OCC é o IPv4 do gateway na SE-03. Qual dest= dos polls do mestre OCC?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 87](caminho/para/imagem.png)
- **Resposta:** 

---

### 88. Unit operacional - 10 pts
- **Enunciado:** O unit= das escritas write_single aponta o slave Modbus que recebeu o setpoint. Qual unit= nos event=write_single?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 88](caminho/para/imagem.png)
- **Resposta:** 

---

### 89. FC escrita - 10 pts
- **Enunciado:** O function code das escritas single denuncia o tipo de holding escrito no gateway. Qual fc= nos event=write_single?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 89](caminho/para/imagem.png)
- **Resposta:** 

---

### 90. Reg setpoint - 10 pts
- **Enunciado:** O addr= é o holding de setpoint que o OCC e o IP corporativo tocaram. Qual addr= alterado nos event=write_single?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 90](caminho/para/imagem.png)
- **Resposta:** 

---

### 91. Setpoint ok - 10 pts
- **Enunciado:** O value= do OCC é o setpoint operacional esperado, antes da escrita anômala. Qual value= o mestre OCC escreveu no setpoint?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 91](caminho/para/imagem.png)
- **Resposta:** 

---

### 92. Setpoint anomalo - 10 pts
- **Enunciado:** O value= de 10.50.10.88 é o setpoint que não deveria ter vindo da rede corporativa. Qual value= escrito pelo IP da rede corporativa 10.50.10.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 92](caminho/para/imagem.png)
- **Resposta:** 

---

### 93. Origem comando - 10 pts
- **Enunciado:** Quem mais gerou event=write_single neste log não é ruído: é a origem das alterações de setpoint. Qual src= gerou o maior número de event=write_single?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 93](caminho/para/imagem.png)
- **Resposta:** 

---

### 94. 1a escrita ruim - 10 pts
- **Enunciado:** Qual o timestamp UTC da primeira escrita do 10.50.10.88?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 94](caminho/para/imagem.png)
- **Resposta:** 

---

### 95. Transação MB - 10 pts
- **Enunciado:** O txn= da primeira escrita de 10.50.10.88 amarra o pedido Modbus anômalo neste log. Qual txn= da primeira escrita do 10.50.10.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 95](caminho/para/imagem.png)
- **Resposta:** 

---

### 96. Volume escrita - 10 pts
- **Enunciado:** A contagem de write_single de 10.50.10.88 mede quantas vezes o IP corporativo tocou o gateway. Quantas linhas event=write_single tem src=10.50.10.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 96](caminho/para/imagem.png)
- **Resposta:** 

---

### 97. Bobina - 10 pts
- **Enunciado:** Além do holding, houve write_coil com function code próprio neste log da SE-03. Qual fc= no event=write_coil?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 97](caminho/para/imagem.png)
- **Resposta:** 

---

### 98. Endereço bobina - 10 pts
- **Enunciado:** O addr= da bobina é o ponto discreto alterado no ensaio de campo. Qual addr= do write_coil?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 98](caminho/para/imagem.png)
- **Resposta:** 

---

### 99. Valor bobina - 10 pts
- **Enunciado:** Qual value= escrito na bobina?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 99](caminho/para/imagem.png)
- **Resposta:** 

---

### 100. Exceção MB - 10 pts
- **Enunciado:** Qual exception= no event=exception?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 100](caminho/para/imagem.png)
- **Resposta:** 

---

### 101. Unit ilegal - 10 pts
- **Enunciado:** O unit= da exception aponta qual slave rejeitou o pedido neste log. Qual unit= provocou a exception?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 101](caminho/para/imagem.png)
- **Resposta:** 

---

### 102. Probe C2 MB - 10 pts
- **Enunciado:** Houve um event=session_probe de uma origem que não é o OCC neste log da SE-03. Qual src= do event=session_probe?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 102](caminho/para/imagem.png)
- **Resposta:** 

---

### 103. Firmware ICG - 10 pts
- **Enunciado:** O firmware= no log fecha a versão do ICG que estava na SE-03 na Relé. Qual firmware= do gateway?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 103](caminho/para/imagem.png)
- **Resposta:** 

---

### 104. Diag do rele - 10 pts
- **Enunciado:** A linha de diagnóstico ainda carrega a marca do caso no campo notes= do event=diag. Qual a flag no campo notes= do event=diag?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 104](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`