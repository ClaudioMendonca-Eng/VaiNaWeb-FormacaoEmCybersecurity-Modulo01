# Formação em Cybersecurity - Módulo 1 🚀



## 🛠️ Descrição do Projeto
| Este projeto foi desenvolvido como parte do **[Módulo 1 da Trilha de Formação em Cybersecurity](https://github.com/Kensei-CyberSec-Lab/formacao-cybersec/tree/main/modulo1-fundamentos/projeto_final_opcao_1)**. Ele simula uma rede corporativa segmentada utilizando Docker, representando uma empresa fictícia com diferentes sub-redes, estações de trabalho, servidores e dispositivos pessoais. O objetivo é realizar o **mapeamento completo dos ativos e sub-redes disponíveis**, identificar máquinas acessíveis, determinar os propósitos das sub-redes e elaborar um inventário técnico detalhado. 🌐 |
|:---:|
| |
| **<a href="/doc/Desafio_Modulo_01-Projeto_01-v.1.0.pdf" target="_blank"><span style="color: blue;">Clique no book para baixar a versão detalhada!</span>** |
| <a href="/doc/Desafio_Modulo_01-Projeto_01-v.1.0.pdf" target="_blank"><img style="margin: 10px" height="700" width="800" src="/doc/img/ebook_animacao_600_390.gif" alt="Ebook"/></a> |
|  <a href="https://kensei.seg.br/lab" target="_blank"><img style="margin: 10px" height="100" width="500" src="/doc/img/logos.png" alt="Logos Kensei e Vai na Web"/></a> |


> [!NOTE]
> **CURSO FORMAÇÃO CIBERSEC**
> 
> ***Autor:*** Claudio Mendonça - ***Data:*** 18/07/2025 - ***Versão:*** 1.0
>
> **Mestre:** [Jose Menezes](https://github.com/jcarlos78) - **Instrutores:** [Gilson Andrade](https://github.com/GilsonJunio) / [João Pedro Belo](https://github.com/silvajpedro)
 
# Formação em Cybersecurity - Módulo 1 🚀

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?logo=kalilinux&logoColor=white)
![Cybersegurança](https://img.shields.io/badge/Cybersegurança-Seguro-brightgreen)
![Nmap](https://img.shields.io/badge/Nmap-0078D7?logo=nmap&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-EE0000?logo=zabbix&logoColor=white)
![Rustscan](https://img.shields.io/badge/Rustscan-F74C00?logo=rust&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)

---
🎙️ <strong>Apresentação em Áudio do Laboratório WAF</strong>

https://github.com/user-attachments/assets/2ba1a4c5-5026-4826-9ece-65f0a601cc58

---

## 📖 Sumário
<a id="topo"></a>

1. [Sumário Executivo](#sumario-executivo)
2. [Objetivo](#objetivo)
3. [Escopo](#escopo)
4. [Metodologia](#metodologia)
   - [Etapas do Reconhecimento das Redes](#etapas-do-reconhecimento-das-redes)
   - [Descoberta de Hosts](#descoberta-de-hosts)
   - [Scan de Portas](#scan-de-portas)
   - [Extras Úteis](#extras-uteis)
   - [Organização dos Resultados](#organizacao-dos-resultados)
   - [Inventário Final - Tabela Descritiva](#inventario-final---tabela-descritiva)
   - [Diagrama](#diagrama)
5. [Diagnóstico](#diagnostico)
6. [Recomendações](#recomendacoes)
   - [Segurança](#seguranca)
   - [Monitoramento](#monitoramento)
   - [Documentação](#documentacao)
   - [Auditoria](#auditoria)
   - [Extras](#extras)
7. [Plano de Ação (modelo 80/20)](#plano-de-acao-modelo-8020)
8. [Conclusão](#conclusao)
9. [Referências Bibliográficas](#referencias-bibliograficas)
10. [Anexos](#anexos)


---

## 🌟 <a name="sumario-executivo"></a>Sumário Executivo
Este projeto realizou uma análise detalhada da infraestrutura de rede, identificando dispositivos conectados, serviços em operação e possíveis riscos à segurança. A abordagem adotada permitiu mapear a rede de forma abrangente, garantindo uma visão clara de sua estrutura e funcionamento. Com base nos resultados, foi elaborado um plano de ação com recomendações práticas para aprimorar a segurança e eficiência da rede. 🔒

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🎯 <a name="objetivo"></a>Objetivo
Simular uma rede corporativa segmentada utilizando Docker, assumindo o papel de analista de segurança para realizar o **mapeamento completo dos ativos e sub-redes disponíveis**. O projeto culmina na criação de um relatório técnico com diagnóstico, recomendações e um plano de ação baseado na regra **80/20**. 🛡️

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🔍 <a name="escopo"></a>Escopo
Durante o projeto, foi identificado um arquivo oculto chamado `.ANOTACAO-ULTIMO-SCAN.TXT`, contendo um roteiro detalhado de comandos utilizados para mapear redes e ativos. Este roteiro incluiu etapas como:
- Reconhecimento de redes.
- Teste de conectividade.
- Descoberta de hosts.
- Análise de portas e serviços.
- Organização e backup dos resultados. 📂

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🧪 <a name="metodologia"></a>Metodologia
A metodologia seguiu um processo estruturado para mapear redes e ativos, identificar serviços e vulnerabilidades, e organizar os resultados para análise. Ferramentas como **Nmap**, **Rustscan**, e **Zabbix** foram utilizadas para garantir eficiência e precisão. 🔧

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🛠️ <a name="etapas-do-reconhecimento-das-redes"></a>Etapas do Reconhecimento das Redes
- Identificação das interfaces de rede e endereços IP disponíveis.
- Teste de conectividade entre sub-redes.
- Descoberta de hosts ativos utilizando **Nmap**.
- Varredura de portas com **Rustscan**.
- Análise detalhada de serviços como **FTP**, **MySQL**, **LDAP**, **SMB** e **HTTP**. 🌐

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🔎 <a name="descoberta-de-hosts"></a>Descoberta de Hosts
Utilizou-se **Nmap** para realizar ping scans e identificar hosts ativos em cada sub-rede. Os resultados foram organizados em arquivos para facilitar a análise. 📄

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🚪 <a name="scan-de-portas"></a>Scan de Portas
**Rustscan** foi utilizado para realizar escaneamentos rápidos e eficientes das portas abertas em cada máquina, permitindo uma análise detalhada dos serviços disponíveis. ⚡

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🛡️ <a name="extras-uteis"></a>Extras Úteis
Foi utilizado a ferramenta `arp` para mapear endereços IP e dispositivos na rede. 🖧

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📂 <a name="organizacao-dos-resultados"></a>Organização dos Resultados
Os resultados foram organizados em diretórios específicos para cada sub-rede, garantindo um ambiente de trabalho limpo e estruturado. 🗂️

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📊 <a name="inventario-final---tabela-descritiva"></a>Inventário Final - Tabela Descritiva
Um inventário técnico foi elaborado, contendo informações detalhadas sobre:
- IPs.
- Nomes de host.
- Sistemas operacionais estimados.
- Portas abertas.
- Serviços ativos. 📝

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🖼️ <a name="diagrama"></a>Diagrama

O diagrama de rede desenvolvido para este projeto oferece uma representação visual clara da infraestrutura, destacando a organização dos dispositivos, sub-redes e conexões entre eles. Ele facilita a compreensão da topologia da rede, permitindo identificar pontos críticos, serviços ativos e fluxos de comunicação. Além de servir como uma ferramenta essencial para análise e planejamento, o diagrama também auxilia na identificação de possíveis vulnerabilidades e na implementação de melhorias, garantindo maior eficiência e segurança na gestão da infraestrutura.

| <a href="/doc/img/diagrama_rede_empresa.png" target="_blank"><img style="margin: 0px" height="900" width="800" src="/doc/img/diagrama_rede_empresa.png" alt="Ebook"/></a> |
|:---:|

- Arquivo: [Draw.io](/doc/img/diagrama_rede_empresa.drawio)

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🩺 <a name="diagnostico"></a>Diagnóstico
O diagnóstico detalhado identificou dispositivos críticos, serviços expostos e possíveis vulnerabilidades, servindo como base para recomendações práticas e um plano de ação estratégico. 🩻

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## ✅ <a name="recomendacoes"></a>Recomendações
As recomendações incluem medidas para:
- Fortalecer a segurança.
- Monitorar a infraestrutura.
- Documentar processos.
- Realizar auditorias.
- Implementar ações complementares para garantir resiliência e eficiência. 🔐

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🔒 <a name="seguranca"></a>Segurança
Configuração de serviços expostos, restrição de acessos, proteção contra ataques e implementação de sistemas de prevenção/detecção de intrusão (**IPS/IDS**). 🛡️

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---
## 📡 <a name="monitoramento"></a>Monitoramento
Implementação de ferramentas de monitoramento contínuo, como **Zabbix** e **Prometheus**, para garantir a visibilidade em tempo real da infraestrutura. As ações incluem:
- Configuração de alertas para eventos críticos.
- Monitoramento de desempenho de servidores e dispositivos.
- Análise de logs para detecção de anomalias.
- Criação de dashboards personalizados para acompanhamento de métricas-chave. 📊

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🗂️ <a name="documentacao"></a>Documentação
Procedimentos operacionais, inventário atualizado e registro de alterações foram documentados para garantir organização e suporte em processos críticos. 📝

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🔍 <a name="auditoria"></a>Auditoria
Auditorias de segurança, conformidade e performance foram realizadas para identificar vulnerabilidades, garantir alinhamento com regulamentações e monitorar serviços críticos. 🕵️‍♂️

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🌟 <a name="extras"></a>Extras
Medidas complementares como:
- Treinamento de equipe.
- Redundância.
- Segmentação de rede.
- Testes de penetração foram recomendadas para fortalecer a infraestrutura. 💡

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📋 <a name="plano-de-acao-modelo-8020"></a>Plano de Ação (modelo 80/20)
Prioriza ações que geram maior impacto na segurança, monitoramento e gestão da infraestrutura, enquanto mantém ações complementares para melhorias contínuas. 🔧

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 🏁 <a name="conclusao"></a>Conclusão
Este projeto forneceu um diagnóstico completo da rede, destacando pontos fortes e áreas que requerem atenção. As recomendações e o plano de ação proposto estabelecem uma base sólida para melhorias contínuas e proteção proativa da infraestrutura. 🚀

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📚 <a name="referencias-bibliograficas"></a>Referências Bibliográficas

### Ferramentas e Documentação Técnica:
1. [Nmap Documentation](https://nmap.org/book/).
2. [Wireshark User Guide](https://www.wireshark.org/docs/).
3. [Zabbix Documentation](https://www.zabbix.com/documentation).
4. [OpenVAS Documentation](https://www.openvas.org/documentation.html).
5. [Nessus Documentation](https://docs.tenable.com/nessus/).
6. [Prometheus Documentation](https://prometheus.io/docs/).
7. [ELK Stack Documentation](https://www.elastic.co/guide/index.html).
8. [Splunk Documentation](https://docs.splunk.com/).

### Normas e Regulamentações:
1. [ISO/IEC 27001:2013 - Information Security Management Systems](https://www.iso.org/standard/54534.html).
2. [GDPR - General Data Protection Regulation](https://gdpr-info.eu/).
3. [LGPD - Lei Geral de Proteção de Dados (Brasil)](https://www.gov.br/lgpd).
4. [PCI DSS - Payment Card Industry Data Security Standard](https://www.pcisecuritystandards.org/).

### Recursos Educacionais e Tutoriais:
1. [OWASP Foundation](https://owasp.org/).
2. [Cybersecurity & Infrastructure Security Agency (CISA)](https://www.cisa.gov/).
3. [MITRE ATT&CK Framework](https://attack.mitre.org/).

### Recursos de Ferramentas de Consulta:
1. [ChatGPT](https://openai.com/chatgpt) - Desenvolvido pela OpenAI, o ChatGPT foi utilizado para consultas rápidas e esclarecimento de dúvidas técnicas, auxiliando na compreensão de conceitos e na elaboração de estratégias para o projeto.
2. [GeminiAI](https://www.deepmind.com) - Criado pelo Google DeepMind, o GeminiAI foi empregado para consultas avançadas e suporte em análises complexas, contribuindo para a tomada de decisões no desenvolvimento do projeto.
3. [GitHub Copilot](https://github.com/features/copilot) - Desenvolvido pela GitHub em parceria com a OpenAI, o Copilot foi utilizado para sugerir trechos de código e soluções práticas, otimizando o tempo de desenvolvimento e garantindo maior eficiência no projeto.
4. [NotebookLM] - AI-powered notebook para consultas e análises em tempo real, onde foi feito o áudio desse repositório.

### Materiais Adicionais:
1. [Material do curso Formação Cibersec](https://escolavainaweb-com.gitbook.io/formacao-cibersec).
2. [Documentação do projeto final](https://drive.google.com/file/d/1yT8bNuMP29qpE0YII3ZK26DEOiocUsRK/view).
3. [Repositório do projeto final módulo 01](https://github.com/Kensei-CyberSec-Lab/formacao-cybersec/tree/main/modulo1-fundamentos/projeto_final_opcao_1).

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📎 <a name="anexos"></a>Anexos
Os anexos e documentos complementares relacionados ao projeto estão disponíveis na pasta [doc](/doc/), localizada no diretório do repositório. Essa pasta contém diagramas, relatórios técnicos, inventários e outros materiais de suporte que auxiliam na compreensão e análise do projeto.

- [ANOTACAO-ULTIMO-SCAN.TXT](/doc/ANOTACAO-ULTIMO-SCAN.TXT)
- [corp_net_ips.txt](/doc/corp_net/corp_net_ips.txt)
- [corp_net_ips_hosts.txt](/doc/corp_net/corp_net_ips_hosts.txt)
- [corp_net_ips_ports.txt](/doc/corp_net/corp_net_ips_ports.txt)
- [guest_net_ips.txt](/doc/guest_net/guest_net_ips.txt)
- [guest_net_ips_hosts.txt](/doc/guest_net/guest_net_ips_hosts.txt)
- [guest_net_ips_ports.txt](/doc/guest_net/guest_net_ips_ports.txt)
- [infra_net_ips.txt](/doc/infra_net/infra_net_ips.txt)
- [infra_net_ips_hosts.txt](/doc/infra_net/infra_net_ips_hosts.txt)
- [infra_net_ips_ports.txt](/doc/infra_net/infra_net_ips_ports.txt)
- [infra_net_servico_ftp-anon.txt](/doc/infra_net/infra_net_servico_ftp-anon.txt)
- [infra_net_servico_ldap-rootdse.txt](/doc/infra_net/infra_net_servico_ldap-rootdse.txt)
- [infra_net_servico_mysql-info.txt](/doc/infra_net/infra_net_servico_mysql-info.txt)
- [infra_net_servico_smb.txt](/doc/infra_net/infra_net_servico_smb.txt)
- [infra_net_servico_webserver.txt](/doc/infra_net/infra_net_servico_webserver.txt)
- [infra_net_servico_zabbix.txt](/doc/infra_net/infra_net_servico_zabbix.txt)
- [recon_ip_maps.txt](/doc/recon_ip_maps.txt)
- [user_processo_smb.txt](/doc/user_processo_smb.txt)

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---


Copyright © 2025 <a href="https://www.claudiomendonca.eng.br" target="_blank">ClaudioMendonca.eng.br</a>. 
