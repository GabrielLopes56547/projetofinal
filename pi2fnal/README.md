O dashboard que estamos desenvolvendo é uma aplicação web que utiliza tecnologias como HTML, CSS e JavaScript, junto com as bibliotecas Chart.js e PapaParse. Vamos resumir algumas das características do dashboard específico que estamos criando:

Funcionalidade Principal: O dashboard tem o objetivo de exibir informações relacionadas a medidas específicas, utilizando gráficos interativos para representar visualmente os dados.

Tipos de Gráficos: Atualmente, o dashboard suporta três tipos principais de gráficos: barras, pizza (ou rosca) e linha. Cada um desses gráficos é dedicado à visualização de dados específicos.

Carregamento de Dados: O usuário pode carregar dados por meio de um arquivo CSV, utilizando um botão de seleção de arquivo. O código JavaScript faz uso da biblioteca PapaParse para analisar e processar os dados do arquivo CSV.

Seleção de Medidas: Um seletor (dropdown) permite ao usuário selecionar a medida específica que deseja visualizar, possibilitando a exploração de diferentes conjuntos de dados.

Exportação de Gráfico: Há um botão "Exportar Gráfico" que permite ao usuário baixar o gráfico atualmente exibido em formato de imagem (PNG).

Alternância de Gráficos: Foi adicionado um botão "Próximo Gráfico" para permitir ao usuário alternar entre os três tipos de gráficos disponíveis.


Estrutura do Projeto
index.html: O arquivo HTML principal que define a estrutura da página.
style.css: O arquivo de estilos que personaliza o visual da página.
script.js: O arquivo JavaScript que contém a lógica para a criação e atualização dos gráficos.
img.fundo.png: Imagem de fundo utilizada na página.