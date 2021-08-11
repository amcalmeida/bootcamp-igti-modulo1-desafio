# Bootcamp IGTI ~ 2021-3 Desenvolvedor React
### _Módulo 01 - Javascript Avançado I - Desafio_

### Objetivos
Exercitar os seguintes conceitos trabalhados no Módulo:
- Implementação de aplicação com JavaScript puro.
- Utilização de bibliotecas (Chart.js, Axios...).

### Enunciado

Construção de um Dashboard com elementos gráficos apresentando os números da Covid-19 a ser consumido de uma API, utilizando JavaScript puro e HTML.

### Atividades

Os alunos deverão desempenhar as seguintes atividades:
1. Implementar um JavaScript puro, HTML e CSS, uma aplicação para apresentação dos números da COVID-19 de um determinado país para um período de datas. A URL base para consumo da API com os dados da COVID é https://api.covid19api.com/. As respectivas rotas serão descritas nas atividades subsequentes.

2. A imagem abaixo ilustra um exemplo de implementação dessa aplicação, com um tipo de estilização obtido da internet (https://keen.io/). O estilo da página não necessariamente precisa ter o mesmo layout apresentado, mas é importante ter os mesmos componentes. O projeto base (HTML e CSS) será disponibilizado no fórum de avisos do professor, caso queiram utilizá-lo como referência.

A página apresentada na Figura 1 trata-se da **Home** de sua aplicação. Nela devem ser apresentados os números globais, até a data corrente, retornados pela API na rota “/summary”, sendo eles:
- **KPIs:** Total de Confirmados, Total de Mortes e Total Recuperados.
- **Pizza:** Novas Confirmados, Novas Mortes e Novos Recuperados
- **Barras:** Pareto com o Top 10 no número de mortes por país.

**_Figura 1 – Home page da aplicação._**
![/images/figura_01.png](/images/figura_01.png)
A página apresentada na Figura 2 trata-se das informações **diárias** por País, acessada pelo menu superior País. Os elementos apresentados na página são:

- **Filtros:** Data Início, Data Fim, País (combo retornado pela rota “/coutries”), Dados (Casos Confirmados, Número de Mortes e Casos Recuperados) e o um botão para aplicar os filtros selecionados.
- **Gráfico de Linhas:** Apresentação **diária** dos números do tipo de dados selecionados pelo filtro (Confirmados, Mortes ou Recuperados). Apresentar no gráfico a linha com o número médio correspondente aos números apresentados na curva diária.
- **KPIs:** Total de Confirmados, Total de Mortes e Total de Recuperados para o país selecionado.

**_Figura 2 – Apresentação dos números diários de um país._**
![/images/figura_02.png](/images/figura_02.png)
3. Nas informações por país, foi utilizada a rota “By Country All Status”. Mais detalhes e exemplos podem ser avaliados na documentação da API:
https://documenter.getpostman.com/view/10808728/SzS8rjbc.

#### Dicas e sugestões
- Utilize o projeto-base fornecido pelo professor como referência.
- A página inicial carregará as informações globais da rota “/summary”.
- Na página das informações diárias por país, utilizei o Brasil como país default.
- Utilizem a biblioteca Axios para consumo da API e os conceitos apresentados nas videoaulas para implementação do trabalho.
- Utilizem a biblioteca Chart.js para apresentação dos gráficos nas páginas.
- Utilizem a biblioteca Lodash para manipulação dos dados.
- Utilizem a importação das libs via CDN, uma vez que a implementação utiliza
JavaScript puro. Exemplo para a Chart.js.: 
```sh
<script
    src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.2.0/chart.min.js">
</script>
```
- Os números diários não são fornecidos já calculados pela API. Será necessário realizar um cálculo com as informações que a API disponibiliza.
- No questionário serão feitas perguntas sobre o JavaScript e sobre o projeto
implementado.
- Caso alguma questão esteja incorreta, solicitarei ao IGTI que anule a mesma. Esse processo não é “instantâneo” e leva algum tempo para acontecer –
geralmente ao final do módulo.] Quando acontecer, [todos os alunos ganharão a pontuação da questão anulada.]
- Demonstrarei minha implementação na Segunda Aula Interativa

### Respostas Finais
Os alunos deverão desenvolver a prática e, depois, responder às seguintes questões objetivas:
