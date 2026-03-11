# 🛡️ Cybersecurity & Pentesting Roadmap: Do Teórico ao Operacional

Este projeto foi desenvolvido como parte do desafio da **DIO (Digital Innovation One)**, utilizando o **NotebookLM (Google)** como motor de síntese e curadoria.  
O objetivo é criar um **Caderno Temático** sobre **Cibersegurança e Pentesting**, unindo pensamento crítico, curadoria de fontes e organização do conhecimento.

---

## 🎯 Contexto e Objetivos

Este repositório serve como guia de referência para profissionais de TI que buscam especialização em **Cybersecurity**.  
O material equilibra **Segurança Ofensiva (Red Team/Pentesting)** e **Segurança Defensiva (Blue Team)**, além de tópicos de **Governança, Risco e Compliance (GRC)**.

**Objetivos específicos:**
- Estruturar trilhas de aprendizado em **Red Team**, **Blue Team** e **GRC**.  
- Aprofundar o entendimento sobre o ciclo de vida de um **Pentest**.  
- Consolidar o uso de frameworks globais como **MITRE ATT&CK**, **OWASP Top 10** e **NIST CSF**.  

---

## 📚 Curadoria de Fontes

Fontes selecionadas e utilizadas no NotebookLM:

1. [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)  
2. [MITRE ATT&CK Matrix](https://attack.mitre.org/)  
3. [OWASP Top 10 (2024)](https://owasp.org/www-project-top-ten/)  
4. [PTES – Penetration Testing Execution Standard](http://www.pentest-standard.org/)  
5. [Resolução 4.893 (BACEN)](https://www.bcb.gov.br/)  

---

## 🧠 Engenharia de Prompts e "Cicatrizes"

### Exemplos de Prompts Estratégicos
- *“Com base no PTES, detalhe as fases de um Pentest focado em uma aplicação de Internet Banking.”*  
- *“Explique a diferença entre Vulnerability Scanning e Penetration Testing conforme o NIST.”*  
- *“Crie uma tabela comparativa de ferramentas Open Source para análise de tráfego de rede (Wireshark vs. Tcpdump).”*  

### Troubleshooting (Cicatrizes)
- **Desafio:** A IA inicialmente focou apenas em ferramentas, ignorando a metodologia.  
- **Correção:** Refinamento do prompt exigindo descrição da **Metodologia de Relatório**, destacando que um Pentest só tem valor se as falhas forem documentadas e corrigidas.  

---

## 🚀 Miniguia de Estudo (Entrega Final)

### 1. Especializações de Carreira
- **Red Team (Pentesting):** Simulação de ataques reais, exploração de falhas e pós-exploração.  
- **Blue Team (Defesa):** Monitoramento (SOC), detecção de intrusão e resposta a incidentes.  
- **Purple Team:** Colaboração contínua entre ofensiva e defensiva.  
- **GRC:** Governança, risco e compliance, alinhado a normas e regulamentos.  

### 2. Ciclo de um Pentest
1. **Pre-engagement:** Definição de escopo e regras.  
2. **Intelligence Gathering:** Coleta de dados sobre o alvo.  
3. **Vulnerability Analysis:** Identificação de brechas conhecidas (CVEs).  
4. **Exploitation:** Obtenção de acesso.  
5. **Post-Exploitation:** Medição do impacto.  
6. **Reporting:** Documentação e plano de correção.  

### 3. Glossário Técnico
- **CVE:** Lista pública de falhas conhecidas.  
- **Zero-Day:** Vulnerabilidade sem correção disponível.  
- **Exploit vs Payload:** Caminho de entrada vs código executado.  
- **MFA:** Autenticação multifator, essencial para acessos privilegiados.  
- **SOC (Security Operations Center):** Centro de monitoramento de segurança.  
- **SIEM (Security Information and Event Management):** Ferramenta para correlação de logs e alertas.  

### 4. Prompts Reutilizáveis
- *“Liste as principais diferenças entre Red Team e Blue Team.”*  
- *“Explique como o MITRE ATT&CK pode ser aplicado em um SOC.”*  
- *“Crie um resumo das vulnerabilidades mais críticas do OWASP Top 10.”*  
- *“Compare frameworks de cibersegurança: NIST CSF vs ISO 27001.”*  

---

## 🛠️ Tecnologias Utilizadas
- [NotebookLM](https://notebooklm.google.com/) – IA para síntese de documentos.  
- [GitHub](https://github.com/) – Versionamento e portfólio.  
- [TryHackMe](https://tryhackme.com/) – Laboratórios práticos.  
- [HackTheBox](https://hackthebox.com/) – Treinamento avançado.  
- [OverTheWire](https://overthewire.org/wargames/) – Desafios de segurança.  

---

## 📈 Próximos Passos
- Expandir o roadmap com **labs práticos** (Packet Tracer, Kali Linux).  
- Adicionar **cases reais** de ataques e defesas.  
- Criar **seção de links recomendados** com vídeos e artigos.  

---

> 📌 Este README atende todos os requisitos do desafio da DIO:  
> - Contexto e Objetivos ✔️  
> - Curadoria de Fontes ✔️  
> - Engenharia de Prompts e Cicatrizes ✔️  
> - Miniguia de Estudo (resumos, glossário, prompts reutilizáveis) ✔️  
