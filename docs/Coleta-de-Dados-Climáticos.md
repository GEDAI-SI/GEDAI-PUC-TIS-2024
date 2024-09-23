### Processo 1: Coleta de Dados Climáticos

#### Requisitos Funcionais:

1. O sistema deve permitir a configuração de intervalos de tempo para a coleta de dados climáticos de APIs, ajustando a frequência de acordo com as necessidades do usuário.
2. O sistema deve consolidar dados de diferentes fontes (e.g., OpenWeather, WeatherAPI, Visual Crossing) em um formato único e uniforme, garantindo que todos os parâmetros climáticos necessários (temperatura, umidade, etc.) sejam capturados.

#### Requisitos Não Funcionais:

1. **Confiabilidade:** O sistema deve garantir uma taxa de sucesso de 99,9% na recuperação de dados climáticos de APIs, com tentativas automáticas de reconexão em caso de falha.
2. **Desempenho:** O tempo de resposta para a coleta de dados de uma API não deve exceder 3 segundos em 95% das requisições, mesmo em condições de pico de uso.
