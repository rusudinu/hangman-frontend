# Hangman Frontend

The backend can be found in [this repo](https://github.com/rusudinu/hangman-api).

1. You will clone and start the backend mentioned above.
2. You will start developing the frontend according to the following requirements:

* You will need to have two routes: one for creating a game and another one for joining a game.
* The game creation route will have a form with an input field for the word to be guessed and another input for the number of allowed guesses.
* The game joining route will have a form with an input field for the game id and another input for the player's name. After joining a game, on the same route, the player will be able to see the game status and the word to be guessed. The player will also be able to make a guess on this page. The player will be able to see the number of guesses left and the letters that have been guessed.

Please note that: these are the minimum requirements. You can add more features if you want. You can use bootstrap, tailwindcss or write the css 'by-hand'.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
