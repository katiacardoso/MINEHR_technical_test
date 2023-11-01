# Teste Técnico - Engenharia de Dados - MINEHR
> Feito por Katia Lorena Cardoso Sena

- O código foi implementado seguindo a ordem descrição do case

- No arquivo [Teste_Tecnico_MINEHR.ipynb](https://github.com/katiacardoso/MINEHR_technical_test/blob/main/Teste_Tecnico_MINEHR.ipynb), é possível visualizar o código implementado e documentado

- A implementação foi realizada pelo Databricks, e para que isso seja possível foi necessário a criação/vinculação de uma conta AWS

- Para a primeira vez que o código é rodado, é necessário instalar via terminal essas bibliotecas :
  - pip install unidecode
  - pip install openpyxl

- O Dataframe final neste estado: 
  - Número de linhas: 47351
  - Número de colunas: 16
  - O que é possível concluir que houve a adição de 5 colunas (grupo_cargo, idade,tempo_empresa, ds_idade_cat e ds_tempo_empresa_cat)
 
  - Feedbacks pós conversa:
    - Importação por URL foi uma boa abordagem
    - Para o agrupamento, faça com o groupBy e depois agregre com o "agg" a coluna que deseja realizar a contagem. É algo realizado a fato e dimensão, conteúdo de banco de dados 
    - O arquivo em formato.parquet, se utilizar aquele comando write, possivelmente estará salvo no S3
  
 
  
 
    
