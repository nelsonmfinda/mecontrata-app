[![CircleCI](https://circleci.com/gh/nelsonmfinda/mecontrata-app/tree/master.svg?style=svg)](https://circleci.com/gh/nelsonmfinda/mecontrata-app/tree/master)
[![Maintainability](https://api.codeclimate.com/v1/badges/9baf1f0c3f77a85329d9/maintainability)](https://codeclimate.com/github/nelsonmfinda/mecontrata-app/maintainability)
[![Inline docs](http://inch-ci.org/github/nelsonmfinda/mecontrata-app.png)](http://inch-ci.org/github/nelsonmfinda/mecontrata-app)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/nelsonmfinda/mecontrata-app)

# meContrata

O **meContrata** é um [jobboard](https://en.wikipedia.org/wiki/Employment_website) onde empresas publicam vagas de emprego, e pessoas que procuram emprego possam candidatar-se as vagas disponiveis de forma gratuita.


## Instalação

 Faça o clone do repositório para sua máquina:
  ```git
  git clone https://github.com/nelsonmfinda/mecontrata-app.git
  ```
* Entre no directório do projecto
  ```bash
  cd mecontrata-app
  ```
* Instale as dependências:
  ```bash
  bundle install
  ```

### Configuração

* Crie a base de dados

```sh
    rails db:create
```

* Faça a migração da base de dados

```sh
    rails db:migrate
```

### Testes

* Execute o comando abaixo para rodar os testes

```sh
    bundle exec rspec
```

## Tecnologias utilizadas

- Ruby 2.5.3 (Recomendo instalar via [rbenv](https://github.com/sstephenson/rbenv))
- Rails 5.2.2
- PostgreSQL
- SendGrid
- Heroku
- Docker
- Redis
- Sidekiq
- RSpec
- Capystrano
- ElasticSearch


## Contribuindo

Por favor, leia [CONTRIBUTING](CONTRIBUTING.md)

## Licença

Este projeto está licenciado sob a licença GNU v3 - Acesse [LICENSE.md](LICENSE.md) para mais detalhes

Copyright (c) 2019 Nelson Mfinda, hello@nelsonmfinda.me

