# 🔍 Resolução PCAP: captura.pcap

- **Alvo:** `captura.pcap`[cite: 5]
- **Ambiente:** Transnorte / Estação de Finanças (`TN-FIN-WS042`)[cite: 5]
- **Status:** Em resolução

---

### 01. Hostname TN-FIN - 10 pts
- **Enunciado:** Qual o hostname enviado pela estação no DHCP?[cite: 5]
- **Análise / Resolução:**
  <!-- Explique seu raciocínio, filtro utilizado e insira os prints aqui -->
  
  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Lease TN-FIN - 10 pts
- **Enunciado:** Qual IPv4 a estação recebeu no DHCP ACK (yiaddr)?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. MAC TN-FIN - 10 pts
- **Enunciado:** Qual o MAC da estação 10.50.10.42?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Gateway TN-FIN - 10 pts
- **Enunciado:** Qual o gateway anunciado na opção DHCP router?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. DNS TN-FIN - 10 pts
- **Enunciado:** Qual o servidor DNS anunciado no DHCP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Dominio TN-FIN - 10 pts
- **Enunciado:** Qual o domain name anunciado no DHCP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. User FTP - 10 pts
- **Enunciado:** Usuário da sessão FTP interna.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Senha FTP - 10 pts
- **Enunciado:** Senha enviada no tráfego FTP.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Mapa SE-03 - 10 pts
- **Enunciado:** Qual o arquivo baixado via RETR no FTP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Host FTP - 10 pts
- **Enunciado:** Qual o IP do servidor FTP?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. Atualizador fantasma - 10 pts
- **Enunciado:** Identificação do binário/atualizador baixado.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. CDN falsa - 10 pts
- **Enunciado:** Domínio/Host simulando CDN IndusCom.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Heartbeat HTTP - 10 pts
- **Enunciado:** URI/Parâmetros do heartbeat HTTP periódico.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Notes HTTP - 10 pts
- **Enunciado:** No mesmo pcap a estação de trabalho baixou as release notes da IndusCom e o corpo desse objeto ainda carrega a marca do caso. Qual a flag no corpo das release notes da IndusCom?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 14](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 15. Inverno na intranet - 10 pts
- **Enunciado:** Houve um POST em claro para o login do OCC e o campo de senha estava no corpo desse pedido. Qual a senha enviada no POST de /api/auth/login?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. TXT backbone - 10 pts
- **Enunciado:** Fora da zona interna, uma resposta TXT de status.litoral-dns.net aparece neste pcap com conteúdo que não é diagnóstico de rede. Qual o conteúdo TXT de status.litoral-dns.net?[cite: 5, 14]
- **Análise / Resolução:**
  
  ![Evidência 16](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 17. Sync vendor - 10 pts
- **Enunciado:** Qual FQDN cdn-sync foi resolvido neste pcap?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. IP do sync - 10 pts
- **Enunciado:** Qual IPv4 foi retornado para cdn-sync.induscom-support.net?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. DNS falastrão - 10 pts
- **Enunciado:** Registro de consulta anômala no DNS.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. SNI TLS TN - 10 pts
- **Enunciado:** Nome TLS/SNI usado no Client Hello da TN-FIN.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. ICMP recado TN - 10 pts
- **Enunciado:** Recado/Flag exfiltrado via Echo ICMP.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 21](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 22. Cookie OCC - 10 pts
- **Enunciado:** Cookie de sessão do portal OCC.[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Basic OT - 10 pts
- **Enunciado:** Qual o par usuário:senha do HTTP Basic em tools.transnorte.local?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Banner OT - 10 pts
- **Enunciado:** Qual o cabeçalho Server HTTP do IndusCom HTTPD?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. WPAD TN - 10 pts
- **Enunciado:** Qual o Host HTTP usado no pedido WPAD?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Scan interno TN - 10 pts
- **Enunciado:** Qual IP interno enviou SYN para o maior número de portas distintas em 10.50.10.20?[cite: 5]
- **Análise / Resolução:**
  
  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:**