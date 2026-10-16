# 🔗 Resolução Cadeia: cg4200.deb

- **Alvo:** `cg4200.deb`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/cg4200.deb`
- **Ambiente:** Pacote Debian ICG-4200 / Estação TN-FIN
- **Status:** Em resolução

---

### 01. Deb ICG-4200 - 10 pts
- **Enunciado:** Este icg4200.deb é o pacote IndusCom que a Transnorte puxou como update do ICG-4200 na Campanha Relé, o .deb que a estação de finanças tratou como firmware oficial do gateway. Qual o nome Package?
- **Análise / Resolução:**
  <!-- Documente sua análise, inspeção dos campos de controle e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Versão deb - 10 pts
- **Enunciado:** A Version deste .deb é a mesma faixa que o vendor vendia como firmware 3.4 do ICG. Qual a Version do pacote?
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Maintainer - 10 pts
- **Enunciado:** O Maintainer no control tenta parecer suporte da IndusCom neste update da Transnorte. Qual o endereço de e-mail do Maintainer?
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Homepage deb - 10 pts
- **Enunciado:** Qual a Homepage declarada nos metadados de controle do pacote?
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. XB-Host - 10 pts
- **Enunciado:** Qual o valor do campo customizado XB-Host presente no arquivo control?
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Conf deb - 10 pts
- **Enunciado:** Qual o caminho/nome do arquivo de configuração instalado pelo pacote deb?
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. C2 deb - 10 pts
- **Enunciado:** Qual o endereço/URL de C2 configurado internamente nos arquivos do pacote?
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Dropper deb - 10 pts
- **Enunciado:** O path do update.bin no pacote é o dropper que o .deb deixa sob usr, fora do conf. Qual o path do update.bin no pacote?
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Flag deb - 10 pts
- **Enunciado:** O channel.txt deste .deb carrega a marca do caso do update ICG-4200. Qual a Flag no channel.txt do pacote?
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`