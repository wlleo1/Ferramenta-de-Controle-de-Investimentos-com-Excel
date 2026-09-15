# Ferramenta-de-Controle-de-Investimentos-com-Excel
Ferramenta criada no bootcamp Excel com IA da Dio!
# Visão Geral da Ferramenta

O arquivo **“Ferramenta de Controle de Investimentos - Cópia.xlsx”** é uma planilha criada para ajudar o usuário a simular investimentos em **Fundos Imobiliários (FIIs)**.

A ferramenta permite informar valores como salário, investimento mensal, tempo de investimento e taxa de rendimento. Com essas informações, ela calcula o **patrimônio acumulado** e uma estimativa dos **dividendos mensais**.

A planilha possui duas áreas principais:

* **Configurações:** onde o usuário informa os dados e visualiza os resultados.
* **Investimento Mensal:** onde ficam os dados usados para definir a distribuição dos investimentos de acordo com o perfil do investidor.

## 1. Configurações

A área **Configurações** é a parte principal da ferramenta. Nela são inseridas as informações usadas nos cálculos.

### Configurações básicas

* **Salário:** valor da renda mensal do usuário.
* **Rendimento da Carteira:** taxa de rendimento mensal estimada.
* **Sugestão de Investimento (30%):** calcula automaticamente 30% do salário como sugestão de valor para investir.

**Exemplo:**
Salário de R$ 3.000,00 → sugestão de investimento de R$ 900,00.

### Simulação de investimento

Nesta parte, o usuário informa:

* **Quanto investir por mês?** — valor do aporte mensal.
* **Por quantos anos?** — tempo que pretende investir.
* **Taxa de rendimento mensal?** — rendimento esperado por mês.
* **Patrimônio Acumulado?** — valor estimado que será acumulado ao final do período.
* **Dividendos Mensais?** — estimativa de quanto o investimento poderá gerar por mês.

O patrimônio é calculado considerando os **aportes mensais, o tempo de investimento e os juros compostos**.

## 2. Investimento Mensal

A área **Investimento Mensal** contém os dados usados para definir como o dinheiro deve ser distribuído entre os diferentes tipos de FIIs.

Ela possui quatro informações principais:

* **CHAVE:** identifica a combinação entre o perfil e o tipo de FII.
* **PERFIL:** pode ser Conservador, Moderado ou Agressivo.
* **TIPO DE FII:** identifica a categoria do fundo.
* **% (Alocação):** mostra quanto deve ser destinado para cada categoria.

Os tipos de FIIs utilizados são:

* PAPEL
* TIJOLO
* HÍBRIDOS
* FOFs
* DESENVOLVIMENTO
* HOTELARIA

## 3. Como funciona o cálculo

O funcionamento é simples:

1. O usuário informa quanto pretende investir por mês.
2. Informa por quantos anos pretende investir.
3. Informa a taxa de rendimento mensal.
4. A planilha calcula o valor que poderá ser acumulado.
5. Com o patrimônio acumulado, calcula uma estimativa dos dividendos mensais.

O tempo informado em anos é convertido para meses.

**Exemplo:**
5 anos × 12 meses = **60 meses**.

## 4. Definição do perfil

O usuário também pode escolher seu perfil de investimento:

* **Conservador**
* **Moderado**
* **Agressivo**

A partir do perfil escolhido, a ferramenta consulta a área **Investimento Mensal** e mostra uma sugestão de distribuição dos investimentos.

**Exemplo de perfil Conservador:**

* TIJOLO: 50%
* PAPEL: 30%
* HÍBRIDOS: 10%
* FOFs: 10%
* DESENVOLVIMENTO: 0%
* HOTELARIA: 0%

Dessa forma, a ferramenta ajuda o usuário a entender **quanto investir, por quanto tempo, quanto poderá acumular e como distribuir o dinheiro entre os FIIs**.

## Resumo

A ferramenta reúne duas funções principais:

**Simulação financeira:** calcula o crescimento do investimento ao longo do tempo.

**Distribuição dos investimentos:** sugere como dividir o dinheiro entre os tipos de FIIs de acordo com o perfil do investidor.
