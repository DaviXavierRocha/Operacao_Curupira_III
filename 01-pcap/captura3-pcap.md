# 🔍 Resolução PCAP: captura3.pcap

- **Alvo:** `captura3.pcap`[cite: 5]
- **Ambiente:** CLM (Câmara de Liquidação Mercantil / `CLM-MESA-014`)[cite: 5, 14, 17]
- **Status:** Em resolução

---

### 53. Hostname CLM - 10 pts
- **Enunciado:** Este pcap saiu da estação de trabalho da Câmara de Liquidação Mercantil na Operação Relé, no segmento em que o kit do Obsidian já autenticava na API interna da liquidação. Qual o hostname enviado pela estação no DHCP?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 53](caminho/para/imagem.png)
- **Resposta:** 

---

### 54. Lease CLM - 10 pts
- **Enunciado:** Qual IPv4 a estação recebeu no DHCP ACK?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 54](caminho/para/imagem.png)
- **Resposta:** 

---

### 55. MAC CLM - 10 pts
- **Enunciado:** Qual o MAC da estação 10.90.30.11?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 55](caminho/para/imagem.png)
- **Resposta:** 

---

### 56. Gateway CLM - 10 pts
- **Enunciado:** Qual o gateway anunciado na opção DHCP router?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 56](caminho/para/imagem.png)
- **Resposta:** 

---

### 57. DNS CLM - 10 pts
- **Enunciado:** Qual o servidor DNS anunciado no DHCP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 57](caminho/para/imagem.png)
- **Resposta:** 

---

### 58. Dominio CLM - 10 pts
- **Enunciado:** Qual o domain name anunciado no DHCP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 58](caminho/para/imagem.png)
- **Resposta:** 

---

### 59. Bind LDAP - 10 pts
- **Enunciado:** Conta utilizada na autenticação / bind LDAP.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 59](caminho/para/imagem.png)
- **Resposta:** 

---

### 60. Senha LDAP - 10 pts
- **Enunciado:** Senha utilizada no bind LDAP.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 60](caminho/para/imagem.png)
- **Resposta:** 

---

### 61. Arquivo TFTP - 10 pts
- **Enunciado:** Qual o arquivo pedido via TFTP RRQ?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 61](caminho/para/imagem.png)
- **Resposta:** 

---

### 62. User RADIUS - 10 pts
- **Enunciado:** Qual o User-Name do RADIUS Access-Request?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 62](caminho/para/imagem.png)
- **Resposta:** 

---

### 63. User MQTT - 10 pts
- **Enunciado:** Usuário no pacote MQTT CONNECT.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 63](caminho/para/imagem.png)
- **Resposta:** 

---

### 64. Senha MQTT - 10 pts
- **Enunciado:** Senha no pacote MQTT CONNECT.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 64](caminho/para/imagem.png)
- **Resposta:** 

---

### 65. Topico MQTT - 10 pts
- **Enunciado:** Qual o topic do MQTT PUBLISH?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 65](caminho/para/imagem.png)
- **Resposta:** 

---

### 66. ClientId MQTT - 10 pts
- **Enunciado:** Qual o clientId do MQTT CONNECT?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 66](caminho/para/imagem.png)
- **Resposta:** 

---

### 67. SRV LDAP - 10 pts
- **Enunciado:** Registro SRV de localização do LDAP.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 67](caminho/para/imagem.png)
- **Resposta:** 

---

### 68. Porta SRV - 10 pts
- **Enunciado:** Porta de serviço especificada na resposta SRV.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 68](caminho/para/imagem.png)
- **Resposta:** 

---

### 69. API key CLM - 10 pts
- **Enunciado:** Os pedidos autenticados da API da CLM carregam Bearer em claro neste pcap. Qual o token Bearer enviado para a API?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 69](caminho/para/imagem.png)
- **Resposta:** 

---

### 70. X-Forwarded-For - 10 pts
- **Enunciado:** O cabeçalho X-Forwarded-For denuncia o IP interno que o proxy viu na estação de trabalho da liquidação. Qual o IP em X-Forwarded-For?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 70](caminho/para/imagem.png)
- **Resposta:** 

---

### 71. SNI TLS CLM - 10 pts
- **Enunciado:** Qual o SNI TLS usado nas conexões para 198.51.100.66?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 71](caminho/para/imagem.png)
- **Resposta:** 

---

### 72. ICMP recado CLM - 10 pts
- **Enunciado:** Qual a flag no payload de um ICMP echo?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 72](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 73. Cookie CLM - 10 pts
- **Enunciado:** Qual o valor do cookie CLMSESS?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 73](caminho/para/imagem.png)
- **Resposta:** 

---

### 74. Sync liquidação - 10 pts
- **Enunciado:** Qual FQDN batch-sync foi resolvido neste pcap?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 74](caminho/para/imagem.png)
- **Resposta:** 

---

### 75. IP do sync CLM - 10 pts
- **Enunciado:** Endereço IP resolvido para o serviço de sync da CLM.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 75](caminho/para/imagem.png)
- **Resposta:** 

---

### 76. Agente CLM - 10 pts
- **Enunciado:** User-Agent das requisições disparadas pelo kit.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 76](caminho/para/imagem.png)
- **Resposta:** 

---

### 77. Host da API - 10 pts
- **Enunciado:** Nome de domínio/Host nas requisições da API interna.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 77](caminho/para/imagem.png)
- **Resposta:** 

---

### 78. Banner API - 10 pts
- **Enunciado:** Cabeçalho Server HTTP retornado pela API da liquidação.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 78](caminho/para/imagem.png)
- **Resposta:**