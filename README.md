# 🚩 Operação Curupira III — CTF Write-ups

Repositório dedicado à documentação técnica, análise forense e resolução dos desafios da **Operação Curupira III** (Campanha Relé / IndusCom / Transnorte).

---

## 📊 Progresso Geral

**Status Geral:** `15 / 487 Desafios Concluídos (3%)`

`[█░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░] 3%`

| Categoria | Concluídos | Total | Status | Arquivos / Write-ups |
| :--- | :---: | :---: | :---: | :--- |
| **01. PCAP** | 15 | 78 | 🟡 Em Andamento | [captura](01-pcap/captura-pcap.md) • [captura2](01-pcap/captura2-pcap.md) • [captura3](01-pcap/captura3-pcap.md) |
| **02. LOG** | 0 | 104 | ⚪ Não iniciado | [syslog](02-log/syslog-log.md) • [access](02-log/access-log.md) • [defender](02-log/defender-log.md) • [modbus](02-log/modbus-log.md) |
| **03. SQLite** | 0 | 78 | ⚪ Não iniciado | [history](03-sqlite/history-db.md) • [historian](03-sqlite/historian-db.md) • [vpn](03-sqlite/vpn-db.md) |
| **04. Stego** | 0 | 72 | ⚪ Não iniciado | [pdf](04-stego/induscom-releasenotes-pdf.md) • [jpg](04-stego/se03-jpg.md) • [docx](04-stego/report-docx.md) • [wav](04-stego/se03-radio-wav.md) |
| **05. Crypto** | 0 | 47 | ⚪ Não iniciado | [vendor_note](05-crypto/vendor-note-txt.md) • [heartbeat](05-crypto/heartbeat-xor.md) • [update](05-crypto/update-enc.md) • [recovery](05-crypto/recovery-pem.md) |
| **06. Warmup** | 0 | 58 | ⚪ Não iniciado | [evidence](06-warmup/evidence-zip.md) • [notes](06-warmup/notes-txt.md) • [updater](06-warmup/updater-bin.md) • [firmware](06-warmup/firmware-bin.md) • [telemetry](06-warmup/telemetry-ndjson.md) |
| **07. Phishing** | 0 | 26 | ⚪ Não iniciado | [bulletin](07-phishing/bulletin-eml.md) • [helpdesk](07-phishing/helpdesk-mbox.md) • [harvest](07-phishing/harvest-eml.md) |
| **08. Cadeia** | 0 | 28 | ⚪ Não iniciado | [cg4200.deb](08-cadeia/cg4200-deb.md) • [dns.rpm](08-cadeia/dns-rpm.md) • [clm-repo.tar](08-cadeia/clm-repo-tar.md) |
| **09. Dropper** | 0 | 26 | ⚪ Não iniciado | [icg4200.iso](09-dropper/icg4200-iso.md) • [dns.lnk](09-dropper/dns-lnk.md) • [clm-login.hta](09-dropper/clm-login-hta.md) |
| **10. Endpoint** | 0 | 30 | ⚪ Não iniciado | [sysmon_tn](10-endpoint/sysmon-tn-jsonl.md) • [sysmon_lit](10-endpoint/sysmon-lit-jsonl.md) • [sysmon_clm](10-endpoint/sysmon-clm-jsonl.md) |
| **11. Memória** | 0 | 34 | ⚪ Não iniciado | [tn-mem](11-memoria/tn-mem-bin.md) • [lit-mem](11-memoria/lit-mem-bin.md) • [clm-mem](11-memoria/clm-mem-bin.md) |
| **12. Disco** | 0 | 35 | ⚪ Não iniciado | [tn-disk](12-disco/tn-disk-img.md) • [lit-disk](12-disco/lit-disk-img.md) • [clm-disk](12-disco/clm-disk-dd.md) |

---

## 📌 Quadro de Atividades (Sprint Log)

### 🟢 Concluído
- [x] Estruturação modular inicial do repositório por categorias e artefatos.
- [x] Mapeamento dos 487 enunciados e metas do CTF.

### 🟡 Em Andamento
- [ ] Início da análise de tráfego de rede em `01-pcap/captura-pcap.md`.

### 🔴 Pendente / Próximos Passos
- [ ] Análise de logs de autenticação e modbus (`02-log/`).
- [ ] Extração forense em bases de dados SQLite (`03-sqlite/`).
- [ ] Análise de artefatos de memória e disco (`11-memoria/` e `12-disco/`).

---

## 🗂️ Estrutura de Diretórios

```text
<!-- ESPAÇO RESERVADO PARA A ÁRVORE DE DIRETÓRIOS -->