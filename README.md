# dessal

# 💧 Dessalinizador por Osmose Reversa com Monitoramento Inteligente

Projeto de Trabalho de Conclusão de Curso (TCC) desenvolvido no curso técnico de Automação Industrial, com foco em controle, monitoramento e interface digital de um sistema de dessalinização por osmose reversa.

O sistema realiza o controle do processo de filtragem da água, coleta dados de qualidade e disponibiliza interface local e web para acompanhamento.

---

## 🎯 Objetivo

Desenvolver um sistema automatizado de dessalinização por osmose reversa com:

- Monitoramento de qualidade da água
- Leitura de sensores (pH e TDS)
- Controle de bombas e válvulas
- Interface touch local
- Integração com interface web
- Arquitetura embarcada com ESP32

---

## ⚙️ Funcionamento do Sistema

O sistema executa o processo de osmose reversa:

1. Entrada de água bruta
2. Pressurização por bomba
3. Passagem pela membrana de osmose reversa
4. Separação em:
   - Água permeada (tratada)
   - Rejeito (concentrado)
5. Monitoramento contínuo dos parâmetros
6. Exibição de dados na tela e na interface web

---

## 🧠 Arquitetura de Controle

- Controlador principal: **ESP32 / ESP32-S3**
- Lógica de controle embarcada
- Rotinas de leitura e validação de sensores
- Regras de acionamento de atuadores
- Estrutura preparada para expansão

---

## 🔌 Hardware Utilizado

### Controlador
- ESP32
- ESP32-S3

### Sensores
- Sensor de pH
- Sensor de TDS
- Sensores de qualidade da água
- Entradas analógicas

### Atuadores
- Bomba de pressurização
- Válvulas solenoides
- Módulos de relé

### Interface
- Tela touch
- Painel de operação local

---

## 💻 Software Embarcado

Funcionalidades implementadas:

- Leitura de sensores
- Conversão de sinais analógicos
- Cálculo de parâmetros
- Tratamento de ruído de leitura
- Lógica de decisão
- Controle de relés
- Rotinas de segurança
- Estrutura de envio de dados

---

## 🌐 Interface Web

- Página de apresentação do sistema
- Visualização de dados
- Estrutura front-end
- Layout responsivo
- Comunicação com o dispositivo

Tecnologias:
- HTML
- CSS
- JavaScript

---

## 📡 Comunicação

- Envio de dados do ESP32 para interface web
- Estrutura de dados em JSON
- Comunicação via Wi-Fi
- Integração embarcado → web

---

## 🧮 Engenharia e Projeto

Inclui:

- Diagrama de blocos
- Fluxograma de operação
- Arquitetura do sistema
- Lógica de controle
- Dimensionamento básico
- Estrutura de processo

---

## 🧪 Testes Realizados

- Teste de leitura de pH
- Teste de leitura de TDS
- Teste de estabilidade de dados
- Teste de interface touch
- Teste de comunicação
- Teste de acionamento de atuadores

---

## 📁 Estrutura do Repositório


---

## 🚀 Possíveis Expansões

- Dashboard online em tempo real
- Armazenamento em nuvem
- Alertas automáticos
- Controle remoto
- App mobile
- Registro histórico de medições

---

## 👩‍💻 Autora

Talita Cordeiro Teixeira  
Técnico em Automação Industrial  
Professora de Letramento Digital  
Área de interesse: Sistemas Embarcados, Automação e Monitoramento Inteligente

---

## 📌 Status do Projeto

Protótipo funcional — em evolução para melhorias de interface e monitoramento remoto.
