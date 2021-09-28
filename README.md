# conversao-peso

## Construir a imagem

* docker image build -t edsontanaka/conversao-peso:1 .

## Executar o container

* docker run -d -p 5000:80 edsontanaka/conversao-peso:1

## Listar os containers

* docker container ls

## Remover o container

* docker container rm -f a7ba0fb2f77d (id do container)
