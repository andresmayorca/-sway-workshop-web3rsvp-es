# web3rsvp-sway

App desarrollada en Sway enfocada en la creacion de eventos.

web3rsvp-sway tiene como intencion crear un contrato inteligente realmente simple, un contrato que todo el que este iniciando en Sway pueda comprender de forma sencilla. web3rsvp-sway lleva a cabo la creacion de eventos (charlas) asegurando la asistencia de cada persona inscrita en dicho evento.


Si tiene tiempo siga las instrucciones de instalación antes del taller. Se admite MacOS y Linux. Si tienes windows, necesitarás un subsistema de windows para linux (WSL).


## Intrucciones de instalación.

1. Instalar `cargo` usando [`rustup`](https://www.rust-lang.org/tools/install)

    Mac y Linux:
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

2. Comprobar que la version es correcta:

    ```bash
    $ cargo --version
    cargo 1.62.0
    ```

3. Instalar `forc` usando [`fuelup`](https://fuellabs.github.io/sway/v0.18.1/introduction/installation.html#installing-from-pre-compiled-binaries)

    Mac y Linux:
    ```bash
    curl --proto '=https' --tlsv1.2 -sSf \
    https://fuellabs.github.io/fuelup/fuelup-init.sh | sh
    ```

4. Comprobar que la version es correcta:

    ```bash
    $ forc --version
    forc 0.18.1
    ```

## Editor

Puede utilizar el editor que prefiera.

- [VSCode plugin](https://marketplace.visualstudio.com/items?itemName=FuelLabs.sway-vscode-plugin)
- [Vim highlighting](https://github.com/FuelLabs/sway.vim)
