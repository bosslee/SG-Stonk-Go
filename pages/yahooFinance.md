---
title: =YahooFinanceSG
metaDescription: How to use Yahoo Finance in Google Sheets
date: 2021-05-09
permalink: /yahoofinance/index.html
eleventyNavigation:
  key: =YahooFinanceSG
  order: 3
---

##  How to use Yahoo Finance custom function in Google Sheets
In this example, we are going to use the sample stock - DBS Group Holdings Ltd D05.SI

### To get the name of the stock
`=YahooFinanceSG('D05.SI','name')`

### To get the CURRENT price of the stock
`=YahooFinanceSG('D05.SI','price')`

### To get the 1Day Change of the stock
`=YahooFinanceSG('D05.SI','change')`

### To get the 1Day Change in Percentage  of the stock
`=YahooFinanceSG('D05.SI','changepct')`

### To get the CURRENT Day High of the stock
`=YahooFinanceSG('D05.SI','dayhigh')`

### To get the CURRENT Day Low of the stock
`=YahooFinanceSG('D05.SI','dayLow')`

### To get the 52 Weeks High of the stock
`=YahooFinanceSG('D05.SI','52whigh')`

### To get the 52 Weeks Low of the stock
`=YahooFinanceSG('D05.SI','52wlow')`

### To get the Price to Earning ration of the stock
`=YahooFinanceSG('D05.SI','pe')`
