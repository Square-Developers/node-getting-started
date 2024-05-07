# Get Started

[Install Node](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) - If you don't have Node already installed on your machine.

[Square Node SDK Guide](https://developer.squareup.com/docs/sdks/nodejs/using-nodejs-sdk) - details on how to use / configure the Square client.

[Node Quickstart guide](https://developer.squareup.com/docs/sdks/nodejs/quick-start) - The quickstart directory is based off of this document.

[NPM repository for Square](https://www.npmjs.com/package/square) - Where the package files are hosted

[Python SDK Source Code](https://github.com/square/square-nodejs-sdk) - Github repo with sdk source code

## Quickstart instructions

Change into the `quickstart` directory

copy `.env.example` to `.env` and replace with your access token
```
SQUARE_ACCESS_TOKEN=yourSandboxAccessToken
```

Install latest version of the square SDK
```
$ npm install square
```

Run the code
```
$ npm run start
```

You should see output similar to this in your console
```
LHJ3ZXJ9RSV8X: Default Test Account, 1600 Pennsylvania Ave NW, Washington
```
