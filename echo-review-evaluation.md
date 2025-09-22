# Echo-Review-Evaluation

[echo-review](README.md)  
[echo-review-evaluation-tools](https://docs.google.com/document/d/e/2PACX-1vRJk1UCyUG5eshAMjtI57gzkd4Bwf6oBooKaNB8ETQI_dP2dM8QbxlaZ4_nbxVD39VxyFm9SN1Whs9R/pub)  
[echo-review-evaluation-alpaca-sdk](https://docs.google.com/document/d/e/2PACX-1vTv72iby2YumdtaaMv0IkPx32uVbOvJrgmW7npQUC1bdOngCR2PQnM-VP9Y9P8-xezxoQO-ak5_0uBI/pub)  
[echo-review-evaluation-btc-markets-api](https://docs.google.com/document/d/e/2PACX-1vQZS00upl6zm4JGGK4Bs6i8bUyHb9KLiaLd7mEYfWkXx3pjYKuG1c40t0Ny4LaQ6dWeDYsp7xK8tjTA/pub)  

# Echo Reviews

### [Candle for Trades](https://docs.google.com/document/d/e/2PACX-1vRhTjSdu5tmzEr7eD38besRGXcJjZ_RNlkhe-pbWm1-KKSd8m2rDQgFHJvAs-3N5rKJnebI9KkldymM/pub)
What if I do SMA on top of the naked trades, not the periodic candle data with specific timewindow? One of the benefits of doing this is it is easier to get updated with live feed. Just adding new entries from the live feed, and retire the old entries, and recalc the SMA through. If it is feasible, then we can use this trend analysis as a live signal detector for BuyerSeller strategy.

### [Keep Local OrderBook with OrderBookUpdates](https://docs.google.com/document/d/e/2PACX-1vSSwqMznNQ242ljNlpUvhbkdRyksQVt1fwsN7zZuXsSCaGtGi5RnMOLRxNMYpBZyu9tb9VadqEF6CJP/pub)
There could be many analyses done on other types of data, but actual trading should be done on the live feed. This OrderBookUpdates is bringing live updates of Push Pull orders, so I need to keep my local copy of Order Book with these live updates.

### [BTC Markets Candle Data](https://docs.google.com/document/d/e/2PACX-1vQw0NAVwb7HByqsBeHQWHiHc_zHqM7oJxJETVQhsruorVdxHI24bw0fK_mWQL9XfepvzCCf5xRV4u4F/pub)
This is a part of the BTC Markets API Evaluation. With this historical data, I’ll try to see the average price changes over the time periods, and also try to see whether any specific time is busier than others.

### [BTC Markets Live MD Client](https://docs.google.com/document/d/e/2PACX-1vQGPCilY-8OCKJYJb52BST59fvXus8Hi6KspL7AFSp8tFhKyq6e4gkdoP5Cz5vJqWUAUtfVzaWuJCvK/pub)
This is part of the BTC Markets API Evaluation, and this time it is about Live Market Data client with WebSocket. I have referenced the implementation here.

### [Generic BTC Markets Connection Client](https://docs.google.com/document/d/e/2PACX-1vSHC6qbVGqAyYna9fnieUrp_KOuOfdZPEcjLOeGj6Dav5fuit9P6t17YLmL38H6X2M6unHWGM71amuF/pub)
This is part of the BTC Markets API Evaluation, and I’ll create a generic connection client for BTC Markets API. This client will handle the authentication and https request and reply.

### [Alpaca Basic Subscription](https://docs.google.com/document/d/e/2PACX-1vQJDXYdoSk7kIJJcBP5aqtKB76PaXB3_yb_-xhUBA_vs9Q-20QsoPT319unoRygO-kicSFXVvTZ3VaR/pub)
I spent some time reviewing alpaca market data sdk, and now it is time to create an account to do more reviews. I’ll go for the basic subscription to begin with. This subscription will let me generate an api key, to explore more features alpaca supports.

### [Echo-Review Tools (ervTools) Python Package](https://docs.google.com/document/d/e/2PACX-1vRJk1UCyUG5eshAMjtI57gzkd4Bwf6oBooKaNB8ETQI_dP2dM8QbxlaZ4_nbxVD39VxyFm9SN1Whs9R/pub)
While I was doing echo-review for Alpaca Crypto Bar Market Data, I realised I needed to write the common tools python package for Echo Reviews. With this package, I’ll generate standard library documents and register to pip registry

### [Alpaca Crypto Bar Market Data](https://docs.google.com/document/d/e/2PACX-1vSbO0Z71FGjZoAHNtqJCIjSdJyvg8Num48C_SKdutLMPdZa9bkfKp11N0Pjbe9GuUlmEgL1ekTcB3qz/pub)
The very first Alpaca SDK evaluation is about getting Crypto Bar Market Data from alpaca service. The implementation class is CryptoBar, and I made the initialisation function to take all the key word arguments as the spec for the class. So that the caller can specify the different requests when constructing the CryptoBar class.

### [VSCode Extension for Unit Test](https://docs.google.com/document/d/e/2PACX-1vQDoSAk7cFIkyfUVZ-vzg4MB0Fax_XKz_f2yOcyW_PJ3lB95XqxGCdtX4uObwgwmTcmGcvo_1wHutW8/pub)
As I have shown in the Alpaca Crypto Bar Market Data echo-review, it is very useful having the unit test class in the same script with the implementation class, and if you can run each unit test right away from the code.

### [Using VSCode for Python](https://docs.google.com/document/d/e/2PACX-1vTO0qs19g1TFRSKFeg3Rdo4wpBodCBolCwpk0rNY4CK8aSoPDoYtAsH2OM4Ozzr_nEp4f1uOR1GYurt/pub)
This is part of the evaluation of alpaca sdk, and I’ll start using VSCode for the python repo created for it. During the creation of the python repo, I just used the command line and web interface, but in actual development I have used VSCode since 2023. The previous tool I’ve used PyCharm from JetBrains was also good, but I think VSCode is better.

### [Create a new repo for a python project](https://docs.google.com/document/d/e/2PACX-1vTC_sEQaTS1hDEwW21iwXDcCElZQb0jiNG4RPP-5gmwDHSZU-L6OtyiP1SRTMVHN8ObO2AvS7r9R_uM/pub)
I’ll create a new repo for Alpaca SDK evaluation, but any python package repo could be started in the same way. I’ll use a virtual environment for a python project, and will add minimal necessary files in the beginning. In this case, I’ll use GitLab for the remote repo service.

---
[echo-review](README.md)  