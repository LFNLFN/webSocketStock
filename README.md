# webSocketStock

1. npm install
2. node server.js
3. use postman as client

`ws://localhost:8000`

try
`{
  "event": "subscribe",
  "stocks": ["IRH", "PXE"]
}`
and
`{
  "event": "unsubscribe",
  "stocks": ["IRH", "PXE"]
}`
