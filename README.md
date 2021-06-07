house-price-prediction

O projeto tem como objetivo prever preços de casas. O projeto foi construído com uso com uso de 
docker para facilitar a execução em diferentes ambientes.

# Como rodar

1- Primeiro copie o arquivo `.env.example` e crie o arquivo `.env` na raíz do projeto.

2- Execute um comando `docker-compose build` para construir a imagem do contêiner research.

3- Utilize o comando `docker-compose run --rm --service-ports research` para subir o Jupyter.

4- Acesse a url indicada pelo shell.


