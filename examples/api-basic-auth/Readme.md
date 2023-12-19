# http api with basic auth

this is a [http api](https://www.winglang.io/docs/standard-library/cloud/api)  example authenticating with basic auth. it's also making use of leveraging [external](https://www.winglang.io/docs/language-reference#52-javascript) javascript - in this case for base64 en/decoding. last but not least, it's encapsulating the basic authentication functionality into a dedicated [class](https://www.winglang.io/docs/examples/classes).

since this example makes use of external javascript, it won't run in the [wing playground](https://www.winglang.io/play) yet.

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
