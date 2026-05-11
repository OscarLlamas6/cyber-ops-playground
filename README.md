# cyber-ops-playground

Laboratorio personal de autoestudio de ciberseguridad — Blue Team, Red Team y Purple Team. Desde fundamentos hasta nivel expert: SOC, SIEM, threat hunting, DFIR, pentesting, AD attacks, malware analysis, cloud security, AI security y más. Diseñado para 18-24 meses de estudio progresivo. **La numeración de carpetas ES el mapa de aprendizaje.**

---

## Leyenda

| Símbolo | Significado |
|---------|-------------|
| 🟢 | Básico |
| 🟡 | Intermedio |
| 🔴 | Avanzado |
| 🔵 | Expert |
| 🛡️ | Blue Team |
| ⚔️ | Red Team |
| 🔄 | Purple Team |
| ⚪ | Común a todos |

---

## ⚠️ Disclaimer legal

> Todo el contenido de este repositorio es estrictamente educativo. Las técnicas ofensivas documentadas están destinadas a entornos de laboratorio controlados, CTFs, y plataformas como HackTheBox o TryHackMe. Nunca apliques técnicas ofensivas en sistemas sin autorización explícita por escrito. El autor no se responsabiliza por el uso indebido de esta información.

---

## Ruta de aprendizaje recomendada

```
Meses  1-3:  01 → 02 → 03 → 04 → 05          (fundamentos universales)
Meses  4-6:  06 → 07 → 08 → 09 → 13          (blue: SOC, SIEM, detección, vuln mgmt)
Meses  7-9:  17 → 18 → 19 → 20 → 25          (red: recon, escaneo, web, social eng)
Meses 10-12: 10 → 11 → 12 → 14 → 15          (blue: IR, hunting, DFIR, hardening, IAM)
Meses 13-15: 21 → 22 → 23 → 26               (red: privesc, lateral, persistencia, AD)
Meses 16-18: 27 → 28 → 29 → 30               (purple: MITRE, BAS, detection eng, malware)
Meses 19-21: 16 → 33 → 34 → 37               (cloud sec, cloud ofensivo, containers, AI sec)
Meses 22-24: 31 → 32 → 35 → 36 → 40         (RE, exploit dev, mobile, ICS, novedades)
```

---

## Índice de categorías

| # | Categoría | Equipo | Nivel | Descripción |
|---|-----------|--------|-------|-------------|
| 01 | [Fundamentos de Seguridad](./01-fundamentos-de-seguridad/) | ⚪ | 🟢 | CIA Triad, amenazas, riesgos, defensa en profundidad |
| 02 | [Redes para Seguridad](./02-redes-para-seguridad/) | ⚪ | 🟢🟡 | Firewalls, VLANs, TLS, análisis de tráfico, Zero Trust |
| 03 | [Sistemas Operativos para Seguridad](./03-sistemas-operativos-para-seguridad/) | ⚪ | 🟢🟡 | Linux/Windows security, logs, AD básico, hardening inicial |
| 04 | [Criptografía](./04-criptografia/) | ⚪ | 🟢🟡🔴 | Simétrica, asimétrica, PKI, TLS, post-cuántica |
| 05 | [Marcos y Frameworks](./05-marcos-y-frameworks/) | ⚪ | 🟢🟡 | MITRE ATT&CK, Kill Chain, NIST CSF, CIS Controls, OWASP |
| 06 | [Blue Team — SOC Operaciones](./06-blue-team-soc-operaciones/) | 🛡️ | 🟢🟡 | Roles SOC, triaje, métricas MTTD/MTTR, runbooks |
| 07 | [SIEM y SOAR](./07-siem-y-soar/) | 🛡️ | 🟡🔴 | Splunk, Elastic, Sentinel, SPL, correlación, SOAR |
| 08 | [Threat Intelligence](./08-threat-intelligence/) | 🛡️ | 🟡🔴 | CTI, IOC/IOA, STIX/TAXII, MISP, APT groups |
| 09 | [Detección de Amenazas](./09-deteccion-de-amenazas/) | 🛡️ | 🟡🔴 | Snort, Suricata, Zeek, EDR, XDR, UEBA, Sigma rules |
| 10 | [Incident Response](./10-incident-response/) | 🛡️ | 🟡🔴 | IR lifecycle NIST, playbooks, ransomware, data breach |
| 11 | [Threat Hunting](./11-threat-hunting/) | 🛡️ | 🔴🔵 | Hipótesis driven, TTP hunting, hunting en cloud |
| 12 | [Forense Digital — DFIR](./12-forense-digital-dfir/) | 🛡️ | 🔴🔵 | Autopsy, Volatility, timeline analysis, cloud forensics |
| 13 | [Vulnerability Management](./13-vulnerability-management/) | 🛡️ | 🟡🔴 | CVSS, Nessus, OpenVAS, Nuclei, EPSS, CISA KEV |
| 14 | [Hardening y Configuración Segura](./14-hardening-y-configuracion-segura/) | 🛡️ | 🟡🔴 | CIS Benchmarks, SELinux, AppArmor, infra inmutable |
| 15 | [Identity y Acceso](./15-identity-y-acceso/) | 🛡️ | 🟡🔴 | IAM, MFA, PAM, Azure AD, OAuth2, Zero Trust Identity |
| 16 | [Cloud Security](./16-cloud-security/) | 🛡️ | 🟡🔴🔵 | AWS/GCP/Azure security, CSPM, CWPP, CASB |
| 17 | [Red Team — Reconocimiento](./17-red-team-reconocimiento/) | ⚔️ | 🟡 | OSINT, Shodan, Maltego, subfinder, dark web recon |
| 18 | [Scanning y Enumeración](./18-scanning-y-enumeracion/) | ⚔️ | 🟡 | Nmap, Masscan, SMB/LDAP/SNMP enum, AutoRecon |
| 19 | [Explotación Web](./19-explotacion-web/) | ⚔️ | 🟡🔴 | OWASP Top 10, SQLi, XSS, SSRF, Burp Suite, JWT |
| 20 | [Explotación de Sistemas](./20-explotacion-de-sistemas/) | ⚔️ | 🟡🔴 | Metasploit, Hashcat, pass-the-hash, Kerberoasting |
| 21 | [Escalada de Privilegios](./21-escalada-de-privilegios/) | ⚔️ | 🟡🔴 | Linux/Windows privesc, BloodHound, cloud privesc |
| 22 | [Movimiento Lateral](./22-movimiento-lateral/) | ⚔️ | 🔴 | Pivoting, SSH tunneling, PSExec, DCOM, WMI |
| 23 | [Persistencia y Evasión](./23-persistencia-y-evasion/) | ⚔️ | 🔴🔵 | LOLBAS, AMSI bypass, EDR evasion, process injection |
| 24 | [C2 y Red Team Infra](./24-c2-y-red-team-infra/) | ⚔️ | 🔴🔵 | Cobalt Strike, Havoc, Sliver, Mythic, domain fronting |
| 25 | [Social Engineering](./25-social-engineering/) | ⚔️ | 🟡🔴 | Phishing, GoPhish, Evilginx2, physical security testing |
| 26 | [Active Directory Attacks](./26-active-directory-attacks/) | ⚔️ | 🔴🔵 | Golden Ticket, DCSync, Zerologon, AD CS, coercion |
| 27 | [Purple Team — MITRE Mapping](./27-purple-team-mitre-mapping/) | 🔄 | 🔴🔵 | ATT&CK Navigator, Atomic Red Team, CALDERA, VECTR |
| 28 | [Breach & Attack Simulation](./28-breach-attack-simulation/) | 🔄 | 🔴🔵 | Picus, Cymulate, AttackIQ, CTEM framework |
| 29 | [Detection Engineering](./29-detection-engineering/) | 🔄 | 🔴🔵 | Sigma, YARA, test-driven detection, detection-as-code |
| 30 | [Malware Analysis](./30-malware-analysis/) | 🔄 | 🔴🔵 | Análisis estático/dinámico, Ghidra, x64dbg, unpacking |
| 31 | [Reverse Engineering](./31-reverse-engineering/) | 🔄 | 🔵 | Ghidra profundo, IDA Pro, Radare2, Frida, firmware RE |
| 32 | [Exploit Development](./32-exploit-development/) | ⚔️ | 🔵 | Buffer overflow, ROP chains, heap exploitation, pwntools |
| 33 | [Cloud Offensive](./33-cloud-offensive/) | ⚔️ | 🔴🔵 | Pacu, AWS/GCP/Azure offensive, container escape, K8s |
| 34 | [Kubernetes y Container Security](./34-kubernetes-y-container-security/) | 🛡️ | 🔴🔵 | K8s RBAC, Falco, OPA, Kyverno, K8s pentesting |
| 35 | [Mobile Security](./35-mobile-security/) | ⚔️🛡️ | 🔴 | Android/iOS, OWASP Mobile, Frida, Objection |
| 36 | [ICS/OT/SCADA Security](./36-ics-ot-scada-security/) | 🛡️ | 🔴🔵 | Modbus, DNP3, Purdue Model, Stuxnet, detección ICS |
| 37 | [AI Security](./37-ai-security/) | 🛡️⚔️ | 🔵 | LLM security, prompt injection, OWASP LLM, MLSecOps |
| 38 | [Compliance y Governance](./38-compliance-y-governance/) | ⚪ | 🟡🔴 | ISO 27001, SOC 2, PCI DSS, GDPR, NIST 800-53 |
| 39 | [Certificaciones y Labs](./39-certificaciones-labs/) | ⚪ | 🟢🔵 | Security+, OSCP, CRTO, CISSP, HTB/THM roadmaps |
| 40 | [Nuevas Tecnologías](./40-nuevas-tecnologias/) | ⚪ | 🔵 | AI ofensivo, deepfakes, quantum, agentes autónomos |

---

## Tabla de seguimiento

| Tema | Categoría | Equipo | Nivel | MITRE ATT&CK ref | Herramienta clave | Estado |
|------|-----------|--------|-------|------------------|-------------------|--------|
| | | | | | | |

---

## Progreso

### 01 - Fundamentos de Seguridad ⚪🟢
- [ ] ⚪🟢 cia-triad-y-conceptos-base
- [ ] ⚪🟢 tipos-de-amenazas-y-actores
- [ ] ⚪🟢 superficie-de-ataque
- [ ] ⚪🟢 modelo-de-defensa-en-profundidad
- [ ] ⚪🟢 gestion-de-riesgos
- [ ] ⚪🟢 tipos-de-controles-preventivo-detectivo-correctivo
- [ ] ⚪🟢 seguridad-fisica
- [ ] ⚪🟢 principio-de-minimo-privilegio

### 02 - Redes para Seguridad ⚪🟢🟡
- [ ] ⚪🟢 protocolos-clave-desde-perspectiva-seguridad
- [ ] ⚪🟢 firewalls-y-segmentacion
- [ ] ⚪🟢 vlans-y-dmz
- [ ] ⚪🟡 ids-ips-fundamentos
- [ ] ⚪🟡 vpns-y-tunneling-seguro
- [ ] ⚪🟡 dns-seguro-y-ataques-dns
- [ ] ⚪🟡 ssl-tls-y-ataques-mitm
- [ ] ⚪🟡 analisis-de-trafico-tcpdump-wireshark
- [ ] ⚪🟡 proxies-y-waf
- [ ] ⚪🟡 zero-trust-network-access

### 03 - Sistemas Operativos para Seguridad ⚪🟢🟡
- [ ] ⚪🟢 linux-fundamentos-para-seguridad
- [ ] ⚪🟢 linux-permisos-y-sudo
- [ ] ⚪🟢 linux-logs-y-auditoria
- [ ] ⚪🟢 windows-fundamentos-para-seguridad
- [ ] ⚪🟡 windows-active-directory-basico
- [ ] ⚪🟡 windows-event-logs
- [ ] ⚪🟡 macos-seguridad
- [ ] ⚪🟡 contenedores-y-seguridad
- [ ] ⚪🟡 hardening-basico-linux
- [ ] ⚪🟡 hardening-basico-windows

### 04 - Criptografía ⚪🟢🟡🔴
- [ ] ⚪🟢 fundamentos-de-criptografia
- [ ] ⚪🟢 simetrica-vs-asimetrica
- [ ] ⚪🟢 hashing-y-integridad
- [ ] ⚪🟡 pki-y-certificados
- [ ] ⚪🟡 tls-profundo
- [ ] ⚪🟡 pgp-y-gpg
- [ ] ⚪🟡 kms-y-gestion-de-claves
- [ ] ⚪🟡 criptografia-en-reposo-y-transito
- [ ] ⚪🔴 ataques-criptograficos-clasicos
- [ ] ⚪🔴 criptografia-post-cuantica

### 05 - Marcos y Frameworks ⚪🟢🟡
- [ ] ⚪🟢 mitre-attack-introduccion
- [ ] ⚪🟡 mitre-attack-tacticas-y-tecnicas
- [ ] ⚪🟡 mitre-defend
- [ ] ⚪🟢 cyber-kill-chain
- [ ] ⚪🟡 nist-csf-2-0
- [ ] ⚪🟡 cis-controls-v8
- [ ] ⚪🟢 owasp-fundamentos
- [ ] ⚪🟡 ptes-penetration-testing-standard
- [ ] ⚪🟡 tiber-eu
- [ ] ⚪🟡 diamond-model

### 06 - Blue Team SOC Operaciones 🛡️🟢🟡
- [ ] 🛡️🟢 que-es-un-soc
- [ ] 🛡️🟢 roles-en-un-soc-l1-l2-l3
- [ ] 🛡️🟢 flujo-de-trabajo-de-alertas
- [ ] 🛡️🟡 triaging-de-incidentes
- [ ] 🛡️🟡 metricas-soc-mttd-mttr
- [ ] 🛡️🟡 shift-handover-y-runbooks
- [ ] 🛡️🟡 fatiga-de-alertas
- [ ] 🛡️🟡 soc-tools-overview

### 07 - SIEM y SOAR 🛡️🟡🔴
- [ ] 🛡️🟡 que-es-un-siem
- [ ] 🛡️🟡 splunk-fundamentos
- [ ] 🛡️🟡 splunk-spl-queries
- [ ] 🛡️🟡 elastic-siem
- [ ] 🛡️🟡 microsoft-sentinel
- [ ] 🛡️🟡 graylog
- [ ] 🛡️🟡 opensearch-security
- [ ] 🛡️🟡 soar-conceptos
- [ ] 🛡️🔴 shuffle-soar
- [ ] 🛡️🔴 reglas-de-correlacion
- [ ] 🛡️🔴 casos-de-uso-siem

### 08 - Threat Intelligence 🛡️🟡🔴
- [ ] 🛡️🟡 cti-fundamentos
- [ ] 🛡️🟡 ioc-ioa-diferencias
- [ ] 🛡️🟡 taxii-y-stix
- [ ] 🛡️🟡 misp-platform
- [ ] 🛡️🟡 opencti
- [ ] 🛡️🟡 feeds-y-fuentes
- [ ] 🛡️🟡 threat-intel-lifecycle
- [ ] 🛡️🔴 apt-grupos-y-ttps
- [ ] 🛡️🔴 diamond-model-cti
- [ ] 🛡️🔴 threat-intel-para-soc

### 09 - Detección de Amenazas 🛡️🟡🔴
- [ ] 🛡️🟡 ids-vs-ips
- [ ] 🛡️🟡 snort-fundamentos
- [ ] 🛡️🟡 suricata
- [ ] 🛡️🟡 zeek-network-analysis
- [ ] 🛡️🟡 edr-fundamentos
- [ ] 🛡️🔴 crowdstrike-falcon
- [ ] 🛡️🔴 microsoft-defender-edr
- [ ] 🛡️🔴 xdr-conceptos
- [ ] 🛡️🔴 ueba-user-behavior
- [ ] 🛡️🔴 ndr-network-detection
- [ ] 🛡️🔴 deteccion-basada-en-anomalias
- [ ] 🛡️🔴 sigma-rules

### 10 - Incident Response 🛡️🟡🔴
- [ ] 🛡️🟡 ir-lifecycle-nist
- [ ] 🛡️🟡 preparacion-y-playbooks
- [ ] 🛡️🟡 identificacion-y-triaje
- [ ] 🛡️🟡 contencion-corto-largo-plazo
- [ ] 🛡️🟡 erradicacion-y-recovery
- [ ] 🛡️🔴 post-incident-review
- [ ] 🛡️🔴 comunicacion-durante-incidente
- [ ] 🛡️🔴 ransomware-response
- [ ] 🛡️🔴 data-breach-response
- [ ] 🛡️🔴 theHive-platform
- [ ] 🛡️🔴 ir-automation

### 11 - Threat Hunting 🛡️🔴🔵
- [ ] 🛡️🔴 que-es-threat-hunting
- [ ] 🛡️🔴 hunting-vs-monitoring
- [ ] 🛡️🔴 hipotesis-driven-hunting
- [ ] 🛡️🔴 ioc-vs-ttp-hunting
- [ ] 🛡️🔴 hunting-con-splunk
- [ ] 🛡️🔴 hunting-con-elastic
- [ ] 🛡️🔵 hunting-en-endpoints
- [ ] 🛡️🔵 hunting-en-red
- [ ] 🛡️🔵 hunting-en-cloud
- [ ] 🛡️🔵 documentacion-de-hunts

### 12 - Forense Digital DFIR 🛡️🔴🔵
- [ ] 🛡️🔴 dfir-fundamentos
- [ ] 🛡️🔴 cadena-de-custodia
- [ ] 🛡️🔴 adquisicion-de-evidencia
- [ ] 🛡️🔴 forense-de-disco
- [ ] 🛡️🔴 forense-de-memoria
- [ ] 🛡️🔴 forense-de-red
- [ ] 🛡️🔴 forense-de-logs
- [ ] 🛡️🔴 autopsy-y-sleuth-kit
- [ ] 🛡️🔴 volatility-memoria
- [ ] 🛡️🔵 forense-en-windows
- [ ] 🛡️🔵 forense-en-linux
- [ ] 🛡️🔵 forense-en-cloud
- [ ] 🛡️🔵 timeline-analysis
- [ ] 🛡️🔵 forense-de-malware-basico

### 13 - Vulnerability Management 🛡️🟡🔴
- [ ] 🛡️🟡 vm-lifecycle
- [ ] 🛡️🟡 cvss-y-scoring
- [ ] 🛡️🟡 cve-y-nvd
- [ ] 🛡️🟡 nessus
- [ ] 🛡️🟡 openvas-greenbone
- [ ] 🛡️🟡 nuclei
- [ ] 🛡️🔴 patch-management
- [ ] 🛡️🔴 risk-based-prioritization
- [ ] 🛡️🔴 epss-scoring
- [ ] 🛡️🔴 cisa-kev

### 14 - Hardening y Configuración Segura 🛡️🟡🔴
- [ ] 🛡️🟡 cis-benchmarks
- [ ] 🛡️🟡 hardening-linux-avanzado
- [ ] 🛡️🟡 hardening-windows-avanzado
- [ ] 🛡️🔴 hardening-kubernetes
- [ ] 🛡️🔴 hardening-docker
- [ ] 🛡️🔴 hardening-bases-de-datos
- [ ] 🛡️🔴 hardening-web-servers
- [ ] 🛡️🔴 seccomp-y-apparmor
- [ ] 🛡️🔴 selinux
- [ ] 🛡️🔴 inmutable-infrastructure

### 15 - Identity y Acceso 🛡️🟡🔴
- [ ] 🛡️🟡 iam-fundamentos
- [ ] 🛡️🟡 autenticacion-multifactor
- [ ] 🛡️🟡 pam-privileged-access
- [ ] 🛡️🟡 active-directory-seguridad
- [ ] 🛡️🟡 azure-ad-entra-id
- [ ] 🛡️🔴 oauth2-oidc-seguridad
- [ ] 🛡️🔴 zero-trust-identity
- [ ] 🛡️🔴 just-in-time-access
- [ ] 🛡️🔴 credential-hygiene
- [ ] 🛡️🔴 service-accounts-workload-identity

### 16 - Cloud Security 🛡️🟡🔴🔵
- [ ] 🛡️🟡 cloud-shared-responsibility
- [ ] 🛡️🟡 aws-security-fundamentals
- [ ] 🛡️🟡 aws-iam-seguridad
- [ ] 🛡️🔴 aws-guardduty
- [ ] 🛡️🔴 aws-security-hub
- [ ] 🛡️🔴 gcp-security-command-center
- [ ] 🛡️🔴 azure-defender
- [ ] 🛡️🔴 cspm-cloud-security-posture
- [ ] 🛡️🔴 cwpp-workload-protection
- [ ] 🛡️🔴 casb
- [ ] 🛡️🔴 cloud-logging-y-monitoreo
- [ ] 🛡️🔵 s3-bucket-misconfiguration
- [ ] 🛡️🔵 secrets-en-cloud

### 17 - Red Team Reconocimiento ⚔️🟡
- [ ] ⚔️🟡 passive-recon-osint
- [ ] ⚔️🟡 google-dorking
- [ ] ⚔️🟡 shodan-y-censys
- [ ] ⚔️🟡 maltego
- [ ] ⚔️🟡 theHarvester
- [ ] ⚔️🟡 recon-ng
- [ ] ⚔️🟡 whois-dns-enum
- [ ] ⚔️🟡 linkedin-y-social-recon
- [ ] ⚔️🟡 dark-web-recon
- [ ] ⚔️🟡 subfinder-amass

### 18 - Scanning y Enumeración ⚔️🟡
- [ ] ⚔️🟡 nmap-fundamentos
- [ ] ⚔️🟡 nmap-avanzado
- [ ] ⚔️🟡 masscan
- [ ] ⚔️🟡 enumeracion-smb
- [ ] ⚔️🟡 enumeracion-ldap
- [ ] ⚔️🟡 enumeracion-snmp
- [ ] ⚔️🟡 enumeracion-web
- [ ] ⚔️🟡 enumeracion-servicios-comunes
- [ ] ⚔️🟡 fingerprinting
- [ ] ⚔️🟡 autorecon

### 19 - Explotación Web ⚔️🟡🔴
- [ ] ⚔️🟡 owasp-top-10-2021
- [ ] ⚔️🟡 sql-injection
- [ ] ⚔️🟡 xss-cross-site-scripting
- [ ] ⚔️🟡 idor
- [ ] ⚔️🟡 ssrf
- [ ] ⚔️🟡 xxe
- [ ] ⚔️🟡 command-injection
- [ ] ⚔️🔴 deserialization
- [ ] ⚔️🔴 authentication-bypass
- [ ] ⚔️🔴 api-security-owasp
- [ ] ⚔️🟡 burpsuite-fundamentos
- [ ] ⚔️🔴 burpsuite-avanzado
- [ ] ⚔️🟡 ffuf-y-fuzzing
- [ ] ⚔️🔴 jwt-attacks
- [ ] ⚔️🔴 graphql-security

### 20 - Explotación de Sistemas ⚔️🟡🔴
- [ ] ⚔️🟡 metasploit-fundamentos
- [ ] ⚔️🔴 metasploit-avanzado
- [ ] ⚔️🟡 exploit-publicos-y-exploit-db
- [ ] ⚔️🟡 buffer-overflow-basico
- [ ] ⚔️🟡 explotacion-smb-eternal-blue
- [ ] ⚔️🟡 password-attacks-hashcat
- [ ] ⚔️🟡 password-attacks-john
- [ ] ⚔️🟡 credential-stuffing
- [ ] ⚔️🔴 pass-the-hash
- [ ] ⚔️🔴 kerberoasting
- [ ] ⚔️🔴 as-rep-roasting

### 21 - Escalada de Privilegios ⚔️🟡🔴
- [ ] ⚔️🟡 privesc-linux-fundamentos
- [ ] ⚔️🟡 privesc-linux-sudo-suid
- [ ] ⚔️🟡 privesc-linux-capabilities
- [ ] ⚔️🟡 privesc-linux-cron-paths
- [ ] ⚔️🔴 privesc-linux-herramientas
- [ ] ⚔️🟡 privesc-windows-fundamentos
- [ ] ⚔️🟡 privesc-windows-servicios
- [ ] ⚔️🟡 privesc-windows-registry
- [ ] ⚔️🔴 privesc-windows-tokens
- [ ] ⚔️🔴 privesc-windows-herramientas
- [ ] ⚔️🔴 privesc-ad-bloodhound
- [ ] ⚔️🔴 privesc-cloud

### 22 - Movimiento Lateral ⚔️🔴
- [ ] ⚔️🔴 pivoting-fundamentos
- [ ] ⚔️🔴 ssh-tunneling
- [ ] ⚔️🔴 proxychains
- [ ] ⚔️🔴 lateral-movement-windows
- [ ] ⚔️🔴 pass-the-ticket
- [ ] ⚔️🔴 dcom-y-wmi-lateral
- [ ] ⚔️🔴 psexec-y-smb-lateral
- [ ] ⚔️🔴 lateral-movement-linux
- [ ] ⚔️🔴 ad-lateral-movement
- [ ] ⚔️🔴 lateral-en-cloud

### 23 - Persistencia y Evasión ⚔️🔴🔵
- [ ] ⚔️🔴 persistencia-linux
- [ ] ⚔️🔴 persistencia-windows
- [ ] ⚔️🔴 persistencia-ad
- [ ] ⚔️🔴 living-off-the-land-lolbas
- [ ] ⚔️🔴 av-evasion-tecnicas
- [ ] ⚔️🔴 amsi-bypass
- [ ] ⚔️🔵 edr-bypass-conceptos
- [ ] ⚔️🔵 ofuscacion-de-payloads
- [ ] ⚔️🔵 process-injection
- [ ] ⚔️🔵 dll-hijacking
- [ ] ⚔️🔵 timestomping-y-anti-forense

### 24 - C2 y Red Team Infra ⚔️🔴🔵
- [ ] ⚔️🔴 c2-frameworks-overview
- [ ] ⚔️🔵 cobalt-strike-conceptos
- [ ] ⚔️🔴 havoc-c2
- [ ] ⚔️🔴 sliver-c2
- [ ] ⚔️🔴 mythic-c2
- [ ] ⚔️🔴 covenant
- [ ] ⚔️🔴 red-team-infra-design
- [ ] ⚔️🔵 redirectors-y-domain-fronting
- [ ] ⚔️🔵 opsec-para-red-teamers
- [ ] ⚔️🔵 malleable-c2-profiles

### 25 - Social Engineering ⚔️🟡🔴
- [ ] ⚔️🟡 phishing-fundamentos
- [ ] ⚔️🟡 spear-phishing
- [ ] ⚔️🟡 vishing
- [ ] ⚔️🟡 smishing
- [ ] ⚔️🟡 pretexting
- [ ] ⚔️🟡 goPhish
- [ ] ⚔️🔴 evilginx2
- [ ] ⚔️🔴 physical-security-testing
- [ ] ⚔️🔴 baiting-y-qrcode-attacks
- [ ] ⚔️🔴 ai-assisted-phishing-2026

### 26 - Active Directory Attacks ⚔️🔴🔵
- [ ] ⚔️🔴 ad-fundamentos-ofensivo
- [ ] ⚔️🔴 bloodhound-sharphound
- [ ] ⚔️🔴 kerberoasting
- [ ] ⚔️🔴 golden-ticket
- [ ] ⚔️🔴 silver-ticket
- [ ] ⚔️🔴 dcsync
- [ ] ⚔️🔵 zerologon
- [ ] ⚔️🔵 printnightmare
- [ ] ⚔️🔵 ad-cs-esc1-esc8
- [ ] ⚔️🔵 ad-delegation-attacks
- [ ] ⚔️🔵 ms-rprn-coercion

### 27 - Purple Team MITRE Mapping 🔄🔴🔵
- [ ] 🔄🔴 mitre-attack-navigator
- [ ] 🔄🔴 mapeo-de-ttps
- [ ] 🔄🔴 cobertura-de-deteccion
- [ ] 🔄🔴 atomic-red-team
- [ ] 🔄🔴 caldera
- [ ] 🔄🔵 vectr-tracking
- [ ] 🔄🔵 adversary-emulation-plans
- [ ] 🔄🔵 purple-team-exercise-design

### 28 - Breach Attack Simulation 🔄🔴🔵
- [ ] 🔄🔴 bas-conceptos
- [ ] 🔄🔴 picus-security
- [ ] 🔄🔴 cymulate
- [ ] 🔄🔴 attackiq
- [ ] 🔄🔵 mandiant-security-validation
- [ ] 🔄🔴 bas-vs-pentest
- [ ] 🔄🔵 continuous-validation
- [ ] 🔄🔵 ctem-framework

### 29 - Detection Engineering 🔄🔴🔵
- [ ] 🔄🔴 que-es-detection-engineering
- [ ] 🔄🔴 sigma-rules
- [ ] 🔄🔴 yara-rules
- [ ] 🔄🔴 detecciones-en-splunk
- [ ] 🔄🔴 detecciones-en-elastic
- [ ] 🔄🔴 detecciones-en-sentinel
- [ ] 🔄🔵 test-driven-detection
- [ ] 🔄🔵 false-positives-tuning
- [ ] 🔄🔵 detection-as-code
- [ ] 🔄🔵 mitre-attack-coverage-matrix

### 30 - Malware Analysis 🔄🔴🔵
- [ ] 🔄🔴 tipos-de-malware
- [ ] 🔄🔴 analisis-estatico-basico
- [ ] 🔄🔴 analisis-dinamico-basico
- [ ] 🔄🔴 sandbox-any-run-cuckoo
- [ ] 🔄🔴 strings-y-pe-analysis
- [ ] 🔄🔴 pestudio-y-die
- [ ] 🔄🔴 wireshark-analisis-malware
- [ ] 🔄🔴 analisis-estatico-avanzado
- [ ] 🔄🔵 desensamblado-ghidra
- [ ] 🔄🔵 desensamblado-ida-pro
- [ ] 🔄🔴 analisis-de-macros-office
- [ ] 🔄🔴 analisis-de-powershell
- [ ] 🔄🔵 debugging-x64dbg
- [ ] 🔄🔵 unpacking-y-deobfuscacion
- [ ] 🔄🔵 ransomware-analysis

### 31 - Reverse Engineering 🔄🔵
- [ ] 🔄🔵 re-fundamentos
- [ ] 🔄🔵 arquitecturas-x86-x64-arm
- [ ] 🔄🔵 ghidra-profundo
- [ ] 🔄🔵 ida-pro
- [ ] 🔄🔵 radare2
- [ ] 🔄🔵 angr-analisis-simbolico
- [ ] 🔄🔵 frida-instrumentacion-dinamica
- [ ] 🔄🔵 re-de-mobile-apps
- [ ] 🔄🔵 re-de-firmware

### 32 - Exploit Development ⚔️🔵
- [ ] ⚔️🔵 buffer-overflow-linux
- [ ] ⚔️🔵 buffer-overflow-windows
- [ ] ⚔️🔵 rop-chains
- [ ] ⚔️🔵 heap-exploitation
- [ ] ⚔️🔵 format-string
- [ ] ⚔️🔵 aslr-dep-bypass
- [ ] ⚔️🔵 kernel-exploits-intro
- [ ] ⚔️🔵 pwn-tools-python
- [ ] ⚔️🔵 ctf-pwn-challenges

### 33 - Cloud Offensive ⚔️🔴🔵
- [ ] ⚔️🔴 cloud-pentesting-intro
- [ ] ⚔️🔴 aws-enum-pacu
- [ ] ⚔️🔴 aws-privilege-escalation
- [ ] ⚔️🔴 gcp-offensive
- [ ] ⚔️🔴 azure-offensive
- [ ] ⚔️🔴 cloud-credential-theft
- [ ] ⚔️🔴 s3-y-blob-attacks
- [ ] ⚔️🔵 lambda-function-attacks
- [ ] ⚔️🔵 container-escape
- [ ] ⚔️🔵 kubernetes-offensive
- [ ] ⚔️🔴 cloudgoat-labs

### 34 - Kubernetes y Container Security 🛡️🔴🔵
- [ ] 🛡️🔴 container-security-fundamentals
- [ ] 🛡️🔴 docker-security
- [ ] 🛡️🔴 k8s-rbac
- [ ] 🛡️🔴 k8s-network-policies
- [ ] 🛡️🔴 pod-security-standards
- [ ] 🛡️🔴 supply-chain-container
- [ ] 🛡️🔴 runtime-security-falco
- [ ] 🛡️🔵 opa-gatekeeper
- [ ] 🛡️🔵 kyverno
- [ ] 🛡️🔴 image-scanning
- [ ] 🛡️🔴 secrets-en-k8s
- [ ] 🛡️🔵 k8s-pentesting

### 35 - Mobile Security ⚔️🛡️🔴
- [ ] ⚔️🛡️🔴 android-security-fundamentos
- [ ] ⚔️🛡️🔴 ios-security-fundamentos
- [ ] ⚔️🛡️🔴 owasp-mobile-top-10
- [ ] ⚔️🔴 apk-reverse-engineering
- [ ] ⚔️🔴 frida-mobile
- [ ] ⚔️🔴 objection
- [ ] ⚔️🔴 burpsuite-mobile
- [ ] 🛡️🔴 mobile-malware

### 36 - ICS/OT/SCADA Security 🛡️🔴🔵
- [ ] 🛡️🔴 ics-ot-fundamentos
- [ ] 🛡️🔴 modbus-y-dnp3
- [ ] 🛡️🔴 opc-ua-seguridad
- [ ] 🛡️🔴 purdue-model
- [ ] 🛡️🔴 ics-amenazas-y-actores
- [ ] 🛡️🔵 stuxnet-y-casos-historicos
- [ ] 🛡️🔵 ics-pentesting-intro
- [ ] 🛡️🔵 ics-deteccion-y-monitoreo

### 37 - AI Security 🛡️⚔️🔵
- [ ] 🛡️⚔️🔵 llm-security-fundamentos
- [ ] ⚔️🔵 prompt-injection-directa
- [ ] ⚔️🔵 prompt-injection-indirecta
- [ ] ⚔️🔵 jailbreaking-tecnicas
- [ ] ⚔️🔵 data-poisoning
- [ ] ⚔️🔵 rag-poisoning
- [ ] ⚔️🔵 model-extraction
- [ ] ⚔️🔵 adversarial-examples
- [ ] 🛡️🔵 owasp-llm-top-10
- [ ] 🛡️⚔️🔵 ai-agent-security
- [ ] 🛡️🔵 mlsecops
- [ ] ⚔️🔵 red-teaming-llms
- [ ] 🛡️🔵 guardrails-y-mitigaciones
- [ ] 🛡️🔵 ai-governance-y-riesgo

### 38 - Compliance y Governance ⚪🟡🔴
- [ ] ⚪🟡 iso-27001
- [ ] ⚪🟡 soc-2
- [ ] ⚪🟡 pci-dss
- [ ] ⚪🟡 gdpr-y-privacidad
- [ ] ⚪🟡 hipaa
- [ ] ⚪🔴 nist-sp-800-53
- [ ] ⚪🟡 cis-controls
- [ ] ⚪🟡 esquema-nacional-seguridad
- [ ] ⚪🔴 risk-management
- [ ] ⚪🔴 grc-platforms

### 39 - Certificaciones y Labs ⚪🟢🔵
- [ ] ⚪🟢 comptia-security-plus
- [ ] ⚪🟡 comptia-cysa-plus
- [ ] ⚪🟡 comptia-pentest-plus
- [ ] ⚪🟡 ceh-roadmap
- [ ] ⚪🟡 ejpt
- [ ] ⚪🔴 oscp-roadmap
- [ ] ⚪🔴 crto-red-team
- [ ] ⚪🔴 gcih-gcfa-grem
- [ ] ⚪🔵 cissp
- [ ] ⚪🔴 cloud-security-aws-gcp
- [ ] ⚪🟢 plataformas-practica-htb-thm
- [ ] ⚪🟢 ctf-recursos

### 40 - Nuevas Tecnologías ⚪🔵
- [ ] ⚪🔵 ai-offensive-tools-2026
- [ ] ⚪🔵 deepfake-y-synthetic-media-attacks
- [ ] ⚪🔵 quantum-criptografia
- [ ] ⚪🔵 ataques-a-agentes-autonomos
- [ ] ⚪🔵 supply-chain-2026
- [ ] ⚪🔵 placeholder-nuevo-tema

---

## Plataformas de práctica recomendadas

| Plataforma | Foco | Tipo |
|------------|------|------|
| HackTheBox (HTB) | Pentesting, CTF | Red Team |
| TryHackMe (THM) | Guiado, principiantes | Red + Blue |
| PentesterLab | Web application security | Red Team |
| VulnHub | VMs vulnerables locales | Red Team |
| OWASP WebGoat / DVWA | Web vulnerable local | Red Team |
| BlueTeamLabs Online | Defensivo, SOC | Blue Team |
| LetsDefend | SOC analyst training | Blue Team |
| CyberDefenders | Blue team challenges, DFIR | Blue Team |
| AttackDefend (INE) | Labs ofensivos y defensivos | Red + Blue |
| Flare-On (Mandiant) | CTF de malware analysis | Purple Team |

---

## 40 - Nuevas Tecnologías — Nota especial

> Esta categoría es una **carpeta viva**. A medida que surjan nuevas amenazas, herramientas, técnicas o CVEs relevantes durante el período de estudio, se agregarán aquí como nuevas subcarpetas. El campo de AI Security (categoría 37) en particular evoluciona muy rápido en 2025-2026.

---

*Repositorio iniciado: 2026 · Duración estimada: 18-24 meses*
