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

O Google Looker Studio é uma ferramenta de automação de Business Intelligence dentro da infraestrutura do Google Cloud. Daria até para dizer que é uma ferramenta de transformação de dados em relatórios e dashboards.  A própria empresa a define-o como “uma busca Google exclusiva para o seu negócio”. 

Na bibliografia recomandada, ele é apresentado como uma ferramenta de visualização de dados do Google que permite criar histórias de dados por meio de painéis interativos [...] que facilita a colaboração contínua [com] uma interface simples de arrastar e soltar que permite que usuários não técnicos e técnicos criem facilmente visuais e relatórios. Em outras palavras, "é o PowerBI do Google". 

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

## De cara com o Looker! E agora?

Ao iniciar a ferramenta você see depra com três opções: Relatórios, Fontes de dados e Exploradores. Eles são organizados nas guias correspondentes sob a barra de pesquisa. Você pode alternar entre esses modos de exibição facilmente. 

Por padrão, a home page exibe a guia Relatórios, que mostra a lista de relatórios que você acessou recentemente. A guia Relatórios também exibe um widget de galeria de modelos na parte superior para que você possa começar a criar um relatório facilmente usando um modelo ou começando a partir de um relatório em branco. 

O botão Criar no canto superior esquerdo permite criar um relatório, uma fonte de dados ou um explorador.

As quatro entidades principais no Looker Studio incluem um [conjunto de dados], um [conector], uma [fonte de dados] e um [relatório]. Eles estão ligados entre si, conforme mostrado, no diagrama a seguir:

    [Dataset] -> [Conector] -> [Data Source] -> [Report | Dashboard]

### Para gravar

- Conjunto de dados é a fonte de dados física na forma de arquivos, tabelas de banco de dados, visualizações do Google Analytics e muito mais que existe fora do Looker Studio. 

- Conector é a entidade que torna possível a conexão entre os dois. O conector funciona como o pipeline entre o conjunto de dados físico e a fonte de dados lógica. O Looker Studio oferece mais de 500 conectores para uma ampla variedade de armazenamentos de dados. 

- Fonte de dados é a construção lógica que se manifesta no Looker Studio com base no conjunto de dados subjacente. 

- Relatório é um recurso utilizado para criar um painel de tela única ou um relatório de várias páginas. Seus campos e métricas são usados para exibir informações. 


### Atenção
    Um único relatório pode usar várias fontes de dados. Da mesma forma, uma única fonte de dados pode ser usada para criar vários relatórios.


O recurso "Explorar" nos permite 'explorar' dados 'ad hoc'. WTF? Isso quer dizer que a partir dela [ferramenta] temos a capacidade de investigar, analisar e extrair insights de dados de forma flexível e improvisada, conforme necessário ou de acordo com os requisitos específicos de uma determinada situação ou problema.

"Ad hoc" [lê-se adoc e não ad roc] é uma expressão latina que significa "para isso" ou "para este fim". Quando aplicado à exploração de dados, "ad hoc" implica que a análise é realizada de maneira oportunista e não planejada, muitas vezes em resposta a uma necessidade imediata ou a uma pergunta específica que surge durante o processo de análise de dados.

## Criando uma fonte de dados
Uma fonte de dados no Looker Studio pode ser criada de duas maneiras: de dentro de um relatório ou diretamente da home page. Quando a fonte de dados é criada a partir da home page ele pode ser usado por vários relatórios e é denominado uma fonte de dados reutilizável e isso permite sua reutilização em outros relatórios.



## Gerenciando a atualização de dados
Quase sempre, as fontes de dados [...] mantêm uma conexão em tempo real com o conjunto de dados subjacente. Isso é muito benéfico nos casos em que o conjunto de dados é enorme ou está sendo atualizado com frequência. Ter uma conexão em tempo real garante que as atualizações de dados mais recentes sejam exibidas e relatórios sejam atualizados automaticamente. A única exceção em que os dados são importados para o Looker Studio é ao se conectar a arquivos CSV, cujo intervalo de atualização 'automática' é de 12h.

### Atenção
Parece haver um limite de tamanho de arquivo para upload: 100 MB por conjunto de dados. Além disso, um usuário individual só pode usar 2 GB de armazenamento no total em todas essas fontes de dados. [...] e se o seu conjunto de dados estiver dividido em vários arquivos CSV com a mesma estrutura – ou seja, os mesmos campos estão na mesma ordem – é possível importá-los juntos para formar uma única fonte de dados.








## Leituras recomandadas

* Leia o capítulo “Google Looker Studio Overview” do livro “Data Storytelling with Google Looker Studio”, de Nicholas Kelly, para iniciar sua jornada com uma visão geral do Google Looker.
Clique aqui para acessar o recurso



### Dicas
- Cada coluna do arquivo csv é uma dimensão

- Métricas são cálculos (agregações)


## Fontes de dados

### Arquivo CSV

Arquivos CSV, ou Comma-separated values, são arquivos de texto que armazenam dados em formato de tabela. Cada linha do arquivo representa uma linha da tabela, e cada coluna é separada por uma vírgula. CSV é um formato de arquivo de texto simples e fácil de entender, o que o torna uma opção popular para o armazenamento e o intercâmbio de dados. Eles são frequentemente usados para importar e exportar dados de aplicativos de planilhas, bancos de dados e outras ferramentas.

Aqui estão algumas vantagens de usar arquivos CSV:

- Simples de entender: Arquivos CSV são um formato de texto simples, o que os torna fáceis de entender e trabalhar.
- Versátil: Arquivos CSV podem ser usados para armazenar uma ampla variedade de dados, incluindo números, texto e datas.
- Compatível com vários aplicativos: Arquivos CSV são compatíveis com uma ampla variedade de aplicativos, incluindo planilhas, bancos de dados e ferramentas de análise de dados.

Se você precisar armazenar ou trocar dados em um formato de texto simples, arquivos CSV são uma ótima opção. Eles são fáceis de entender, versáteis e compatíveis com uma ampla variedade de aplicativos.



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











