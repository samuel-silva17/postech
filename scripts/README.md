# Scripts e analises

## Índice

- [Introdução](#Introdução)
- [Dados_Abertos_Escolas e Dados_Abertos_Municipios](#dados_abertos_escolas-e-dados_abertos_municipios)
- [Seção](#Seção)
- [Clusterização_Embu_Guaçu](#clusterização_embu_guaçu)

## Introdução

Nessa pasta contém os arquivos com as analises usadas para prover arquivos brutos que são utilizados na visualização no Power BI.

## Dados_Abertos_Escolas e Dados_Abertos_Municipios

Essas analises estão divididas em algumas seções, e em cada uma delas é feita a leitura de algumas bases da Educação Brasileira, para que possamos gerar um arquivo consolidado ao final, que será utilizado na solução de BI.

## Seção

Censo Escolar = Leitura dos microdados do Censo escolar de 2023 filtrando o município de Embu-Guaçu, gerando assim o arquivo **censo_escolar** que se encontra na pasta de output.

Indicadores INEP = Essa seção contém as subseções com os indicadores e avaliações do INEP

    1. AFD (Adequação da Formação Docente): Formação dos docentes abrangendo de educação infantil a EJA (Ensino Jovens e Adultos)
    2. ATU (Média de alunos por turma): Media de alunos por turma.
    3. Horas Aula Diária
    4. INSE (Indicador de nível socioeconômico): O Inse do Saeb 2021 é formado pela combinação de dois elementos: a escolaridade dos pais e a posse de bens e serviços. Vai do nível I até o nível VII, sendo este o 'mais alto nível socioeconômico.
    5. IED (Índice de Esforço Docente): O esforço empreendido pelos docentes no exercício da profissão é uma característica que não se pode acessar e mensurar diretamente, no entanto esse estudo considera que esse construto se revela através de um conjunto de variáveis tomadas como definidoras do esforço do trabalho docente
    6. IRD (Índice de Regularidade Docente)
    7. TDI (Taxa de Distorção Idade-Série): Representa a proporção de matriculados entre seis e 18 anos de idade no ensino fundamental com idade superior em dois anos ao recomendado para cursar os nove anos do ensino fundamental.
    8. TXREND: Taxa de Rendimento escolar
    9. TDI (Taxa de Distorção Idade-Série): Representa a proporção de matriculados entre seis e 18 anos de idade no ensino fundamental com idade superior em dois anos ao recomendado para cursar os nove anos do ensino fundamental.

IDEB = O Índice de Desenvolvimento da Educação Básica é um indicador criado pelo governo federal para medir a qualidade do ensino nas escolas públicas

Base Consolidada = Base final que consolida as analise anteriores formando o arquivo **escolas** e o **inep** na pasta de output.


## Clusterização_Embu_Guaçu

Essa analise é reponsável por prover um pequeno modelo de Machine Learning para agrupar e escalonar os dados, para plotar as médias e a taxa de abandono e compor os indicadores que vão alimentar o BI e assim trazer a soluação para a Passos Mágicos, junto com as outras bases.

## History Changes

| 2024-04-03 | Entrega final do trabalho |