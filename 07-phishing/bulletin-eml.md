# 🎣 Resolução Phishing: bulletin.eml

- **Alvo:** `bulletin.eml`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/bulletin.eml`
- **Ambiente:** Caixa postal da estação de finanças (TN-FIN) / Incidente IndusCom
- **Status:** Em resolução

---

### 01. Boletim falso - 10 pts
- **Enunciado:** Este bulletin.eml é o boletim falso da IndusCom que chegou na caixa da estação de finanças da Transnorte na Campanha Relé, o recado que a estação de trabalho de ops.cardoso abriu como se fosse aviso oficial do vendor. Qual o endereço de e-mail do destinatário To?
- **Análise / Resolução:**
  <!-- Documente sua análise dos cabeçalhos, etapas e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. From boletim - 10 pts
- **Enunciado:** O From declarado neste bulletin tenta parecer suporte da IndusCom, não o domínio do canal que devolve a resposta. Qual o endereço de e-mail do From declarado?
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Return-Path - 10 pts
- **Enunciado:** O Return-Path deste boletim, sem os sinais de agrupamento, denuncia o envelope real do envio. Qual o Return-Path (sem <> )?
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Reply-To - 10 pts
- **Enunciado:** O Reply-To deste bulletin aponta para onde a estação de trabalho da Transnorte responderia se clicasse em responder. Qual o endereço de e-mail do Reply-To?
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Assunto boletim - 10 pts
- **Enunciado:** O Subject deste boletim é o gancho que a IndusCom falsa usou na caixa da TN-FIN. Qual o Subject?
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Message-ID - 10 pts
- **Enunciado:** O Message-ID deste bulletin, sem os sinais de agrupamento, amarra a mensagem ao domínio do canal. Qual o Message-ID (sem <> )?
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Portal boletim - 10 pts
- **Enunciado:** A URL do portal no corpo é o link que o boletim mandava a estação de trabalho da Transnorte abrir. Qual a URL do portal no corpo?
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Flag boletim - 10 pts
- **Enunciado:** A Flag no corpo deste bulletin.eml é a marca do phish da Relé na caixa de finanças. Qual a Flag no corpo?
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`