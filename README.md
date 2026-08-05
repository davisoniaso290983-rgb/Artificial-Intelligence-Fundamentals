a# 🚚 Otimização Inteligente de Rotas para a Sabor Express

> Projeto acadêmico desenvolvido para a disciplina **Fundamentos da Inteligência Artificial**.

📌 Status: 🚧 Em desenvolvimento

🎓 Curso:  Gestão da Tecnologia da Informação – UniFECAF

👩 Autora: Sonia Ávila de Oliveira

##  Descrição do Projeto

Este projeto foi desenvolvido como atividade da disciplina **Artificial Intelligence Fundamentals**.

O desafio consiste em criar uma solução baseada em Inteligência Artificial para otimizar as rotas de entrega da empresa fictícia **Sabor Express**, um serviço de delivery localizado na região central da cidade.

Atualmente, as rotas são definidas manualmente pelos entregadores, utilizando apenas sua experiência. Essa abordagem pode gerar atrasos, aumento no consumo de combustível, percursos ineficientes e redução da satisfação dos clientes.

A proposta deste projeto é aplicar algoritmos clássicos de Inteligência Artificial para representar a cidade como um grafo, calcular rotas mais eficientes e agrupar entregas próximas, contribuindo para uma operação mais rápida, econômica e organizada.

---

#  Objetivos

## Objetivo Geral

Desenvolver uma solução computacional utilizando algoritmos clássicos de Inteligência Artificial para otimizar as rotas de entrega da empresa Sabor Express.

## Objetivos Específicos

- Representar a cidade através de um grafo.
- Modelar bairros, ruas e pontos de entrega.
- Encontrar caminhos eficientes entre diferentes localidades.
- Comparar diferentes algoritmos de busca.
- Agrupar entregas próximas utilizando técnicas de aprendizado não supervisionado.
- Avaliar os resultados obtidos.

---

# Ferramentas e Tecnologias

- Python 3.13
- NetworkX
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Visual Studio Code
- Git
- GitHub

---

## 📂 Estrutura do Projeto


O projeto foi organizado em pastas para facilitar o desenvolvimento, manutenção e organização do código-fonte. Cada diretório possui uma responsabilidade específica dentro da solução.

## Estrutura do Projeto

- 📁 src
  - 📁 algorithms
  - 📁 models
  - 📁 utils
- 📁 data
- 📁 docs
- 📁 images
- 📁 notebooks
- 📁 tests
- 📄 README.md
- 📄 requirements.txt
- 📄 .gitignore
---

### 📁 src/

A pasta **src** (source) reúne todo o código-fonte do projeto. É nela que serão desenvolvidas as funcionalidades da aplicação, incluindo a implementação dos algoritmos de Inteligência Artificial, a modelagem do problema e as funções responsáveis pelo processamento dos dados.

---

### 📁 src/algorithms/

Nesta pasta serão implementados os algoritmos utilizados para resolver o problema proposto.

Os principais algoritmos previstos para este projeto são:

- **Breadth-First Search (BFS)** para busca em largura;
- **Depth-First Search (DFS)** para busca em profundidade;
- **A*** para encontrar o menor caminho utilizando heurísticas;
- **K-Means** para agrupar entregas em regiões próximas.

Cada algoritmo será desenvolvido em um arquivo separado, permitindo facilitar sua manutenção, reutilização e comparação de desempenho.

---

### 📁 src/models/

A pasta **models** será responsável pela representação computacional do cenário do problema.

Nela serão criadas as estruturas que representam a cidade utilizada na simulação, incluindo:

- bairros;
- pontos de entrega;
- ruas;
- conexões entre localidades (arestas);
- pesos das rotas, como distância ou tempo estimado.

Essas informações formarão o grafo que será utilizado pelos algoritmos de busca.

---

### 📁 src/utils/

A pasta **utils** armazenará funções auxiliares utilizadas durante todo o desenvolvimento do projeto.

Entre elas poderão estar funções para:

- leitura de arquivos;
- manipulação de dados;
- cálculos auxiliares;
- impressão dos resultados;
- geração de gráficos e relatórios.

O objetivo é evitar repetição de código e tornar a aplicação mais organizada.

---

### 📁 data/

A pasta **data** armazenará todos os conjuntos de dados utilizados pela aplicação.

Serão incluídos arquivos em formato CSV contendo informações como:

- bairros;
- pontos de entrega;
- coordenadas geográficas;
- conexões entre localidades;
- distâncias ou tempos estimados entre os pontos.

Esses dados servirão como base para a construção do grafo utilizado pelos algoritmos.

---

### 📁 docs/

A pasta **docs** será destinada à documentação complementar do projeto.

Nela poderão ser armazenados materiais como:

- diagramas;
- fluxogramas;
- documentação técnica;
- anotações de desenvolvimento;
- materiais de apoio utilizados durante o projeto.

Seu objetivo é centralizar toda a documentação relacionada à solução desenvolvida.

---

### 📁 images/

A pasta **images** armazenará todas as imagens utilizadas na documentação do projeto.

Entre elas poderão estar:

- diagramas do grafo;
- fluxogramas;
- gráficos comparativos;
- capturas de tela da execução do sistema;
- imagens utilizadas no README.

Essa organização facilita a manutenção da documentação visual do projeto.

---

### 📁 notebooks/

A pasta **notebooks** será utilizada para armazenar experimentos realizados com o Jupyter Notebook.

Esse ambiente poderá ser utilizado para:

- exploração dos dados;
- testes dos algoritmos;
- geração de gráficos;
- análises preliminares antes da implementação definitiva.

Embora não seja obrigatória para o funcionamento da aplicação, essa pasta facilita estudos e experimentações durante o desenvolvimento.

---

### 📁 tests/

A pasta **tests** conterá os testes desenvolvidos para validar o funcionamento da aplicação.

Os testes serão utilizados para verificar:

- o funcionamento dos algoritmos;
- a consistência dos resultados;
- possíveis falhas durante o desenvolvimento.

Essa prática contribui para aumentar a confiabilidade da solução.

---

### 📄 README.md

O arquivo **README.md** é o principal documento do projeto.

Ele reúne todas as informações necessárias para compreender a proposta da solução, incluindo:

- descrição do problema;
- objetivos;
- tecnologias utilizadas;
- estrutura do projeto;
- algoritmos implementados;
- instruções de execução;
- resultados obtidos;
- referências bibliográficas.

Esse documento funciona como o guia principal para qualquer pessoa que deseje conhecer ou executar o projeto.


### 📄 requirements.txt

O arquivo **requirements.txt** lista todas as bibliotecas Python necessárias para executar o projeto.

Por meio dele é possível instalar automaticamente todas as dependências utilizando o comando:

```bash
pip install -r requirements.txt
```

Esse procedimento garante que o ambiente de desenvolvimento possua todas as bibliotecas necessárias para o funcionamento da aplicação.

---
### 📄 .gitignore

O arquivo **.gitignore** define quais arquivos e diretórios não devem ser enviados ao repositório GitHub.

Entre eles normalmente estão:

- ambiente virtual (.venv);
- arquivos temporários;
- cache do Python;
- configurações locais do ambiente de desenvolvimento.

Essa prática mantém o repositório mais organizado e evita o envio de arquivos desnecessários.


#  Modelagem do Problema

A cidade será representada como um **grafo ponderado**, onde:

- Cada vértice representa um bairro ou ponto de entrega;
- Cada aresta representa uma rua;
- O peso da aresta representa a distância ou o tempo estimado entre dois pontos.

Essa representação permite aplicar algoritmos clássicos de busca para encontrar rotas mais eficientes.

---

#  Algoritmos Utilizados

Este projeto utilizará os seguintes algoritmos estudados na disciplina:

- Busca em Largura (BFS)
- Busca em Profundidade (DFS)
- Algoritmo A*
- K-Means

Cada algoritmo será implementado e avaliado individualmente durante o desenvolvimento do projeto.

---

#  Resultados

Esta seção será atualizada conforme a implementação dos algoritmos.

Serão apresentados:

- caminhos encontrados;
- tempo de execução;
- comparação entre algoritmos;
- gráficos;
- visualizações do grafo.

---

#  Limitações

As limitações identificadas durante o desenvolvimento serão documentadas nesta seção.

Entre elas poderão estar:

- simplificação da malha urbana;
- utilização de dados simulados;
- ausência de informações em tempo real sobre trânsito.

---

#  Melhorias Futuras

Como evolução deste projeto, podem ser implementadas:

- integração com APIs de mapas;
- utilização de dados reais de trânsito;
- otimização dinâmica das rotas;
- uso de aprendizado por reforço;
- interface gráfica para visualização das rotas.

---

#  Como Executar

1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/Artificial-Intelligence-Fundamentals.git
```

2. Instale as dependências

```bash
pip install -r requirements.txt
```

3. Execute o projeto

```bash
python src/main.py
```

---

#  Referências

- Material da disciplina Artificial Intelligence Fundamentals.
- Russell, S.; Norvig, P. *Artificial Intelligence: A Modern Approach*.
- Documentação oficial do NetworkX.
- Documentação oficial do Scikit-Learn.
