# Pépito-API

This is the documentation to use the Pépito *Server-sent events* (SSE) API.  
It will let you know when Pépito is *in* or *out* with the corresponding picture.

## Technical Information

**SSE API Endpoint**

````
https://api.thecatdoor.com/sse/v1/events
````

**Response Example**
```json
{"event":"heartbeat","time":1725714568}
{"event":"heartbeat","time":1725714578}
{"event":"pepito","type":"in","time":1725714575,"img":"https://storage.thecatdoor.com/assets/1725714575-in-799154526.jpg"}
{"event":"heartbeat","time":1725714588}
{"event":"heartbeat","time":1725714598}
{"event":"pepito","type":"out","time":1725715521,"img":"https://storage.thecatdoor.com/assets/1725715521-in-722148161.jpg"}
{"event":"heartbeat","time":1725715532}
```

Go to [examples](./examples) to see some basic client examples.

## Pépito's Accounts

### Official

* X - https://x.com/pepitothecat
* TikTok - https://www.tiktok.com/@pepitothecat2007

### Unofficial

*Add yours here using PR or issue*


## Usage Policy

You are free to use this API for non-commercial usage.  
If you use it to publish on a public platform (like Bluesky, Mastodon, Threads, etc.), you must specify that it's an unofficial account.  
Additionally, please add the account link to the list above.

## Support

For any question, please submit an issue or send me a Private Message on [X](https://x.com/pepitothecat).
