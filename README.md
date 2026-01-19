Websocket is a Computer Communications Protocl, Provides full-duplex communication channels over a single TCP Connection.
The HTTP 1.1 Upgrade header can be used to upgrade an already established client/server connection to a different protocl (Over the same transport protocol).
WebSockets use the HTTP/1.1 Upgrade mechanism to switch protocols, and since this happens at the HTTP server level, we need access to the raw Node.js server rather than only Express.
const app = express();
const server = http.createServer(server);

To install socket.io use => npm install socket.io
