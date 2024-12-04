# Projeto de Análise e Agrupamento com K-Means

Este projeto realiza análise e agrupamento de dados utilizando o algoritmo **K-Means**, focado no reconhecimento de padrões em dados de sensores.

## Bibliotecas Utilizadas
- **Pandas**: Manipulação de dados e leitura de arquivos.
- **NumPy**: Operações matemáticas e manipulação de arrays.
- **Scikit-learn**: Implementação do K-Means, redução de dimensionalidade (PCA) e avaliação com Silhouette Score.
- **Matplotlib** e **Seaborn**: Visualização de gráficos 2D e 3D.

## Etapas Principais
1. **Análise Exploratória**: Exploração das distribuições e padrões nos dados.
2. **Pré-processamento**: Normalização com `StandardScaler` e redução de dimensionalidade com PCA.
3. **Agrupamento**: Implementação do K-Means com inicialização K-means++.
4. **Otimização**: Determinação do número ideal de clusters com Elbow Method e Silhouette Score.
5. **Visualização**: Representação dos clusters em gráficos 2D e 3D para análise.

## Resultados
Clusters foram gerados com base nos dados dos sensores, permitindo a interpretação de diferentes padrões de atividades, suportados por métricas de avaliação.

## Contribuições Futuras
- Exploração de algoritmos alternativos de agrupamento.
- Integração com modelos supervisionados para validação dos clusters.
