# http api server side rendered html

this is a [http api](https://www.winglang.io/docs/standard-library/cloud/api) example rendering a html template from a [bucket](https://www.winglang.io/docs/standard-library/cloud/bucket). it's making use of [external](https://www.winglang.io/docs/language-reference#52-javascript) javascript - in this case reading the template (preflight) and rendering it (inflight).

since this example makes use of external javascript, it won't run in the [wing playground](https://www.winglang.io/play) yet.

![diagram](./diagram.png)

## prerequisite

please make sure to use a current and working setup of the [wing cli](https://docs.winglang.io/getting-started/installation)

## usage

### wing console

```
wing it
```

get the url from the api and open it in the browser. each page reload will increase the counter.

![console](./console.png)
![browser](./browser.png)

### wing tests

```
wing test --debug  main.w
```
