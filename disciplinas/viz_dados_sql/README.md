# Visualização de Dados e Introdução a SQL

Bem-vindo! Este repositório visa à apresentação de um material de apoio sobre Visualização de Dados e Introdução a SQL. Nossa ideia é explorar e aprofundar, se possível, alguns fundamentos da visualização de dados e forneceremos uma introdução básica à linguagem SQL.

## Visualização de Dados

### Breve explanação

#### O que é Visualização de Dados?

A visualização de dados é o processo de representar informações de forma visual, como gráficos, tabelas ou mapas, para facilitar a compreensão de padrões, tendências e insights nos dados.

#### Importância da Visualização de Dados

- Facilita a compreensão e interpretação dos dados.
- Permite identificar padrões, tendências e insights.
- Ajuda na tomada de decisões informadas e estratégicas.

#### Ferramentas de Visualização de Dados

Existem diversas ferramentas disponíveis para visualização de dados, como:
- Tableau
- Power BI
- Google Data Studio
- Matplotlib (para Python)
- ggplot2 (para R)
- Google Looker Studio (o Power BI do Google)

### Vamos ao que interessa

## Dados, informação e conhecimento. Qual a diferença?

No contexto de Tecnologia da Informação (TI), os termos "dados", "informações" e "conhecimento" têm significados distintos. Dados são os elementos básicos e brutos, as informações são dados processados e organizados para serem compreensíveis, e o conhecimento é uma compreensão mais profunda e contextualizada das informações, que pode ser aplicada para resolver problemas ou tomar decisões. É basicamente isso, mas se quer mais detalhes, dê uma olhadinha abaixo:

- Dados: são fatos brutos, sem contexto ou significado específico e tanto podem ser ser números, palavras, símbolos, quanto elementos que ainda não foram processados ou organizados de forma significativa. Por exemplo, uma lista de números ou palavras sem qualquer contexto é considerada dados.

- Informações: são dados que foram processados, organizados ou interpretados para adquirir significado ou contexto. As informações resultam da análise, interpretação ou estruturação deles e seu objetivo é torná-los úteis para um determinado propósito ou contexto. Por exemplo, se os números em uma lista forem organizados em uma tabela com colunas rotuladas, pode ser mais fácil entender o que os eles representam. Logo, aqueles dados se transformaram em informações.

- Conhecimento: é uma compreensão mais profunda e abrangente do contexto em que as informações estão inseridas. Podemos entender como uma compreensão construída a partir das informações, mas não limitadas a elas. Ele inclui insights, compreensão de relações entre diferentes conjuntos de informações e a capacidade de aplicar esse entendimento para resolver problemas ou tomar decisões. Por exemplo, se alguém utiliza as informações de uma tabela para identificar tendências ou padrões relevantes e, com base nisso, desenvolve uma estratégia para melhorar um processo ou tomar uma decisão de negócio, isso seria um bom exemplo de aplicação de conhecimento.

O "lance" desta disciplina de Visualização de Dados e Introdução a SQL é que o link entre tudo o que falamos e o mundo de T.I. são os Bancos de Dados. Eu sei que você já sabe que os bancos de dados fornecem uma estrutura para armazenamento, organização e recuperação de dados que impulsionam a inteligência e as decisões nos sistemas de informação e blá, blá, blá..., que são essenciais para gerenciar dados, transformá-los em informações significativas e fornecer a base para a aplicação de conhecimento no contexto de TI. É isso mesmo. Parece facinho, mas não é só isso. 

"Saca só!", os bancos de dados fornecem estruturas de acordo com modelos pré estabelecidos, específicos, como relacional, documental, de grafos, entre outros, o que torna a parada bem mais complexa. Mas não vamos complicar as coisas. Deixemos isso de lado, por enquanto. Nosso "lance" é com o modelo *relacional*. SQL, Sacou? Mas vamos por partes. Conheces o tal do Google Locker Studio, uma ferramenta gratuita para extrair e gerar informações através do Google Looker Studio?

## Google Loocker Studio. 

O Google Looker Studio é uma ferramenta de automação de Business Intelligence dentro da infraestrutura do Google Cloud. Daria até para dizer que é uma ferramenta de transformação de dados em relatórios e dashboards.  A própria empresa a define como “uma busca Google exclusiva para o seu negócio”. Em outras palavras, "é o PowerBI do Google". 

Para usar o Google Looker Studio, você precisa primeiro se conectar a uma fonte de dados. O Looker Studio suporta uma ampla variedade de fontes de dados, incluindo bancos de dados, planilhas, arquivos e APIs.

Depois de conectar-se a uma fonte de dados, você pode começar a criar relatórios e painéis. O Looker Studio fornece uma variedade de recursos de visualização de dados, incluindo gráficos, tabelas, mapas e muito mais. Você também pode usar o Looker Studio para criar análises avançadas, como modelos preditivos e análises de séries temporais.

Aqui estão alguns conceitos básicos que você precisa saber para usar o Google Looker Studio:

### Conceitos

- Dados: Os dados são a matéria-prima da análise de dados. O Looker Studio pode se conectar a uma ampla variedade de fontes de dados, incluindo bancos de dados, planilhas, arquivos e APIs.

- Visualizações: As visualizações são uma maneira de apresentar dados de forma clara e concisa. O Looker Studio fornece uma variedade de recursos de visualização de dados, incluindo gráficos, tabelas, mapas e muito mais.

- Análises: As análises são uma maneira de obter insights dos dados. O Looker Studio pode ser usado para criar análises avançadas, como modelos preditivos e análises de séries temporais.

Legal. Relatório eu sei o que é, mas o que é esse tal de Dashboard?

### Dashboard

Um dashboard é uma interface gráfica que exibe de forma visual (e consolidada) informações importantes e relevantes de um sistema, processo ou conjunto de dados. Essas informações são apresentadas de maneira simplificada e intuitiva, geralmente em formato de gráficos, tabelas, indicadores de desempenho e outros elementos visuais, facilitando a análise e a tomada de decisões.

De modo geral, dashboards são ferramentas poderosas para monitoramento, análise e comunicação de informações que permitem aos usuários compreenderemm rapidamente o estado ou o desempenho de um sistema e, assim, tomarem decisões informadas com base nos dados apresentados.

É por issi que os dashboards são amplamente utilizados em diversas áreas e contextos, incluindo negócios, finanças, marketing, monitoramento de sistemas, análise de dados, entre outros. Eles fornecem uma visão rápida e abrangente do estado atual ou do desempenho de um determinado aspecto, permitindo que os usuários identifiquem tendências, padrões ou áreas de interesse rapidamente.

#### Principais características:

* Visualização de Dados: Apresentação de dados de forma visual, utilizando gráficos, diagramas, mapas, etc., para facilitar a compreensão e a análise.

* Consolidação de Informações: Apresentação de informações de diferentes fontes ou aspectos em um único local, proporcionando uma visão integrada.

* Personalização: Capacidade de personalizar o conteúdo e a aparência do dashboard de acordo com as necessidades e preferências do usuário.

* Interatividade: Possibilidade de interação com os elementos do dashboard, como filtragem, zoom, detalhamento, etc., para explorar os dados em maior profundidade.

* Atualização em Tempo Real: Capacidade de atualizar automaticamente os dados exibidos no dashboard em tempo real ou em intervalos definidos.

## Introdução a SQL

### O que é SQL?

SQL (Structured Query Language) é uma linguagem de consulta estruturada utilizada para manipular e gerenciar bancos de dados relacionais.

### Principais Comandos SQL

- SELECT: Recupera dados de uma ou mais tabelas.
- INSERT: Insere novos registros em uma tabela.
- UPDATE: Atualiza registros existentes em uma tabela.
- DELETE: Remove registros de uma tabela.
- CREATE TABLE: Cria uma nova tabela.
- ALTER TABLE: Modifica a estrutura de uma tabela.
- DROP TABLE: Exclui uma tabela.

### Exemplo de Consulta SQL

```sql
SELECT nome, idade FROM clientes WHERE cidade = 'São Paulo';
```











