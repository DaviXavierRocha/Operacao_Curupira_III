# 📋 Resolução LOG: syslog.log

- **Alvo:** `syslog.log`[cite: 2]
- **Ambiente:** Servidor Linux / Concentrador VPN (`tn-vpn-01`)[cite: 3, 4]
- **Status:** Em resolução

---

### 01. Host VPN syslog - 10 pts
- **Enunciado:** Este syslog é o rastro de autenticação do concentrador atingido na Operação Relé, com força bruta externa e um login aceito na mesma janela em que a Transnorte ainda tratava o evento como rotina. Qual o hostname do equipamento que gerou o syslog?[cite: 3]
- **Análise / Resolução:**
  <!-- Documente sua análise e insira seus prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. Brute SSH - 10 pts
- **Enunciado:** Nas linhas event=failed_password deste syslog, a força bruta externa concentra as falhas numa única origem da faixa de documentação. Qual IP externo gerou o maior número de event=failed_password?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. Conta no brute - 10 pts
- **Enunciado:** Depois da chuva de falhas, o mesmo IP da força bruta teve um event=accepted_password neste syslog. Qual usuário teve event=accepted_password a partir do IP da força bruta?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. C2 no syslog - 10 pts
- **Enunciado:** O accepted_password desse IP ainda registra o src_host que a vítima apresentou no login bem-sucedido. Qual src_host aparece no login bem-sucedido desse IP?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Porta origem VPN - 10 pts
- **Enunciado:** Qual a porta de origem do acesso vindo do IP da força bruta?[cite: 2, 4]
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Hora do VPN - 10 pts
- **Enunciado:** Qual o timestamp/horário do login aceito vindo da força bruta?[cite: 2, 4]
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. PID da sessão - 10 pts
- **Enunciado:** O pid= do sshd nesse accepted_password de 198.51.100.88 amarra a sessão aceita no host. Qual o pid= do accepted_password vindo de 198.51.100.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Sudo no syslog - 10 pts
- **Enunciado:** Depois do acesso, alguém elevou privilégio com sudo no mesmo host deste syslog. Qual usuário executou event=sudo?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Comando sudo - 10 pts
- **Enunciado:** O cmd= passado ao sudo é o que o operador ou o implante rodou com root neste concentrador. Qual o cmd= executado via sudo?[cite: 4]
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. TTY sudo - 10 pts
- **Enunciado:** Qual TTY foi utilizado na execução do sudo?[cite: 2, 4]
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. User inventado - 10 pts
- **Enunciado:** A força bruta também tentou contas que o host nem tinha, e um user= se repete em event=invalid_user. Qual user= mais aparece em event=invalid_user?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Aviso syslog - 10 pts
- **Enunciado:** Uma linha event=notice deste syslog carrega a marca do caso no campo msg=, fora do ruído de sshd. Qual a flag no campo msg= de event=notice?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 13. VPN da estação - 10 pts
- **Enunciado:** Houve um event=vpn_connect no mesmo syslog, já depois da senha aceita na força bruta. Qual usuário fez event=vpn_connect?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Origem VPN - 10 pts
- **Enunciado:** O src= desse vpn_connect é o IP de onde o túnel foi montado no concentrador da Transnorte. Qual src= do event=vpn_connect?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. Scan no syslog - 10 pts
- **Enunciado:** Além do C2, um IP interno da Transnorte também aparece em failed_password neste syslog. Qual IP interno 10.50.10.88 aparece em failed_password?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. Volume brute - 10 pts
- **Enunciado:** A contagem de event=failed_password de 198.51.100.88 mede o volume da força bruta neste recorte. Quantas linhas de event=failed_password vem de 198.51.100.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. Chave OCC syslog - 10 pts
- **Enunciado:** A estação de finanças 10.50.10.42 também autenticou por chave, com user= no accepted_publickey. Qual user= teve accepted_publickey a partir de 10.50.10.42?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. Cron do aviso - 10 pts
- **Enunciado:** Os jobs CRON deste host ainda mostram qual conta o agendador usou no recorte da Relé. Qual user= aparece nos jobs CRON?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Facility SSH - 10 pts
- **Enunciado:** As linhas proc=sshd da força bruta compartilham a mesma facility= neste syslog. Qual facility= das linhas proc=sshd do brute force?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Sessão aberta - 10 pts
- **Enunciado:** O event=session_opened registra quem de fato abriu a sessão depois do accepted_password. Qual user= em event=session_opened?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. Iface VPN - 10 pts
- **Enunciado:** O vpn_connect nomeia a interface de túnel usada nesse acesso ao concentrador. Qual tun= no event=vpn_connect?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. Cwd sudo - 10 pts
- **Enunciado:** O cwd= do sudo mostra de que diretório o comando elevado foi disparado. Qual cwd= do evento sudo?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Proc do aviso - 10 pts
- **Enunciado:** O proc= da linha notice amarra a flag a um daemon específico, não ao sshd da força bruta. Qual proc= gerou event=notice com a flag?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. OpenVPN - 10 pts
- **Enunciado:** O proc= do vpn_connect identifica o binário que montou o túnel neste syslog. Qual proc= do event=vpn_connect?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. Link tunel - 10 pts
- **Enunciado:** As linhas proc=kernel event=link registram o state= da interface no incidente da Relé. Qual state= aparece nas linhas proc=kernel event=link?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Unit OpenVPN - 10 pts
- **Enunciado:** O systemd registrou a unit do OpenVPN no mesmo host deste syslog. Qual unit= openvpn nas linhas systemd?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:**