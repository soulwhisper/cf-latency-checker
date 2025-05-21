# Cloudflare Latency Checker

- Ping a given IP/FQDN with port and returns the latency;
- FQDN will be resolved by cloudflare;

## Usage
`https://your.workers.dev/?ip=1.1.1.1:80` or `https://your.workers.dev?ip=cloudflare.com&port=80`

## Reponse
```json
  {"latency":60}
```
Latency is in milliseconds

## Deploy
1. Clone this repo
2. Run `wrangler login`
3. Run `wrangler publish`

## Reference

- source:[GewoonJaap/ping-latency-cf-worker](https://github.com/GewoonJaap/ping-latency-cf-worker)
