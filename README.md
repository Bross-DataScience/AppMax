# AppMax

O Ambiente utilizado para o desafio foi o Google Colaboratory, que é um ambiente de notebooks python na nuvem, dispensando qualquer instalação em sua máquina e totalmente **gratuito**, pode ser acessado no seguinte link: [Google Colab](https://colab.research.google.com/).

para utilizarmos o pyspark no Google Colab precisamos instalar o **Pyspark** com o seguinte comando:
```bash
!pip install pyspark
```
Pronto com tudo devidamente configurado podemos iniciar com o projeto. 

- Este arquivo deve ser carregado em um DataFrame do PySpark.
- Para começar, você deve unir as colunas **nome** e **sobrenome** em uma única coluna
chamada **nome_completo**.
- A coluna **ultima_compra** tem algumas linhas com valor nulo, remova essas linhas.
- Remova a substring ‘$’ de todos os valores da coluna **salario**, vale notar que o tamanho da string de todos os valores da coluna **salario** é 8.
- Agora que a coluna **salario** é uma coluna do tipo string contendo apenas números, faça a alteração do tipo de dado para double.
- O objetivo é adicionar esses dados no data warehouse, que está disponível no redshift, portanto precisamos passar a coluna **ultima_compra** para o tipo de dado timestamp.
- Por fim, o setor financeiro da ByteComercio está conduzindo um estudo sobre os clientes e solicitou o salário médio dos clientes, sendo assim você precisa encontrar este valor.
