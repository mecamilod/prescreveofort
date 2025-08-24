Consulta de Procedimentos de OPMEs Este projeto é uma aplicação web de página única (single-page) projetada para facilitar a consulta, filtragem e ordenação de procedimentos de OPMEs (Órteses, Próteses e Materiais Especiais) do Sistema Único de Saúde (SUS), conforme a tabela SIGTAP. A interface foi criada para ser intuitiva, permitindo que o usuário encontre informações de forma rápida e eficiente, seja por meio da pesquisa geral, filtros específicos por coluna ou ordenação dos dados. 💻 Tecnologias

HTML5: Estrutura da página.

CSS3: Estilização, com o auxílio do Tailwind CSS (via CDN) para agilizar o layout.

JavaScript: Responsável por toda a interatividade, incluindo carregamento de dados, pesquisa, filtros, ordenação e paginação. ✨ Funcionalidades

Pesquisa Geral: Uma barra de pesquisa unificada para encontrar termos em qualquer coluna relevante (Categoria, Procedimento e CIDs).

Filtros por Coluna: Caixas de texto dedicadas a filtrar os dados em colunas específicas.

Ordenação de Dados: Clique nos cabeçalhos da tabela para ordenar os dados em ordem crescente ou decrescente.

Paginação: Controle de navegação para visualizar grandes conjuntos de dados de forma paginada.

Responsividade: O layout se adapta a diferentes tamanhos de tela, garantindo uma boa experiência tanto em desktops quanto em dispositivos móveis.

Carregamento de Dados Dinâmico: Os dados são carregados de um arquivo dados.json externo, facilitando a atualização do conteúdo sem a necessidade de modificar o código HTML. 📁 Estrutura de Arquivos Para que o projeto funcione corretamente, a seguinte estrutura de arquivos é necessária: / ├── index.html ├── dados.json └── logoofort.png

index.html: O arquivo principal contendo o código-fonte da aplicação.

dados.json: O arquivo JSON que armazena a lista de procedimentos.

logoofort.png: A imagem de logo utilizada no cabeçalho. O arquivo dados.json deve ser um array de objetos, onde cada objeto representa um procedimento e suas respectivas propriedades, como no exemplo abaixo: [ { "CATEGORIA": "Órteses", "PROCEDIMENTO": "Procedimento de exemplo 1", "IDADE MÍNIMA": "0", "IDADE MÁXIMA": "99", "QUANTIDADE MÁXIMA": "1", "CIDS": "C00-C97" }, { "CATEGORIA": "Próteses", "PROCEDIMENTO": "Procedimento de exemplo 2", "IDADE MÍNIMA": "18", "IDADE MÁXIMA": "60", "QUANTIDADE MÁXIMA": "2", "CIDS": "Z00-Z99" } ]

👨‍💻 Créditos

Desenvolvido por: Maria Eduarda Camilo Damião
Atualização: Agosto de 2025
