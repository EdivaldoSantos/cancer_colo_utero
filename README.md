**Identificação do tipo de câncer do colo do útero**

Câncer cervical ou câncer do colo do útero, é a parte inferior do útero. A maioria dos cânceres cervicais é causada pelo papiloma vírus humano (HPV ou vírus da verruga).

Este vírus provoca alterações nas células cervicais que podem se transformar em câncer ao longo do tempo. Os sintomas podem incluir corrimento vaginal incomum, dor durante o sexo e sangramento vaginal após o sexo, sangramento entre as menstruações ou após a menopausa.

O tratamento pode ser cirurgia, quimioterapia e radiação. Se descoberto numa fase precoce, é muito provável a cura. Um dos maiores desafios para buscar um  tratamento do câncer do colo do útero, é determinar o método de tratamento adequado, que pode variar dependendo das diferenças fisiológicas dos pacientes.

**Objetivo**

Desenvolver um algoritmo que identifique com precisão o tipo de colo do útero de uma mulher com base em imagens.

**Especificação Técnica**

O dataset utilizado para o desenvolvimento desse projeto foi localizado no portal https://www.kaggle.com/, **“intel-mobileodt-cervical-cancer-screening”**. Importado para meu Google Drive para facilitar a integração com o Google Colab.

O formato dos dados utilizados neste dataset são;
Arquivos em CSV;
Imagens em JPG

Utilizaremos um diretório para Treinamento e outro para teste (Validação do algoritmo)


Bibliotecas utilizadas

Para o desenvolvimento desse projeto o Google Colab, Google Drive o Python 3.7.11 e as biblioteca:

**OpenCV** - É uma biblioteca que possui funções de manipulações básicas de imagens e vídeos, desde o carregamento de arquivos, até a conversão de um formato em outro.

**Numpy** - É uma biblioteca com funções para se trabalhar com computação numérica. Seu principal objeto é o vetor n-dimensional, ou ndarray.

**Pandas** - Uma biblioteca que oferece estruturas e operações para manipular tabelas numéricas e séries temporais; uma ferramenta de processamento de dados de alto desempenho; com recursos flexíveis de manipulação de planilhas e de banco de dados relacionais.

**Matplotlib** - Essa biblioteca é utilizada para criação de gráficos e visualização de dados.

**Scikit-learn** - É uma biblioteca de aprendizado de máquina, nela encontramos vários algoritmos de classificação, regressão e agrupamento incluindo máquinas de vetores de suporte.

**Seaborn** - É uma biblioteca de visualização de dados Python baseada em matplotlib . Ele fornece uma interface de alto nível para desenhar gráficos estatísticos atraentes e informativos.


**PIL** - Oferece amplo suporte a formatos de arquivo, uma representação interna eficiente e recursos de processamento de imagem bastante poderosos,
projetada para acesso rápido a dados armazenados em alguns formatos básicos de pixel.

**TensorFlow** - Biblioteca de código aberto para computação numérica usando grafos de fluxo de dados, que é tudo o que uma rede neural realmente é.

**Keras** - Biblioteca de rede neural modular que pode usar tanto Theano ou TensorFlow como um backend.


# Referências 
https://insightlab.ufc.br/8-bibliotecas-de-deep-learning-mais-usadas-em-python/
https://didatica.tech/o-que-e-tensorflow-para-que-serve/
https://pypi.org/project/Pillow/
https://imasters.com.br/back-end/primeiros-passos-com-pil-a-biblioteca-de-imagens-do-python
https://www.tensorflow.org/?hl=pt-br
https://www.hashtagtreinamentos.com/graficos-com-seaborn-no-python
https://seaborn.pydata.org/



Refrencia 
A Biblioteca Padrão do Python
https://docs.python.org/pt-br/3/library/index.html



OS
"os.path.join"  -- https://acervolima.com/python-metodo-os-path-join/#:~:text=os.-,path.,o%20%C3%BAltimo%20componente%20de%20caminho.
Acesso a arquivos e diretórios - https://docs.python.org/pt-br/3/library/filesys.html


glob
https://ichi.pro/pt/o-modulo-python-glob-78993832066349
