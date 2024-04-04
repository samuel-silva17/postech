# Datathon Passos Mágicos - Pós Tech Fase 5

## Índice

- [Introdução](#Introdução)
- [Solução Para a Passos Mágicos](#solução-para-a-passos-mágicos)
- [Abas Painel (Power BI)b](#abas-painel-power-bi)

## Introdução

Esse projeto da Pós Tech Fiap e Alura, consistia em entregar uma solução de negócio para a Ong **Passos Mágicos** de Embu-Guaçu, aonde fomos desafiados com dados reais fornecidos pela própria Ong.

## Solução Para a Passos Mágicos

Desenvolvemos um painel BI para que que a Passos Mágicos possa acompanhar o diagnóstico dos indicadores educacionais das escolas do município de Embu-Guacu em cada etapa de ensino. Através dele, é possível fazer uma comparação de Embu com os outros municípios de SP (exceto a capital) e principalmente,  fazer uma comparação entre as escolas de Embu-Guaçu, possibilitando identificar aquelas que estejam enfrentando maiores dificuldades na taxa de aprendizagem e até no abandono escolar e consequentemente, alunos cujo processo de aprendizagem esteja mais comprometido devido a essas deficiências. 

Para facilitar o mapeamento dessas escolas, também criamos um modelo de clusterizacao (kmeans) para identificar grupos de escolas em situações mais frágeis. 

Considerando que o número de vagas da Passos não é o suficiente para atender toda a demanda e o objetivo da ONG é focar nos estudantes mais vulneráveis, sugerimos que eles priorizem os estudantes dessas escolas com piores indicadores de qualidade de ensino e acompanhem a evolução dos mesmos em relação àsdemais escolas. Dessa forma, será possível medir o impacto que a Passos teve não só em seus alunos, mas no ambiente em que eles estão inseridos.

![Capa Power BI](https://drive.google.com/file/d/1_Q5WLhh2N8_Ntrh31Z9tPdJiieNCoIww/view?usp=drive_link)

Foi desenvolvida uma solução para apresentar indicadores sobre o Ponto de Virada que é um indicador metrificado pela Passos, para que assim possa acompanhar o desenpenho médio anual das notas desse indicador importante, que sinaliza que o aluno acredita que o ensino pode mudar a vida dele.

## Abas Painel (Power BI)

Menu = Contém o menu de navegação do Painel.

Divisão por estapa de ensino nas abas = Anos Iniciais, Anos Finais e Ensino Médio

Clusterização = Utilizado modelo de Machine Learning (kmeans) para prever o acompanhamento de alunos que estão saindo das escolas, gerando assim novas estrategias para a Passos atuar com esses alunos em futuro.

Dados Completos = Tabela com todos das escolas de Embu-Guaçu para acompanhamento.

Ponto de Virada = Indicador para a Passos Mágicos medir o quanto o aluno acredita que o ensino pode mudar e transformar a sua vida, motivando assim o aluno e a Passos como indicador que o ensino esta funcionando.






