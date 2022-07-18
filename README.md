# A empresa Star Jeans!

## PROBLEMA DO NEGÓCIO:
    Eduardo e Marcelo são dois brasileiros, amigos e sócios de empreendimento. Depois de vários negócio bem sucedidos, eles estão planejando entrar no mercado de moda dos USA como um modelo de negócio do tipo E-commerce.
    
    A idéia inicial é entrar no mercado com apenas um produto e para um público específico, no caso o produto seria calças Jenas para o público masculino. O objetivo é manter o custo de operação baixo e escalar a medida que forem conseguindo clientes.
    
    Porém, mesmo com o produto de entrada e a audiência definidos, os dois sócios não tem experiência nesse mercado de moda e portanto não sabem definir coisas básicas como preço, o tipo de calça e o material para a fabricação de cada peça.
    
    Assim, os dois sócios contrataram uma consultoria de Ciência de Dados para responder as seguintes perguntas: 
        1. Qual o melhor preço de venda para as calças? 
        2. Quantos tipos de calças e suas cores para o produto inicial? 
        3. Quais as matérias-prima necessárias para confeccionar as calças?

    As principais concorrentes da empresa Start Jeans são as americadas H&M e Macys.

## Etapas do Pensamento analítico:
    1. Identificação da causa raíz;
    2. Definir um escopo fechado para uma pergunta aberta;
    3. Quebrar o problema definido em tarefas menores;
    4. Organizar as tarefas por ordem lógica;
    5. Executar com uma mentalidade cíclica.

## Questão de negócio: Qual o melhor preço de venda do produto?
    1. Identificação da causa raiz:
        - Motivação: Qual o contexto?
            - A empresa está entrtando no mercado de varejo de moda dos USA e não tem expertise para precificar o produto;
            - Definir o preço do produdo para maximizar o lucro.
         - Qual é a causa raíz do problema?
            - Precificação do produto;
            - Preço ótimo para maximizar o lucro:
    2. Definir um escopo fechado para uma pergunta aberta.
            - Pergunta aberta: Qual o melhor preço de venda do produto?
            - Escopo fechado: Produto | Tempo | Localidade | Atributos do Produto. 
                - Mediana dos preços dos sites concorrentes por produto, tipo e cor dos últimos 30 dias. 
    3. Quebrar o problema definido em tarefas menores:
        - Mediana dos preços dos sites concorrentes por produto, tipo e cor dos últimos 30 dias.

        Tarefas:
            - Calcular a mediana de preços dos sites concorrentes por produto, tipo e cor dos últimos 30 dias;
            - Montar uma base de dados que contenha informações do produto, preço, tipo, cor, dias de exposição;
            - Definir o Schema (colunas da tabale);
            - Definir a infraestrutura (banco de dados, csv, API);
            - Desegin do ETL;
            - Agendamento da atualização da tabela;
            - Entrega do produto final.

    4. Organizar as tarefas por ordem lógica:
        1. Montar uma base de dados que contenha informações do produto, preço, tipo, cor, dias de exposição;
        2. Definir o Schema;
        3. Definir a infraestrutura;
        4. Fazer o ETL;
        5. Calcular a mediana de preços dos sites concorrentes por produto, tipo e cor dos últimos 30 dias;
        6. Fazer a visualização do produto final (tabela, gráfico);
        7. Entregar o produto final.
    
    5. Executar com uma mentalidade cíclica.
        1. Preciso passar por todas tarefas o mais rápido possível para:
            1. Identificar bloqueios;
            2. Identificar impeditivos que possam desvalidar o projeto;
            3. Entregar o valor para empresa rapidamente. 
        2. Fazer escolhas simples (keep it simple)

## Etapas de um projeto de dados:
    1. Questão do negócio;
    2. Entendimento do negócio;
    3. Coleta de dados;
    4. Limpeza de dados;
    5. Exploração de dados;
    6. Modelagem de dados;
    7. Aplicação dos algorítmos de Machine Learning;
    8. Avaliação de performance dos algorítmos;
    9. Publicação do modelo em Produção.  

## Método CRISP-DS de desenvolvimento:
![CRISP](https://user-images.githubusercontent.com/84943660/176204325-9ce23c8c-ef2d-4c79-b4ee-e79c634ec0d3.png)

## Método SAPE (saída, processo e entrada):
    Problema do negócio:
        - Qual é o melhor preço de venda para calças.
        - Quantos tipos de calças e suas cores para o produto inicial? 
        - Quais as matérias-prima necessárias para confeccionar as calças?
    Saída (produto final):
        1. A resposta para a pergunta;
            - Mediana dos preços dos concorrentes.
        2. Formato da entrega;
            - Tabela ou gráfico.
        3. Local da entrega.
            - App Streamlit
    Processo (passa a passo):
        1. Passo a passo para construir o cálculo de mediana ou média;
            - Realizar o cálculo da mediana sobre o produto, tip e cor. 
        2. Definir o formato da entrefa (vizualização, tablea, frase);
            - Gráfico de barras com a mediana dos preços dos produtos por tipo e cor nos últimos 30 dias;
            - Tabela com as seguintes colunas: id | product_name | product_type | product_color | product_price;
            - Definição do schema: Colunas e seu tipo;
            - Definição da infraestrutura de armazenamento (SQLITE3);
            - Design do ETL (Scrips de extração, transformação e carga);
            - Planejamento de agendamento dos scripts (dependências entre os scripts);
            - Fazer as visualizações;
            - Entregar o produto final 
        3. Decidir o local da entrega (tableau, telegram, email, streamlit, intranet).
            - App com streamlit.
    Entrada (fonte de dados):
        1. Fonte de dados; 
            - Site H&M: https://www2.hm.com/en_us/men/products/jeans.html
            - Site Macys: https://www.macys.com/shop/mens-clothing/mens-jeans
        2. Ferramentas 
            - Python 3.9.12;
            - Bibliotecas de Webscrapping (BS4, Selenium); https://www.crummy.com/software/BeautifulSoup/bs4/doc/
            - VSCODE;
            - Airflow, Crontjob;
            - Streamlit.


- https://developers.whatismybrowser.com (user agent)













