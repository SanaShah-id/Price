# Price

## Retrieve current prices

## Resource URL
https://api.blockchain.com/v3/exchange/tickers

## Resource description
Retrieve the latest price

## Endpoints and methods
[GET]   /tickers

## Request example
curl -X GET "https://api.blockchain.com/v3/exchange/tickers" -H  "accept: application/json"

## Response body

```json
[
  {
    "symbol": "TFUEL-USDC",
    "price_24h": 0.05244,
    "volume_24h": 0,
    "last_trade_price": 0.05244
  },
  {
    "symbol": "XLM-EUR",
    "price_24h": 0.07812,
    "volume_24h": 73243.6892557,
    "last_trade_price": 0.07703
  },
  {
    "symbol": "ALGO-BTC",
    "price_24h": 0.00001488,
    "volume_24h": 0,
    "last_trade_price": 0.00001488
  },
  {
    "symbol": "EFI-USDT",
    "price_24h": 0.137,
    "volume_24h": 0,
    "last_trade_price": 0.137
  },
  {
    "symbol": "XTZ-USDT",
    "price_24h": 0.84,
    "volume_24h": 0,
    "last_trade_price": 0.84
  },
  {
    "symbol": "XLM-BTC",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.00000551
  },
  {
    "symbol": "USDC-GBP",
    "price_24h": 0.8882,
    "volume_24h": 0,
    "last_trade_price": 0.8882
  },
  {
    "symbol": "OGN-USDT",
    "price_24h": 0.2322,
    "volume_24h": 0,
    "last_trade_price": 0.2322
  },
  {
    "symbol": "CLOUT-USD",
    "price_24h": 12.99,
    "volume_24h": 0,
    "last_trade_price": 12.99
  },
  {
    "symbol": "STX-USDC",
    "price_24h": 0.331,
    "volume_24h": 0,
    "last_trade_price": 0.324
  },
  {
    "symbol": "CEUR-USDT",
    "price_24h": 1.07,
    "volume_24h": 0,
    "last_trade_price": 1.07
  },
  {
    "symbol": "EOS-USD",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "PAX-USD",
    "price_24h": 1.0004,
    "volume_24h": 0,
    "last_trade_price": 1.0004
  },
  {
    "symbol": "BCH-USD",
    "price_24h": 103.22,
    "volume_24h": 24.59981555,
    "last_trade_price": 101.84
  },
  {
    "symbol": "DAI-EUR",
    "price_24h": 0.0433,
    "volume_24h": 0,
    "last_trade_price": 0.0433
  },
  {
    "symbol": "USDT-GBP",
    "price_24h": 0.7987,
    "volume_24h": 1184.0892,
    "last_trade_price": 0.7987
  },
  {
    "symbol": "CRV-USDT",
    "price_24h": 0.6464,
    "volume_24h": 0,
    "last_trade_price": 0.6464
  },
  {
    "symbol": "LINK-USDT",
    "price_24h": 5.752,
    "volume_24h": 0,
    "last_trade_price": 5.752
  },
  {
    "symbol": "CHZ-USD",
    "price_24h": 0.0667,
    "volume_24h": 1.00000001,
    "last_trade_price": 0.0667
  },
  {
    "symbol": "APE-USD",
    "price_24h": 2.267,
    "volume_24h": 0,
    "last_trade_price": 2.267
  },
  {
    "symbol": "STX-USD",
    "price_24h": 0.522,
    "volume_24h": 0,
    "last_trade_price": 0.522
  },
  {
    "symbol": "MATIC-USDT",
    "price_24h": 0.997,
    "volume_24h": 0,
    "last_trade_price": 0.997
  },
  {
    "symbol": "WDGLD-USD",
    "price_24h": 174.52,
    "volume_24h": 0,
    "last_trade_price": 174.52
  },
  {
    "symbol": "ETH-USD",
    "price_24h": 1764.9,
    "volume_24h": 99.29752263,
    "last_trade_price": 1729.21
  },
  {
    "symbol": "SNX-USD",
    "price_24h": 2.2646,
    "volume_24h": 0,
    "last_trade_price": 2.2646
  },
  {
    "symbol": "LEND-USD",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.4909
  },
  {
    "symbol": "XLM-PAX",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.06981
  },
  {
    "symbol": "XRP-EUR",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.22
  },
  {
    "symbol": "XLM-USD",
    "price_24h": 0.08381,
    "volume_24h": 188127.7803355,
    "last_trade_price": 0.08287
  },
  {
    "symbol": "BAT-USDC",
    "price_24h": 0.30129,
    "volume_24h": 0,
    "last_trade_price": 0.30144
  },
  {
    "symbol": "LINK-USDC",
    "price_24h": 7.033,
    "volume_24h": 0,
    "last_trade_price": 7.055
  },
  {
    "symbol": "DGLD-BTC",
    "price_24h": 0.009727,
    "volume_24h": 0,
    "last_trade_price": 0.009534
  },
  {
    "symbol": "BCH-EUR",
    "price_24h": 105.36,
    "volume_24h": 0,
    "last_trade_price": 105.36
  },
  {
    "symbol": "BCH-BTC",
    "price_24h": 0.006,
    "volume_24h": 0,
    "last_trade_price": 0.006
  },
  {
    "symbol": "CLOUT-BTC",
    "price_24h": 0.000302,
    "volume_24h": 0,
    "last_trade_price": 0.000302
  },
  {
    "symbol": "BTC-USD",
    "price_24h": 26057.83,
    "volume_24h": 18.98785635,
    "last_trade_price": 25843.34
  },
  {
    "symbol": "BCH-ETH",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.582678
  },
  {
    "symbol": "ETH-TRY",
    "price_24h": 23950.9,
    "volume_24h": 0,
    "last_trade_price": 23950.9
  },
  {
    "symbol": "WLUNA-USD",
    "price_24h": 0.00013,
    "volume_24h": 0,
    "last_trade_price": 0.00013
  },
  {
    "symbol": "THETA-USD",
    "price_24h": 0.6932,
    "volume_24h": 0,
    "last_trade_price": 0.6932
  },
  {
    "symbol": "GALA-USD",
    "price_24h": 0.011,
    "volume_24h": 0,
    "last_trade_price": 0.011
  },
  {
    "symbol": "CUSD-USDT",
    "price_24h": 490,
    "volume_24h": 0,
    "last_trade_price": 490
  },
  {
    "symbol": "BTC-TRY",
    "price_24h": 390682,
    "volume_24h": 0,
    "last_trade_price": 390682
  },
  {
    "symbol": "ALGO-USD",
    "price_24h": 0.145,
    "volume_24h": 74.176697,
    "last_trade_price": 0.18
  },
  {
    "symbol": "ETH-EUR",
    "price_24h": 1647.77,
    "volume_24h": 0.53551257,
    "last_trade_price": 1617.3
  },
  {
    "symbol": "DOGE-USD",
    "price_24h": 0.06108,
    "volume_24h": 3648.5867372,
    "last_trade_price": 0.06108
  },
  {
    "symbol": "GRT-USD",
    "price_24h": 0.11561,
    "volume_24h": 0,
    "last_trade_price": 0.11561
  },
  {
    "symbol": "STX-USDT",
    "price_24h": 0.512,
    "volume_24h": 0,
    "last_trade_price": 0.512
  },
  {
    "symbol": "XRP-USD",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.29
  },
  {
    "symbol": "XLM-ETH",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.00019195
  },
  {
    "symbol": "USD-GBP",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "YFI-USD",
    "price_24h": 5327.95,
    "volume_24h": 0.18956634,
    "last_trade_price": 5327.95
  },
  {
    "symbol": "BTC-PAX",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 6115
  },
  {
    "symbol": "UMA-USDC",
    "price_24h": 3.3229,
    "volume_24h": 0,
    "last_trade_price": 3.3229
  },
  {
    "symbol": "WBTC-USDC",
    "price_24h": 18996.89,
    "volume_24h": 0,
    "last_trade_price": 19154.51
  },
  {
    "symbol": "MKR-USDT",
    "price_24h": 1013.83,
    "volume_24h": 0,
    "last_trade_price": 1013.18
  },
  {
    "symbol": "NEAR-USD",
    "price_24h": 1.3729,
    "volume_24h": 0,
    "last_trade_price": 1.3729
  },
  {
    "symbol": "CRV-USDC",
    "price_24h": 0.9327,
    "volume_24h": 0,
    "last_trade_price": 0.9327
  },
  {
    "symbol": "TRX-USD",
    "price_24h": 0.0704,
    "volume_24h": 12730.872951,
    "last_trade_price": 0.0704
  },
  {
    "symbol": "UNI-USDT",
    "price_24h": 3.977,
    "volume_24h": 0,
    "last_trade_price": 3.977
  },
  {
    "symbol": "DOT-EUR",
    "price_24h": 4.2,
    "volume_24h": 607.02463328,
    "last_trade_price": 4.18
  },
  {
    "symbol": "BAT-USDT",
    "price_24h": 0.185,
    "volume_24h": 0,
    "last_trade_price": 0.185
  },
  {
    "symbol": "BCH-PAX",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 339.24
  },
  {
    "symbol": "DAI-USDC",
    "price_24h": 0.9996,
    "volume_24h": 0,
    "last_trade_price": 0.9996
  },
  {
    "symbol": "UNI-USD",
    "price_24h": 4.389,
    "volume_24h": 0,
    "last_trade_price": 4.389
  },
  {
    "symbol": "TFUEL-USDT",
    "price_24h": 0.06478,
    "volume_24h": 0,
    "last_trade_price": 0.06478
  },
  {
    "symbol": "SOL-USDT",
    "price_24h": 15.9,
    "volume_24h": 1670.87788191,
    "last_trade_price": 15.115
  },
  {
    "symbol": "ETH-BTC",
    "price_24h": 0.067636,
    "volume_24h": 17.83496137,
    "last_trade_price": 0.067211
  },
  {
    "symbol": "WDGLD-BTC",
    "price_24h": 0.007,
    "volume_24h": 0,
    "last_trade_price": 0.007
  },
  {
    "symbol": "CELO-USDT",
    "price_24h": 0.47,
    "volume_24h": 0,
    "last_trade_price": 0.47
  },
  {
    "symbol": "USDC-EUR",
    "price_24h": 1.017,
    "volume_24h": 0,
    "last_trade_price": 1.0169
  },
  {
    "symbol": "XTZ-USDC",
    "price_24h": 1.59,
    "volume_24h": 0,
    "last_trade_price": 1.59
  },
  {
    "symbol": "WBTC-USDT",
    "price_24h": 29395.12,
    "volume_24h": 0,
    "last_trade_price": 29395.12
  },
  {
    "symbol": "MKR-USDC",
    "price_24h": 1032.03,
    "volume_24h": 0,
    "last_trade_price": 1032.03
  },
  {
    "symbol": "LINK-USD",
    "price_24h": 5.157,
    "volume_24h": 0,
    "last_trade_price": 5.156
  },
  {
    "symbol": "LTC-USD",
    "price_24h": 78.36,
    "volume_24h": 810.41634397,
    "last_trade_price": 76.3
  },
  {
    "symbol": "DOGE-USDT",
    "price_24h": 0.06075,
    "volume_24h": 42.1940422,
    "last_trade_price": 0.06075
  },
  {
    "symbol": "GRT-USDC",
    "price_24h": 0.10872,
    "volume_24h": 0,
    "last_trade_price": 0.10877
  },
  {
    "symbol": "CRV-USD",
    "price_24h": 0.6429,
    "volume_24h": 0.45045046,
    "last_trade_price": 0.6429
  },
  {
    "symbol": "COMP-USD",
    "price_24h": 33.9,
    "volume_24h": 0,
    "last_trade_price": 33.9
  },
  {
    "symbol": "CEUR-EUR",
    "price_24h": 1,
    "volume_24h": 0,
    "last_trade_price": 1
  },
  {
    "symbol": "GBP-USD",
    "price_24h": 1.2532,
    "volume_24h": 9611.559,
    "last_trade_price": 1.2442
  },
  {
    "symbol": "LTC-BTC",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.005827
  },
  {
    "symbol": "EFI-USD",
    "price_24h": 0.148,
    "volume_24h": 0,
    "last_trade_price": 0.148
  },
  {
    "symbol": "EOS-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "DAI-USDT",
    "price_24h": 0.999,
    "volume_24h": 0,
    "last_trade_price": 0.999
  },
  {
    "symbol": "SOL-USDC",
    "price_24h": 32.136,
    "volume_24h": 0,
    "last_trade_price": 32.133
  },
  {
    "symbol": "BTC-GBP",
    "price_24h": 20852.79,
    "volume_24h": 1.22145185,
    "last_trade_price": 20728.76
  },
  {
    "symbol": "USDC-USD",
    "price_24h": 1.0005,
    "volume_24h": 0,
    "last_trade_price": 1.0005
  },
  {
    "symbol": "MKR-USD",
    "price_24h": 600.5,
    "volume_24h": 0,
    "last_trade_price": 600.5
  },
  {
    "symbol": "SNX-USDT",
    "price_24h": 3.7085,
    "volume_24h": 0,
    "last_trade_price": 3.7085
  },
  {
    "symbol": "LTC-TRY",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "UMA-USDT",
    "price_24h": 2.7633,
    "volume_24h": 0,
    "last_trade_price": 2.7633
  },
  {
    "symbol": "WBTC-USD",
    "price_24h": 25588.42,
    "volume_24h": 0,
    "last_trade_price": 25588.42
  },
  {
    "symbol": "UMA-USD",
    "price_24h": 2.0219,
    "volume_24h": 0,
    "last_trade_price": 2.0219
  },
  {
    "symbol": "UNI-USDC",
    "price_24h": 5.215,
    "volume_24h": 0,
    "last_trade_price": 5.215
  },
  {
    "symbol": "CELO-USD",
    "price_24h": 0.47,
    "volume_24h": 0,
    "last_trade_price": 0.47
  },
  {
    "symbol": "THETA-USDC",
    "price_24h": 1.0949,
    "volume_24h": 0,
    "last_trade_price": 1.0931
  },
  {
    "symbol": "LTC-EUR",
    "price_24h": 73.34,
    "volume_24h": 41.51493913,
    "last_trade_price": 71.42
  },
  {
    "symbol": "SNX-USDC",
    "price_24h": 2.3583,
    "volume_24h": 0,
    "last_trade_price": 2.3595
  },
  {
    "symbol": "WDGLD-DGLD",
    "price_24h": 0.9901,
    "volume_24h": 0,
    "last_trade_price": 0.99
  },
  {
    "symbol": "THETA-USDT",
    "price_24h": 0.6563,
    "volume_24h": 0,
    "last_trade_price": 0.6563
  },
  {
    "symbol": "GRT-USDT",
    "price_24h": 0.09659,
    "volume_24h": 0,
    "last_trade_price": 0.09659
  },
  {
    "symbol": "DOT-USD",
    "price_24h": 4.54,
    "volume_24h": 1802.47173805,
    "last_trade_price": 4.52
  },
  {
    "symbol": "EUR-USD",
    "price_24h": 1.0737,
    "volume_24h": 20,
    "last_trade_price": 1.0737
  },
  {
    "symbol": "XTZ-USD",
    "price_24h": 0.81,
    "volume_24h": 0,
    "last_trade_price": 0.81
  },
  {
    "symbol": "USDT-TRY",
    "price_24h": 8.29,
    "volume_24h": 0,
    "last_trade_price": 8.29
  },
  {
    "symbol": "RARE-USDT",
    "price_24h": 0.21162,
    "volume_24h": 0,
    "last_trade_price": 0.21162
  },
  {
    "symbol": "COMP-USDT",
    "price_24h": 56.4,
    "volume_24h": 0,
    "last_trade_price": 56.4
  },
  {
    "symbol": "USDT-USD",
    "price_24h": 1.0001,
    "volume_24h": 39877.1345,
    "last_trade_price": 0.9999
  },
  {
    "symbol": "LEND-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.4854
  },
  {
    "symbol": "CELO-USDC",
    "price_24h": 0.85,
    "volume_24h": 0,
    "last_trade_price": 0.84
  },
  {
    "symbol": "USD-EUR",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "ETH-GBP",
    "price_24h": 1411.75,
    "volume_24h": 7.26627539,
    "last_trade_price": 1388.51
  },
  {
    "symbol": "OGN-USD",
    "price_24h": 0.22,
    "volume_24h": 0,
    "last_trade_price": 0.22
  },
  {
    "symbol": "ZRX-USDC",
    "price_24h": 0.3452,
    "volume_24h": 0,
    "last_trade_price": 0.3452
  },
  {
    "symbol": "TFUEL-USD",
    "price_24h": 0.05842,
    "volume_24h": 0,
    "last_trade_price": 0.05842
  },
  {
    "symbol": "ADA-USD",
    "price_24h": 0.2723,
    "volume_24h": 30572.66362116,
    "last_trade_price": 0.2811
  },
  {
    "symbol": "BAT-USD",
    "price_24h": 0.18044,
    "volume_24h": 0,
    "last_trade_price": 0.18044
  },
  {
    "symbol": "AAVE-USDT",
    "price_24h": 52.22,
    "volume_24h": 0,
    "last_trade_price": 52.23
  },
  {
    "symbol": "ADA-USDT",
    "price_24h": 0.2684,
    "volume_24h": 0,
    "last_trade_price": 0.2684
  },
  {
    "symbol": "APE-USDC",
    "price_24h": 5.962,
    "volume_24h": 0,
    "last_trade_price": 5.982
  },
  {
    "symbol": "USDC-USDT",
    "price_24h": 1.0003,
    "volume_24h": 0,
    "last_trade_price": 1.0003
  },
  {
    "symbol": "ETH-PAX",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 219.41
  },
  {
    "symbol": "BCH-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 358.46
  },
  {
    "symbol": "ZRX-USDT",
    "price_24h": 0.34513,
    "volume_24h": 0,
    "last_trade_price": 0.34513
  },
  {
    "symbol": "CUSD-USD",
    "price_24h": 0.9893,
    "volume_24h": 0,
    "last_trade_price": 0.9881
  },
  {
    "symbol": "ALGO-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.3614
  },
  {
    "symbol": "SUSHI-USDC",
    "price_24h": 0.995,
    "volume_24h": 0,
    "last_trade_price": 0.995
  },
  {
    "symbol": "ENJ-USD",
    "price_24h": 0.2786,
    "volume_24h": 0,
    "last_trade_price": 0.2786
  },
  {
    "symbol": "LTC-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 73.28
  },
  {
    "symbol": "DAI-GBP",
    "price_24h": 750,
    "volume_24h": 0,
    "last_trade_price": 750
  },
  {
    "symbol": "EFI-USDC",
    "price_24h": 0.136,
    "volume_24h": 0,
    "last_trade_price": 0.136
  },
  {
    "symbol": "BTC-EUR",
    "price_24h": 24285.62,
    "volume_24h": 11.58874969,
    "last_trade_price": 24027.17
  },
  {
    "symbol": "USDT-EUR",
    "price_24h": 0.93,
    "volume_24h": 20976.8733,
    "last_trade_price": 0.9303
  },
  {
    "symbol": "DGLD-USD",
    "price_24h": 163.1,
    "volume_24h": 0,
    "last_trade_price": 163.1
  },
  {
    "symbol": "EOS-USDC",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "YFI-USDT",
    "price_24h": 5313.94,
    "volume_24h": 0,
    "last_trade_price": 5313.94
  },
  {
    "symbol": "WLUNA-USDT",
    "price_24h": 0.01,
    "volume_24h": 0,
    "last_trade_price": 0.01
  },
  {
    "symbol": "RARE-USD",
    "price_24h": 0.30455,
    "volume_24h": 0,
    "last_trade_price": 0.30455
  },
  {
    "symbol": "SUSHI-USDT",
    "price_24h": 1.477,
    "volume_24h": 0,
    "last_trade_price": 1.477
  },
  {
    "symbol": "RARE-USDC",
    "price_24h": 0.21139,
    "volume_24h": 0,
    "last_trade_price": 0.21139
  },
  {
    "symbol": "COMP-USDC",
    "price_24h": 48.89,
    "volume_24h": 0,
    "last_trade_price": 48.42
  },
  {
    "symbol": "ENJ-USDT",
    "price_24h": 0.3109,
    "volume_24h": 0,
    "last_trade_price": 0.3109
  },
  {
    "symbol": "CUSD-USDC",
    "price_24h": 1.0024,
    "volume_24h": 0,
    "last_trade_price": 1.0024
  },
  {
    "symbol": "LTC-PAX",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 74.03
  },
  {
    "symbol": "MATIC-USDC",
    "price_24h": 0.752,
    "volume_24h": 0,
    "last_trade_price": 0.752
  },
  {
    "symbol": "PAX-EUR",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0.9444
  },
  {
    "symbol": "NEAR-EUR",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "AAVE-USD",
    "price_24h": 59.91,
    "volume_24h": 0,
    "last_trade_price": 59.91
  },
  {
    "symbol": "DOT-GBP",
    "price_24h": 3.57,
    "volume_24h": 0,
    "last_trade_price": 3.57
  },
  {
    "symbol": "BTC-USDT",
    "price_24h": 26043.9,
    "volume_24h": 3.62039105,
    "last_trade_price": 25846.58
  },
  {
    "symbol": "WLUNA-USDC",
    "price_24h": 0.001,
    "volume_24h": 0,
    "last_trade_price": 0.001
  },
  {
    "symbol": "ETH-USDT",
    "price_24h": 1763.34,
    "volume_24h": 13.29142347,
    "last_trade_price": 1737.9
  },
  {
    "symbol": "APE-USDT",
    "price_24h": 2.9,
    "volume_24h": 0,
    "last_trade_price": 2.9
  },
  {
    "symbol": "SOL-USD",
    "price_24h": 15.719,
    "volume_24h": 1099.96640334,
    "last_trade_price": 15.384
  },
  {
    "symbol": "ZRX-USD",
    "price_24h": 0.35948,
    "volume_24h": 0,
    "last_trade_price": 0.35948
  },
  {
    "symbol": "ADA-USDC",
    "price_24h": 0.4406,
    "volume_24h": 0,
    "last_trade_price": 0.439
  },
  {
    "symbol": "MATIC-USD",
    "price_24h": 0.582,
    "volume_24h": 0,
    "last_trade_price": 0.582
  },
  {
    "symbol": "SUSHI-USD",
    "price_24h": 0.55,
    "volume_24h": 9.21297904,
    "last_trade_price": 0.555
  },
  {
    "symbol": "NEAR-USDT",
    "price_24h": 0,
    "volume_24h": 0,
    "last_trade_price": 0
  },
  {
    "symbol": "DAI-USD",
    "price_24h": 0.9992,
    "volume_24h": 0,
    "last_trade_price": 0.9992
  }
]
```

## Example value
```json
[
  {
    "symbol": "BTC-USD",
    "price_24h": 4998,
    "volume_24h": 0.3015,
    "last_trade_price": 5000
  }
]
```

## Response description
The following table describes each item in the response.
| Response item | Description | Data type |
| ------ | ------ | ------ |
| Symbol | a mark or character used as a conventional representation of an object, function, or process. | String |
| Price | the amount of money expected, required, or given in payment for something. | Integer |
| Volume | the number of shares traded in a particular stock, index, or other investment over a specific period of time | Integer |
