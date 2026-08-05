🚚 Otimização Inteligente de Rotas para a Sabor Express

Projeto acadêmico desenvolvido para a disciplina Fundamentos da Inteligência Artificial.

📌 Status: 🚧 Em desenvolvimento

🎓 Curso: Gestão da Tecnologia da Informação – UniFECAF

👩 Autora: Sonia Ávila de Oliveira

---
## Descrição do Projeto

Este projeto foi desenvolvido como atividade da disciplina Fundamentos da Inteligência Artificial.

O desafio consiste em desenvolver uma solução baseada em Inteligência Artificial para otimizar as rotas de entrega da empresa fictícia Sabor Express, um serviço de delivery localizado na região central da cidade.

Atualmente, as rotas são definidas manualmente pelos entregadores, utilizando apenas sua experiência. Essa abordagem pode gerar atrasos, aumento no consumo de combustível, percursos ineficientes e redução da satisfação dos clientes.

A proposta deste projeto é aplicar algoritmos clássicos de Inteligência Artificial para representar a cidade como um grafo, calcular rotas mais eficientes e agrupar entregas próximas, contribuindo para uma operação mais rápida, econômica e organizada.

---
## Objetivos
### Objetivo Geral

Desenvolver uma solução computacional utilizando algoritmos clássicos de Inteligência Artificial para otimizar as rotas de entrega da empresa Sabor Express.

## Objetivos Específicos
Representar a cidade por meio de um grafo.
Modelar bairros, ruas e pontos de entrega.
Encontrar caminhos eficientes entre diferentes localidades.
Comparar algoritmos clássicos de busca.
Agrupar entregas utilizando técnicas de aprendizado não supervisionado.
Avaliar os resultados obtidos.

---
## Ferramentas e Tecnologias
Python 3.13
NetworkX
NumPy
Pandas
Matplotlib
Scikit-Learn
Visual Studio Code
Git
GitHub

---

Estrutura do Projeto

O projeto foi organizado em diretórios para facilitar o desenvolvimento, manutenção e organização do código-fonte.

📁 src
📁 algorithms
📁 models
📁 utils
📁 data
📁 docs
📁 images
📁 notebooks
📁 tests
📄 README.md
📄 requirements.txt
📄 .gitignore
Explicação das Pastas
📁 src/

A pasta src (source) reúne todo o código-fonte do projeto. Nela serão desenvolvidas as funcionalidades da aplicação, incluindo a implementação dos algoritmos de Inteligência Artificial, a modelagem do problema e as funções responsáveis pelo processamento dos dados.

📁 src/algorithms/

Nesta pasta serão implementados os algoritmos responsáveis pela resolução do problema proposto.

Entre os algoritmos previstos para este projeto estão:

Breadth-First Search (BFS);
Depth-First Search (DFS);
A*;
K-Means.

Cada algoritmo será desenvolvido em um módulo independente, facilitando sua manutenção, reutilização e comparação de desempenho.

📁 src/models/

A pasta models armazenará a representação computacional do cenário utilizado na aplicação.

Serão implementadas as estruturas responsáveis por representar:

bairros;
ruas;
pontos de entrega;
conexões entre localidades;
pesos das arestas (distância ou tempo).

Essas estruturas formarão o grafo utilizado pelos algoritmos.

📁 src/utils/

A pasta utils armazenará funções auxiliares utilizadas em diferentes partes da aplicação.

Entre elas poderão estar funções para:

leitura de arquivos;
manipulação de dados;
cálculos auxiliares;
geração de gráficos;
impressão dos resultados.

O objetivo é evitar repetição de código e aumentar a organização do projeto.

📁 data/

A pasta data armazenará todos os arquivos de dados utilizados pela aplicação.

Serão incluídos arquivos CSV contendo informações como:

bairros;
ruas;
pontos de entrega;
conexões entre localidades;
distâncias entre os pontos.

Esses dados servirão de base para construção do grafo.

📁 docs/

A pasta docs armazenará a documentação complementar do projeto.

Entre os documentos previstos estão:

diagramas;
fluxogramas;
documentação técnica;
anotações do desenvolvimento.
📁 images/

A pasta images armazenará todas as imagens utilizadas na documentação.

Entre elas:

diagramas;
gráficos;
fluxogramas;
capturas de tela;
imagens utilizadas no README.
📁 notebooks/

A pasta notebooks será utilizada para armazenar experimentos realizados com o Jupyter Notebook.

Ela poderá conter análises exploratórias, testes dos algoritmos e experimentações antes da implementação definitiva.

📁 tests/

A pasta tests conterá os testes desenvolvidos para validar a aplicação.

Os testes serão utilizados para verificar:

funcionamento dos algoritmos;
consistência dos resultados;
possíveis falhas durante o desenvolvimento.
📄 README.md

O arquivo README.md é o principal documento do projeto.

Ele apresenta:

descrição do problema;
objetivos;
tecnologias utilizadas;
estrutura do projeto;
algoritmos implementados;
instruções de execução;
resultados obtidos;
referências bibliográficas.
📄 requirements.txt

O arquivo requirements.txt lista todas as bibliotecas Python necessárias para executar o projeto.

As dependências podem ser instaladas por meio do comando:

pip install -r requirements.txt
📄 .gitignore

O arquivo .gitignore define quais arquivos e diretórios não devem ser enviados ao repositório Git.

Entre eles:

ambiente virtual (.venv);
arquivos temporários;
cache do Python;
configurações locais do ambiente.

Essa prática mantém o repositório organizado e evita o envio de arquivos desnecessários.

---
## Modelagem do Problema

O cenário será representado por um grafo ponderado, no qual:

cada vértice representa um bairro ou ponto de entrega;
cada aresta representa uma rua;
o peso da aresta representa a distância ou o tempo estimado entre dois pontos.

Essa representação permite aplicar algoritmos clássicos de busca para determinar rotas mais eficientes.

---
## Algoritmos Utilizados

Este projeto utilizará algoritmos clássicos estudados na disciplina.

## Algoritmo                              	Objetivo
Breadth-First Search (BFS) : Encontrar caminhos utilizando busca em largura.
Depth-First Search (DFS)	 : Explorar caminhos utilizando busca em profundidade.
A*	                       : Encontrar o menor caminho utilizando heurísticas.
K-Means	                   : Agrupar pontos de entrega em regiões próximas.

---
## Fluxo da Solução

Mapa da Cidade
       │
       ▼
Construção do Grafo
       │
       ▼
Aplicação dos Algoritmos
(BFS • DFS • A*)
       │
       ▼
Agrupamento com K-Means
       │
       ▼
Resultados e Análises

---
## Como Executar

1- Clone o repositório. 
git clone https://github.com/SEU-USUARIO/Artificial-Intelligence-Fundamentals.git

2- Instale as dependências.
pip install -r requirements.txt

3- Execute o projeto.
python src/main.py

---
## Resultados

Esta seção será atualizada conforme o desenvolvimento do projeto.

Serão apresentados:

caminhos encontrados;
comparação entre algoritmos;
tempo de execução;
gráficos;
visualizações do grafo.

---

## Limitações

As limitações identificadas durante o desenvolvimento serão documentadas nesta seção.

Entre elas poderão estar:

simplificação da malha urbana;
utilização de dados simulados;
ausência de informações de trânsito em tempo real.

---

## Melhorias Futuras

Como evolução do projeto, poderão ser implementadas:

integração com APIs de mapas;
utilização de dados reais de trânsito;
otimização dinâmica das rotas;
comparação entre diferentes heurísticas do algoritmo A*;
utilização de aprendizado por reforço;
desenvolvimento de uma interface gráfica para visualização das rotas.

---
## Referências
Material da disciplina Fundamentos da Inteligência Artificial – UniFECAF.
Russell, S.; Norvig, P. Artificial Intelligence: A Modern Approach.
Documentação oficial do Python.
Documentação oficial do NetworkX.
Documentação oficial do Scikit-Learn.
