# 🔗 Resolução Cadeia: clm-repo.tar

- **Alvo:** `clm-repo.tar`
- **Link do Alvo:** `https://download.gohacking.com.br/curupira3/clm-repo.tar`
- **Ambiente:** Dump de Repositório APT / CLM (Câmara de Liquidação Mercantil)
- **Status:** Em resolução

---

### 20. Repo CLM - 10 pts
- **Enunciado:** Qual a estrutura ou arquivo raiz de metadados do repositório APT contido no tarball?
- **Análise / Resolução:**

  ![Evidência 20](caminho/para/imagem.png)
- **Resposta:** 

---

### 21. Label repo - 10 pts
- **Enunciado:** O Label no InRelease identifica a casa de liquidação neste repo falso. Qual o Label no InRelease?
- **Análise / Resolução:**

  ![Evidência 21](caminho/para/imagem.png)
- **Resposta:** 

---

### 22. Suite repo - 10 pts
- **Enunciado:** O Suite no InRelease nomeia a linha deste repo da Relé, não uma distro pública. Qual o Suite no InRelease?
- **Análise / Resolução:**

  ![Evidência 22](caminho/para/imagem.png)
- **Resposta:** 

---

### 23. Codename repo - 10 pts
- **Enunciado:** O Codename no InRelease aponta a subestação que o vendor colou neste InRelease. Qual o Codename no InRelease?
- **Análise / Resolução:**

  ![Evidência 23](caminho/para/imagem.png)
- **Resposta:** 

---

### 24. Hash clearsign - 10 pts
- **Enunciado:** O Hash do PGP SIGNED MESSAGE no InRelease é o algoritmo que o clearsign declara. Qual o Hash do PGP SIGNED MESSAGE no InRelease?
- **Análise / Resolução:**

  ![Evidência 24](caminho/para/imagem.png)
- **Resposta:** 

---

### 25. SHA256 Packages - 10 pts
- **Enunciado:** Qual o hash SHA256 declarado no InRelease para o índice Packages?
- **Análise / Resolução:**

  ![Evidência 25](caminho/para/imagem.png)
- **Resposta:** 

---

### 26. Package CLM - 10 pts
- **Enunciado:** Qual o nome do pacote malicioso listado no arquivo Packages?
- **Análise / Resolução:**

  ![Evidência 26](caminho/para/imagem.png)
- **Resposta:** 

---

### 27. Filename pool - 10 pts
- **Enunciado:** Qual o caminho relativo (Filename) apontado no índice para o arquivo deb no pool?
- **Análise / Resolução:**

  ![Evidência 27](caminho/para/imagem.png)
- **Resposta:** 

---

### 28. Flag repo - 10 pts
- **Enunciado:** Qual a flag contida na assinatura ou nos arquivos internos deste repositório malicioso?
- **Análise / Resolução:**

  ![Evidência 28](caminho/para/imagem.png)
- **Resposta (Flag):** `CTF{...}`