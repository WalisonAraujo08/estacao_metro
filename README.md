Estação Metrô

Integrantes:

Walison Araujo Santana — R.A.: 1696860<br>
Cauã Tomas da Paixão — R.A.: 1696689<br>
Bruno Ferrer — R.A.: 1696323<br>

Sobre o projeto<br>

O MetrôBot SP é um sistema desenvolvido em Python para auxiliar passageiros no planejamento de rotas pelo metrô de São Paulo. O projeto utiliza conceitos de Inteligência Artificial, grafos, algoritmos de busca e lógica para interpretar solicitações e encontrar caminhos entre estações e locais.

O sistema permite informar uma origem e um destino, além de considerar situações como estações fechadas, manutenção de elevadores e necessidades de acessibilidade. A partir dessas informações, o MetrôBot analisa o cenário, identifica uma rota possível e apresenta informações como as estações do caminho, quantidade de paradas, tempo estimado e eventuais alertas.

O projeto utiliza os algoritmos BFS (Busca em Largura) e DFS (Busca em Profundidade) para realizar a busca pelas estações. Também possui um mecanismo de inferência baseada em regras, utilizado para transformar informações fornecidas pelo usuário em fatos e decisões sobre a rota.

Além disso, o sistema possui uma interface interativa desenvolvida com ipywidgets, permitindo que o usuário informe sua solicitação e selecione opções como algoritmo de busca, estações fechadas e estações com elevadores em manutenção.

O projeto também conta com funcionalidades de interpretação de texto, permitindo que pedidos escritos de forma natural, como "Estou na Catedral da Sé e quero ir até a Pinacoteca", sejam transformados em informações utilizadas pelo sistema para calcular a rota.
