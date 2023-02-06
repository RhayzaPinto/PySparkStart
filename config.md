### Preparando Ambiente de trabalho

No presente trabalho, utilizaremos a plataforma Jupyter Notebook para análise do arquivo [diamonds.csv](link).

Para isso, será necessário o download e configuração do ambiente, no SO Windows 10. Serão necessários 8 etapas para conclusão da configuração.

> Etapa 1: Download e instação do [Python](https://www.python.org/)</b>
> Etapa 2: Download e instalação do [Anaconda](https://www.anaconda.com/)</b>
> Etapa 3: Instalação do Java</b>
> Etapa 4: Instação do PySpark</b>
> Etapa 5: Instalação do FindSpark</b>
> Etapa 6: Validação da instalação do PySpark no terminal do PySpark</b>
> Etapa 7: Utilização do PySpark no jupyter Notebook</b>
> Etapa 8: Rodar PySpark da IDE</b>

# Etapa 1: Download e instação do Python

Vá em https://www.python.org/  e clique em download Latest, como na imagem:

![Pull image](./images/1.PNG)

Escolha a versão que melhor atende seu sistema operacional.

![Pull image](./images/2.PNG)

Siga os passos do executável para concluir a instalação.

# Etapa 2: Download e instalação do Anaconda

Vá em https://www.anaconda.com/ e clique no botão com a imagem do sistema operacional que você utiliza. Complete o download e instação do executável.

# Etapa 3: Instalação do Java

PySpark utiliza Java como dependência, portanto, você precisa ter Java no seu Windows. Como o Java é de terceiros, você pode instalá-lo utilizando o `conda`. `conda` é o gerenciador de pacotes no qual a distribuição do Anaconda é construída. É um gerenciador de pacotes multiplataforma e independente de linguagem. Como o Oracle Java não é mais de código aberto, estou usando o OpenJDK versão 11. Abra o Terminal do Windows e execute o comando ``conda install openjdk`` para instalar o Java.

![Pull image](./images/3.PNG)

Digite `y` para continuar a instalação.

![Pull image](./images/4.PNG)

# Etapa 4: Instação do PySpark

Para instalar o PySpark no Anaconda, utilizarei o comando `conda` também.

No terminal, digite `conda install pyspark`. Aguarde a instalação.

![Pull image](./images/6.PNG)

# Etapa 5: Instalar FindSpark

Para utilizar o PySpark no Jupyter Notebook, primeiramente, você precisa encontrar a Instalação PySpark. Para isso, utilize o pacote `findspark`.

Digite `conda install -c conda-forge findspark` no terminal.