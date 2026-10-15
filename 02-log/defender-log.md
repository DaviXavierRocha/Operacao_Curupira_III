# 📋 Resolução LOG: defender.log

- **Alvo:** `defender.log`[cite: 2]
- **Ambiente:** Microsoft Defender Antivirus / Estação TN-FIN[cite: 3]
- **Status:** Em resolução

---

### 53. Host Defender - 10 pts
- **Enunciado:** Este log é o antivírus da estação de finanças da Transnorte atingida na Campanha Relé, o primeiro alarme de host contra o updater da IndusCom e o webshell que veio no mesmo pacote. Qual hostname aparece no campo host=?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 53](caminho/para/imagem.png)
- **Resposta:** 

---

### 54. IP Defender - 10 pts
- **Enunciado:** O src_ip= das detecções amarra o alerta à estação de finanças, não a um servidor. Qual src_ip= da estação nas detecções de malware?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 54](caminho/para/imagem.png)
- **Resposta:** 

---

### 55. Produto Defender - 10 pts
- **Enunciado:** O product= diz qual motor de AV ou EDR escreveu estas linhas na estação de trabalho da Transnorte. Qual product= gerou o log?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 55](caminho/para/imagem.png)
- **Resposta:** 

---

### 56. Ameaca principal - 7 pts
- **Enunciado:** Qual threat= associado ao updater da IndusCom?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 56](caminho/para/imagem.png)
- **Resposta:** 

---

### 57. Path updater - 10 pts
- **Enunciado:** Qual path= do Trojan ObsidianUpdater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 57](caminho/para/imagem.png)
- **Resposta:** 

---

### 58. Hash updater - 10 pts
- **Enunciado:** Qual sha256= do update.exe da IndusCom?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 58](caminho/para/imagem.png)
- **Resposta:** 

---

### 59. PID malware - 10 pts
- **Enunciado:** Qual pid= do processo ObsidianUpdater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 59](caminho/para/imagem.png)
- **Resposta:** 

---

### 60. Pai malware - 10 pts
- **Enunciado:** Qual parent= do updater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 60](caminho/para/imagem.png)
- **Resposta:** 

---

### 61. Ação Defender - 10 pts
- **Enunciado:** Qual action= o Defender tomou no ObsidianUpdater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 61](caminho/para/imagem.png)
- **Resposta:** 

---

### 62. Severidade - 10 pts
- **Enunciado:** A severity= da primeira detecção do updater mede o peso que o produto deu ao alerta. Qual severity= da detecção ObsidianUpdater?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 62](caminho/para/imagem.png)
- **Resposta:** 

---

### 63. Primeira detecção - 10 pts
- **Enunciado:** O horário UTC da primeira detecção marca quando o host finalmente viu o updater da IndusCom. Qual o timestamp UTC da primeira detecção do updater?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 63](caminho/para/imagem.png)
- **Resposta:** 

---

### 64. User logado - 10 pts
- **Enunciado:** O user= das detecções é a conta da estação de trabalho em que o binário do vendor rodou. Qual user= nas detecções de malware nesta estação?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 64](caminho/para/imagem.png)
- **Resposta:** 

---

### 65. C2 bloqueado - 10 pts
- **Enunciado:** O event=network_block registrou a URL que o host tentou alcançar depois do drop. Qual url= o Defender bloqueou no event=network_block?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 65](caminho/para/imagem.png)
- **Resposta:** 

---

### 66. IP C2 Defender - 10 pts
- **Enunciado:** Qual dest= do network_block?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 66](caminho/para/imagem.png)
- **Resposta:** 

---

### 67. Webshell Defender - 10 pts
- **Enunciado:** Qual threat= do webshell PHP?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 67](caminho/para/imagem.png)
- **Resposta:** 

---

### 68. Path webshell - 10 pts
- **Enunciado:** Qual path= do webshell detectado?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 68](caminho/para/imagem.png)
- **Resposta:** 

---

### 69. Hash webshell - 10 pts
- **Enunciado:** Qual o hash sha256 atribuído ao webshell?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 69](caminho/para/imagem.png)
- **Resposta:** 

---

### 70. Motor Defender - 10 pts
- **Enunciado:** Qual engine= nas detecções ObsidianUpdater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 70](caminho/para/imagem.png)
- **Resposta:** 

---

### 71. Assinaturas - 10 pts
- **Enunciado:** Qual signatures= nas detecções ObsidianUpdater?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 71](caminho/para/imagem.png)
- **Resposta:** 

---

### 72. Classificação - 10 pts
- **Enunciado:** A classification= diz como o produto enquadrou o ObsidianUpdater nesta estação. Qual classification= do ObsidianUpdater?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 72](caminho/para/imagem.png)
- **Resposta:** 

---

### 73. RTP - 10 pts
- **Enunciado:** As linhas event=rtp_ok registram o estado da proteção em tempo real no host da Transnorte. Qual rtp= nas linhas event=rtp_ok?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 73](caminho/para/imagem.png)
- **Resposta:** 

---

### 74. PUA - 10 pts
- **Enunciado:** Houve detecções PUA além do Trojan, com threat= próprio neste log. Qual threat= das detecções PUA?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 74](caminho/para/imagem.png)
- **Resposta:** 

---

### 75. Volume updater - 10 pts
- **Enunciado:** A contagem de event=malware_detected com ObsidianUpdater mede quantas vezes o host alertou o mesmo binário. Quantas linhas event=malware_detected citam ObsidianUpdater?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 75](caminho/para/imagem.png)
- **Resposta:** 

---

### 76. Notes Defender - 10 pts
- **Enunciado:** Qual arquivo IndusCom_ReleaseNotes foi varrido como clean?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 76](caminho/para/imagem.png)
- **Resposta:** 

---

### 77. Nota do scan - 10 pts
- **Enunciado:** Qual a flag no campo notes= do scan das release notes?[cite: 2]
- **Análise / Resolução:**

  ![Evidência 77](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 78. Ação webshell - 10 pts
- **Enunciado:** A action= do HackTool PHP diz o que o Defender fez com o sync.php nesta estação. Qual action= no HackTool PHP?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 78](caminho/para/imagem.png)
- **Resposta:**