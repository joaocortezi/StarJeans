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




















