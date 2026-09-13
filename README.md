# Calculadora de Salário Líquido 2026 - Especialista em Financiamento do FNDE

Aplicação web completa, responsiva e interativa desenvolvida em HTML, CSS e JavaScript puro para cálculo de remuneração bruta e líquida da carreira de **Especialista em Financiamento e Execução de Programas e Projetos Educacionais do Fundo Nacional de Desenvolvimento da Educação (FNDE)**, com base na **Tabela Salarial Oficial de 2026**.

---

## 🌟 Principais Recursos

1. **Dois Modos de Cálculo Flexíveis**:
   - 🏛️ **Modo Carreira FNDE 2026**:
     - Seleção visual das **4 Classes** (D, C, B, A) e **5 Padrões** (I a V) — totalizando 20 níveis remuneratórios.
     - Seleção da **Retribuição por Titulação (RT)**: Graduação (Sem RT), Especialização (Pós Lato Sensu), Mestrado e Doutorado.
     - Acúmulo opcional com **Cargos em Comissão e Funções de Confiança (FCE 01 a FCE 17)**.
   - ✏️ **Modo Salário Livre / Independente**:
     - Campo aberto para digitar qualquer valor de **Salário Bruto Tributável (R$)**.
     - Campo para **Outras Indenizações / Auxílios Isentos (R$)** (diárias, transporte, ajuda de custo etc.).
     - Permite simular qualquer remuneração do serviço público ou cargos federais de forma 100% independente da tabela da carreira.
2. **Regras Fiscais e Previdenciárias Oficiais (Executivo Federal)**:
   - **Previdência (CPSS)** com alíquotas progressivas da EC 103/2019.
   - **Regime Pós-2013**: limitado ao Teto do RGPS de **R$ 8.475,55**, resultando no desconto máximo de CPSS fixado em **R$ 988,09**, com adesão opcional ao **Funpresp-Exe** sobre o excedente.
   - **Regime Pré-2013**: integral sem teto com alíquotas progressivas completas.
   - **Funpresp-Exe** (Previdência Complementar do Servidor Público Federal): alíquotas de 7,0% a 8,5% com cálculo da contrapartida paritária de 1:1 da União e dedução de 100% na base do IRPF.
   - **Imposto de Renda (IRPF)** com tabela progressiva e comparação automática entre as deduções legais e o desconto simplificado da Receita Federal.
   - **Dependentes e Pensão Alimentícia**.
3. **Cargos em Comissão e Funções de Confiança (FCE - Lei nº 14.204/2021)**:
   - Seleção e acúmulo de **Funções Comissionadas Executivas (FCE 01 a FCE 17)** privativas de servidores efetivos.
   - Cálculo automático do acréscimo de 100% da função à remuneração bruta.
   - Aplicação da regra legal (Lei nº 10.887/2004): a previdência (CPSS) incide sobre a remuneração do cargo efetivo, e a FCE compõe a base de cálculo do IRPF retido na fonte.
   - Aba dedicada com a tabela oficial de remuneração das FCEs, filtro instantâneo por nomenclatura e exportação para CSV.
4. **Benefícios e Indenizações Isentas**:
   - **Auxílio-Alimentação de R$ 1.192,00** (valor oficial vigente em 2026, isento de IR e CPSS).
   - **Outras Indenizações Isentas** (campo configurável para ajudas de custo, diárias e adicionais indenizatórios).
   - **Auxílio Pré-Escolar (Creche)** para dependentes até 5 anos (R$ 484,90 cada).
   - **Auxílio-Saúde Suplementar** (per capita).
   - **KPI de Remuneração Bruta Total**: exibe o montante bruto integral somado à alimentação e demais vantagens, detalhando no subtítulo a separação entre Base Tributável e Vantagens Isentas.
5. **Espelho de Contracheque / Holerite Oficial Simplificado**:
   - Modelo visual limpo e oficial inspirado no SouGov/Siape sem coluna de código, focado na clareza de **Descrição da Rubrica**, **Referência**, **Proventos** e **Descontos**.
   - Discriminação de todas as rubricas de proventos (Vencimento Básico, RT, FCE, Salário Informado, Indenizações, Benefícios) e descontos.
   - Botão **Imprimir / Salvar PDF** formatado para folha A4.
6. **Tabelas Panorâmicas e Exportação**:
   - Aba da Tabela Salarial 2026 (20 padrões x 4 titulações lado a lado).
   - Aba da Tabela FCE 2026 (FCE 01 a FCE 17 com nomenclaturas e valores).
   - Botões para **Exportar para CSV (Excel)** em ambas as tabelas.
7. **Gráficos e Compartilhamento**:
   - Barra de decomposição visual do salário (% Líquido, % CPSS, % IRPF, % Funpresp).
   - Botão **Copiar Resumo** formatado para WhatsApp e redes sociais (contemplando tanto o modo carreira quanto o modo salário livre).
   - Alternância entre **Modo Claro (Light)** e **Modo Escuro (Dark)**.
   - **100% Offline e Portátil**: Nenhum servidor é necessário. Basta abrir o arquivo `index.html` em qualquer navegador.

---

## 📂 Como Usar e Compartilhar

1. **No Computador (Windows / Mac / Linux)**:
   - Dê um duplo clique no arquivo [`index.html`](index.html). Ele abrirá instantaneamente em qualquer navegador (Chrome, Edge, Firefox, Safari).
2. **No Celular**:
   - Envie o arquivo `index.html` pelo WhatsApp ou Telegram e abra no navegador do smartphone.
3. **Na Nuvem**:
   - Pode ser hospedado gratuitamente no GitHub Pages, Vercel, Netlify ou servidor web corporativo.

---

## 📊 Estrutura Salarial 2026 (Resumo)

| Classe | Padrão | VB (R$) | RT Espec. (R$) | RT Mestrado (R$) | RT Doutorado (R$) | Total Sem RT (R$) | Total Espec. (R$) | Total Mestrado (R$) | Total Doutorado (R$) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **D** | **V** | 17.391,23 | 2.269,71 | 4.294,18 | 5.808,92 | 17.391,23 | 19.660,94 | 21.685,40 | 23.200,14 |
| **D** | **IV** | 16.881,07 | 2.203,13 | 4.168,21 | 5.638,52 | 16.881,07 | 19.084,20 | 21.049,28 | 22.519,59 |
| **D** | **III** | 16.385,88 | 2.138,50 | 4.045,94 | 5.473,12 | 16.385,88 | 18.524,38 | 20.431,81 | 21.858,99 |
| **D** | **II** | 15.905,21 | 2.075,77 | 3.927,25 | 5.312,57 | 15.905,21 | 17.980,98 | 19.832,46 | 21.217,77 |
| **D** | **I** | 15.438,64 | 2.014,88 | 3.812,05 | 5.156,73 | 15.438,64 | 17.453,52 | 19.250,69 | 20.595,37 |
| **C** | **V** | 14.896,79 | 1.944,16 | 3.678,26 | 4.975,74 | 14.896,79 | 16.840,96 | 18.575,05 | 19.872,53 |
| **C** | **IV** | 14.459,81 | 1.887,13 | 3.570,36 | 4.829,78 | 14.459,81 | 16.346,94 | 18.030,17 | 19.289,59 |
| **C** | **III** | 14.035,64 | 1.831,78 | 3.465,63 | 4.688,10 | 14.035,64 | 15.867,41 | 17.501,27 | 18.723,74 |
| **C** | **II** | 13.623,91 | 1.778,04 | 3.363,97 | 4.550,58 | 13.623,91 | 15.401,96 | 16.987,88 | 18.174,49 |
| **C** | **I** | 13.224,27 | 1.725,89 | 3.265,29 | 4.417,09 | 13.224,27 | 14.950,15 | 16.489,55 | 17.641,36 |
| **B** | **V** | 12.760,13 | 1.665,31 | 3.150,68 | 4.262,07 | 12.760,13 | 14.425,45 | 15.910,82 | 17.022,20 |
| **B** | **IV** | 12.385,83 | 1.616,46 | 3.058,26 | 4.137,04 | 12.385,83 | 14.002,29 | 15.444,09 | 16.522,87 |
| **B** | **III** | 12.022,50 | 1.569,04 | 2.968,55 | 4.015,68 | 12.022,50 | 13.591,54 | 14.991,05 | 16.038,18 |
| **B** | **II** | 11.669,83 | 1.523,02 | 2.881,47 | 3.897,89 | 11.669,83 | 13.192,84 | 14.551,30 | 15.567,71 |
| **B** | **I** | 11.327,50 | 1.478,34 | 2.796,94 | 3.783,55 | 11.327,50 | 12.805,84 | 14.124,44 | 15.111,05 |
| **A** | **V** | 10.839,71 | 1.414,68 | 2.676,50 | 3.620,62 | 10.839,71 | 12.254,39 | 13.516,22 | 14.460,33 |
| **A** | **IV** | 10.473,15 | 1.366,84 | 2.585,99 | 3.498,18 | 10.473,15 | 11.839,99 | 13.059,14 | 13.971,34 |
| **A** | **III** | 10.118,99 | 1.320,62 | 2.498,54 | 3.379,89 | 10.118,99 | 11.439,61 | 12.617,53 | 13.498,87 |
| **A** | **II** | 9.776,80 | 1.275,96 | 2.414,05 | 3.265,59 | 9.776,80 | 11.052,76 | 12.190,85 | 13.042,39 |
| **A** | **I** | 9.446,18 | 1.232,81 | 2.332,42 | 3.155,16 | 9.446,18 | 10.679,00 | 11.778,60 | 12.601,34 |

---

## 🏛️ Tabela de Cargos em Comissão e Funções de Confiança (FCE - Lei 14.204/2021)

| Código | Nomenclatura Oficial | Categoria | Valor Integral (R$) |
| :---: | :---: | :---: | :---: |
| **FCE 17** | Dirigente Máximo | Alta Direção | 16.765,90 |
| **FCE 16** | Diretor | Diretoria | 14.045,67 |
| **FCE 15** | Diretor | Diretoria | 12.196,47 |
| **FCE 14** | Coordenador-Geral | Coordenação-Geral | 10.432,37 |
| **FCE 13** | Coordenador-Geral | Coordenação-Geral | 8.651,81 |
| **FCE 12** | Coordenador | Coordenação | 6.513,87 |
| **FCE 11** | Coordenador | Coordenação | 5.193,87 |
| **FCE 10** | Coordenador | Coordenação | 4.455,87 |
| **FCE 09** | Chefe de Divisão | Chefia de Divisão | 3.498,47 |
| **FCE 08** | Chefe de Divisão | Chefia de Divisão | 3.356,01 |
| **FCE 07** | Chefe de Divisão | Chefia de Divisão | 2.908,64 |
| **FCE 06** | Chefe de Serviço | Chefia de Serviço | 2.463,00 |
| **FCE 05** | Chefe de Serviço | Chefia de Serviço | 2.099,09 |
| **FCE 04** | Chefe de Seção | Chefia de Seção | 1.553,73 |
| **FCE 03** | Chefe de Seção | Chefia de Seção | 1.294,43 |
| **FCE 02** | Chefe de Setor | Chefia de Setor | 723,98 |
| **FCE 01** | Chefe de Setor | Chefia de Setor | 428,38 |
