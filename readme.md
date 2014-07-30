# Insight WebSocket example

[Insight-API](https://github.com/bitpay/insight-api) is an api to the bitcoin blockchain.

This project is an example of how to use the socket.io websocket that insight offers.

To see the demo in action:
```
$ cd /path/to/this/repo
$ python -m SimpleHTTPServer
$ # Open http://localhost:8000 in a browser
```

The expected result is a stream of log messages in the console that contain transaction and block data.

## Progress

2014-07-30: Currently the websocket connects but does not respond with any data.


## Notes

Example of connecting to the websocket in the insight HTML interface

https://github.com/bitpay/insight/blob/d8712e7a8350e1bf36f695903a88af4d141417fb/public/src/js/controllers/index.js#L22


Example of topics available for subscription

https://github.com/bitpay/insight-api/blob/f0d135714feba5cf4287b972f60882c1e8b7d699/app/controllers/socket.js#L39
