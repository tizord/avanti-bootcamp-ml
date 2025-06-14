# ATIVIDADE 1 - Conceitos básicos de machine learning

## 1. Explique, com suas palavras, o que é machine learning?

O aprendizado de máquinas (Machine learning ou ML) é uma sub área da Inteligência Artificial, onde a máquina é capaz de aprender de forma contínua a partir da experiência obtidas nas execuções das tarefas anteriores. No aprendizado de máquina utiliza técinas de matemática e estatísticas, que permitem a máquina aprender/descobrir padrões nos dados, em oposição ao paradigma da execução de instruções rígidas. 

## 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

Um algoritmo de aprendizado de máquina aprende a partir dos dados que são fornecidos a ele. Após ele aprender, deve-se certificar de que ele é capaz de resolver outros problemas de mesma natureza/domínio.
Para que se possa ter um algoritmo confiável que é capaz de resolver outros problemas de um mesmo domínio de forma eficiente é necessário avaliar a capacidade dele de generalizar o problema sem fazer suposições erradas e abrangentes, ou seja, deve-se avaliar o viés e a variância do modelo. Para fazer isso, fazemos a divisão dos dados em conjunto de treinamento, validação e teste, onde:
* Conjunto de treinamento: É usado para treinar o modelo. O modelo vai aprender a partir desse modelo,
* Conjunto de teste: É usado para testar o modelo, ou seja, usamos dados que o algoritmo nunca viu e avaliamos se ele é capaz de resolver o problema satisfatóriamente ou se ele decorou as respostas do conjunto de teste,
* Conjunto de validação: Serve para comparar diferentes modelos e hiperparametros desses modelos.

Repare que o conjunto de teste não deve e não popde ser usado nem para treinar o modelo, nem para validar. Podemos comparar com uma prova, onde o conjunto de treino é a lista de exerícios, o conjunto de validação é o simulado da prova e o conjunto de teste é a prova de fato. Se a prova for igual a lista de exercícios, os alunos podem performar bem apenas porque decoraram as respostas.

## 3.​ Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Dependeria de alguns fatores como:
1. Quantidade de dados faltantes,
2. Atributo que possui os dados faltantes,
3. Tarefa de aprendizado de máquina que vou executar

Se a quantidade de dados faltantes fosse muito pequena em relação a base de dados, eu optaria por removê-los. Se fosse uma quantidade relevante eu optaria ou por usar uma estratégia de substituir pela média/moda dos atributos da mesma classe ou usar algum modelo preditivo para predizer esses valores.

## 4.​ O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

A matriz de confusão é uma matriz usada na avaliação de algoritmos de classificação, que possui 4 quadrantes a saber:
* Verdadeiro Positivo (VP): Modelo previu corretamente uma instância positiva como positiva,
* Falso Positivo (FP): Modelo previu incorretamente uma instância negativa como positiva,
* Verdadeiro Negativo (VN): Modelo previu corretamente uma instância negativa como negativa,
* Falso Negativo (FN): Modelo previu incorretamente uma instância positiva como negativa.

A partir da quantidade de classificações em cada um desses quadrantes é possível calcular as seguintes métricas:

* Precisão
* Revocação
* F1 Score
* Acurácia

Que são medidas relevantes sobre o algoritmo de classificação.


## 5.​ Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?

Eu acho muito interessante e válido aplicar o ML nas mais diversas áreas se a aplicação desses algoritmos tiver o intuito de ajudar as pessoas inseridas nessas áreas e não apenas visar o lucro e a eliminação da força de trabalho. Posto isso, a área que eu acho mais interessante de usar o ML é na criação, embasamento, sustentação, mensuração e correção de politicas públicas. Acho fantástico poder usar o ML e tornar a vida de todas as pessoas melhores, seja alocando melhor os recursos, seja identificando a causa raiz de problemas caros para a sociedade.