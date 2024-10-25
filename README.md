# Análise de Restaurantes iFood (Fevereiro 2021)

## Visão Geral
Este projeto realiza uma análise exploratória de dados de restaurantes no iFood com base no dataset de **fevereiro de 2021**, utilizando técnicas de manipulação de dados, visualizações e métodos de verificação de hipóteses. O principal objetivo é entender os fatores que influenciam a demanda, popularidade e satisfação dos clientes. O projeto utiliza o método STAR para organizar as conclusões, explorando cada hipótese formulada sobre o dataset.

## 📁 Acesso ao Dataset
- Dataset utilizado: [Link para o arquivo CSV](https://www.kaggle.com/datasets/ricardotachinardi/ifood-restaurants-data/data?select=ifood-restaurants-february-2021.csv)
- Apresentação com hipóteses e conclusões: [Link para a apresentação PPT](#) _(Inserir link da apresentação aqui)_

![Apresentação Final Ifood](https://github.com/user-attachments/assets/3acca348-d5e7-4919-b8ca-2374c1996ab1)

## 🎯 Objetivos e Hipóteses Analisadas
O projeto foi desenvolvido com base nas seguintes hipóteses:

1. **Capitais têm mais pedidos que cidades não-capitais.**
2. **Categorias de restaurantes mais populares têm tempos de entrega mais rápidos.**
3. **Restaurantes mais caros e rápidos são mais bem avaliados, independentemente da categoria.**
4. **Restaurantes mais distantes compensam o tempo de entrega com um melhor serviço e avaliação.**
5. **Maior variedade de opções de pagamento leva a melhores avaliações dos clientes.**

## 🛠️ Ferramentas Utilizadas
- **Python**: Manipulação de dados, análise estatística e visualização.
- **Pandas**: Manipulação e análise de dados.
- **Matplotlib e Seaborn**: Visualização de dados.
- **Requests e BeautifulSoup**: Web scraping de dados adicionais do IBGE.

## Metodologia STAR

### 1. **Situação**
Para explorar padrões de consumo no iFood, foi utilizado um dataset com informações de pedidos realizados em restaurantes no Brasil durante fevereiro de 2021. As colunas foram traduzidas para português e dados externos sobre códigos de municípios foram coletados do site do IBGE. Foram feitas manipulações no dataset para remover dados duplicados e ausentes, garantindo a qualidade das análises.

### 2. **Tarefa**
Testar cinco hipóteses diferentes relacionadas a fatores que influenciam a popularidade, eficiência e qualidade de restaurantes. Cada hipótese foi verificada através de análises descritivas e comparativas, com a criação de gráficos e cálculos de médias para suportar ou refutar as suposições.

### 3. **Ação**
- **Importação de Dados**: Carregamento do dataset e limpeza de dados.
- **Web Scraping**: Extração de informações de códigos de municípios do site do IBGE.
- **Análises Exploratórias**: Visualizações e análises de correlação entre variáveis relevantes.
- **Teste de Hipóteses**: Utilização de agrupamentos, médias e gráficos para validar ou refutar cada hipótese.

### 4. **Resultado**
#### Hipótese 1: Capitais concentram mais pedidos.
- **Resultado**: Parcialmente verdadeira. Capitais como São Paulo e Rio de Janeiro estão entre as cidades com mais pedidos, mas grandes cidades não-capitais também têm demanda significativa.

#### Hipótese 2: Categorias populares têm tempos de entrega mais rápidos.
- **Resultado**: Refutada. As categorias populares não estão entre as que têm tempos de entrega mais rápidos, sugerindo que a logística de categorias muito demandadas é mais complexa.

#### Hipótese 3: Restaurantes caros e rápidos são mais bem avaliados.
- **Resultado**: Parcialmente refutada. Restaurantes caros têm avaliações melhores, mas o tempo de entrega não é um fator determinante.

#### Hipótese 4: Restaurantes distantes compensam com um melhor serviço.
- **Resultado**: Parcialmente verdadeira. Restaurantes mais caros conseguem compensar o tempo e a distância com uma melhor avaliação, mas isso não se aplica a restaurantes mais baratos.

#### Hipótese 5: Variedade de opções de pagamento influencia avaliações.
- **Resultado**: Parcialmente verdadeira. Oferecer mais opções de pagamento melhora as avaliações até certo ponto, mas adicionar muitas opções além do necessário não gera ganho significativo.

## 📊 Resultados e Visualizações
Gráficos e tabelas foram criados para ilustrar cada análise, incluindo a relação entre a distância do restaurante e a avaliação média, popularidade de categorias versus tempos de entrega, e a diversidade de opções de pagamento comparada com a satisfação dos clientes.

## 📌 Conclusões Finais
- **Demanda Geográfica**: Capitais e grandes cidades não-capitais são os principais polos de pedidos.
- **Popularidade vs. Eficiência**: Categorias mais populares não são necessariamente mais rápidas.
- **Preço e Qualidade**: O preço é um fator de maior impacto na percepção de qualidade do que a rapidez da entrega.
- **Logística Complexa**: Restaurantes distantes podem ser bem avaliados se oferecerem um serviço de alta qualidade.
- **Opções de Pagamento**: Diversificar as opções de pagamento é benéfico até certo limite.

## 🔧 Como Utilizar o Código
Para reproduzir as análises deste projeto:

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:
   ```bash
     pip install pandas matplotlib seaborn requests beautifulsoup4
   ```
3. Baixe o arquivo CSV no link fornecido e execute os notebooks.
    [Link para o arquivo CSV](https://www.kaggle.com/datasets/ricardotachinardi/ifood-restaurants-data/data?select=ifood-restaurants-february-2021.csv)
## 📚 Referências
- [Documentação do Pandas](https://pandas.pydata.org/pandas-docs/stable/)
- [Documentação do Matplotlib](https://matplotlib.org/stable/contents.html)
- [Documentação do Seaborn](https://seaborn.pydata.org/tutorial.html)
- [IBGE](https://www.ibge.gov.br/explica/codigos-dos-municipios.php)


