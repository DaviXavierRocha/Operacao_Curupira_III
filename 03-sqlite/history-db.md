# 🗄️ Resolução SQLite: history.db

- **Alvo:** `history.db`
- **Ambiente:** Google Chrome / Estação TN-FIN
- **Status:** Em resolução

---

### 01. Host Chrome - 10 pts
- **Enunciado:** Este arquivo é o export SQLite do histórico do Chrome da estação de finanças da Transnorte na Campanha Relé, com o portal interno, o heartbeat da CDN e o download do update.exe na mesma timeline. Qual value em meta tem key host?
- **Análise / Resolução:**
  <!-- Documente sua consulta SQL, raciocínio e insira prints aqui -->

  ![Evidência 01](caminho/para/imagem.png)
- **Resposta:** 

---

### 02. User Chrome - 10 pts
- **Enunciado:** A tabela meta deste histórico ainda identifica a conta do perfil em que o Chrome da estação de trabalho rodou. Qual value em meta tem key user?
- **Análise / Resolução:**

  ![Evidência 02](caminho/para/imagem.png)
- **Resposta:** 

---

### 03. IP Chrome - 10 pts
- **Enunciado:** A meta.src_ip amarra este SQLite ao IPv4 da estação de finanças no caso Relé. Qual value em meta tem key src_ip?
- **Análise / Resolução:**

  ![Evidência 03](caminho/para/imagem.png)
- **Resposta:** 

---

### 04. Browser - 10 pts
- **Enunciado:** A meta.browser confirma o cliente usado na estação de trabalho de finanças quando o boletim da IndusCom foi aberto. Qual value em meta tem key browser?
- **Análise / Resolução:**

  ![Evidência 04](caminho/para/imagem.png)
- **Resposta:** 

---

### 05. Perfil Chrome - 10 pts
- **Enunciado:** A meta.profile aponta o path do perfil de onde este histórico do Chrome foi exportado. Qual value em meta tem key profile?
- **Análise / Resolução:**

  ![Evidência 05](caminho/para/imagem.png)
- **Resposta:** 

---

### 06. Página top - 10 pts
- **Enunciado:** Qual a URL mais visitada (maior visit_count) registrada no histórico de navegação?
- **Análise / Resolução:**

  ![Evidência 06](caminho/para/imagem.png)
- **Resposta:** 

---

### 07. Título OCC - 10 pts
- **Enunciado:** Qual o title registrado na navegação do portal OCC da Transnorte?
- **Análise / Resolução:**

  ![Evidência 07](caminho/para/imagem.png)
- **Resposta:** 

---

### 08. Volume OCC - 9 pts
- **Enunciado:** Qual o total de acessos (visit_count) somados para as páginas do domínio do portal OCC?
- **Análise / Resolução:**

  ![Evidência 08](caminho/para/imagem.png)
- **Resposta:** 

---

### 09. Login digitado - 10 pts
- **Enunciado:** Qual a URL ou termo de login registrado com transition do tipo typed pelo operador?
- **Análise / Resolução:**

  ![Evidência 09](caminho/para/imagem.png)
- **Resposta:** 

---

### 10. Beacon Chrome - 10 pts
- **Enunciado:** Qual a URL periódica de beacon/heartbeat que aparece registrada nas visitas?
- **Análise / Resolução:**

  ![Evidência 10](caminho/para/imagem.png)
- **Resposta:** 

---

### 11. 1o beacon Chrome - 8 pts
- **Enunciado:** Qual o timestamp da primeira visita registrada para o endpoint de beacon?
- **Análise / Resolução:**

  ![Evidência 11](caminho/para/imagem.png)
- **Resposta:** 

---

### 12. Transição beacon - 10 pts
- **Enunciado:** Qual o tipo de transição de navegação (page_transition) registrado para as requisições de beacon?
- **Análise / Resolução:**

  ![Evidência 12](caminho/para/imagem.png)
- **Resposta:** 

---

### 13. Volume C2 Chrome - 10 pts
- **Enunciado:** Quantas entradas ou visitas constam registradas no histórico direcionadas à infraestrutura do C2?
- **Análise / Resolução:**

  ![Evidência 13](caminho/para/imagem.png)
- **Resposta:** 

---

### 14. Webshell Chrome - 10 pts
- **Enunciado:** Qual a URL do webshell acessada ou registrada no histórico do navegador?
- **Análise / Resolução:**

  ![Evidência 14](caminho/para/imagem.png)
- **Resposta:** 

---

### 15. Drop updater - 10 pts
- **Enunciado:** O download do update.exe deixou o path de destino no perfil da estação de trabalho de finanças. Qual target_path do download update.exe?
- **Análise / Resolução:**

  ![Evidência 15](caminho/para/imagem.png)
- **Resposta:** 

---

### 16. URL updater - 10 pts
- **Enunciado:** A URL de origem do update.exe é de onde a estação de trabalho puxou o binário da IndusCom. Qual url do download update.exe?
- **Análise / Resolução:**

  ![Evidência 16](caminho/para/imagem.png)
- **Resposta:** 

---

### 17. MIME updater - 10 pts
- **Enunciado:** O MIME registrado nesse download denuncia que o update.exe não era o PDF de boletim. Qual mime do download update.exe?
- **Análise / Resolução:**

  ![Evidência 17](caminho/para/imagem.png)
- **Resposta:** 

---

### 18. Veredito DL - 10 pts
- **Enunciado:** O campo danger do Chrome registra como o navegador classificou o update.exe da IndusCom. Qual danger do download update.exe?
- **Análise / Resolução:**

  ![Evidência 18](caminho/para/imagem.png)
- **Resposta:** 

---

### 19. Referer updater - 10 pts
- **Enunciado:** O referrer do download amarra o update.exe à página que a estação de trabalho estava vendo no portal. Qual referrer do download update.exe?
- **Análise / Resolução:**

  ![Evidência 19](caminho/para/imagem.png)
- **Resposta:** 

---

### 20. Tam. updater - 10 pts
- **Enunciado:** O tamanho do update.exe fecha o objeto que depois vira ObsidianUpdater no antivírus. Qual total_bytes do download update.exe?
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. Hora do drop - 10 pts
- **Enunciado:** O start_time marca quando a estação de trabalho começou a puxar o binário da IndusCom. Qual start_time do download update.exe?
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. Notes Chrome - 10 pts
- **Enunciado:** O boletim também foi baixado e o target_path mostra onde a estação de trabalho salvou as release notes. Qual target_path do download IndusCom_ReleaseNotes?
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Tam. notes Chrome - 10 pts
- **Enunciado:** Qual o total de bytes transferidos registrado na tabela de downloads para o arquivo de release notes?
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Busca operador - 10 pts
- **Enunciado:** Qual termo de busca foi pesquisado pelo operador no histórico de palavras-chave/navegação?
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. Volume DLs - 10 pts
- **Enunciado:** A contagem de linhas na tabela downloads fecha quantos objetos a estação de trabalho puxou neste recorte. Quantas linhas existem na tabela downloads?
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. URL oculta - 10 pts
- **Enunciado:** Há uma URL marcada hidden = 1 cujo title carrega a marca do caso neste histórico. Qual title da url com hidden = 1?
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`