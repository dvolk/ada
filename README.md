## Development setup

1. Download and install zola: https://getzola.org
2. clone this repo
3. run `zola serve`
4. Open browser at http://localhost:1111

## Deployment

```
zola build && rm -rf ada && cp -r public ada && scp -P 44444 -r ada ubuntu@eclipse.oxfordfun.com:/var/www/html/
```
