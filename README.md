# Mobile Flash Cards - Native App

This project was bootstrapped with [expo](https://expo.io/).

Mobile Flash cards is an APP that allows you to create flashcards on your mobile device, you can create multiple Deck collections and inside those decks you will have two options, one to create cards and another to take a Quiz.

You should think of cards as "Questions", they should be created in a "Correct" or "Incorrect" format, which will allow you to choose your answer accordingly in the Quiz.

## Tech-Stack
This project was built with React Native and Redux, even tho Redux was not a requirement. It started out from scratch, functions were built to get and set data accordingly, aswell as set data thru Async-Storage on your local mobile phone, which will allow you to retrieve your data even when you close the application.


This APP is using Redux & Async-Storage, the initial data is loaded from Async-storage and set as Redux state, which allows components to get information from the STORE, also everytime actions envoked, you can verify that there are api calls that hold the Async logic as well as the Reducers to modify the state, providing those sweet refrehes, without mutating the state.

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of `node/Git`
* You have a `Windows/Linux/Mac` machine. State which OS is supported.
* Mobile phone (`iOS` or `Android`)

## Installing Would You Rather

To install Would You Rather, follow these steps:

Windows/Linux and macOS:
* Download or Run git clone https://github.com/nchathu2014/flash-card-app to clone this repository.
* clone this repository to your local machine.
* install all project dependencies with `npm install`
* start the development server with `npm start` or `expo start`

## Contributing to Mobile Flash Cards
To contribute to <flash-cards-app>, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Contributors

Thanks to the following people who have contributed to this project:

* [@nchathu2014](https://github.com/nchathu2014) 💻 🎨 📖

## Contact

If you want to contact me you can reach me at <https://www.linkedin.com/in/nchathu/>.

