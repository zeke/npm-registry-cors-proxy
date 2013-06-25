## cors-proxy

A proxy that does CORS

    npm install -g cors-proxy
    cors-proxy

Use it with a function like

```js
function proxy(url) {
    return 'http://localhost:5000/?url=' + encodeURIComponent(url);
}
```

And you can make [CORS](http://en.wikipedia.org/wiki/Cross-origin_resource_sharing)
requests to localhost:5000 from localhost on other ports.
