# 🏎️ Dashboard de Análise de Vendas - Porsche

## 📌 1. Sobre o projeto

Dashboard interativo desenvolvido em HTML com apoio de Inteligência Artificial, com o objetivo de transformar uma base de vendas da Porsche em informações visuais para análise de desempenho comercial.

O relatório apresenta indicadores de vendas, status das transações, modelos comercializados, receita por família de modelo e desempenho dos vendedores. Os valores financeiros são apresentados em dólares americanos (US$).

**Dashboard publicado:** [Acessar o relatório de vendas Porsche](https://alinealmeida-collab.github.io/IA-Report---Dashboard-Sales-da-Porshe/)

**Base utilizada:** `Base_Porsche_tratada.xlsx`

## 🎯 2. Perguntas de negócio

As perguntas foram definidas para permitir uma análise do comportamento das vendas por região, modelo e desempenho comercial.
A seleção dessas perguntas buscou combinar análise geográfica, desempenho comercial e preferência por modelos, apoiando a interpretação dos dados sob uma perspectiva executiva.

- **Quais são os principais modelos de carros vendidos por estado?**  
  Permite identificar a distribuição geográfica das vendas e os modelos com maior presença em cada estado.

- **Qual é o ranking dos cinco principais vendedores?**  
  Facilita a identificação dos vendedores com melhor desempenho, considerando os indicadores apresentados no relatório.

- **Quais modelos cada vendedor vendeu mais?**  
  Permite relacionar o desempenho individual ao portfólio de veículos comercializados, identificando os modelos de maior destaque por vendedor.


## 💬 3. Prompt utilizado e evolução até a versão final

O desenvolvimento ocorreu de forma iterativa. O prompt inicial definiu os filtros, as perguntas de negócio e a identidade visual; as versões seguintes refinaram os gráficos e a organização do dashboard.

### 3.1. Prompt inicial

 Utilizando a base de dados anexada, renderize em Canva um dashboard HTML.

 **Filtros:**
 - Modelo da Porsche;
 - Cidade;
 - Ano do modelo;
 - Forma de pagamento;
 - Vendedor.

 **Perguntas de negócio e KPIs:**
 - Quais modelos de carros são mais vendidos por cidade?
 - Qual é o ranking dos cinco principais vendedores e quais modelos cada vendedor vendeu mais?

 **UI/UX:** utilizar como referência a identidade visual do site da Porsche no Brasil, com uma apresentação requintada e elegante.

### 3.2. Refinamento visual e dos gráficos

Na segunda etapa, o prompt foi ajustado para aproximar o dashboard da identidade visual da Porsche Brasil e melhorar a leitura executiva dos indicadores.

Principais solicitações:

- Utilizar somente cores alinhadas à identidade visual da marca;
- Melhorar os gráficos para facilitar a análise executiva;
- Destacar em vermelho a barra que representa a informação principal no gráfico de modelos;
- Substituir a cor prata das barras por dourado;
- Incluir uma imagem de um Porsche no cabeçalho;
- Reorganizar os gráficos de cidades e modelos para evitar sobreposição e melhorar a leitura.

### 3.3. Ajustes finais

Na etapa final, as solicitações se concentraram na adequação da análise geográfica e na simplificação visual do relatório.

- Substituir cidades por estados nos filtros, gráficos e demais referências geográficas;
- Transformar a visualização de vendas por região em um mapa de calor, contemplando todos os estados com registros;
- Alterar o gráfico de status das vendas para pizza, exibindo somente a quantidade de vendas por status, sem percentuais;
- Remover subtítulos interpretativos específicos dos gráficos para reduzir informações redundantes e priorizar os dados visuais.

Essas iterações permitiram refinar o resultado a partir da avaliação visual do dashboard, com foco em consistência, legibilidade e objetividade.

## 🧹 4. Tratamento da base de dados

Antes de utilizar a base com a IA, realizei manualmente, sem auxílio de IA, o ajuste dos campos de data que apresentavam o valor `INVALID`.

Esse tratamento foi necessário para corrigir os dados de entrada antes da geração do relatório.

 **Arquivo utilizado:** `Base_Porsche_original.xlsx`

Conforme informado no dashboard publicado, a base contém **100 registros de vendas** e os nomes dos vendedores foram padronizados. As contagens incluem todas as vendas, inclusive aquelas com status cancelado. Portanto, os indicadores de volume devem ser interpretados considerando esse critério.

## 🛠️ 5. Ferramentas e abordagem de desenvolvimento

Durante o desenvolvimento, tentei utilizar o ChatGPT e o Claude com Canvas. Em ambos os casos, o retorno indicou que o formato solicitado era desconhecido.

Diante dessa limitação, utilizei o **Claude para gerar o dashboard a partir do prompt**, sem utilizar Canvas na etapa de geração final.

O processo envolveu definição das perguntas de negócio, preparação dos dados, elaboração do prompt, avaliação do resultado e refinamento iterativo das instruções.

## 🖥️ 6. Visualização do relatório

<img width="1141" height="531" alt="image" src="https://github.com/user-attachments/assets/91837029-6026-4582-8966-f501556deae8" />
<img width="1116" height="305" alt="image" src="https://github.com/user-attachments/assets/3bf39710-6046-4654-9cd7-cb95284e2a5f" />


🔗 **Acesse o dashboard publicado:** [Painel de Vendas Porsche](https://alinealmeida-collab.github.io/IA-Report---Dashboard-Sales-da-Porshe/)


## 📚 7. Considerações finais

O projeto demonstra a aplicação de Inteligência Artificial na geração de dashboards HTML a partir de uma base estruturada e de instruções em linguagem natural.

O principal aprendizado foi a importância de combinar perguntas de negócio bem definidas, preparação prévia dos dados e refinamento iterativo dos prompts. A avaliação crítica do resultado também foi essencial para melhorar a organização visual e aproximar a apresentação das necessidades de análise executiva.
