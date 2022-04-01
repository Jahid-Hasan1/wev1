# Clock Auto-Liquidity Engine (CALE)

**Market Liquidity is an important element that plays a vital role in allowing the buy & sell of $C24 tokens on PancakeSwap.**

In simple terms, think of Liquidity as a big pool of money that is split into half (50/50) between **$C24** tokens & $BNB tokens. There is a conversion ratio is set that determinesto the amount of $C24 you can get with BNB, for example: 1 BNB = 18.1 **C24**.

When someone buys **C24**, the price per Clock24 appreciates and the ratio above will also change accordingly to account for this. The same is applicable in the opposite direction for sells.

Liquidity allows everyone to buy & sell their C24/BNB at anytime, however, if there is a liquidity constraint in the pool, you might get bad prices. To counter this, what our C24 Auto-Liquidity Engine (SALE) does is, to add more liquidity to that pool by itself and eventually solving that issue.

**Here is how the C24 Auto-Liquidity Engine (CALE) works:**

After every 24 hours our C24 Auto-Liquidity Engine (CALE) will inject automatic liquidity into the market. On each buy or sell order there is a **2.5% tax fee** that will automatically gets stored into an Auto-LP wallet and built into our protocol's smart contract, the is the mechanism which smartly takes the 50% of the amount of C24 stored in the wallet, and will **automatically** buy BNB at the current market price.

The remaining 50% of **C24** in the Auto-LP wallet will be used for the **Clock24** side of liquidity, therefore giving equal an 50/50 weighting of C24/BNB which will then be **automatically** added as new, additional liquidity into the market pair and raising the amount of liquidity in the pool.

The CALE will do this **every 24 hours;** by constantly adding liquidity to the pool which will, in turn, allow **$C24** token holders to sell their tokens easily, at anytime with minimum to no market slippage. It will also aid in **maintaining protocol stability** to make sure the APY is sustained for the entire life of C24.
