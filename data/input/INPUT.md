# O que é um “cenário” no MiningDES?

> Um cenário é uma descrição completa e consistente do ambiente operacional, recursos disponíveis, regras de decisão, incertezas e objetivos de negócio sob os quais o sistema caminhão–escavadeira será avaliado.

Ele responde à pergunta:

> “Se o mundo fosse assim, como o sistema se comportaria?”

---

## 1️⃣ Ambiente físico da mina
### 🔹 Frentes de lavra (mine faces)

* ID da frente

* Tipo de material (minério A, B, estéril, ROM, etc.)

* Teor médio esperado

* Variabilidade do teor

* Capacidade máxima de produção

* Disponibilidade operacional: Em que fração do tempo aquela frente está realmente apta a receber caminhões e produzir material.

📌 Impacta diretamente qualidade, produção e roteamento.

### 🔹 Rotas

* Origem → destino

* Distância

* Velocidade média

* Restrições operacionais

* Variabilidade de tempo

📌 Define o tempo de ciclo e o congestionamento.

### 🔹 Destinos

* Britador

* Pilhas

* Pátios de blending

* Bota-fora

📌 Importante para qualidade e custo.

## 2️⃣ Recursos operacionais
### 🔹 Caminhões

* Quantidade

* Capacidade (t)

* Velocidade carregado / vazio

* Consumo ou custo por hora

* Taxa de falha

* Tempo de reparo

### 🔹 Escavadeiras

* Quantidade

* Taxa de carregamento (t/min)

* Compatibilidade com caminhões

* Custo operacional

* Taxa de falha

📌 Aqui já nasce o acoplamento caminhão–escavadeira.

## 3️⃣ Processos operacionais

* Tempo de carregamento (distribuição)

* Tempo de transporte

* Tempo de descarga

* Regras de fila

* Regras de prioridade

* Eventos de falha

* Manutenções

📌 Essa camada transforma recursos em dinâmica DES.

## 4️⃣ Produtos e qualidade
### 🔹 Produtos comercializáveis

* ID do produto

* Faixa de teor aceitável

* Penalidades por fora de especificação

* Preço por tonelada

### 🔹 Regras de blending

* Mistura permitida

* Janelas de tempo

* Restrições operacionais

📌 Aqui se conecta operação ↔ mercado.

## 5️⃣ Demanda e plano de produção

* Volume demandado por produto

* Horizonte de planejamento

* Prioridades de atendimento

* Flexibilidade da demanda

📌 A demanda induz decisões de despacho.