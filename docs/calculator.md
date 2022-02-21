# Position size calculator
Have you ever asked yourself what your position size should be if you have an entry, stoploss, and a maximum amount of risk you want to take?

## Calculator
|Our position size calculator will answer that question for you. If you have created a trade plan and have an entry, target, and stop loss, your optimal position size will be calculated automatically based on how much risk you are willing to take.|![Position size calculator](calculator.PNG)|

### Variables
Our calculator has the following variables that you can change:

|Variable|Description|
|--|--|
|Direction|The direction of the trade, either `LONG` or `SHORT`.|
|Fees|Includes fee calculations and subtract these from the position size. The percentage is retrieved from the defined fee in the portfolio.|
|Risk per trade %|Percentage of balance that is lost when the stop loss is hit, and the order is sold.|
|Entry price|Price at which the position is purchased.|
|Stop loss|Price at which the position should be exited.|
|Target|Price at which you intent to sell your position.|


### Calculations
Based on the provided variables, the following values are calculated:

|Variable|Description|
|--|--|
|Target %|How high your target price is in percentages based on your entry price.|
|Stop loss%| How low your stop loss price is in percentages based on your entry price.|
|Value at risk| How much of your balance is at risk if your stop loss is hit.|
|Entry fee|Total fee that is paid for entering the position.|
|Exit fee|Total fee that is paid for exiting your position with a stop loss. Fee calculated with a market order.|
|Order cost|How much your order will cost, including fees.|
|Order value|The value of your order, without fees.|

We hope that our calculator will help you manage your risk and trade profitable!
