# AM-Trabalho1
Primeiro Trabalho de Aprendizado de Máquina

Passos:

DONE -> O algoritmo de indução de uma árvore de decisão, usando como critério de seleção de atributos para divisão de nós o Ganho de Informação (baseado no conceito de entropia), como visto na disciplina, tratando tanto atributos categóricos quanto numéricos;

-> Uma função para percorrer a árvore de decisão treinada e realizar a classificação de uma nova instância (do conjunto de teste);

-> O mecanismo de bootstrap (amostragem com reposição) para geração de subconjuntos a partir do conjunto de dados de treinamento originais. Cada bootstrap será utilizado como conjunto de treinamento de um modelo/árvore no aprendizado ensemble;

-> O mecanismo de amostragem de m atributos a cada divisão de nó, a partir dos quais serão será selecionado o melhor atributo de acordo com o Ganho de Informação;

-> O treinamento de um ensemble de árvores de decisão, adotando os mecanismos de bootstrap e seleção de atributos com amostragem, como mencionados acima;

-> O mecanismo de votação majoritária entre as múltiplas árvores de decisão no ensemble, para classificação de novas instâncias utilizando o modelo de Florestas Aleatórias;

-> A técnica de validação cruzada (cross-validation) estratificada, para avaliar poder de generalização do modelo e a variação de desempenho de acordo com diferentes valores para os parâmetros do algoritmo (p.ex., número de árvores no ensemble).
