# MiningDES

**MiningDES** é uma ferramenta de apoio à decisão para o planejamento operacional de sistemas de carregamento e transporte em mineração, baseada em **Simulação a Eventos Discretos (DES)** integrada a **Otimização Multiobjetivo**.

O projeto foca no problema clássico de **despacho caminhão–escavadeira (Truck–Shovel)**, no qual decisões operacionais locais têm impactos significativos sobre produção, custo, qualidade do produto e risco operacional.

---

## 📌 O problema

Em operações de mina a céu aberto, o sistema caminhão–escavadeira é responsável pela maior parte da movimentação de material e representa uma parcela relevante do custo operacional.

As decisões de despacho — como:
- qual caminhão deve atender qual escavadeira,
- quando realocar frota entre frentes,
- como responder a falhas e variabilidade operacional,

são tomadas em um ambiente **dinâmico, estocástico e altamente acoplado**, no qual melhorias em produção podem gerar impactos negativos em custo, qualidade ou estabilidade do sistema.

Na prática, muitas dessas decisões ainda são baseadas em regras heurísticas fixas ou experiência operacional, com **baixa visibilidade dos trade-offs envolvidos**.

---

## 🎯 Objetivo do MiningDES

O **MiningDES** busca **sanar a falta de visibilidade integrada** entre desempenho operacional, econômico e de qualidade no despacho caminhão–escavadeira, permitindo que gestores e engenheiros:

- Avaliem diferentes políticas de despacho **antes de aplicá-las na mina real**
- Compare cenários operacionais sob **incerteza**
- Entendam claramente os **trade-offs multiobjetivo** do sistema

---

## 💼 Impacto esperado para a empresa de mineração

O uso do MiningDES permite:

- Elaboração de **planos operacionais mais eficientes**
- Redução de custo por tonelada movimentada
- Melhoria da aderência às especificações de produto
- Redução do risco operacional e da variabilidade
- Maior previsibilidade da produção
- Tomada de decisão baseada em evidências quantitativas

Tudo isso **sem necessidade de investimentos adicionais em equipamentos**, apenas melhorando a forma como o sistema é operado.

---

## ⚖️ Natureza multiobjetivo do problema

O despacho caminhão–escavadeira é tratado como um **problema multiobjetivo**, no qual diferentes políticas são avaliadas simultaneamente segundo:

- **Produção**
  - Toneladas movimentadas
  - Utilização de equipamentos
- **Custo**
  - Custo operacional total
  - Custo por tonelada
- **Qualidade**
  - Aderência às especificações de teor
  - Variabilidade do produto entregue
- **Risco**
  - Robustez frente a falhas
  - Variabilidade da produção e do tempo de ciclo

O MiningDES permite explorar esses objetivos de forma conjunta, identificando **soluções dominadas e não dominadas (fronteira de Pareto)**.

---

## 📤 Saídas geradas pela ferramenta

Para cada cenário simulado, o MiningDES gera:

### 🔹 Indicadores numéricos (KPIs)
- Produção total e média
- Utilização de caminhões e escavadeiras
- Tempos de fila e ociosidade
- Custo operacional e margem
- Indicadores de qualidade e conformidade

### 🔹 Séries temporais
- Produção ao longo do tempo
- Teor médio entregue
- Filas, congestionamentos e estados dos equipamentos

### 🔹 Resumo executivo
- Comparação entre cenários
- Indicadores agregados multiobjetivo
- Visualizações de trade-offs
- Apoio direto à escolha da política operacional

---

## 🧩 Arquitetura conceitual

O MiningDES combina:

1. **Simulação a Eventos Discretos**
   - Representação fiel da dinâmica operacional
   - Inclusão de variabilidade e falhas
2. **Otimização Multiobjetivo**
   - Geração e avaliação de políticas de despacho
   - Exploração do espaço de soluções
3. **Camada de Análise e Visualização**
   - KPIs, gráficos e relatórios para tomada de decisão

---

## 🚧 Status do projeto

Projeto em desenvolvimento.  
Estrutura inicial focada na modelagem do sistema caminhão–escavadeira e definição dos indicadores de desempenho.

---

## 📄 Licença

A definir.
