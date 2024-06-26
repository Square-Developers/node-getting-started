# Square Node SDK Quickstart

This quickstart sample creates a Square client instance with your Square access token and then lists the locations in your account.
The sample is based on the [Node SDK Quickstart guide](https://developer.squareup.com/docs/sdks/nodejs/quick-start).

## Setup

[Install Node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) - If you don't have Node already installed on your machine.

## Quickstart instructions

1. Change into the `quickstart` directory

1. copy `.env.example` to `.env` and replace with your access token
    ```
    SQUARE_ACCESS_TOKEN=yourSandboxAccessToken
    ```

1. Install latest version of the square SDK
    ```
    $ npm install square
    ```

1. Run the code
    ```
    $ npm run start
    ```

1. You should see output similar to this in your console
    ```
    LHJ3ZXJ9RSV8X: Default Test Account, 1600 Pennsylvania Ave NW, Washington
    ```

## Resources

[Square Node SDK Guide](https://developer.squareup.com/docs/sdks/nodejs/using-nodejs-sdk) - details on how to use / configure the Square client.

[NPM repository for Square](https://www.npmjs.com/package/square) - Where the package files are hosted

[Node SDK Source Code](https://github.com/square/square-nodejs-sdk) - Github repo with sdk source code