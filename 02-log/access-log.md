# 📋 Resolução LOG: access.log

- **Alvo:** `access.log`[cite: 2]
- **Ambiente:** Servidor Web Apache (Portal OCC / IndusCom)[cite: 3]
- **Status:** Em resolução

---

### 27. Estação OCC - 10 pts
- **Enunciado:** Este access log Apache é o do portal OCC/IndusCom visto pela estação de finanças na Campanha Relé, com login, download das release notes e o heartbeat que não é de navegador. Qual IP fez o POST em /api/auth/login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Operador OCC - 10 pts
- **Enunciado:** A linha desse POST ainda registra o usuário que o portal OCC aceitou no login da Relé. Qual usuário autenticado nesse POST de login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta:** 

---

### 29. Status login OCC - 10 pts
- **Enunciado:** O status HTTP da resposta diz se o login em /api/auth/login passou ou foi rejeitado neste access log. Qual o status HTTP do POST em /api/auth/login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 29](caminho/para/imagem.png)
- **Resposta:** 

---

### 30. Hora login OCC - 10 pts
- **Enunciado:** O horário UTC desse POST marca quando a estação de trabalho autenticou no portal, no recorte da Relé. Qual o timestamp UTC do POST de login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 30](caminho/para/imagem.png)
- **Resposta:** 

---

### 31. Referer login OCC - 10 pts
- **Enunciado:** O Referer do POST mostra de qual página do portal o login do OCC foi enviado. Qual o referer do POST de login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 31](caminho/para/imagem.png)
- **Resposta:** 

---

### 32. Notes Apache - 10 pts
- **Enunciado:** O GET das release notes deixa o path que a estação de trabalho usou para baixar o boletim da IndusCom. Qual o path do download IndusCom_ReleaseNotes?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 32](caminho/para/imagem.png)
- **Resposta:** 

---

### 33. Vhost notes - 10 pts
- **Enunciado:** O Host desse GET denuncia o vhost em que o boletim da IndusCom estava servido. Qual o vhost (campo Host) do download das release notes?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 33](caminho/para/imagem.png)
- **Resposta:** 

---

### 34. Tam. notes - 10 pts
- **Enunciado:** O tamanho enviado nesse GET fecha o objeto que a estação de trabalho salvou como release notes. Quantos bytes foram enviados nesse download das release notes?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 34](caminho/para/imagem.png)
- **Resposta:** 

---

### 35. Updater Apache - 10 pts
- **Enunciado:** No mesmo access log, /v1/heartbeat é batido por um User-Agent que não é Chrome nem Firefox. Qual User-Agent não é navegador aparece em /v1/heartbeat? Envie no formato CTF{User-Agent}.[cite: 3]
- **Análise / Resolução:**

  ![Evidência 35](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 36. Beacon Apache - 10 pts
- **Enunciado:** O path do heartbeat no Apache é o equivalente em log do URI periódico visto no pcap da Transnorte. Qual o path do beacon HTTP no Apache?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 36](caminho/para/imagem.png)
- **Resposta:** 

---

### 37. Vhost beacon - 10 pts
- **Enunciado:** O Host do GET /v1/heartbeat é o vhost da CDN ou do portal usado pelo pulso do Obsidian. Qual o vhost do GET /v1/heartbeat?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 37](caminho/para/imagem.png)
- **Resposta:** 

---

### 38. Primeiro beacon - 10 pts
- **Enunciado:** O primeiro GET /v1/heartbeat neste access log marca quando o canal periódico acordou. Qual o timestamp UTC do primeiro GET /v1/heartbeat?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 38](caminho/para/imagem.png)
- **Resposta:** 

---

### 39. WPAD Apache - 10 pts
- **Enunciado:** A estação também pediu WPAD neste access log, com path próprio de autoconfig de proxy. Qual o path WPAD pedido neste access log?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 39](caminho/para/imagem.png)
- **Resposta:** 

---

### 40. Vhost WPAD - 10 pts
- **Enunciado:** O Host do WPAD neste log denuncia o nome usado na autoconfig de proxy da Transnorte. Qual o vhost do pedido WPAD?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 40](caminho/para/imagem.png)
- **Resposta:** 

---

### 41. Varredura 404 - 10 pts
- **Enunciado:** Alguém no segmento gerou a maior parte das respostas 404, como varredura de path no portal. Qual IP gerou o maior número de respostas 404?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 41](caminho/para/imagem.png)
- **Resposta:** 

---

### 42. Volume 404 - 10 pts
- **Enunciado:** A contagem de 404 de 10.50.10.88 mede o volume dessa varredura interna neste access log. Quantas linhas 404 vem de 10.50.10.88?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 42](caminho/para/imagem.png)
- **Resposta:** 

---

### 43. Ferramenta OT - 10 pts
- **Enunciado:** Um path específico respondeu 401, o ponto em que a autenticação do portal falhou. Qual o path que devolveu HTTP 401?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 43](caminho/para/imagem.png)
- **Resposta:** 

---

### 44. Vhost OT - 10 pts
- **Enunciado:** O Host da linha 401 denuncia em qual vhost a autenticação foi recusada. Qual o vhost da resposta 401?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 44](caminho/para/imagem.png)
- **Resposta:** 

---

### 45. User OT - 10 pts
- **Enunciado:** A linha 401 ainda registra o usuário tentado nesse path do portal. Qual usuário aparece na linha do 401?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 45](caminho/para/imagem.png)
- **Resposta:** 

---

### 46. Webshell Apache - 10 pts
- **Enunciado:** O C2 198.51.100.88 também aparece neste access log, pedindo um path específico. Qual path o IP 198.51.100.88 requisitou?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 46](caminho/para/imagem.png)
- **Resposta:** 

---

### 47. Query webshell - 10 pts
- **Enunciado:** O pedido a /vendor/sync.php carrega a query string do canal de sync do vendor. Qual query string o C2 enviou em /vendor/sync.php?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 47](caminho/para/imagem.png)
- **Resposta:** 

---

### 48. Build escondido - 10 pts
- **Enunciado:** O path escondido /vendor/.sync/build ainda leva a marca do caso na query string. Qual a flag na query string de /vendor/.sync/build?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 48](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`

---

### 49. Dashboard OCC - 10 pts
- **Enunciado:** Depois do POST de login, o cliente pediu o dashboard do OCC neste access log. Qual o path do dashboard OCC acessado após o login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 49](caminho/para/imagem.png)
- **Resposta:** 

---

### 50. Metodo login - 10 pts
- **Enunciado:** O método da linha de /api/auth/login confirma se foi POST de formulário ou outro verbo. Qual o metodo HTTP usado em /api/auth/login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 50](caminho/para/imagem.png)
- **Resposta:** 

---

### 51. Scanner UA - 10 pts
- **Enunciado:** Os 404 de 10.50.10.88 compartilham um User-Agent de ferramenta, não de mesa. Qual User-Agent o IP 10.50.10.88 usou nos 404?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 51](caminho/para/imagem.png)
- **Resposta:** 

---

### 52. Next login - 10 pts
- **Enunciado:** O POST de login também carregou query string além do corpo neste access log. Qual a query string do POST de login?[cite: 3]
- **Análise / Resolução:**

  ![Evidência 52](caminho/para/imagem.png)
- **Resposta:**