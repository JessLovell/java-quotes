# Lab 08: OO Design

## Challenge
* Use the file recentquotes.json to show random popular book quotes. Your program should use GSON to parse the .json file. The app needs no functionality other than showing the quote and the author when it is run. The app should choose one quote each time it is run.
* Use JUnit to write at least one test for each of the Feature Tasks.

## To Test
1. Clone the repo and `cd` into this directory.
2. In the command line type `./gradlew run`. This will show a random quote from the [Ron Swanson Quote API](https://github.com/jamesseanwright/ron-swanson-quotes#ron-swanson-quotes-api).
3. To search an author type `./gradlew run --args 'author name'` or for names of 1+ words type: `./gradlew run --args 'author "first lastname"'`.
4. To search a phrase or word type `./gradlew run --args 'author "many words go here"'`.
5. To search an All-American, Ron Swanson quote type `./gradlew run --args 'american'`.


## Collaborators: [Jessica Lovell](https://www.linkedin.com/in/lovelljessica/) and [Evan Slaton](https://www.linkedin.com/in/evanslaton/)