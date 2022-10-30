# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_


Setup development environment that's hosted in the cloud called Github Codespace. No need to install anything on your own computer!

Go here https://docs.github.com/en/codespaces/overview

It takes about a minute to boot. Once it's up and ready you can start working directly in the browser or use VS Code to connect to the codespace in the cloud.

Next, Go ahead and create your own codespace with this link: https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=559421944 and  click on the Create codespace button and wait for it to boot.

Next, when your codespace is up and running you can run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.

After the server is up, make sure you test it by pointing your browser to https://lexusr2023-laughing-waffle-g9qrrvq99g4fpwgv-3000.githubpreview.dev/api/ping

Now, it’s time to check the frontend and make sure it’s connected to the backend. If everything is working properly, you’ll be able to create a new user on https://lexusr2023-laughing-waffle-g9qrrvq99g4fpwgv-3001.githubpreview.dev/register
