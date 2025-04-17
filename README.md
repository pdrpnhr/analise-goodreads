# Sobre essa análise

Como exercício de análise de dados, exportei meus dados do aplicativo Goodreads e estou analisando meus padrões de leitura, a fim de responder uma pergunta-chave: **nos anos que li mais, que fatores contribuíram para isso?**. Para responder isso, levantei as seguintes perguntas iniciais:

## Perguntas iniciais:

1) Em que ano li mais, considerando o total de livros lidos?
2) Em que ano li mais, considerando o total de _páginas_ lidas?
3) Quais foram os anos em que li mais e menos, considerando esses dois critérios acima?
4) Nos anos em que li mais, quais foram os gêneros principais?
5) Nos anos que li menos, quais foram os gêneros principais?

## Follow-up questions:

À medida que realizo a análise, algumas novas perguntas aparecem. Vou adicionado-as a essa sessão à medida que surgem:

1) Qual foi o meu padrão de leitura em 2015 (gênero e tamanho médio de livro) que resultou num tamanho médio por livro muito menor?
2) Como o ritmo de leitura se distribui ao longo dos meses em cada ano? 

## Próximas investigações:

Além de perguntas de follow-up (que podem me ajudar a responder à pergunta-chave), também estão surgindo novas investigações interessantes:

1) Quão diferente é o meu gosto do gosto geral, considerando as colunas "My Rating" e "Average Rating"? Isso muda por gênero?
2) Quais são minhas editoras preferidas, considerando média de Rating e total de livros lidos?
3) Quanto tempo em média demoro entre acrescentar um livro à minha lista e de fato lê-lo?

# Linguagens e bibliotecas utilizadas:

- Linguagem: Python
- Bibliotecas:
    - Pandas
    - Matplotlib
    - Seaborn

# Limitações da análise:

- Os dados anteriores a 2013 são menos confiáveis, pois criei a conta nesse ano. Assim, todos os livros cuja data de leitura ('Date Read') são anteriores a 2013 foram adicionados retroativamente, dependendo da minha memória.
- Releituras não são contabilizadas; o arquivo inclui apenas a primeira data de leitura do livro.

# Principais achados:

- O período em que mais li foi quando estava estudando, seja na graduação (2011 a 2015), seja no mestrado (2016 a 2017).
- Depois disso, houve um pico de leituras em livros/ano em 2022, ano em que tive um acidente que reduziu minha mobilidade. Isso pode ter me incentivado a ler mais.
- Em 2015, ano que o número de páginas lidas caiu, apesar de o total de livros não, li muitos livros de poesia e quadrinhos (vale a pena tentar sinalizar quais livros são quadrinhos?)