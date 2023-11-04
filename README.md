# Interactive TD Debug Tool - Application

## Requirements

## Installation

First you need to clone the repository. In order to do that you have to run the command

```sh
git clone --recurse-submodules https://github.com/Erro48/itd-debugtool-application.git
```

With this command you clone the repository and the inner submodules.

To install the application properly, first of all you have to install the two submodules.

```sh
cd cors-anywhere && npm i
cd ../itd-debugtool && npm i
cd ..
```

Then, to build the images you have to run the following command:

```sh
docker compose build
```

## Usage

To start the application you have to run the following command:

```sh
docker compose up
```
