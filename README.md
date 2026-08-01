# SOC Lab - Laboratório de Segurança

Laboratório doméstico integrado de SOC, Cybersecurity e DevSecOps.

<img width="1916" height="592" alt="image" src="https://github.com/user-attachments/assets/a06a7970-bb7c-4854-8d93-4977840bfc35" />
<img width="1899" height="940" alt="image" src="https://github.com/user-attachments/assets/b4af461f-f09d-4adc-adb8-6f3ab73f8ca2" />
<img width="1909" height="940" alt="image" src="https://github.com/user-attachments/assets/fc181559-9d71-4292-bba2-7c188483920a" />






## 🎯 Objetivo

Unir desenvolvimento Java (Spring Boot) com operações de segurança (SIEM/SOC) para formação profissional completa.

## 🏗️ Infraestrutura

### SIEM/SOC
- **Wazuh:** 4.7.5 (Manager, Indexer, Dashboard)
- **Servidor:** Ubuntu Server 24.04 LTS (Hyper-V)
- **IP do Manager:** 172.31.188.66
- **Dashboard:** https://172.31.188.66

### Agentes Monitorados
- ✅ Windows 11 (DESKTOP-41TK77D) - 172.31.176.1
- ✅ Kali Linux (kali) - 172.31.184.74

## ✅ Status Atual

- [x] Wazuh instalado via script nativo 
- [x] 2 agentes ativos e comunicando
- [x] Detecção de Brute Force funcional (Rule 60204, Level 10)
- [x] MITRE ATT&CK integrado (T1110 - Brute Force)
- [x] 561+ alertas coletados em 24h

## 📁 Estrutura do Projeto

soc-lab/
├── wazuh/ # Configurações do servidor Wazuh
── incidents/ # Documentação de incidentes (INC-XXX.md)
├── scripts/ # Automações (Python, PowerShell, Bash)
├── docs/ # Documentação técnica e laboratórios
└── README.md # Este arquivo


## 📋 Incidentes Documentados

- [INC-001](incidents/INC-001.md) - Brute Force Attack - Windows Authentication Failures

##  Próximos Passos

- [ ] Integrar aplicação Java (Locadora System)
- [ ] Criar automação SOAR com Spring Boot
- [ ] Documentar 5 cenários de ataque diferentes
- [ ] Criar dashboard customizado em Java
- [ ] Publicar artigos técnicos

## 🛠️ Tecnologias

- **Backend:** Java 21, Spring Boot 3.3.1
- **SIEM:** Wazuh 4.7.5, OpenSearch
- **SO:** Ubuntu Server 24.04, Windows 11, Kali Linux
- **Virtualização:** Hyper-V
