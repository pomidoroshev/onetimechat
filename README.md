# One Time Chat

Source code for https://onetimechat.online

## Message structure:

`[<command>, [param1, param2, ...]]`

## Client-to-server commands:

- `[send, <id>, {...}]` - send new message

## Server-to-clients commands:

- `[init, <id>]` - initiaize a client with new `id`
- `[add, <id>, <message>]` - add new message from a client with id=`<id>`
- `[rm, <id>]` - remove all messages from a client with id=`<id>`
- `[fetch]` - fetch all messages from client
