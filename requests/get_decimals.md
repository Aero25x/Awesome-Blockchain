[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hidden_coding)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aero25x)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/aero25x)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@flaming_chameleon)
[![Reddit](https://img.shields.io/badge/Reddit-FF3A00?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/HiddenCode/)


## Avalanche get token decimals
just replace `0xb2F85b7AB3c2b6f62DF06dE6aE7D09c010a5096E` by your token contract address
```
curl -X POST \           
  -H "Content-Type: application/json" \
  --data '{
    "jsonrpc": "2.0",
    "id": 1,
    "method": "eth_call",
    "params": [
      {
        "to": "0xb2F85b7AB3c2b6f62DF06dE6aE7D09c010a5096E",
        "data": "0x313ce567"
      },
      "latest"
    ]
  }' \
  https://api.avax.network/ext/bc/C/rpc
```
or this one compressed
```
curl -X POST -H "Content-Type: application/json" --data '{"jsonrpc": "2.0", "id": 1, "method": "eth_call", "params": [{"to": "0xb2F85b7AB3c2b6f62DF06dE6aE7D09c010a5096E", "data": "0x313ce567"}, "latest"]}' https://api.avax.network/ext/bc/C/rpc
```



[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/hidden_coding)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aero25x)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white)](https://x.com/aero25x)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@flaming_chameleon)
[![Reddit](https://img.shields.io/badge/Reddit-FF3A00?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/HiddenCode/)
