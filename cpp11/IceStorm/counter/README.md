This demo shows how to implement the observer pattern using [IceStorm][1].

To run the demo, start the IceStorm service:

```
icebox --Ice.Config=config.icebox
```

This configuration assumes there is a subdirectory named db in the
current working directory.

In a separate window:

```
server
```

In another window:

```
client
```

Press 'i' and 'd' to increment and decrement the counter. You can also
start more clients in other windows and observe that each is
initialized and subsequently updated with the current counter value.

[1]: https://doc.zeroc.com/ice/4.0/ice-services/icestorm
