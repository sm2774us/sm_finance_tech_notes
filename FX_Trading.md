# FX Trading Basics

Foreign exchange is a business of exchanging one currency for another. This exchange can take two basic forms: an **outright** or a **swap**. 
When two parties simply exchange one currency for another the transaction is an **outright**. 
For example, if one party gives the other dollars for Euros, they have completed an _**outright**_ transaction. 
If this exchange takes place for immediate delivery, it is called a _**spot**_ transaction; if it takes place for forward delivery, it is called a _**forward**_.

Two parties can also agree to exchange and re-exchange one currency for another. For example, one party gives the other dollars for Euros for immediate delivery 
and simultaneously agrees to re-exchange Euros for dollars at a specified rate at some time in the future.
These transactions are called _**swaps**_.

## FX Spot

### WHAT IS AN OUTRIGHT?

An outright currency transaction involves two parties exchanging one currency for another.
The two parties must agree on the two currencies, the amount of one currency, the settlement date, and the exchange rate.
The amount of the second currency will be derived from a calculation involving the amount of the first currency and the exchange rate.

- __Outright rate of exchange/ spot:__ The amount of one unit of currency expressed in terms of the other.
- __Outright Transaction:__  The exchange of one currency for the other at the outright rate of exchange.

### VALUE DATES

The value date is the day the two parties actually exchange the two currencies. 
It is impractical, in most circumstances, for the value date and the trade date to be the same.
The forward value date is usually required to allow both parties time to arrange for payments which often occur in different time zones.

By market convention, foreign exchange trades settle two mutual business days (T + 2) after that trade date unless otherwise specified.
This is commonly referred to as value for spot. The spot exchange rate is the benchmark price the market uses to express the underlying value of the currency.
Rates for dates other than the spot are always calculated relative to the spot rate. 

Listed below are the various value dates available in the market-they are all determined relative to the deal date.
__Assume the deal date is Monday, December 12.__

| **Settlement**        | **Settlement/Value Date** | **Definition**                                                       |
| --------------------- | ------------------------- | -------------------------------------------------------------------- |
| Cash                  | December 12               | Deal Date                                                            |
| Value "Tomorrow Next" | December 13               | One Mutual Business Day after Deal Date#                             |
| Spot                  | December 14               | Two Mutual Business Day after Deal Date++                            |
| Forward Outright      | December 15 or later      | Threw Business Days or More After Deal Date; Always Longer than Spot |


`# The Settlement Date May Not Fall on a Day That is a National Holiday in Either Country.`

`++ Exception: Spot for the Canadian Dollar Against the USD is One Business Day Later. Assuming Today is Monday, December 12, Spot Would be December 13.`

#### QUESTIONS

Using the trader's calendar below, indicate the date on which each of these trades would settle. Assume you are at a New York bank dealing in currencies against the US dollar. Today is December 4th.

![FX_Trading_Calendar_Dec_2002](./assets/FX_Trading_Calendar_Dec_2002.png)

1. You do a trade in CAD for cash settlement => December 4
2. You do a spot CAD trade => December 5
3. You do a GBP trade for value tomorrow => December 5 
4. You do a spot GBP trade => December 6
5. You do a spot CHF trade => December 6

### CREDIT AND SETTLEMENT RISKS

Foreign Exchange contracts represent a Credit Risk between Lehman and the client. The risk is equal to the replacement cost of any deal in the event that the client cannot fulfill its obligations. For spot transactions, the exposure is for only the two days between the trade date and the value date. However, for forward contracts the exposure is greater because the time between the trade date and the value date is greater. For example, if Lehman contracted to buy USD/sell EUR one year forward at 1.0425 and the current forward rate is 1.0845, Lehman has a gain of over 4% of the face value of the contract. If the client cannot fulfill the contract, Lehman must replace the forward at the rate currently available and, therefore, stands to lose the 4% mark-to-market gain. Since the bank reports mark-to-market gains as income, client nonperformance has bottom line implications.

_Settlement Risk_ is another form of credit risk which can potentially be much greater. Each currency deal actually involves two settlements, since each currency settles in its home country. Since the exchange of currencies cannot be simultaneous due to time differences, each party is at risk for the time period between the two settlements. For example, assume you have sold JPY against the USD. The JPY will settle in Japan-your JPY account will be debited and the JPY delivered to the bank of the buyer-hours before your dollar account in New York is credited. Your risk is that you deliver JPY to the Japanese clearing, but the bank which owes you dollars in return for your JPY declares bankruptcy by the opening of business in NY. You have paid out the JPY but will not receive your dollars in exchange.

### EXCHANGE RATE QUOTATION TERMS

* The major currency pairs can be quoted in either European or Ameerican terms.
* Those that quote in number of US dollars per one unit of another currency is American. An example of this is EUR/USD which is quoted as the number of USD per one Euro.
* A currency quoted as the number of units of a specific currency per one USD is quoted in American terms. An example of this would be dollar-yen, which is quoted in yen per one USD. When rates are spoken the base currency comes first. It is imperative that you remember these conventions!

| **American Terms**         | **European Terms**         | **Other Major Cross Rates** |
| -------------------------- | -------------------------- | --------------------------- |
| EUR/USD - "Euro-Dollar"    | USD/JPY - "Dollar-Yen"     | EUR/NOK - "Euro-Nockie"     |
| AUD/USD - "Aussid-Dollar"  | USD/CAD - "Dollar-Cad"##   | EUR/SEK - "Euro-Stockie"    |
| NZD/USD - "Kiwi-Dollar"    | USD/CHF - "Dollar-Swiss"$  | USD/MEX - "Dollar-Mex"      |
| GBP/USD - "Sterling,Cable" | USD/SEK - "Dollar-Stockie" | USD/ZAR - "Dollar-Rand"     |
|                            | USD/NOK - "Dollar-Nockie"  | GBP/JPY - "Sterling-Yen"    |
|                            |                            | EUR/GBP - "Euro-Sterling"   |

The arithmetic way to express these quotations will always have the base currency in the denominator and the rates currency in the numerator. 
Do not allow this representation to confuse you when actually saying the currency pairs. This is simply how they would look mathematically. Examples are USD /EUR and JPY /USD being the nomenclature for arithmetic expression of Dollars per Euro and JPY per USD, respectively. The following will illuminate this point.

Since two currencies are involved, one has to be quoted in terms of the other. When we say that the exchange rate for the yen against the dollar is 123.50 yen,
we are valuing the dollar in terms of the yen-123.50 yen per dollar. The arithmetic expression tells you which currency is being quoted in terms of the yen.
In the case of the USD /EUR, the EUR is being quoted in terms of the USD.

The way the two currencies are referred to verbally will usually tell you which one is the base, since the base currency is usually stated first.
For example, when the two currencies involved are the US dollar and the yen, the relationship is called dollar-yen-meaning the number of yen per dollar.
This tells you that the dollar is the base and that the rate will be quoted in terms of yen per dollar.

> **Do not let the terminology confuse you; a "dollar-yen" rate is quoted as Yen per USD.**
> 

`##Also Known as the 'Loon'.`

`$ Sometimes Known as the 'Fondue Franc'`

* The currency in the numerator always states how much of that currency is required for one unit of the base currency.

  - U.S. terms: the dollar is in the numerator; for example, USD /GBP--giving the units of dollar per pound.
  - European Terms: the non-dollar currency is in the numerator; for example, JPY /USD, giving the units of yen per dollar.

    >            Numerator      Terms Currency
    >          ------------- = -----------------
    >           Denominator      Base Currency
    > 

#### QUESTIONS

* In many cases, you will see only the terms account; it is assumed you know the base. For example, if you see JPY124.25 you know that this means 124.25 Yen per $1.
 
1. GBP 1.5541: base <u>Sterling</u>: quoted in <u>US</u> terms.
2. CAD 1.5476: base <u>USD</u>: quoted in <u>European</u> terms.
3. AUD 0.5565: <u>AUD</u>: quoted in <u>US</u> terms.
4. EUR 1.0500: <u>EUR</u>: quoted in <u>US</u> terms. 

### RECIPROCAL QUOTATION TERMS (RATES)

* The method of quotation can be changed from US to European terms, or vice versa, simply by calculating the reciprocal of the rate. For example, Canadian dollars are usually quoted in European terms, that is, the number of Canadian dollars per one US dollar.

                   CAD/USD = 1.5672
                   
* However, at least for Canadian banks, you sometimes see it quoted in US terms. That is, the number of USD per CAD.
  
  To take the reciprocal: 
  
   >       1 / 1.5672    = 0.6381   =
   >         0.6381 USD per 1 CAD
   >

### EXCHANGE RATE MOVEMENTS

* The exchange rate is constantly changing, which means the value of one currency in terms of the other is in constant flux. When this relationship changes, the market speaks of one currency as strengthening or weakening vis-a-vis the second currency. For example, if the dollar strengthens, by definition, the other currency must have weakened.
* Whenever the base currency buys more of the terms currency or whenever there is an increase in the numerator, the base currency has strengthened and the terms currency has weakened. For example, if dollar-yen opened at 124.10 and closed at 124.60, you would say that the dollar strengthened since one dollar buys more yen at the close than it did at the open. In this case, the dollar closed higher or "up."
* Based on their outlook on a currency, traders will often take positions in that currency, buying it if they think it will strengthen and selling it if they think it will weaken.
  * Assume an FX trader bought one million dollar's worth of Swiss Francs at 1.4996 at the open because she thought Francs would strengthen over that day.
    However, her outlook for the day was wrong, and when she closed out her position by buying back the dollars at 1.5040 she experienced a $2,925.53 (CHF4,400) loss. 
    
     CHF loss:
     >           -$1,000,000.00  =  +CHF1,499,600 @ 1.4996
     >
     >           +$1.000.000.00  =  -CHF1.504.000 @ 1.5040
     >
     >           --------------     -----------------------
     >
     >                 -0-          -CHF4,400
     >
     >

  * The Swiss loss can then be converted into a dollar loss by dividing the Swiss loss by the ending exchange rate.
  
     > CHF 4400 / 1.5040 = $2925.53
     >


#### QUESTIONS

* Based on the rates given below, decide which currency strengthened and which one weakened, whether it closed up or down, and your profit/loss based on the position you took at the open.

_Remember: When the rate increases, the base strengthens, and the terms weakens._

Q1. Sterling opens at 1.5409 and closes at 1.5425.
The Dollar ______ and the Pound ______. Therefore, the Dollar closed (up/down) for the day, relative to the GBP. If you sold 1MM GBP and bought USD at the open and the reversed the trade at the close, your (profit/loss) would be ______ (currency and amount).

A1. The Dollar <u>weakened</u> and the Pound <u>strengthened</u>, since one Pound will buy more Dollars. The Dollar closed down for the day. You had a <u>loss</u> of </u>£1,037.28 or $1,600</u>.

```
    -£1,000,000 = +$1,540,900 @ 1.5409        -£1,000,000 @ 1.5409 = +$1,540,900

      +£998.963 = -$1,540,900 @ 1.5425        +£1,000,000 @ 1.5425 = -$1,542,500

    ----------------------------------        -----------------------------------

        -£1,037 =      0                             0             =     -$1,600
```

Q2. Dollar-Yen opens at 124.05 and closes at 123.50.
The Dollar ______ and the Yen ______.  Therefore, the Yen closed (up/ down) for the day, relative to the USD. If you sold USD 1MM at the open 
and reversed the position at the close, your (profit/loss) would be ______.

A2. The Dollar <u>weakened</u> and the <u>Yen</u> strengthened, since one Dollar will buy fewer Yen. The Yen closed up for the day. You had a <u>profit</u> of <u>¥550,000 or $4,453</u>.

```
   -$1,000,000 = +¥124,050,000 @ 124.05       -$1,000,000 @ 124.05 = +¥124,050,000

   +$1,004,453 = -¥124,050,000 @ 123.50       +$1,000,000 @ 123.50 = -¥123,500,000

   ----------------------------------        --------------------------------------

       +$4,453 =      0                             0             =      +¥550,000
``` 

Q3. CHF/USD opens at 1.5030 and closes at 1.5035.
The USD ______ and the Swiss Franc ______. Therefore, the Dollar closed (up/ down) for the day, relative to the CHF. If you sold CHF 10MM at the open 
and bought them back at the close, your (profit/loss) would be ______. 

A3. The Dollar <u>strengthened</u> and the <u>Swissie</u> weakened since one Dollar will buy more Swissie. The Dollar closed up for the day. You had a <u>profit</u> of <u>CHF3,327 or $2,213</u>.

```
    -CHF10,000,000 = +$6,653,360 @ 1.5030        -CHF10,000,000 @ 1.5030 = +$6,653,360 @ 1.5030

    +CHF10,003,327 = +$6,653,360 @ 1.5035        +CHF10,000,000 @ 1.5035 = +$6,651,147 @ 1.5035

    -------------------------------------        ----------------------------------------------

         +CHF3,327 =      0                             0                = +$2,213
```


_In the problems above we saw the following market moves:_

|            | **Open**   | **Close** |
| ---------- | ---------- | --------- |
| GBP/USD    | 1.5409     | 1.5425    |
| JPY/USD    | 124.05     | 123.50    |
| CHF/USD    | 1.5030     | 1.5035    |

* Dealers refer to small moves as pips. For example, in the case of USD/GBP, Sterling moved 16 pips whereas in the case of the USD /JPY, the market moved 55 pips. One hundred pips is a "point" or a "big figure". Note that pips or points can be a different decimal place depending on the quoting convention of the market. In the Sterling market, one pip is 0.0001 but in the Yen market, one pip is 0.01.

### SHORTCUT

On the preceding page, you calculated the profit and loss due to a change in the rates. There is a shortcut method to calculating these gains and losses.

   > Base currency gain/loss = % change * base amount
   > 

   Where % change = (pip change/ closing rate)

   > Terms currency gain/loss = pip change * base amount
   >
   
   * Example: In the Sterling case, the opening rate was 1.5409, the closing rate was 1.5425, for a 16 pip change.
     * Base gain/loss £1,037
     * Terms gain/loss = $1,600
     *
   * Note: It is mathematically equivalent (and possibly more understandable) to fmd the Base gain/loss by multiplying 
     the pip change by the notional and dividing that figure by the closing exchange rate [(0.0016 * 1,000,000) /  1.5425]. Since the exchange rate 
     is measured in Dollar terms, the pip change is the Dollar gain/loss. Multiply that dollar gain/loss by the notional to get the total USD gain/loss.
     Divide that gain/loss by the closing rate to get the amount of Sterling that equates to.

#### QUESTIONS

Using the shortcut method, re-calculate the following gains or losses. 

Q1. JPY /USD opens at 124.11 and closes at 123.80; you bought one million dollar's worth of Yen on the open and sold it on the close.

A1. Base currency gain  = .31 / 123.80 * $1,000,000 =     $2,504
    Terms currency gain = .31 * $1,000,000          = JPY310,000

Q2. CHF /USD opens at 1.5000 and closes at 1.5035; you sold 1,000,000 USD at the open and bought it back at the close.

A2. Base currency loss = .0035/1.5035 * $1,000,000 =   ($2,328)
    Terms currency loss = .0035 * $1,000,000       = (CHF3,500)
    
### BIDS AND OFFERS 

X!hen making a market in a currency, market-makers (traders) quote two rates: Bid Rate at \X!hich Market Maker Will Buy the Base Currency Offer Rate at \X!hich Market Maker Will Sell the Base Currenc The difference between the bid and the offer is called the spread. USD/GBP = JPY/USD = 1.5464/74, so the spread is 0.0010 USD/GBP. 123.50/123.60, so the spread is 0.10 JPY /USD. The market may move 10 pips, with the new quote being 1.5474/84, but the spread remains the same under normal market conditions. Also, note that although the spread in both markets above is 10 pips, the value of 10 pips in the USD /GBP is different from the value if the 10 pips in the JPY /USD market. However, in the market, spreads are generally comparable between currencies on a percentage basis. In general, greater uncertainty among traders is reflected in wider spreads in the market. The size of the spread reflects: o The liquidiry of that currency-the more liquid the currency, the narrower the spread. o The size of the deal-the bigger the transaction, the wider the spread because the dealer is taking on more risk. o The time of the day-spreads tend to be widest in the New York afternoon because both Europe and Asia are closed or during the Asian lunchtime. 16 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356499 

### THE RULE OF THE LEFT BID -RIGHT OFFER 

Market makers always trade the base currency. They buy the base currency on the left side of the quote and sell the base currency on the right side of the quote. Example I: If a market maker quotes Sterling at 1.5460/70, he will buy Sterling at $1.5460 per pound and sell Sterling at $1.5670 per pound. This means you can buy Sterling at 1.5470 (offer) and sell it at 1.5460 (bid). Example II: If a market-maker quotes the dollar against the CHF at 1.5044/50, he will buy the dollars at 1.5044 CHF per dollar but sell them for 1.5050 CHF per dollar. This mean you can buy them at 1.5050 CHF per dollar and sell them at 1.5044. To be sure about what side of the market you are dealing on, alwqys think in terms of the base currency. This means every transaction can be thought of in terms of these rules: 1. Determine what the market-maker is quoting as the base currency. 2. Determine what you need to do in terms of the base currency. 3. Remember that the market-maker buys the base on the left and sells it on the right. In Example I, the market-maker is quoting the dollar as the base. You have the USD and need the CHF, so you must sell the USD and buy the CHF. You deal on the market-maker's bid Oeft). In Example II, the market-maker is quoting the Sterling as the base. You have the USD and want the Sterling, so you must buy the Sterling. The market-maker will sell them to you at the offered (right) side of the market.

#### QUESTIONS

CONFIDENTIAL TREATMENT REQUESTED BY BARCLAYS SOURCE: LEHMAN LIVE QUESTIONS On which rate would you deal in each of the problems below? 1. You have just received a 1,000,000 GBP payment. You want to convert these pounds into dollars. You get a quote of 1.5457/61. 2. You have to buy Australian dollars to make a large payment. The quote is .5535/37. 3. You need to make a SEK payment. You get a quote of9.3854/9.3934. 4. You have received a large JPY denominated dividend which you want to convert into dollars. The quote is 123.19/23. 18 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356501 


1.5457 USD/GBP The base currency is GBP. You want to sell GBP and buy USD. You will deal on the bid (left) side of the market; that is where the trader is buying the GBP from you. 2 . .5537 USD/AUD The base currency is the AUD. You want to buy AUD. You will deal on the offered (right) side of the market; that is where the trader is  selling the AUD to you. 3. 9.3854 SEK/USD The base currency is the US$. You need to buy SEK to make the payment and sell USD. You will deal on the bid (left) side of the market; that is there the trader is  selling SEK and buying USD from you. 4. 123.23 JPY /USD The base currency is the USD. You want to sell JPY and buy USD. You will deal on the offered (right) side of the market; that is where the trader is selling USD. 19 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356502 

#### QUESTIONS

### CROSS RATES

So far, the exchange rates we have examined have involved the dollar as either the base or the terms currency. However, the dollar is not always involved. \X!hen people talk about the price of one foreign currency in terms of another and neither of the currencies is the dollar, it is called a cross rate. • • "Euro-yen" is a classic, widely traded cross-rate whose price movements reflect the market's view on the Euro and the yen against various currencies. "Euro-yen" is a cross rate between the EUR/JPY. Most commonly, traders derive cross rates using the two rates versus the USD because those two rates are known. We will look first at how to derive them algebraically and then at a shortcut rule. With cross rates, it is crucial to remember the base currency conventions. Same terms (both are quoted in either US or European terms): Example: • Assume you want the CHF /JPY cross; that is, the number ofJPY for 1 CHF . • • • • • • 1.5029 CHF =  1 USD 125.22 JPY =  1 USD Therefore, CHF = 125.22 JPY 1 CHF = 125.22/1.5029 1CHF =  83.3189 JPY CHF /JPY =  83.3189 The shortcut rule is: If two currencies are quoted against the $ on the same terms, divide the base currency into the terms currency of the cross currency pa1r. Difforent terms (one currenry is quoted in US terms and the other in European terms). For example: • Assume you want the GBP /JPY cross rate; i.e., the number ofJPY per 1 GBP . • 125.06 JPY =  1 USD • 1 GBP = 1.5467 USD • Therefore, 1GBP = 125.06 GBP * $1.5467 = 193.4303 • GBP /JPY= 193.4303 22 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356505 


The short cut rule is: If two currencies are quoted on diffirent terms, multipfy one rate by the other. 23 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. SOURCE: LEHMAN LIVE LBEX-LL 3356506 


#### QUESTIONS

Calculate the cross rates for the following currencies: 1. EUR/SEK 0.9772 EUR/USD 9.3622 USD/SEK 2. EUR/GBP 0.9772 EUR/USD 1.5465 USD/GBP 3. AUD/NZD 0.5535 USD I AUD 0.4841 USD /NZD 24 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. SOURCE: LEHMAN LIVE LBEX-LL 3356507 

ANSWERS 1. 9.1487 EUR/SEK 2. 0.6318 EUR/GBP 3. 1.1433 AUD/NZD **Remember the shortcut rules: If two currencies are quoted in the same terms, divide the base currency of the cross currency pair into the terms currency of the pair. If two currencies are quoted in different terms, multip!J one rate by the other. 25 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. SOURCE: LEHMAN LIVE LBEX-LL 3356508 


### BID-OFFER FOR THE CROSS RATES OF CURRENCIES ON SAME TERMS

So far we have ignored bid/offer spreads in calculating cross rates. The same rules apply--divide by the base rate for currencies in the same terms and multiply the rates for those in different terms-but now you have to figure out when to use the bid and when to use the offer of the first two currencies to create the bid/ offer of the cross. Example: • • • Assume you are the market-maker, and you want to derive the cross-rate market for CHF /JPY. First, always determine the base of the new cross. In this cross, the Swiss Franc is the base and the yen is the terms currency. Now work with what you know. Since CHF is the base, you know that 1) the currency being traded is the CHF, so 2) the bid and offer of the cross are for CHF. You also know the value of CHF and JPY relative to the dollar. You will use this information to derive the value of the CHF in terms of the JPY. To get the bid side of the cross, bZ!J the base and sell the terms of the cross. To get the JPY per CHF bid, you buy the CHF and sell JPY. 1. Buy CHF. As the market maker dealing in base currencies, to buy CHF you sell dollars on your offer at 1.5031. 2. Sell JPY. Again as the trader, when sellingJPY, you buy dollars on your bid of125.06. 3. You want to know the value of 1 CHF in terms of JPY. Since CHF and JPY are both in European terms, you divide the base of the cross into the terms of the cross to get the cross rate-CHF expressed in terms of JPY. The bid for JPY /CHF: 125.06 1.5031 Sell Terms OPY) I Buy USD Buy Base   (CHF) I Sell USD 83.2013 JPY /CHF bid 26 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356509 

To get the offered side of the cross, sell the base and buy the terms . 1. Sell CHF. From your perspective, you buy USD on your bid of 1.5026. 2. Buy JPY. To buy JPY, you sell USD on the offer of 125.09. 3. You want to know the value of 1CHF in terms ofJPY. The offer for JPY ICHF: • • 125.09 1.5026 BuyJPY I Sell USD Sell CHF I Buy USD 83.2490 JPY I CHF offer To simplify, always remember what to do with the base currency of the cross-then do the opposite with the terms currency. Bid bZ!J base of the cross against the dollar Offir sell base of the cross against the dollar Another way to simplify is to think of presenting the Bid-Ask spread in the most favorable terms for the market maker. This is done by making the spread as wide as possible. So, If you are calculating a spread of currencies on the same terms, i.e. dividing, you would make the widest spread by dividing the larger number by the smaller number and the smaller number by the larger number. Doing so makes minimizes the bid and maximizes the offer. In our example this is done by dividing 125.06 by 1.5031 and 125.09 by 1.5026. Similarly, for currencies on different terms, where one multiplies the currencies to get the cross rate, one minimizes the bid by multiplying both of the smaller numbers against each other and both of the larger numbers against each other. We will see this is the next example. EXCHANGE RATE MOVEMENT REVISITED FOR CROSSES Cross rates also move such that one currency strengthens or weakens vis-a-vis the other one. As with dollar-based currencies, it is easier to conceptualize when you think of cross rate moves in terms of the base. For example, if "Swiss-yen" moves from 83.24 to 83.50, the Swiss Franc has strengthened since one Swiss Franc buys more yen. Similarly, a move from 83.24 to 83.00 is a weaker CHF I stronger JPY rate. 27 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 335651 0 

### BID-OFFER FOR CROSS RATES OF CURRENCIES ON DIFFERENT TERMS

The procedure for finding cross rate bid-offer spread for currencies in different terms is exactly the same except you multipfy the two rates rather than divide. Example: • Assume you want to determine the bid/offer cross rate ofEUR/CHF or "Euro-Swiss." Within the cross, Euro is the base currency and the CHF is the terms currency. USD/CHF • Bid of the Cross: buy the base and sell the terms of the cross . 1. Buy EUR. As the trader you buy the EUR on your bid of .9791. 2. Sell CHF. As the trader you sell CHF and buy USD on your bid of 1.4984. 3. Multiply the two rates and get the cross-rate bid. 1 EUR = $0.9791 * 1.4984 CHF EUR/CHF = 1.4671 • Offer of the Cross: sell the base and buy the terms . 1. Sell EUR. As the trader you sell the euro on your offer of .9796. 2. Buy CHF. As the trader you buy CHF and sell USD on your offer of 1.4991. 3. Multiply the two rates and get the cross-rate offer. 1 EUR = $0.9796 * 1.4991 CHF EUR/CHF = 1.4685 Note: Unlike currencies on the same terms where you use the bid of the terms and the offer of the base currency to get the bid of the cross, there is no "cross-over" for the currencies on different terms: Bid of base * bid of terms = bid of cross Offer of base * offer of terms = offer of cross 28 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356511 


### SUMMARY DIFFERENT TERMS

Bid: buy the base currency and sell the terms, multip!J the two rates to get the cross. Offer: sell the base currency and buy the terms, multip!J the two rates to get the cross. SAME TERMS Bid: buy the base and sell the terms, divide by the base of the cross. Offer: sell the base and buy the terms, divide by the base of the cross. 29 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356512 

#### QUESTIONS

Determine the bid/ offer cross rates. 1. What is the NOK/EUR cross? 2. What is the JPY /CAD rate? 30 Confidential Treatment Requested By Lehman Brothers Holdings, Inc. LBEX-LL 3356513 
