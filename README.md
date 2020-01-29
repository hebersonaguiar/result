## GetUp Cloud - Result

Esse respositório foi criado em base ao [Example Voting App](https://github.com/dockersamples/example-voting-app). A aplicação result é um front-end é baseda em `ASP.NET` que mostra os resultados da votação em tempo real da aplicação [Vote](https://github.com/hebersonaguiar/vote).

Essa aplicação foi criada em container e para o desafio [GetUp Cloud Docs](https://github.com/hebersonaguiar/getupclouddocs) não foi realizada nenhum tipo de alteração em relação ao seu desenvolvimento, para o projeto foi realizado o clone desse repositório, buildado e enviado ao [Hub Docker](https://hub.docker.com), para isso foram realizados os seguintes passos:

* Clone do repositório:

```bash
git clone https://github.com/hebersonaguiar/result.git
```

* Build da imagem:

```bash
docker build -t hebersonaguiar/result result/
```

* Login no [Hub Docker](https://hub.docker.com):

```bash
docker login
```
Obs: foi utilizado uma conta pessoal.

* Push da imagem para o [Hub Docker](https://hub.docker.com):

```bash
docker push hebersonaguiar/result
```