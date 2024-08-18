# Webex Bot with Websockets and Adaptive Form Capabilities

This code is a fork of [https://github.com/DJF3/Webex-Bot-with-Websockets](https://github.com/DJF3/Webex-Bot-with-Websockets).

## Overview

This project adds adaptive form capabilities to WebEx Bot messages, which can be exchanged over websockets.

## Features

- WebEx Bot communication via websockets.
- Adaptive form integration in WebEx Bot messages.

## Adaptive Form Designer

You can design your own adaptive form using the [Webex Buttons and Cards Designer](https://developer.webex.com/buttons-and-cards-designer).

## Getting Started

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/webex-bot-with-websockets-adaptiveform.git
    cd webex-bot-with-websockets-adaptiveform
    ```

2. Install dependencies:
    ```sh
    poetry install
    ```

3. Set your WebEx Bot token in the environment variable `MY_BOT_TOKEN`.

4. Run the bot:
    ```sh
    python webex-bot-ws.py
    ```
