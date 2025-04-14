# UE5 Web Socket server (blueprint) example

## Requirements
- Unreal Engine 5.0 or later
- WebSocket with Blueprint Plugin: https://www.fab.com/listings/4c33791a-74f8-487e-9fcd-1a49593187f4

## Installation
1. Clone the repository to your local machine.
2. Open the `wsServer/wsServer.uproject` file in Unreal Engine 5.

## Blueprint
<img src="./wsServer/bp.jpg" alt="Blueprint" width="800"/>

## Test
1. Open the `wsServer` project in Unreal Engine 5.
2. Click the "Play" button to start the WebSocket server.
3, cd to `wsClient` folder
4. Run `node client.js` to start the WebSocket client.
5. You should see the client sending messages to the server and receiving responses.