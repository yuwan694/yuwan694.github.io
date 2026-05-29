# Echo-Review-Algo-Trading

[echo-review](README.md)  

# Echo Reviews

### [Back Test Benchmark](https://docs.google.com/document/d/1fMtzggJ0wTTLV600LdSsMA5HRJrEFJw3clXsKeSYj4M/edit?tab=t.0)
The backtick framework already has the feature of running many parameter combinations at a go, and storing the result in a CSV file. This feature is implemented in the BtBenchmark class, which utilises only two strategies at the moment. In this page, I’ll drive this feature a bit further into the parameter performance comparison or analysis direction. Not just using data frame or CSV result to see the performance results of each parameter set, but also visualise on the plots and tables.

### [ATR Band Scanning](https://docs.google.com/document/d/1rN6w4kc3D_21BROBkldpj-mVfhPVwKmUeEewQdJa4OE/edit?tab=t.0)
I heard the ATR Band in this posting for the first time, https://concretumgroup.substack.com/p/how-to-manage-an-intraday-trend-trade, and later I found this ATR band can be used to determine whether an instrument providing enough volatility for profit. So I decided to run this scan first, before running a back test for all instruments. I will implement the ATR Band Scanning in the backtick framework. I think I can add a research class for this one without disturbing backtick classes too much.

### [The backtick Back Testing framework](https://docs.google.com/document/d/1FVd5p77uBJlOhKa8zl9s1A9MCz8MllbglJNq8P5V4ag/edit?tab=t.0)
There are many back testing frameworks out there in the open source domain, but I decided to go for one myself with the help of Claude AI, to understand the basic concepts of the back testing. This very simple framework is also working for basic analysis of the daily bar input market data for various stocks over the world. It clearly have limitations, and some part of the code should be extended later, but still very useful to see overall progress of the research and back testing cycles.

---
[echo-review](README.md)  