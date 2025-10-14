# Repositório de imagens do projeto CryptoShield, desenvolvido para o Challenge FIAP x TecBan 2025.

Este repositório reúne as principais **evidências visuais** do projeto **CryptoShield**, desenvolvido no âmbito do **Challenge FIAP x TecBan 2025**.

As imagens demonstram a execução prática do sistema de **monitoramento e detecção de fraudes em transações on-chain**, validando todas as integrações do projeto:

---

### [Execução em tempo real – Terminal](https://github.com/Crypto-Shield256/Projeto/blob/main/Terminal.png)
Execução do **monitor de fraudes desenvolvido em Python**, analisando blocos em tempo real na **rede Ethereum Sepolia (testnet)**.

O terminal exibe o processamento contínuo de transações e a emissão de alertas, com integração validada ao **Splunk Enterprise** e ao **Telegram Bot**, demonstrando o funcionamento completo da arquitetura de **detecção e notificação automatizada**.

### [Alertas automáticos – Telegram Bot](https://github.com/Crypto-Shield256/Projeto/blob/main/Telegram.png)
Notificações do **bot CryptoShield Alerts**, responsável por enviar **notificações automáticas via Telegram** sobre transações suspeitas detectadas pelo sistema.

Os alertas incluem rede, bloco, horário (UTC e local), endereços envolvidos, valor em ETH, severidade e motivos da detecção, além de link direto para consulta no **Etherscan**.

Essa integração permite que **gestores e analistas recebam avisos imediatos mesmo fora do ambiente corporativo**, em **dias de folga ou situações de plantão remoto**, garantindo **resposta rápida e proatividade** diante de eventos suspeitos.

### [Alchemy - API](https://github.com/Crypto-Shield256/Projeto/blob/main/Alchemy.png)
Painel da **Alchemy** exibindo o volume de requisições processadas, demonstrando a conectividade entre o monitor e a blockchain Ethereum Sepolia.

### [Armazenamento e análise – Splunk Enterprise](https://github.com/Crypto-Shield256/Projeto/blob/main/Splunk%20Enterprise.png)
Painel do **Splunk Enterprise**, solução voltada para **armazenamento de logs, correlação de eventos e análise avançada de dados**.

Cada alerta enviado pelo sistema é estruturado em formato JSON, contendo detalhes sobre o tipo de detecção, endereços, valores e nível de risco.

Essa integração permite **consultas precisas e históricas** dos alertas, possibilitando auditorias, investigações forenses e **melhoria contínua dos critérios de detecção**.

### [Monitoramento do servidor – Ubuntu Server LTS](https://github.com/Crypto-Shield256/Projeto/blob/main/Ubuntu%20LTS.png)
É possível observar os processos ativos do **Splunk**, **MongoDB** e **Python**, confirmando o funcionamento simultâneo e estável de todos os componentes do sistema com baixo consumo de recursos — reforçando a **viabilidade e eficiência operacional** do projeto.

---

> Todas as execuções foram realizadas em ambiente controlado utilizando a **rede Sepolia (testnet oficial da Ethereum)**, garantindo **segurança e realismo** sem uso de ativos reais.

---

## Autoria
Projeto desenvolvido pela equipe **CryptoShield**:
- Henrique Ribeiro
- Henrique Yun Seong Lee
- Melissa Ramos Tavernari
- Leonardo Pimentel Soriano

---

## Licença
Este repositório e seu conteúdo visual são disponibilizados sob a licença **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**.

Isso significa que:
- O material **pode ser visualizado, compartilhado e referenciado**,  
- **desde que haja crédito aos autores**,  
- e **sem uso comercial** ou redistribuição modificada sem autorização prévia.

Mais detalhes: [https://creativecommons.org/licenses/by-nc/4.0/](https://creativecommons.org/licenses/by-nc/4.0/)

