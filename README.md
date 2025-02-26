<h1 align="center">
  Game List V1 (Ruby on Rails Backend)
  <br> 
</h1>

<h4 align="center">Game List is a social game-tracking app that allows users to easily search, filter, and track their video game collections, enabling them to share their gaming status and interact with others through comments, likes, and following. The V1 frontend made in React.js can be accessed <a href="https://github.com/Yzma/game-list-frontend-v1">here.</a></h4>
<br>

<p align="center">
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#database-erd">Database ERD</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#authors">Authors</a> 
</p>

<h3 align="center">Live Demo: <a href="https://gamelistapp.netlify.app/home/">https://gamelistapp.netlify.app/home</a></h3>
<br>

## Tech Stack

- [Ruby on Rails](https://rubyonrails.org/)
- [GraphQL](https://graphql.org/)
- [BCrypt](https://github.com/bcrypt-ruby/bcrypt-ruby)
- [RSpec](https://rspec.info/)
- [Postgres SQL](https://www.postgresql.org/)


## Database ERD

![Database ERD](/public/Database%20ERD.png)

## Getting Started

**Prerequisites:**

* [Ruby](https://www.ruby-lang.org/en/)
* [Git](https://git-scm.com) 
* [psql](https://www.postgresql.org/docs/current/app-psql.html)

1. Clone the repository

```sh
git clone https://github.com/Yzma/game-list-backend-v1.git
```

2. Move to the correct directory

```sh
cd game-list-backend-v1
```

3. Install dependencies

```sh
gem install
```

4. Fill out all variables in .env file.

```sh
PORT=3000
DATABASE_USERNAME=
DATABASE_PASSWORD=
DATABASE_DEVELOPMENT_DATABASE=
DATABASE_TEST_DATABASE=
SECRET_KEY_BASE=
```

5. Seed the database

```sh
rails db:seed
```

6. Run the application

```sh
rails start
```

## Authors

- <a href="https://github.com/Yzma">Andrew Caruso</a>
- <a href="https://github.com/changLiCoding">Chang Li<a>
- <a href="https://github.com/tienviet10">Viet Tran<a>
