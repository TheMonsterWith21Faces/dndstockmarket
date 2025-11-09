# D&D Stock Market

A simple stock market I created for my D&D world. Why? I don't know, it was just a stupid idea that got stuck in my head one day.

DM Dashboard
Open the html file to go to the DM dashboard. This page allows you to advance to the next day of in-world trading, reset your world back to day 1, import or export a JSON file with market history and company data, and open news and edit screens.

News Screen
This is your player-facing section. It will detail your market's top gainers and losers over the last 24 hours, give news updates, and show graphs of your biggest gains/losses.

Edit Screen
On this screen you can manually override company info, enter new companies, and export a new JSON file. Here's how to add or edit a new company:
ID - this field is just a behind-the-scenes identifier for each company. it can be whatever.
Symbol - your four-character symbol for your company. just as Apple is AAPL in real life, your necromancy company may be NCRO.
Name - name of the company
Static valuation - this is a where it gets a little more complicated. this is a secret value that is the true amount this company's shares are worth. If it is 50 and the company is currently trading for 75 then the market is going to subtly correct itself over time and the stock will slowly edge toward 50. It can still go below 50 and could be subject to catastrophes and windfalls (more on that in a minute), but it will orbit toward 50. 
Current price - what players can currently buy it for
Vol Tier - Volatility Tier, Tier 1 companies are predictable, stable, established. Tier 2 companies are semi-stable but do experience more fluctuation in price than a tier 1 company. Tier 3 companies are very unstable and their prices are subject to heavy market volatility.
Cat/wind Mod - Catastrophe and Windfall Mod. Any value higher than 1 makes it more likely they will experience one of these conditions. you may be thinking "isn't this a lot like volatility tier" to which I would say, shut up.
Gravity mod - This is your gravity modifier. Gravity, in this case, is how aggressively prices try to catch up to their static valuation. If a valuation is 50 and a stock is at 100, then a gravity mod of 1 might see the stock drop by 7% trying to slowly normalize. if gravity is at 10 then you might see a drop of 44%, very quickly correcting itself.
Listed - this just dictates whether or not this stock is listed and can be purchased.

RNG will fill in the nubmers for you.

Catastrophes and Windfalls - these are random, rare events that happen to companies where they experience a huge gain or loss in their stock price due to either a shortage, scandal, boom in popularity, etc. 

Using in your adventure

Use the edit tool to create companies. Once you've created your companies make sure you export your JSON file. keep it safe. Go to the DM screen and import the JSON file and you'll see your companies populate. Once you're playing make sure to press the "Advance Market Day" button every time a day passes in the players' world. Even if the players arent interacting with it, the market is always moving.

[https://themonsterwith21faces.github.io/dndstockmarket/
](https://themonsterwith21faces.github.io/dndstockmarket/)



