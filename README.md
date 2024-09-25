# Projeto de Análise de Dados de Salários e Atributos de Emprego de Desenvolvedores (2024)

## Descrição do Projeto

Este projeto utiliza um conjunto de dados de 2024 que contém informações sobre salários e atributos de emprego dos desenvolvedores de dados. O objetivo principal é realizar análises estatísticas e visuais a partir das variáveis presentes no dataset, como salário, título de emprego, nível de experiência, tipo de emprego, proporção de trabalho remoto, localização do funcionário e tamanho da empresa.

Este conjunto de dados oferece insights valiosos sobre as tendências salariais, a distribuição das funções de desenvolvedor em diferentes regiões, o impacto do trabalho remoto e o tamanho da empresa sobre o emprego. Pesquisadores, analistas e organizações podem usar essas informações para entender melhor o cenário de remuneração e padrões de emprego entre desenvolvedores de dados.

## Estrutura do Projeto

### Tarefas Realizadas:

1. **Tabela de Frequências para a Variável `salário_in_usd`** (1 ponto):
   - Construção de uma tabela de frequências para representar a variável `salário_in_usd`, que contém o salário convertido em dólares americanos para comparação entre regiões.

2. **Tabela de Frequências para a Variável `job_title`** (1 ponto):
   - Construção de uma tabela de frequências para representar os títulos de trabalho (por exemplo, Engenheiro de Dados, Cientista de Dados).

3. **Gráficos para Variáveis** (6 pontos):
   - Gráficos apropriados para as seguintes variáveis:
     - `experience_level`: Nível de experiência do desenvolvedor.
     - `employment_type`: Tipo de emprego (tempo integral, meio período, contrato, etc.).
     - `salário_in_usd`: Distribuição do salário em dólares americanos.
     - `remote_ratio`: Proporção de trabalho realizado remotamente.
     - `company_size`: Tamanho da empresa baseado no número de funcionários.
   - Parágrafo de análise para cada gráfico, destacando os principais achados.

4. **Medidas Descritivas e Boxplot para `salário_in_usd`** (3 pontos):
   - Cálculo de medidas descritivas (média, mediana, mínimo, máximo, desvio padrão, coeficiente de variação, 1º e 3º quartis).
   - Construção de um boxplot para a variável `salário_in_usd`.
   - Parágrafo detalhando as informações obtidas com base nas medidas descritivas e no boxplot.

5. **Tabela de Contingência e Gráfico entre `experience_level` e `remote_ratio`** (3 pontos):
   - Tabela de contingência mostrando a frequência e o percentual (de linha, coluna ou geral) entre as variáveis `experience_level` (nível de experiência) e `remote_ratio` (proporção de trabalho remoto).
   - Gráfico apropriado representando essa relação, acompanhado de um parágrafo com os principais achados.

6. **Tabela de Contingência e Gráfico entre `employment_type` e `company_size`** (3 pontos):
   - Tabela de contingência mostrando a relação entre `employment_type` (tipo de emprego) e `company_size` (tamanho da empresa).
   - Gráfico correspondente, seguido de um parágrafo explicando os resultados.

7. **Medidas Descritivas Estratificadas por `experience_level` para `salário_in_usd`** (3 pontos):
   - Cálculo das medidas descritivas para `salário_in_usd`, estratificadas pela variável `experience_level`.
   - Boxplot estratificado e parágrafo comparando medianas, variabilidade, presença de outliers e outras informações relevantes.

8. **Medidas Descritivas Estratificadas por `employment_type` para `salário_in_usd`** (3 pontos):
   - Cálculo das medidas descritivas para `salário_in_usd`, estratificadas pela variável `employment_type`.
   - Boxplot estratificado e parágrafo comparando as características dos dados, conforme feito com `experience_level`.

9. **Uso de Gráfico de Linhas** (1 ponto):
   - Discussão sobre uma situação hipotética onde um gráfico de linhas seria adequado para representar os dados.
   - Exemplos de informações que podem ser extraídas de um gráfico de linhas.

10. **Mapas de Calor em Tabelas** (1 ponto):
    - Pesquisa sobre a utilidade dos mapas de calor em tabelas, incluindo um exemplo hipotético de sua aplicação.

## Descrição das Variáveis do Dataset:

- **experience_level**: Nível de experiência do funcionário (júnior, pleno, sênior).
- **employment_type**: Tipo de contrato de trabalho (tempo integral, meio período, contrato).
- **job_title**: Cargo ou título do funcionário (ex.: Engenheiro de Dados).
- **salário**: Salário original recebido na moeda local.
- **salário_currency**: Moeda em que o salário é pago.
- **salário_in_usd**: Salário convertido para dólares americanos para comparação.
- **employee_residence**: Local de residência do funcionário.
- **remote_ratio**: Porcentagem de trabalho remoto realizado.
- **company_location**: Localização da empresa.
- **company_size**: Tamanho da empresa, baseado no número de funcionários.

## Como Executar o Projeto:

1. **Pré-requisitos**:
   - Python 3.x

2. **Instalação das dependências**:
   ```bash
   pip install -r requirements.txt
