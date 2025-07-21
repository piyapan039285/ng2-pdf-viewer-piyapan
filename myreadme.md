
## Install

```
nvm use 16.13
export PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true
npm install 


docker-compose up -d
docker-compose exec ng2-pdf-viewer bash
  npm ci
  npm run test:ci
```


## publish
```
npm run packagr
cd dist
npm login
npm publish
```