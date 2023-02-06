### Preparando Ambiente de trabalho

No presente trabalho, utilizaremos a plataforma Jupyter Notebook para análise do arquivo [diamonds.csv](link).

Para isso, será necessário o download e configuração do ambiente, no SO Windows 10. Serão necessários 5 etapas para conclusão da configuração.

> Etapa 1: Download e instação do [Python](https://www.python.org/)<br>
> Etapa 2: Download e instalação do [Anaconda](https://www.anaconda.com/)<br>
> Etapa 3: Instalação do [Java](https://www.java.com/pt-BR/download/manual.jsp)<br>
> Etapa 4: Instação do PySpark<br>
> Etapa 5: Validação<br>

# Etapa 1: Download e instação do Python

Vá em https://www.python.org/  e clique em download Latest, como na imagem:

![Pull image](./images/1.PNG)

Escolha a versão que melhor atende seu sistema operacional.

![Pull image](./images/2.PNG)

Siga os passos do executável para concluir a instalação.

# Etapa 2: Download e instalação do Anaconda

Vá em https://www.anaconda.com/ e clique no botão com a imagem do sistema operacional que você utiliza. Complete o download e instação do executável.

# Etapa 3: Instalação do Java

PySpark utiliza Java como dependência, portanto, você precisa ter Java no seu Windows. Para instalá-lo, vá em https://www.java.com/pt-BR/download/manual.jsp e faça o download e instalação pelo executável.

![Pull image](./images/3.PNG)

# Etapa 4: Instação do PySpark

Para instalar o PySpark no Anaconda, vá no prompt de comando do Anaconda, clique com o botão direito e clique em `Executar como administrador`.

No terminal, digite `pip install pyspark`. Aguarde a instalação.

![Pull image](./images/4.PNG)

# Etapa 5: Validação

Ainda no terminal do Anaconda, digite `jupyter notebook` para abrir o Jupyter Notebook.

![Pull image](./images/5.PNG)

![Pull image](./images/6.png)

Abra um novo notebook Python 3.

![Pull image](./images/7.png)

Na primeira célula, digite `import pyspark` e clique em `run`.

![Pull image](./images/8.png)

Não deve ter nenhuma saída.