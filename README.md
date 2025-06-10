### Telecom X - Análise de Evasão de Clientes
Esse desafio tem objetivo de realizar a análise de dados na Telecom X e fará parte do projeto "Churn de Clientes". A empresa enfrenta um alto índice de cancelamentos e precisa entender os fatores que levam à perda de clientes.

Seu desafio será coletar, tratar e analisar os dados, utilizando Python e suas principais bibliotecas para extrair insights valiosos. A partir da sua análise, os demais colegas da  equipe de Data Science poderá avançar para modelos preditivos e desenvolver estratégias para reduzir a evasão.

### O que você será praticado:
✅ Importar e manipular dados de uma API de forma eficiente.
✅ Aplicar os conceitos de ETL (Extração, Transformação e Carga) na preparação dos dados.
✅ Criar visualizações de dados estratégicas para identificar padrões e tendências.
✅ Realizar uma Análise Exploratória de Dados (EDA) e gerar um relatório com insights relevantes.

Extração de dados de uma API em formato JSON.
Normalização das colunas e correção de tipos de dados.
Preenchimento e tratamento de valores nulos.
Criação de nova coluna  Daily_Charges.

🛠️ Tecnologias Utilizadas
Python 3.10+
Pandas
NumPy
Plotly.express
Matplotlib & Seaborn
Jupyter Notebook

# Informações levantadas:

Constatou-se que 26,5% dos clientes cancelaram os seus serviços com a operadora.

## Maior taxa de cancelamento:
### 1. Na modalidade de assinatura mensal;
### 2. Cliente com idade abaixo 65 anos;
### 3. Maior taxa de cancelamneto ocorre nos 3 primeiros meses de uso, sendo o primeiro mês com maior numeros de caoncelamento;
### 4. Não utilizavam os serviços digitais extras (Backups, suporte tecnico, Streaming de TV e videos, etc...).

# Relatório de Análise de Cancelamento de Clientes da Operadora
Este relatório detalha as principais informações levantadas a partir da análise da base de dados da operadora, com foco nos padrões e fatores que contribuem para o cancelamento de serviços pelos clientes.

### 1. Taxa Geral de Cancelamento
Foi constatado que 26,5% do total de clientes cancelaram seus serviços com a operadora. Esta é uma métrica crucial que indica uma parcela significativa da base de clientes que não permanece utilizando os serviços, o que pode impactar diretamente a receita e a sustentabilidade do negócio.
<img src="graficos\grafico_pizza.png" alt="Gráfico com a distribuição de clientes">

### 2. Modalidade de Assinatura com Maior Taxa de Cancelamento
A análise revelou que a modalidade de assinatura mensal apresenta a maior taxa de cancelamento. Este dado sugere que os clientes com contratos mais flexíveis, que não exigem um compromisso de longo prazo, são mais propensos a encerrar sua relação com a operadora. Isso pode indicar uma menor fidelização ou uma maior sensibilidade a fatores como preço e qualidade do serviço para esse grupo.

### 3. Período Crítico de Cancelamento
Observou-se que a maior taxa de cancelamento ocorre nos três primeiros meses de uso do serviço, sendo o primeiro mês o período com o maior número de cancelamentos. Este é um ponto de atenção crítico, pois indica que a experiência inicial do cliente é determinante para sua permanência. Possíveis causas para esse padrão incluem:

Expectativas não atendidas: O serviço pode não corresponder ao que foi prometido ou esperado pelo cliente.
Problemas na ativação ou instalação: Dificuldades iniciais podem levar à frustração e ao cancelamento precoce.
Falta de engajamento inicial: O cliente pode não se sentir valorizado ou não ser devidamente introduzido aos benefícios do serviço.
Ofertas de concorrentes: Clientes novos podem estar mais abertos a propostas de outras operadoras.

### 4. Impacto dos Serviços Digitais Extras
Um fator relevante identificado é que os clientes que cancelaram não utilizavam os serviços digitais extras oferecidos pela operadora, como Backups, suporte técnico, Streaming de TV e vídeos, entre outros. Isso sugere que:

Falta de valor percebido: Clientes que não utilizam esses adicionais podem não ver um valor agregado suficiente no serviço total, tornando-o mais suscetível ao cancelamento.
Desconhecimento dos benefícios: Pode haver uma falha na comunicação sobre a existência ou os benefícios desses serviços digitais.
Satisfação com serviços básicos: Se o cliente está satisfeito apenas com o serviço principal e não vê necessidade dos adicionais, a falta de engajamento com eles não seria um problema. No entanto, se o engajamento com esses serviços extras é um indicador de maior satisfação e fidelização, sua não utilização se torna um risco.

# Recomendações Preliminares:
Com base nessas informações, é recomendável que a operadora concentre esforços em:

Ações de retenção para novos clientes: Especialmente nos primeiros três meses, com foco no primeiro mês de uso.
Reavaliação da oferta para assinaturas mensais: Entender os motivos do cancelamento nesta modalidade e buscar estratégias para aumentar a fidelização.
Promoção e engajamento com serviços digitais extras: Garantir que os clientes conheçam e utilizem os benefícios adicionais, que podem ser um fator de retenção.
Esta análise fornece um ponto de partida para investigações mais aprofundadas e para o desenvolvimento de estratégias de retenção mais eficazes.

