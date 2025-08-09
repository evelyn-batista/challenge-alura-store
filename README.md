# Challenge Alura Store

## Objetivos
Nosso objetivo será ajudar o Sr. João a decidir qual loja da sua rede Alura Store vender para poder investir em um novo negocio. Serão avaliadas 4 lojas fictícias da Alura store e identificar aquela com menor eficiência.

## Métricas analisadas
- Faturamento total de cada loja.
- Categorias mais populares.
- Média de avaliação dos clientes.
- Produtos mais e menos vendidos.
- Custo médio do frete.

## Análise de dados

### Faturamento total
- Loja 1: R$ 1,534,509.12
- Loja 2: R$ 1,488,459.06
- Loja 3: R$ 1,464,025.03
- Loja 4: R$ 1,384,497.58
### Frete médio
- Loja 1: R$ 34,69
- Loja 2: R$ 33,62
- Loja 3: R$ 33,07
- Loja 4: R$ 31,28 

![Faturamento e frete médio por loja](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/faturamento-freteMedio-bar.png?raw=true)

Observamos que a loja 1 possui o maior faturamento e a loja 4 possui um faturamento muito menor em relação aos demais.

### Média de avaliação das lojas (máximo 5)
- Loja 1: 3,98
- Loja 2: 4,04
- Loja 3: 4,05
- Loja 4: 4,00
 
 As duas lojas com menor média de avaliação são a 1 e 4 com diferença de 0,02 pontos entre si mas uma diferença de no mínimo 0,04 pontos em relação aos demais.

### Produtos Mais e Menos Vendidos em Quantidade
#### Mais vendidos
- Loja 1:
    - Micro-ondas: R$ 46.348,89
    - TV Led UHD 4K: R$ 189.534,28
    - Guarda roupas: R$ 39.282,78
  
  Todos vendendo 60 unidades.
- Loja 2:
    - Iniciado em programação: R$ 4.169,96
  
  Com 65 unidades vendidas.
- Loja 3:
    - Kit banquetas: R$ 22.265,96
  
  Com 57 unidades vendidas.
- Loja 4: Cama box: R$ 43.928,57

  Com 62 unidades vendidas.

#### Menos vendidos
- Loja 1:
    - Headset: R$ 6307,71
    - Celular ABXY: R$ 43.534,47
  
  Ambos com 33 unidades vendidas.
- Loja 2:
    - Jogo de tabuleiro: R$ 7.748,58
      
  Com 32 unidades vendidas.
- Loja 3:
    - Blocos de montar: R$ 1.649,81
  
  Com 35 unidades vendidas.
- Loja 4:
    - Guitarra: R$ 34.430,67
  
  Com 33 unidades vendidas.

Através dessas informações, podemos ficar tentados a concluir que a loja 2 vende muito produtos com valores menores em relação as outras lojas, porém note que todas as lojas possui uma amplitude similar de unidades vendidas por produto, logo todos os produtos em cada loja vendem no mínimo 32 unidades e no máximo 65 unidades geralmente.

O gráfico a seguir nos ajuda a visualizar melhor a relevância de venda dos produtos, separado por categoria, em cada loja.
![Unidades vendidas por categoria](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/linhas-unidade-categoria.png?raw=true)

Nele, percebemos que todas as lojas possuem um desempenho similar,a loja 2 possui um rendimento abaixo da média nos eletrônicos, porém compensa em instrumentos musicais e livros, estando bem acima das outras lojas. Por outro lado a loja 4 possui um desempenho muito abaixo nos eletrodomésticos e está constantemente abaixo ou igual as outras lojas no restante.
## Gráficos complementares para análise

Tendo em vista o desempenho da loja 4 em unidades por categoria, vamos ver o quanto isso afeta o rendimento ao longo dos dias.

![Receita diária ao longo do tempo](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/dispersao-receita-diaria.png?raw=true)

Pelo gráfico de dispersão, observamos que a receita diária da loja 4 está bem limitada abaixo de 2000, começando a ter muitos buracos acima disso, aparentando ter um desempenho geral inferior as outras lojas. 

![Distribuição da receita em número de dias](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/hist-distribuicao-diaria.png?raw=true)

O histograma acima corrobora com a informação anterior, onde vemos que a loja 4 possui uma quantidade de dias muito maior de receita abaixo de 2000. 

As outras lojas, apesar de também ter uma alta concentração, possui uma quantidade menor de dias, além de sabermos pelo faturamento que essa receita deve ser compensada em dias especiais e comemorativos.

Por fim temos o gráfico de calor abaixo. Nele podemos observar que a loja 4 possui regiões com uma concentração menor que o restante das lojas, mostrando um desempenho abaixo dos demais em certas regiões. Apesar de ter uma pequena região onde as outras não possuem desempenho visível, as demais possuem uma área bem menor que as outras 3 lojas.

![Heatmap](https://github.com/NiveskZ/challenge-alura-store/blob/main/imgs/heatmap-regiao.png?raw=true)

## Conclusão
A análise consolidada dos dados evidencia que a Loja 4 apresenta o desempenho mais deficiente. Com um faturamento substancialmente menor que as demais unidades, sua venda é estrategicamente vantajosa. A decisão é reforçada pela ausência de categorias de produtos que se sobressaiam, pelo baixo desempenho regional e pela inconsistência na distribuição de sua receita, o que minimiza o impacto de sua saída da rede.
