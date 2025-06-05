# 🛡️ Análise de Incidente de Segurança com tcpdump – Caso yummyrecipesforme.com

Este repositório contém uma análise detalhada de um incidente de segurança cibernética envolvendo o comprometimento do site fictício `yummyrecipesforme.com`. O caso aborda um ataque de força bruta realizado por um ex-funcionário, que resultou na inserção de um script malicioso e redirecionamento para um site falso com malware.


## 🎯 Objetivo

Este repositório tem como objetivo:

- Demonstrar como utilizar `tcpdump` para analisar tráfego de rede em um ambiente comprometido.
- Identificar sinais de ataque de força bruta e injeção de malware.
- Documentar o processo investigativo de forma estruturada e didática.
- Propor soluções práticas para prevenir ataques semelhantes no futuro.

## 🔍 Cenário do Incidente

- **Ataque:** Força bruta para acesso ao painel administrativo.
- **Vetor:** Inserção de código JavaScript malicioso no site.
- **Impacto:** Redirecionamento dos usuários para `greatrecipesforme.com` com malware.
- **Falha de segurança:** Senha padrão mantida + ausência de 2FA.

## ⚙️ Tecnologias e Conceitos Utilizados

- `tcpdump` – ferramenta de captura e análise de pacotes.
- Protocolos de rede: DNS, HTTP, TCP.
- Modelo TCP/IP (camadas de rede).
- Técnicas de mitigação de ataques de força bruta.
- Redirecionamento malicioso (phishing + malware).

## 🛡️ Recomendação de Segurança

A principal recomendação apresentada no relatório foi a **implementação de autenticação de dois fatores (2FA)**, além de políticas de senhas fortes e monitoramento de tentativas de login.

## 📚 Para Estudo

Este repositório pode ser usado como material de apoio para estudantes e profissionais iniciantes na área de:

- Análise de tráfego de rede
- Resposta a incidentes
- Segurança ofensiva e defensiva
- Ferramentas de linha de comando para forense de rede

## 📜 Licença

Este projeto é fornecido apenas para fins **educacionais** e de **treinamento**. Nenhum dos domínios ou arquivos representa um sistema real.

