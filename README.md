# EP2_IA

Este repositório tem um conjunto de experimentos para treinamento de classificador utilizando árvore de decisão e redes neurais. 

Na pasta **docs/** é possivel encontrar o enunciado do exercício, a documentação do projeto e um artigo com a descrição sobre o problema de classificação escolhido.

Dentro da pasta **datasets/**, devem estar os arquivos .csv contendo os exemplos para treinamento e teste do problema. 

Além disso, a pasta contém um *Jupyter Notebook* em Python, que possui algumas funcionalidades para tratamento e análise deste dataset. 

Para rodar o notebook basta tê-lo instalado em sua máquina e rodar o seguinte comando:
```
jupyter notebook
```

Os classificadores estão dentro da pasta **classifiers/**, tanto os arquivos .jar como os .xml já treinados. Para rodá-los, mas ta rodar os seguintes comandos e fazer o carregamento dos arquivos .xml:
```
java -jar -Xmx1024m dTree.jar
java -jar -Xmx1024m neural.jar
```
**Observação:** a flag -Xmx1024m serve apenas para aumentar o tamanho do *heap* do java e reduzir as chances do programa quebrar.