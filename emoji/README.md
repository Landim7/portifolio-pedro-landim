# Renderizador e Processador de Emoji (Matriz RGB) 🎨

Este projeto é um script Python que demonstra como manipular imagens digitais em baixo nível, tratando-as como matrizes de pixels (grades) e aplicando transformações de cor diretamente nos canais RGB.

## 📋 Descrição do Projeto

O script define um "Emoji" através de um dicionário contendo uma grade $5 \times 5$ de pixels. Cada pixel é representado por uma tupla RGB (Red, Green, Blue). O programa processa essa matriz para alterar a tonalidade das cores e renderiza o resultado visualmente.

## 🚀 Funcionalidades

* [cite_start]**Definição de Matriz de Imagem**: Utiliza uma estrutura de dados para mapear um rosto sorridente (Smile) usando coordenadas de cores.
* **Processamento de Imagem (Filtro de Brilho)**: 
    * [cite_start]O algoritmo percorre cada pixel da grade.
    * [cite_start]Identifica pixels amarelos $(255, 255, 0)$.
    * [cite_start]Aplica uma redução de 50% na intensidade de cada canal de cor ($valor / 2$), escurecendo o tom do emoji.
* [cite_start]**Visualização Gráfica**: Utiliza a biblioteca `matplotlib` para converter a matriz numérica em uma imagem visual real, removendo os eixos para uma exibição limpa.

## 🛠️ Tecnologias Utilizadas

* [cite_start]**Python 3**: Linguagem base.
* [cite_start]**Matplotlib**: Biblioteca utilizada para a renderização da grade de cores como imagem.
* [cite_start]**Manipulação de Matrizes**: Uso de listas aninhadas para representar dimensões espaciais ($x, y$).

## 💻 Resultado Esperado

O script processa o emoji original e exibe no console a nova matriz de cores escurecidas, seguida pela geração de uma imagem 2D:

```text
Emoji: Smile
[(127, 127, 0), (127, 127, 0), ... ]
...
[Visualização da imagem gerada pelo Matplotlib]
```

[Voltar ao início](https://github.com/Landim7/portifolio-pedro-landim)
