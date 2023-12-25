# Uber Trade Manager ReadMe

## About
Uber Trade Manager is a fast and efficient trade execution tool designed to simplify forex trading operations. It allows traders to easily open positions with calculated parameters, manage risk, and streamline their trading processes.

This code sample demonstrates how Uber Trade Manager works by automatically opening positions based on user-clicked chart areas. It calculates lot size, take profit, and stop loss levels based on user-defined risk percentage, reward ratio, and trail stop ratio.

## Global Variables
- **riskPercentage**: The risk percentage per trade.
- **rewardRatio**: The risk-to-reward ratio.
- **trailStopRatio**: The trail stop ratio.

## Functionality
The code uses the following functionality to execute trades:

### OnTick()
- Checks if there are any pending orders. If yes, returns.
- Checks if the user clicked on the chart. If not, returns.
- Gets the coordinates of the clicked object.
- Checks if the user clicked within the chart area. If not, returns.
- Calculates the lot size based on the risk percentage.
- Calculates the take profit and stop loss levels.
- Opens a new position with the calculated parameters.
- Checks if the order was placed successfully. If not, prints an error message.
- Sets a trail stop loss.

### OnDeinit()
- Closes all open positions before shutting down.

## Product Description
Uber Trade Manager is a powerful trade execution tool that simplifies forex trading operations. With its fast and efficient functionality, traders can streamline their trading processes and optimize their results.

Key features of Uber Trade Manager include:
- Automatic trade execution based on user-clicked chart areas.
- Calculation of lot size, take profit, and stop loss levels based on user-defined parameters.
- Risk management tools, including risk percentage per trade and trail stop ratio.
- Simplified forex trading operations for enhanced efficiency and profitability.

Please note that ForexRobotEasy is not the official developer of Uber Trade Manager. We only provide this code as a sample that can work as described in the product. For the official developer and more detailed reviews and trading results of Uber Trade Manager, please visit [this link](https://forexroboteasy.com/forex-robot-review/uber-trade-manager-review-streamline-forex-trading-with-advanced-features/). To obtain the official version of this product, please refer to the MQL5 platform.
