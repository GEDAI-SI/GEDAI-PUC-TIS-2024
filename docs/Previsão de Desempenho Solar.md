## Processo 3: Previsão de Desempenho Solar 
**Responsável**: Guilherme Henrique Pereira Rocha 
**Aprovador**: Gabriel de Assis Lopes Diniz 

Esse processo utiliza modelos preditivos para estimar o desempenho futuro dos painéis solares, com base nas condições climáticas previstas. A previsão é essencial para otimizar a operação e o planejamento energético. As etapas envolvem: 

### Coleta de Dados Climáticos 

A coleta de dados climáticos no aplicativo envolve a obtenção de informações históricas e em tempo real sobre as condições meteorológicas. Para isso, são utilizadas fontes confiáveis, como serviços meteorológicos globais ou regionais (e.g., APIs de serviços como OpenWeather ou WeatherAPI ou a API da Visual Crossing). Esses dados incluem informações sobre temperatura, umidade, precipitação, irradiância solar, velocidade do vento e outros fatores que influenciam na produção de energia solar. 

Serviços Meteorológicos: O aplicativo se conecta periodicamente a APIs de provedores de serviços meteorológicos para recuperar dados sobre as condições atuais e previsões futuras, proporcionando aos usuários uma visão antecipada do clima que pode afetar o desempenho das placas solares. 

### Modelagem Preditiva 

Utilização de algoritmos que analisam os dados climáticos futuros para prever a produção de energia solar em curto e médio prazo. 

### Cálculo do Desempenho Futuro 

Com base nos dados e no histórico de eficiência do sistema, o desempenho esperado é calculado, permitindo ajustes antecipados na operação. 

Visualização de Previsões 

As estimativas de desempenho são apresentadas em relatórios e gráficos, facilitando o planejamento e a tomada de decisões operacionais.

### Refinamento Técnico
Ao fim dos processos 1 e 2, na página de detalhes do painel, o usuário terá a opção de verificar o desempenho solar futuro. Haverá um botão que ao ser clicado uma acionará uma integração que vai receber os dados futuros que serão tratados no sistema, após isso, o usuário será redirecionado para uma página dentro do sistema que mostra os cálculos de desempenho futuro do painel cadastrado.
