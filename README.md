#  Fundamentos da Inteligência Artificial

>  **Status do Projeto:** Em desenvolvimento

Projeto desenvolvido para a disciplina **Fundamentos da Inteligência Artificial**

**Curso:** Gestão da Tecnologia da Informação – UniFECAF

**Autora:** Sonia Avila

## Projeto: Otimização Inteligente de Rotas para a Sabor Express

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

#  Tecnologias Utilizadas

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

# 📂 Estrutura do Projeto

```
Artificial-Intelligence-Fundamentals/

├── data/
│   ├── bairros.csv
│   ├── ruas.csv
│   └── pedidos.csv
│
├── docs/
│
├── images/
│
├── notebooks/
│
├── src/
│   ├── algorithms/
│   ├── models/
│   ├── utils/
│   └── main.py
│
├── tests/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

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
