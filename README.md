# Formação em Cybersecurity - Módulo 1 🚀

## 🛠️ Descrição do Projeto
Este projeto foi desenvolvido como parte do **Módulo 1 da Trilha de Formação em Cybersecurity**. Ele simula uma rede corporativa segmentada utilizando Docker, representando uma empresa fictícia com diferentes sub-redes, estações de trabalho, servidores e dispositivos pessoais. O objetivo é realizar o **mapeamento completo dos ativos e sub-redes disponíveis**, identificar máquinas acessíveis, determinar os propósitos das sub-redes e elaborar um inventário técnico detalhado. 🌐


| <a href="/doc/img/ebook_animacao.gif" target="_blank"><img style="margin: 10px" height="600" width="390" src="/doc/img/ebook_animacao_600_390.gif" alt="Ebook"/></a> |
|:---:|
| |

---

## 📖 Sumário

1. [Sumário Executivo](#sumário-executivo)
2. [Objetivo](#objetivo)
3. [Escopo](#escopo)
4. [Metodologia](#metodologia)
5. [Etapas do Reconhecimento das Redes](#etapas-do-reconhecimento-das-redes)
6. [Descoberta de Hosts](#descoberta-de-hosts)
7. [Scan de Portas](#scan-de-portas)
8. [Extras Úteis](#extras-úteis)
9. [Organização dos Resultados](#organização-dos-resultados)
10. [Inventário Final - Tabela Descritiva](#inventário-final---tabela-descritiva)
11. [Diagrama](#diagrama)
12. [Diagnóstico](#diagnóstico)
13. [Recomendações](#recomendações)
14. [Segurança](#segurança)
15. [Monitoramento](#monitoramento)
16. [Documentação](#documentação)
17. [Auditoria](#auditoria)
18. [Extras](#extras)
19. [Plano de Ação (modelo 80/20)](#plano-de-ação-modelo-8020)
20. [Conclusão](#conclusão)
21. [Referências Bibliográficas](#referências-bibliográficas)
22. [Anexos](#anexos)

---

## 🌟 Sumário Executivo
Este projeto realizou uma análise detalhada da infraestrutura de rede, identificando dispositivos conectados, serviços em operação e possíveis riscos à segurança. A abordagem adotada permitiu mapear a rede de forma abrangente, garantindo uma visão clara de sua estrutura e funcionamento. Com base nos resultados, foi elaborado um plano de ação com recomendações práticas para aprimorar a segurança e eficiência da rede. 🔒

---

## 🎯 Objetivo
Simular uma rede corporativa segmentada utilizando Docker, assumindo o papel de analista de segurança para realizar o **mapeamento completo dos ativos e sub-redes disponíveis**. O projeto culmina na criação de um relatório técnico com diagnóstico, recomendações e um plano de ação baseado na regra **80/20**. 🛡️

---

## 🔍 Escopo
Durante o projeto, foi identificado um arquivo oculto chamado `.ANOTACAO-ULTIMO-SCAN.TXT`, contendo um roteiro detalhado de comandos utilizados para mapear redes e ativos. Este roteiro incluiu etapas como:
- Reconhecimento de redes.
- Teste de conectividade.
- Descoberta de hosts.
- Análise de portas e serviços.
- Organização e backup dos resultados. 📂

---

## 🧪 Metodologia
A metodologia seguiu um processo estruturado para mapear redes e ativos, identificar serviços e vulnerabilidades, e organizar os resultados para análise. Ferramentas como **Nmap**, **Rustscan**, e **Zabbix** foram utilizadas para garantir eficiência e precisão. 🔧

---

## 🛠️ Etapas do Reconhecimento das Redes
- Identificação das interfaces de rede e endereços IP disponíveis.
- Teste de conectividade entre sub-redes.
- Descoberta de hosts ativos utilizando **Nmap**.
- Varredura de portas com **Rustscan**.
- Análise detalhada de serviços como **FTP**, **MySQL**, **LDAP**, **SMB** e **HTTP**. 🌐

---

## 🔎 Descoberta de Hosts
Utilizou-se **Nmap** para realizar ping scans e identificar hosts ativos em cada sub-rede. Os resultados foram organizados em arquivos para facilitar a análise. 📄

---

## 🚪 Scan de Portas
**Rustscan** foi utilizado para realizar escaneamentos rápidos e eficientes das portas abertas em cada máquina, permitindo uma análise detalhada dos serviços disponíveis. ⚡

---

## 🛡️ Extras Úteis
Ferramentas como `arp` e `netdiscover` foram utilizadas para mapear endereços IP e dispositivos na rede, complementando a análise. 🖧

---

## 📂 Organização dos Resultados
Os resultados foram organizados em diretórios específicos para cada sub-rede, garantindo um ambiente de trabalho limpo e estruturado. 🗂️

---

## 📊 Inventário Final - Tabela Descritiva
Um inventário técnico foi elaborado, contendo informações detalhadas sobre:
- IPs.
- Nomes de host.
- Sistemas operacionais estimados.
- Portas abertas.
- Serviços ativos. 📝

---

## 🖼️ Diagrama
**[Espaço reservado para o diagrama da rede]**

---

## 🩺 Diagnóstico
O diagnóstico detalhado identificou dispositivos críticos, serviços expostos e possíveis vulnerabilidades, servindo como base para recomendações práticas e um plano de ação estratégico. 🩻

---

## ✅ Recomendações
As recomendações incluem medidas para:
- Fortalecer a segurança.
- Monitorar a infraestrutura.
- Documentar processos.
- Realizar auditorias.
- Implementar ações complementares para garantir resiliência e eficiência. 🔐

---

## 🔒 Segurança
Configuração de serviços expostos, restrição de acessos, proteção contra ataques e implementação de sistemas de prevenção/detecção de intrusão (**IPS/IDS**). 🛡️

---

## 📈 Monitoramento
Ferramentas como **Zabbix**, **Nagios** e **Prometheus** foram recomendadas para monitoramento em tempo real, com alertas configurados para eventos críticos. 📡

---

## 🗂️ Documentação
Procedimentos operacionais, inventário atualizado e registro de alterações foram documentados para garantir organização e suporte em processos críticos. 📝

---

## 🔍 Auditoria
Auditorias de segurança, conformidade e performance foram realizadas para identificar vulnerabilidades, garantir alinhamento com regulamentações e monitorar serviços críticos. 🕵️‍♂️

---

## 🌟 Extras
Medidas complementares como:
- Treinamento de equipe.
- Redundância.
- Segmentação de rede.
- Testes de penetração foram recomendadas para fortalecer a infraestrutura. 💡

---

## 📋 Plano de Ação (modelo 80/20)
Prioriza ações que geram maior impacto na segurança, monitoramento e gestão da infraestrutura, enquanto mantém ações complementares para melhorias contínuas. 🔧

---

## 🏁 Conclusão
Este projeto forneceu um diagnóstico completo da rede, destacando pontos fortes e áreas que requerem atenção. As recomendações e o plano de ação proposto estabelecem uma base sólida para melhorias contínuas e proteção proativa da infraestrutura. 🚀

---

## 📚 Referências Bibliográficas
**[Espaço reservado para as referências bibliográficas]**

---

## 📎 Anexos
**[Espaço reservado para anexos e documentos complementares]**