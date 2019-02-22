## End-User Observation
### Persona #1: Juan Fernandez

Juan is a senior at Stern studying finance. He has an investment banking job lined up for when he graduates but likes trading stocks as a hobby and for personal profit.

Juan currently has brokerage accounts at Interactive Brokers, Charles Schwab and Robinhood. Additionally, he has a Coinbase account where he sometimes trades cryptocurrencies.

Juan voices concern over not being able to visualize all his investments in a unique dashboard. He wishes he could perform analysis over all his portofolios combined in order to better understand his financial situation.

Some of the features Juan considers would benefit himself are: 
* asset allocation graphs over assets in all his portofolios
* a graph of the historical returns of:
    * all his portfolios combined
    * each portfolio by itself in order to compare them to each other


## Use Cases

**Title:** Check the list of portfolios

**Actor:** Trader

**Scenario:** Trader requests information on the list of portfolios. System requests most recent information all connected APIs. System displays brief and important information relating to all the portfolios. 



**Title:** Add portfolio

**Actor:** Trader, Application

**Scenario:** Trader requests to add a new portfolio to the dashboard. System requests the specific API for the portfolio. System requests the most updated data and adds the new portfolio and its information.



**Title:** Check one specific portfolio

**Actor:** Trader, Application

**Scenario1:**  Trader requests PNL information. System requests most recent numerical information on profit and losses.
**Scenario2:**  Trader requests allocation graphs. System requests most recent numerical information on allocation of total assets and displays graphical information.
**Scenario3:**  Trader requests data in a table format. System requests most recent data from APIs and displays them in a table format.
**Scenario4:**  Trader requests general account information. System requests and displays account information directly from associated APIs.



**Title:** Compare two different portfolios from dashboard

**Actor:** Trader

**Scenario:** Trader requests two portfolios to be compared. System requests the most recent information on the two portfolios selected from their APIs, displays them in each of the specific methods mentioned above. See "check one specific portfolio".



**Title:** Check summary for a period of time

**Actor:** Trader 

**Scenario:** Trade requests summary PNL for a period of time. System requests information only from selected period of time from all portfolios and compiles them into a visualizable format. 
