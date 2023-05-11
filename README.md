# A3DATA DESAFIO 

Para uma avaliação sobre o ensino superior no Brasil, a EdTech resolveu avaliar algumas
informações existentes no Censo de Educação Superior, disponibilizado pelo Ministério da
Educação do Brasil.

https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-da-educacao-superior

Utilizando os dados de 2021, fiz a extração do mesmo utilizando um ambiente docker.

primeiro fui ao Dockerhub e peguei a imagem Jupyter/pyspark-nootebook

## Comandos necessários para iniciar a criação de uma imagem no Dockerfile:

Docker build -t "Desafio" .

Nesse comando, buildei a imagem e coloquei o nome da mesma, chamada "Desafio" usando a tag -t.

para a inicialização do contaneir:

Docker run -p 8888:8888 Desafio

a tag -p serve para definir a porta do rost e para o contaneir e passei o nome da imagem.





