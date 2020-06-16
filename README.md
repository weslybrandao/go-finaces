<p align="left">
   <img src="https://ik.imagekit.io/p7fa4kfbgx/logo-docs_54tQ2vm6R.gif" width="100"/>
</p>

# Go Finances

> Manage all your spending

[![Author](https://img.shields.io/badge/author-weslybrandao-ff5900?style=flat-square)](https://github.com/weslybrandao)
[![Languages](https://img.shields.io/github/languages/count/weslybrandao/go-finaces?color=ff5900&style=flat-square)](#)
[![Stars](https://img.shields.io/github/stars/weslybrandao/go-finaces?color=ff5900&style=flat-square)](https://github.com/weslybrandao/go-finaces/stargazers)
[![Forks](https://img.shields.io/github/forks/weslybrandao/go-finaces?color=ff5900&style=flat-square)](https://github.com/weslybrandao/go-finaces/network/members)
[![Contributors](https://img.shields.io/github/contributors/weslybrandao/go-finaces?color=ff5900&style=flat-square)](https://github.com/weslybrandao/go-finaces/graphs/contributors)

# 🖼 Interface

<p align="center">
   <img src="https://ik.imagekit.io/p7fa4kfbgx/Capturar_hH2YKFqeb.PNG" width="1200"/>
</p>



# 🔎 Features
* 💻 Transactions CRUD
* 📁 Import transactions from CSV files


# ⚙ Installation

**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) first, then in order to clone the project via HTTPS, run this command:**

```git clone https://github.com/weslybrandao/go-finaces.git```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you use a SSH key registered in your Github account, clone the project using this command:

```git clone git@github.com:weslybrandao/go-finaces.git```

**Install dependencies**

```yarn install```

Create your enviroment variables based on the examples of ```.env.example```

```cp .env.example .env```

After copying the examples, make sure to fill the variables with new values.

**Setup a database**

Install [Postgres](https://www.postgresql.org/) to create a database or if you have [Docker](https://www.docker.com/) in your machine, fill the environment values related to database configurations and then run the following commands in order to create a postgres container.

```docker-compose up```

# 🚀 Getting Started

Run the transactions in order to configure the database schema

```yarn typeorm migration:run```

Run the following command in order to start the application in a development environment:

```yarn dev:server```

# :postbox: Faq

**Question:** What are the tecnologies used in this project?

**Answer:** The tecnologies used in this project are [NodeJS](https://nodejs.org/en/) + [Express Framework](http://expressjs.com/en/) to handle the server and [TypeORM](https://typeorm.io/#/) 

# 🐛 Issues

Feel free to **file a new issue** with a respective title and description on the the [GoFinances](https://github.com/weslybrandao/go-finaces/issues) repository. If you already found a solution to your problem, **i would love to review your pull request**.


Made with love by [Wesly Souza](https://github.com/weslybrandao) 💻😁
