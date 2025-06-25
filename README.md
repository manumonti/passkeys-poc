# SimpleWebAuthn Passkeys + TACo PoC

This project is based on the example code from [SimpleWebAuthn repo](https://github.com/MasterKale/SimpleWebAuthn).

This contains a simple implementation of **@simplewebauthn/server** and **@simplewebauthn/browser**.

## Usage

Recommended node version: v20.

A server that provides a webpage in which you can register a passkey and then
authenticate with it can be run as follows. This server will mock a database of
registered passkeys (only one is accepted).

```bash
npm install
```

```bash
npm start
```

[http://localhost:8000](http://localhost:8000)
