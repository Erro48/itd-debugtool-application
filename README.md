# Interactive TD Debug Tool - Application

An application created to make it easier to debug and test thing descriptions. It consists of two programs:

- _iTD DebugTool_: the core application that takes care of parsing and debugging of the Thing Descriptions.
- _cors-anywhere_: proxy server that is responsible for managing cors policies (this project it's a fork from [Rob--W project](https://github.com/Rob--W/cors-anywhere))

To see further details on the projects, check out the relative repositories.

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
