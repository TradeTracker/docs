# Release notes

Since we have started our open beta program, we'd also like to show which features have been implemented lately.
If you want to request a feature, please shoot us a message on [Discord](https://dddheff.r.af.d.sendibt2.com/tr/cl/UT8I96hC9DLmYRMx9QF3i1KZk4h1nKvmFtwV73SeaIsysSV477-4TAosep86UbCUB0v7GhSTMNP_1I4EqOFuoEb8T_gTV0VgOCbBlMkuz7LxK4lJbFgaW7iPPulNf2UVovjHVmlqbEdSwH_elkqdpRjcA447txiVMOqHR9W27Udoxp2IlopdD5A5giQ3FYuqJ02kk6wRhQ), or create an issue on [GitHub](https://github.com/TradeTracker/issues). We'd love to have your feedback, and ideas!

## 2022-04-16

 * Trade setup page now displays the sum of the fees paid for the entries and exits.
 * Unrealized profit that is negative is now displayed in red on the dashboard.

## 2022-03-28

 * Updated the charts in light theme.
 * Really fixed the bug with theme switching.
 * (Experimental) Added chart for PNL% vs. Holding time (in days).
 * (Experimental) Added expected risk vs. actual risk.

## 2022-03-17

 * Launched a new website: https://www.tradetracker.app.

## 2022-03-13

 * Added 7-day sum and 30-day sum to the daily bar charts on the dashboard.
 * Fixed a bug with the theme switcher.

## 2022-02-28

 * Improved a few animations.
 * Improved the demo data generator with meaningful tags and a fixed a bug in it.
 * New portfolio now uses the quick setup page to create a portfolio.
 * Quick setup page displays a warning if Binance is used without USDT or BTC.

## 2022-02-27

 * Added an improvement for tags. All tags are now displayed in the tag section!

## 2022-02-19
 
  * Updated to .NET 6.0.
  * Minor UI change on the Risk/Reward page.
  * Fixed issue where the fees did not display on the risk/reward page.

## 2021-11-28

 * Added functionality to export all the trades in a portfolio as a CSV file.
 * Added the possibility to edit the date created on a trade.
 * Fixed some issues with the CI/CD pipeline.
 * Added Google Analytics to measure engagement.

## 2021-05-17

 * Added a logout button to the main navigation.

## 2021-05-14

 * Resolved an issue where Bitfinex is using a legacy format if a symbol is longer than 3 characters. Symbols like `DOGEUSD` should now work properly.

## 2021-05-13

 * Adjusted the cumulative PNL percentage charts calculation.
 * Added average risk percentage to the dashboard.
 * Minor code cleaning.

## 2021-03-31

 * Fixed an issue where the last day is plotted inconsistently in the daily charts.
 * Fixed an issue where the fees weren't included in calculating the PNL and risk for open positions.
 * Fixed an issue where an order could be added to an already closed trade.
 * Clamped risk between 0 and the account balance, such that the risk never exceeds 100%.
 * If no stop loss is entered, the risk is the position value.
 * Fixed an issue where the drawdown is calculated incorrectly.

## 2021-03-30

 * Added a risk of loss chart to the risk/reward page.
 * Minor changes in decimal formatting for charts.
 * Fixed a bug where the drawdown was calculated incorrectly.
 * Fixed a bug where the total return on investment (%) was calculated incorrectly.

## 2021-03-25

 * Added a quick setup page to quickly setup a portfolio and a first deposit.
 * Restyled the goal page.
 * User can now set a password when registering.
 * Tags now pop up with a cool animation.
 * Fade-in effect is set a little bit slower.
 * No longer possible to open trade from a different portfolio.

## 2021-03-24

 * Rewrote the getting started section on [docs.tradetracker.app](https://docs.tradetracker.app).
 * Trade set up page will now display the fees for each order, and also the total paid fee.
 * Added more metrics to the dashboard.
 * Minor changes to the design of various dashboard elements.
 * Fixed the error when a user doesn't fill the form on the login page.
 * Added a tags analysis chart to the dashboard.

## 2021-03-23

 * Added a note field to the trade set-up page.
 * Added a TradingView chart URL field to the trade set-up page.
 * Added functionality to add and remove tags on the trade set-up page.
 * Open your added TradingView chart directly from the trades and risk/reward page.
 * Removed the open trade button. If you now click on the row, the trade will open.
 * Functionality to delete a trade from the risk/reward page.
 * Demo data generator will also generate a random tag.
 * All open positions are now displayed on the trades page, with live ticker updates.
 * Added pagination to the trade and risk reward pages.
 * Minor bug fixes.

## 2021-03-22

 * Added live ticker support for the following exchanges: Bitmex, Coinbase (USD, EUR, BTC), Huobi, Bittrex, KuCoin, and Poloniex.
 * Added a small message in the footer that refers to Discord, and GitHub.

