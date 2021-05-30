# Nano vote visualizer

Forked from https://github.com/numsu/nano-vote-visualizer and use another node (NanoTicker) to collect stats from, as redundancy.

* Hosted at: [votes.nanos.cc](https://votes.nanos.cc) for the live net
* Hosted at: [votes.nanos.cc/beta](https://votes.nanos.cc/beta) for the beta net

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.0.0.

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `npm run build:live` to build the project source to use the live network configuration.

Run `npm run build:beta` to build the project source to use the beta network configuration.

Change the environment.*.ts files if you want to host the service with your own node.
## Docker

### Building
Run `docker build -t nano-vote-visualizer:latest .` to build a runnable container for the live network.

Run `docker build -t nano-vote-visualizer:latest --build-arg ENVIRONMENT=beta .` to build a runnable container for the beta network.

### Running
Run `docker run -d --rm -p 8080:80 nano-vote-visualizer:latest` to spin up the container to http://localhost:8080.

## Contributing
Please be welcomed to open issues and contribute to the project with pull requests. If you require assistance, you can contact me on Discord.

## Donations
Donations are welcome, you can sent Nano to:

`nano_1iic4ggaxy3eyg89xmswhj1r5j9uj66beka8qjcte11bs6uc3wdwr7i9hepm`