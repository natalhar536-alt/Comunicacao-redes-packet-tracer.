# Comunicação entre 3 Redes Distintas no Cisco Packet Tracer

Projeto prático desenvolvido durante a Aula 07 do Programa Mulher Digital, utilizando a plataforma Cisco Packet Tracer para aplicar conceitos fundamentais de redes e infraestrutura de TI.

## 🎯 Objetivo do Projeto
O desafio consistiu em montar e configurar uma infraestrutura digital onde três redes de computadores de classes totalmente diferentes pudessem se comunicar de forma segura e bem-sucedida através de um roteador central.

## 🛠️ Equipamentos e Estrutura Utilizada
* **1 Roteador Cisco 2911:** Responsável por interligar e fazer o mapeamento de caminhos entre as três redes.
* **3 Switches Cisco 2960:** Utilizados para concentrar os computadores de cada localidade (Switch A, Switch B e Switch C).
* **6 Computadores (PCs):** Sendo duas estações de trabalho configuradas para cada classe de rede.
* **Cabeamento:** Conexões realizadas via cabos de cobre do tipo direto (Copper Straight-Through).

## 📊 Configurações Técnicas Realizadas

### 1. Divisão e Endereçamento das Redes:
* **Rede Classe A:** Configurada com o Gateway `10.0.0.1` (Interface GigabitEthernet0/0 do Roteador).
* **Rede Classe B:** Configurada com o Gateway `172.16.0.1` (Interface GigabitEthernet0/1 do Roteador).
* **Rede Classe C:** Configurada com o Gateway `192.168.1.1` (Interface GigabitEthernet0/2 do Roteador).

### 2. Configuração dos Computadores:
Cada computador recebeu manualmente o seu endereço IP dinâmico e sua respectiva máscara de sub-rede dentro do sistema para garantir o fluxo correto de dados.

## 🚀 Resultados e Testes de Conexão
Após realizar todas as conexões de cabos e ativações de portas, realizei testes de envio de pacotes de dados (ICMP) entre computadores de redes diferentes (ex: PC A1 enviando dados para o PC C1). O painel de testes acusou o status de **"Successful"** (Sucesso), comprovando que a comunicação de bastidores funciona perfeitamente.

## 📸 Evidências do Projeto

### Topologia da Rede Funcionando:
<img width="1912" height="1030" alt="Captura de tela 2026-09-13 134805" src="https://github.com/user-attachments/assets/598f2ebc-a783-4a3b-baec-495d1762b6f5" />

### 🎥 Vídeo de Apresentação e Tutorial do Projeto
* **Desenvolvimento Prático:** Realizei a montagem e a configuração completa de toda a infraestrutura da rede do início ao fim no meu simulador.
* **Apresentação em Vídeo:** A gravação e a explicação do tutorial foram realizadas em equipe, onde dividimos os tópicos para a apresentação final do grupo.

[Assista ao Vídeo Completo no YouTube](https://youtu.be/Z2j3y9h8_Ro)
*(Nota: Minha participação técnica acontece durante a apresentação a partir do tempo 03:01).*
