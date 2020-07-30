# ipgeolocation cloudlfare worker 

Based on the IP address of the visitor, it returns the country.

If you have a paid cloudflare account, you will be able to retrieve more specific geo information (eg the state in the US).

TODO: find someone that wants to code it or throw the 5$/month in my general direction so I can make it happen

[`index.js`](https://github.com/cloudflare/worker-template/blob/master/index.js) is the content of the Workers script.

## to deploy
If you aren't familiar with workers or wrangler, check the doc from cloudflare, it's quite clear.

1. cp wrangler.example.toml wrangle.toml
2. fill the missing information about your cloudflare account
3. wrangler publish

Further documentation for Wrangler can be found [here](https://developers.cloudflare.com/workers/tooling/wrangler).
