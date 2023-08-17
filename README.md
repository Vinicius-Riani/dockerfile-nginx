# dockerfile-nginx
1 - Criar pasta com nome app e arquivo index.html
    Copiar o codigo da api viacep no arquivo index.html
2 - Criar arquivo nginx.conf
3 - Criar o arquivo Dockerfile
    Executado o comando para criar a imagem.
    $docker build -t viacep-docker .

4 - Executado comando docker para criar o container:
    $docker container run --name app-cep -p 80:80 viacep-docker
