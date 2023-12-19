# hello wing

the example from the [getting started](https://docs.winglang.io/getting-started/hello) guide.

this is a simple example of a winglang project that demonstrates the usage of cloud services. the program creates a cloud bucket and a cloud queue. it then adds a consumer to the queue, which writes a message to a file in the bucket.

you can also open this in the [wing playground](https://play.winglang.io/?code=ynjpbmcgy2xvdwq7dqoncmxldcbidwnrzxqgpsbuzxcgy2xvdwquqnvja2v0kck7dqpszxqgcxvldwugpsbuzxcgy2xvdwquuxvldwuoktsncg0kcxvldwuuywrkq29uc3vtzxioaw5mbglnahqgkg1lc3nhz2u6ihn0cikgpt4gew0kicbidwnrzxquchv0kcj3aw5nlnr4dcisicjizwxsbywgjhttzxnzywdlfsipow0kfsk7)

![diagram](./diagram.png)

## prerequisite

please make sure to use a current and working setup of the [wing cli](https://docs.winglang.io/getting-started/installation)

## usage

### wing console

```
wing it
```

### wing tests

```
wing test --debug  main.w
```
