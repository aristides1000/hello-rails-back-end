# Hello Rails Back End

> This repository includes an API endpoint application for random hello messages. Its purpose is to train Microverse students in API creation and implementation in the React-Redux front-end view.

## Built With

- Ruby v3.0.1
- Ruby on Rails v6.1.4.1

## Front Live Demo

[React Repository Link](https://github.com/aristides1000/hello-react-front-end)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 3.0.1
Rails: 6.1.4.1
Postgres: >=9.5

### Setup

Instal gems with:

```
bundle install
```

Setup database with:

```
rails db:setup
rails db:migrate
rails db:seed
```

### Github Actions

To make sure the linters' checks using Github Actions work properly, you should follow the next steps:

1. On your recently forked repo, enable the GitHub Actions in the Actions tab.
2. Create the `feature/branch` and push.
3. Start working on your milestone as usual.
4. Open a PR from the `feature/branch` when your work is done.


### Usage

Start server with:

```
rails server
```

Open `http://localhost:3000/` in your browser.

## API Endpoints

### Get Message

#### Method: `get`
#### Endpoint: `/api/greeting`
#### Header: `{ "Content-Type": "application/json", "Accept": "application/json" }`

## Author

👤 **Author**
Arístides José Molina Pérez

- GitHub: [@aristides1000](https://github.com/aristides1000)
- Twitter: [@aristides_1000](https://twitter.com/@aristides_1000)
- LinkedIn: [aristides jose molina perez](https://www.linkedin.com/in/aristides-jose-molina-perez-09b0579a)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/aristides1000/hello-rails-back-end/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Ariel Camus CEO Microverse: For letting us start this journey.
- Google: For letting us find crucial information in order to create this project.

## 📝 License

This project is [CC0-1.0](LICENSE) licensed.
