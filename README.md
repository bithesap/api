# api
Bithesap Bitcoin & Altcoin Exchange Ticker Api for Price Information

Bithesap Bitcoin & Altcoin Borsası Fiyat Bilgisi için Ticker Api

http://www.bithesap.com

#

<code>GET</code> https://api.bithesap.com/v1/public/ticker
``` json
{
  "btc_try": {
    "last": 40693,
    "lowestAsk": 40693,
    "highestBid": 39950,
    "percentChange": -6.11,
    "change": -2621.75,
    "volume": 24.81,
    "high24hr": 44280.627,
    "low24hr": 39973.55,
    "lastUpdate": 1517325305
  }
}
```

|    |

| Değer        | Açıklama           | 
| :------------- |:-------------| 
| btc_try	| Piyasa kodu
| last	| En son fiyat
| lowestAsk	| En düşük satış fiyatı
| highestBid	| En yüksek alış fiyatı
| percentChange |       	Günlük fiyat değişimi yüzde olarak
| change	| Günlük fiyat değişimi Türk Lirası olarak
| volume	| Hacim
| high24hr	| Son 24 saat en yüksek fiyat
| low24hr	| Son 24 saat en düşük fiyat
| lastUpdate| 	Son güncelleme saati

Saat formatı unix epoch formatında (https://www.epochconverter.com/) olup UTC zaman dilimdedir.

