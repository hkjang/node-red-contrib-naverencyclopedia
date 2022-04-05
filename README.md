node-red-contrib-naverencyclopedia
================

Node-RED node for naverencyclopedia



## Install

To install the stable version use the `Menu - Manage palette - Install`
option and search for node-red-contrib-naverencyclopedia, or run the following
command in your Node-RED user directory, typically `~/.node-red`

    npm install node-red-contrib-naverencyclopedia

## Wrapper naver encyclopedia  API  
- https://developers.naver.com/docs/search/encyclopedia/

## Sample parameters
```js

msg.url = 'https://openapi.naver.com/v1/search/encyclopedia.json';

msg.params = {};
msg.params.query = '테스트'; //#검색어
msg.params.display = "10" // #출력 백과사전 수
msg.params.start = "1" //# 출력 위치

return msg;

```
## Sample flows
```json

```
