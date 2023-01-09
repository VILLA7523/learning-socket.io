# learning-socket.io

Socket.IO es una biblioteca que permite la comunicación de baja latencia, bidireccional y basada en eventos entre un cliente y un servidor.

``` javascript
const server = createServer(app);
const io = socketio.init(server);
const adIo = socketio.initAdIo(server, '/socket/adpage');
```
