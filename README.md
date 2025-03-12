# Em Direção a uma Infraestrutura de Suporte para Avaliação Empírica de Soluções para Cidades Inteligentes

Este repositório contém a análise de dados do **Índice de Desenvolvimento da Educação Básica (IDEB)** e sua correlação com o **Produto Interno Bruto (PIB)** nos municípios brasileiros, com foco em Pernambuco. O objetivo é investigar a relação entre desenvolvimento econômico e desempenho educacional, contribuindo para a avaliação de soluções para cidades inteligentes.

## Metodologia

### Coleta de Dados
- Os dados foram coletados do site oficial do Governo Federal, incluindo tabelas do PIB e do IDEB para todos os municípios brasileiros.
- Foram selecionados 185 municípios pernambucanos no ano de 2021, descartando aqueles com dados nulos, resultando em 182 municípios válidos.

### Análise de Dados
- Utilizamos as bibliotecas Python **Pandas**, **NumPy**, **Seaborn** e **Scipy** para análise exploratória e estatística.
- Foram calculadas estatísticas descritivas (média, variância, desvio padrão) e aplicada a correlação de Spearman para avaliar a relação entre o PIB per capita e o IDEB.
- Gráficos de dispersão foram criados para visualizar a distribuição dos dados.

### Resultados
- A análise revelou uma correlação muito fraca e negativa (-0.029) entre o PIB per capita e o IDEB em Pernambuco.
- Para todo o Brasil, a correlação foi ligeiramente positiva (0.288), mas ainda fraca.
- O desempenho educacional (IDEB) mostrou maior correlação com indicadores de rendimento e notas do SAEB (Sistema de Avaliação da Educação Básica).

## Principais Conclusões
- **Ausência de correlação significativa**: O desenvolvimento econômico (PIB per capita) não é um fator determinante para o desempenho educacional (IDEB).
- **Fatores complexos**: O desempenho educacional é influenciado por uma combinação de fatores que vão além do crescimento econômico.
- **Desafios para cidades inteligentes**: Soluções para melhorar a educação devem considerar múltiplas variáveis, não apenas o desenvolvimento econômico.

## Ferramentas Utilizadas
- **Python**: Linguagem de programação principal.
- **Pandas e NumPy**: Manipulação e análise de dados.
- **Seaborn e Matplotlib**: Visualização de dados.
- **Scipy**: Análise estatística (correlação de Spearman).

## Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/claraaqn/IC-Dadis_IDEB.git
