# 🎣 Resolução Phishing: helpdesk.mbox

- **Alvo:** `helpdesk.mbox`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/helpdesk.mbox`
- **Ambiente:** Caixa helpdesk@litoral.telecom / Litoral Telecom
- **Status:** Em resolução

---

### 09. Helpdesk mbox - 10 pts
- **Enunciado:** Este helpdesk.mbox é o export da caixa helpdesk@litoral.telecom da Litoral Telecom na Campanha Relé, o volume em que um lure da IndusCom ficou misturado ao chamado real do helpdesk. Quantas mensagens há no mbox?
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. From lure - 10 pts
- **Enunciado:** O From da mensagem da campanha neste mbox é o endereço que o lure usou para parecer suporte do vendor. Qual o endereço From da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. To lure - 10 pts
- **Enunciado:** O To da mensagem da campanha aponta a caixa da Litoral que o lure escolheu neste mbox. Qual o endereço To da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Return-Path lure - 10 pts
- **Enunciado:** O Return-Path da mensagem da campanha, sem os sinais de agrupamento, denuncia o envelope deste lure. Qual o Return-Path da mensagem da campanha (sem <> )?
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Reply-To lure - 10 pts
- **Enunciado:** O Reply-To da mensagem da campanha é para onde a Litoral responderia se tratasse o lure como ticket. Qual o endereço Reply-To da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Message-ID lure - 10 pts
- **Enunciado:** O Message-ID da mensagem da campanha, sem os sinais de agrupamento, identifica o lure no meio do helpdesk. Qual o Message-ID da mensagem da campanha (sem <> )?
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. IP Received - 10 pts
- **Enunciado:** O IPv4 no Received da mensagem da campanha é o salto que entregou o lure na caixa da Litoral. Qual o IPv4 no Received da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Portal lure - 10 pts
- **Enunciado:** A URL do portal no corpo da mensagem da campanha é o link DNS falso que o lure mandava abrir. Qual a URL do portal no corpo da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Flag lure - 10 pts
- **Enunciado:** A Flag no corpo da mensagem da campanha é a marca deste lure no mbox da Litoral. Qual a Flag no corpo da mensagem da campanha?
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`