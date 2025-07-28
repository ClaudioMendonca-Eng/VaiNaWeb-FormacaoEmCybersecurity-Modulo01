# Formação em Cybersecurity - Módulo 1 🚀



## 🛠️ Descrição do Projeto
| Este projeto foi desenvolvido como parte do **[Módulo 1 da Trilha de Formação em Cybersecurity](https://github.com/Kensei-CyberSec-Lab/formacao-cybersec/tree/main/modulo1-fundamentos/projeto_final_opcao_1)**. Ele simula uma rede corporativa segmentada utilizando Docker, representando uma empresa fictícia com diferentes sub-redes, estações de trabalho, servidores e dispositivos pessoais. O objetivo é realizar o **mapeamento completo dos ativos e sub-redes disponíveis**, identificar máquinas acessíveis, determinar os propósitos das sub-redes e elaborar um inventário técnico detalhado. 🌐 |
|:---:|
| |
| **<span style="color: blue;">Clique no book para baixar a versão detalhada!</span>** |
| <a href="/doc/img/ebook_animacao.gif" target="_blank"><img style="margin: 10px" height="700" width="800" src="/doc/img/ebook_animacao_600_390.gif" alt="Ebook"/></a> |

TODO: Mudar link para o arquivo 'Modulo01-Fundamentos-Projeto-01.pdf'

---

## 📖 Sumário
<a id="topo"></a>

1. [Sumário Executivo](#sumario-executivo)
2. [Objetivo](#objetivo)
3. [Escopo](#escopo)
4. [Metodologia](#metodologia)
5. [Etapas do Reconhecimento das Redes](#etapas-do-reconhecimento-das-redes)
6. [Descoberta de Hosts](#descoberta-de-hosts)
7. [Scan de Portas](#scan-de-portas)
8. [Extras Úteis](#extras-úteis)
9. [Organização dos Resultados](#organizacao-dos-resultados)
10. [Inventário Final - Tabela Descritiva](#inventario-final---tabela-descritiva)
11. [Diagrama](#diagrama)
12. [Diagnóstico](#diagnostico)
13. [Recomendações](#recomendacoes)
14. [Segurança](#seguranca)
15. [Monitoramento](#monitoramento)
16. [Documentação](#documentacao)
17. [Auditoria](#auditoria)
18. [Extras](#extras)
19. [Plano de Ação (modelo 80/20)](#plano-de-acao-modelo-8020)
20. [Conclusão](#conclusao)
21. [Referências Bibliográficas](#referencias-bibliograficas)
22. [Anexos](#anexos)


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
Ferramentas como `arp` e `netdiscover` foram utilizadas para mapear endereços IP e dispositivos na rede, complementando a análise. 🖧

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
**[Espaço reservado para o diagrama da rede]**

| <a href="/doc/img/diagrama_rede_empresa.png" target="_blank"><img style="margin: 0px" height="900" width="800" src="/doc/img/diagrama_rede_empresa.png" alt="Ebook"/></a> |
|:---:|

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
**[Espaço reservado para as referências bibliográficas]**

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---

## 📎 <a name="anexos"></a>Anexos
**[Espaço reservado para anexos e documentos complementares]**

<p align="right">
  <a href="#topo" style="text-decoration: none; background-color: #007bff; color: white; padding: 10px 20px; border-radius: 5px;">Voltar ao Topo</a>
</p>

---