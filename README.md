# CollaborativeGeometricOnlineArtGadget

Very simple chat implementation where clients can chat in terms of different pre-defined shapes.

The project utilizes the following tech:

- [SocketIO](https://socket.io/)
- [Angular](https://angular.io/)
- [NodeJS](https://nodejs.dev/)
- [Nx Workspace](https://nx.dev/)

![Visualization of the chat with four clients](https://user-images.githubusercontent.com/43444902/122090866-8157b080-ce08-11eb-87c9-ef95e81f4d01.gif?style=centerme)

![Logic overview](https://user-images.githubusercontent.com/43444902/122124758-04403180-ce30-11eb-9e43-ef77c7c8bbbb.png)

## Architecture

This is a [Nx Workspace](https://nx.dev/) and has the following folder structure:

```
.
├── ...
├── apps                    # The worskpace applications
│   ├── client-app          # Frontend/[Angular](https://angular.io/) application that clients uses
│   ├── client-app-e2e      # Frontend/[Angular](https://angular.io/) application End-to-end, integration tests (alternatively `e2e`)
│   └── server-app          # Backend/[NodeJS](https://nodejs.dev/) application controlling shape surface and clients
├── libs                    # The worskpace applications
│   ├── interfaces          # Interfaces shared between applications
│   └── utils               # Utility functions shared between applications
└── ...
``` 
## Commands

Run tests

> npm run test

Start all applications

> npm run dev

**Visit** [localhost:4200](http://localhost:4200)
