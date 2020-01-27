# Cinema-microservice:
Este repositório apresenta uma api em microsserviços com *__Node.js__* e *__Mongodb__* para um cinema fake.
O projeto é dividido em dois serviços básicos:
* [__movies-services__](https://github.com/davigsa/cinema-microservice/tree/master/movies-service/src)
* [__cinema-catalog-service__]()

---

## Serviço de Filmes:
1. Neste cenário, foi desenvolvido o microservice MOVIES e sua respectiva database. Cabe a esse serviço fornecer informações referentes ao catálogo de filmes cujos direitos de exibição foram comprados pela rede. Além do CRUD básico, espera-se deste serviço que seja possível saber quais filmes são os lançamentos da rede, basicamente os que entraram nos últimos 30 dias, que é mais ou menos a duração do status de lançamento de um filme.

2. MovieSchema:
   * Identificador Único;
   * Título;
   * Duração (minutos);
   * Imagem;
   * Sinopse;
   * Data de lançamento;
   * Categorias;

---
> Este projeto foi desenvolvido baseado no [artigo](https://imasters.com.br/devsecops/arquitetura-de-micro-servicos-em-node-js-mongodb) do blog __iMasters__
