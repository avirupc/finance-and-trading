#### Module 1. Introduction to Stock Markets 
# Chapter 7 - Stock market index explained: Sensex, Nifty & how they work

[Chapter link](https://zerodha.com/varsity/chapter/the-stock-markets-index/)

> #### 📌 Terminology
> - **Sensex** — Short form of Sensitive Insex
> - **Nifty** — Short form of National Stock Exchange Fifty

### A simple question: How to understand how the overall market is performing?

There are ~ 5000 listed companies in BSE, ~ 2000 in NSE.<br>
So, it is practically not possible to check and track every company.
Instead, we check a few important companies accross key industrial sectors.

The (weighted) aggregations of these companies share prices are called market indices.

#### Few important indices in India:
- S&P BSE Sensex: Represents BSE
- Nifty 50: Represents NSE
- Nifty Bank Index / Bank Nifty

<br>

>**I would highly recommend to visit this official site from NSE: https://niftyindices.com/ <br>**
>It contains many cool charts and graphs illustrating various indices, their evolutions, sectoral distributions and many more!

## Practical uses of the index

1. Information: <br>
An index reflects the overall sentiment and trend in the market. The index broadly represents the country's state of the economy.

2. Benchmarking: <br>
A yardstick to measure the performance is required for all the trading or investing activity people do.  Assume over the last year, you invested Rs.100,000/- and generated Rs.20,000 return to make your total corpus Rs.120,000/-. How do you think you performed? Well, on the face of it, a 20% return looks great. However, what if Nifty moved to 30% during the same year?<br>
Well, suddenly, it may seem to you that you have underperformed in the market! Usually, the objective of market participants is to outperform the Index. Now, if not for the Index, you can’t figure out how you performed in the stock market. It would be best if you had the index to benchmark the performance.

3. Trading: <br>
Majority of the traders in the market trades on the index.

4. Portfolio hedging: <br>
(To be discussed later. You can check the [site](https://zerodha.com/varsity/chapter/the-stock-markets-index/) if needed.)

## Index computation methodology

Indian stock exchanges follow a **free float market capitalization** method. The weights are assigned based on the company's free-float market capitalization.<Br>

Free-float market capitalization = total no. of shares outstanding in the market × stock price

#### So, what is meant by 'total no. of shares outstanding in the market'?

Let's break this down step by step:
1. **Authorized Shares:** A company is authorized to legally issue certain amount of shares, say, 10,000.
2. **Issued Shares:** No. of shares the company has actually issued, say, 8000.
3. **Treasury Shares:** No. of shares the company has brought back, say 1000.
4. **Outstanding Shares:** Issued shares -  Treasury shares = 7000
5. **Free-float Shares:** Shares available for the public to trade, say, 5000.<br><br>
Outstanding shares may include shares owned by the promoters/governmets/strategic investors/employees/parent companies. So these will not be available for the market to trade. Hence these are not part of the free-float shares.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Market cap. = Stock price × Total outstanding shares <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;But, &nbsp;Free-float market cap. =  Stock price × Total outstanding shares in free-float market

Take an example:

A large percentage of TCS shares is hekld by Tata Sons promoter group. These shares count as outstanding shares because they **exist** and **are owned** by somebody.<br>
**BUT** they do not generally count towards the free-float because they are not regularly available for trading in the market.

### Mini mind-map

```
Authorized Shares: 10,000
└── Issued Shares: 8,000
    ├── Treasury Shares: 1,000
    └── Outstanding Shares: 7,000
        ├── Shares owned by promoters, partners etc.: 2,000
        └── Free Float Shares: 5,000
```