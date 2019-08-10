# Projeto de uma API-Pizzaria :pizza:

### Falando sobre o projeto :finnadie:

É um desafio para uma vaga backend de uma empresa gringa chamada [AmbulnzLLC](https://github.com/AmbulnzLLC) que propôs que fizéssemos uma API que retorne um JSON para que seja consumida por um frontend, ai pra quem quiser tentar fazer o projeto é esse [aqui](https://github.com/AmbulnzLLC/fullstack-challenge/tree/master/backend) ó!! :boom::rocket:

### Mais informações sobre o desafio :trollface:

#### O que a API deve ter ? :suspect:

Ela deve ter as seguintes entidades com os relacionamentos adequados

- [x] pizza - has a name and price (e.g. Margherita $5, Pepperoni $6, ...)
- [x] order - has items
- [x] order item - has a pizza and quantity

#### O que a API deve retornar ? :rage4:

Ela deve retornar uma resposta em JSON para as seguintes rotas

- [x] /api/orders (list of orders)
- [x] /api/orders/:id (details of an individual order)
- [x] /api/pizzas (list of pizzas; see './backend/example-pizzas.json')

A resposta em JSON deve ter a seguinte estrutura:

```
[
  {
    "name": "Margherita",
    "price": 5,
    "ingredients": [
      "tomato",
      "mozzarella"
    ]
  },
  {
    "name": "Bufala",
    "price": 6,
    "ingredients": [
      "tomato",
      "mozarella di bufala"
    ]
  },
  {
    "name": "Romana",
    "price": 5,
    "ingredients": [
      "tomato",
      "mozzarella",
      "anchovies",
      "oregano",
      "oil"
    ]
  },
  {
    "name": "Diavola",
    "price": 7.5,
    "ingredients": [
      "tomato",
      "mozzarella",
      "spicy salami"
    ]
  },
  {
    "name": "Pizza Bianca",
    "price": 5,
    "ingredients": [
      "mozzarella",
      "oregano"
    ]
  }
]
```

### Implementações que quero fazer :flushed:

- [x] Fazer testes unitários
- [x] Criar todos validators

<h2 align="center">
  Acessem a He4rt e a Rocketseat :purple_heart:
</h2>

<h3 align="center">
  <img src="https://heartdevs.com/wp-content/uploads/2018/12/logo.png" width="215"><br>
    Visite nosso discord, vamo codar junto!! :godmode:
	<a href="https://discord.io/He4rt" target="_blank">
	<img src="https://discordapp.com/api/guilds/452926217558163456/embed.png" alt="Discord server"/></a><br>
</h3>

[Twitter He4rt](https://twitter.com/He4rtDevs)

[Meu Twitter](https://twitter.com/m7Aei_He4rt)
