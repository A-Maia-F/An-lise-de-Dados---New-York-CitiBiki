# Análise de Dados - New York CitiBiki

Projeto de Análise Exploratória de Dados com base na base pública do sistema de bicicletas compartilhadas Citi Bike da cidade de Nova York, disponível no Google BigQuery.

## Objetivo
Extrair, tratar e analisar dados reais de viagens realizadas com bicicletas compartilhadas em Nova York para identificar padrões de uso, comportamentos dos usuários e gerar insights para apoiar decisões estratégicas em mobilidade urbana.

## Tecnologias e Ferramentas Utilizadas
- Google BigQuery – extração de dados públicos via SQL
- Python – linguagem de programação principal
- Pandas – tratamento e manipulação de dados
- Matplotlib & Seaborn – visualização de dados
- Jupyter Notebook – desenvolvimento interativo e exploratório
- pandas-gbq – integração entre Python e BigQuery

# Tratamento e Transformações
- Conversão de colunas de data/hora para tipo datetime.
- Criação da variável "trip_duration_min" para medir duração das viagens.
- Extração de colunas derivadas: weekday (dia da semana) e hour (hora do início da viagem).
-Verificação e análise de valores ausentes e estatísticas descritivas.

# Principais Resultados
- Tempo médio das viagens: ~15 minutos
- Horários com mais viagens: entre 17h e 19h
- Dia da semana com mais uso: Quinta-feira
- Distribuição por gênero: maior uso por homens
- Duração média: viagens femininas tendem a ser um pouco mais curtas
