# Pépito-API

![Pépito](pepito.jpeg)

This is the documentation to use the Pépito API.  
It will let you know when Pépito is *in* or *out* with the corresponding picture.

## Technical Information

### SSE API (Real-time updates)

**Endpoint**

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

### REST API (Last status)

**Endpoint**

````
https://api.thecatdoor.com/rest/v1/last-status
````

**Response Example**
```json
{
    "event": "pepito",
    "type": "in",
    "time": 1753422874,
    "img": "https://storage.thecatdoor.com/assets/1753422874-in-181661935.jpg"
}
```

Go to [examples](./examples) to see some basic client examples.

## Pépito's Accounts

### Official

* X - https://x.com/pepitothecat
* TikTok - https://www.tiktok.com/@pepitothecat2007

### Unofficial

*Add yours here using PR or issue*
* BlueSky - https://bsky.app/profile/pepitothe-cat.bsky.social
* BlueSky - https://bsky.app/profile/pepitocat.bsky.social
* Tumblr - https://www.tumblr.com/pepitothecat ([#6](https://github.com/Clement87/Pepito-API/issues/6))
* Discord - [Discord Bot Invite](https://discord.com/oauth2/authorize?client_id=1369049895276777533) ([#7](https://github.com/Clement87/Pepito-API/pull/7) [Source Code](https://github.com/TheLonelyPug/Pepito-discord))
* Mastodon - https://mastodon.social/@PepitoTheCat ([#2](https://github.com/Clement87/Pepito-API/issues/2))
* Threads - https://www.threads.net/@pepito.thecat
* Telegram - Bot name [@Pepito_IO_Bot](https://t.me/Pepito_IO_Bot) - https://github.com/sensifier/PEPITO
* Is-Pepito-out frontend - [https://is-pepito-out.vercel.app/](https://is-pepito-out.vercel.app)

## Usage Policy

You are free to use this API for non-commercial usage.  
If you use it to publish on a public platform (like Bluesky, Mastodon, Threads, etc.), you must specify that it's an unofficial account.  
Additionally, please add the account link to the list above.

## Support

For any question, please submit an issue or send me a Private Message on [X](https://x.com/pepitothecat).
