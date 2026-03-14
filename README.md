# Projeto de Infraestrutura de Rede: Supermercado Colina

## 📋 Sobre o Projeto
[cite_start]Este projeto consiste no planejamento e simulação de uma infraestrutura de rede completa para uma rede de supermercados fictícia denominada **Colina**, localizada em Curitiba-PR[cite: 7, 8]. [cite_start]O objetivo foi integrar conhecimentos de redes locais (LAN), interconexão de unidades e Internet das Coisas (IoT) em um cenário empresarial realístico[cite: 2, 4].

[cite_start]O projeto abrange três unidades principais estrategicamente conectadas[cite: 8]:
* [cite_start]**Matriz:** Unidade completa com setores de atendimento, caixa, padaria e açougue[cite: 17].
* [cite_start]**Centro de Operações (Escritório Administrativo):** Foco em gestão, servidores e RH[cite: 12].
* [cite_start]**Filial:** Unidade de menor porte otimizada para praticidade[cite: 10].

## 🛠️ Tecnologias e Ferramentas Utilizadas
* [cite_start]**Simulador:** Cisco Packet Tracer[cite: 6].
* [cite_start]**Protocolos de Endereçamento:** IPv6 (Unicast-routing e endereçamentos Link-Local FE80::1)[cite: 17, 20].
* [cite_start]**Serviços de Rede:** DNS, WEB, SMTP e POP3 para comunicação interna e externa[cite: 15, 16].
* [cite_start]**Hardware Simulado:** Roteadores, Switches, Hubs e Dispositivos IoT[cite: 6].

## 🏗️ Arquitetura da Rede
[cite_start]A rede foi dividida em clusters geográficos para otimização do tráfego e funcionalidade[cite: 10, 11].

### Destaques Técnicos:
* [cite_start]**Segmentação Administrativa:** O escritório foi subdividido em setores como Diretoria, Gerência, RH e Marketing, garantindo segurança e organização[cite: 12].
* [cite_start]**Integração IoT:** Implementação de automação residencial/comercial, incluindo portas automáticas e ar-condicionado controlados pela rede[cite: 11].
* [cite_start]**Servidores de Comunicação:** Configuração de servidores de e-mail (SMTP/POP3) para troca de informações segura entre as unidades[cite: 16].
* [cite_start]**Transição de Hardware:** Substituição estratégica de Hubs por Switches para melhor gerenciamento de pacotes e suporte a IPv6[cite: 14].

## 📂 Organização das Unidades
* **Escritório Administrativo:** Gateway padrão `FE80::1`. [cite_start]Contém o núcleo de servidores (WEB/DNS)[cite: 15, 17].
* [cite_start]**Matriz:** Estruturada com setores de Granel, Padaria, Açougue e monitoramento por câmeras[cite: 17, 18].
* [cite_start]**Filial:** Sistema autônomo baseado na planta da matriz, mas em escala reduzida, utilizando equipamentos padronizados para facilitar a manutenção[cite: 10, 20].

## 🚀 Como Visualizar
1. Baixe o arquivo `.pkt` na pasta `/packet-tracer-files`.
2. Abra no **Cisco Packet Tracer** (versão recomendada: 8.x).
3. Consulte o relatório completo na pasta `/docs` para detalhes de comandos de configuração.

---
[cite_start]**Autores:** Cristian Yehudi Marques Ros, Fabricio Corrêa de Souza, Matheus Gonçalves Gotardo e Nicole Guerreiro Diniz[cite: 1].
[cite_start]**Instituição:** Centro Universitário Campos de Andrade (UNIANDRADE)[cite: 2].
