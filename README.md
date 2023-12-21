# Price Action Toolkit

This is a code sample for the Price Action Toolkit, a professional forex trading tool developed by the Forex Robot Easy Team. This code is provided as an example and is not the official code for the product. To find the official developer of this product, please use MQL5.

## Description

The Price Action Toolkit is a forex trading tool that utilizes price action patterns to identify potential trading opportunities. It includes functionalities such as risk-based entry, lot size calculation, stop loss management, candlestick pattern identification, fast trade execution buttons, and position management.

## Developer's Site

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/price-action-toolkit-a-professional-forex-traders-review-and-download-of-the-ea-for-scalpers/).

## Installation

To use the Price Action Toolkit, you need to include the necessary libraries: `Trade.mqh` and `Pattern.mqh`. These libraries provide the required functions and classes for trading and pattern identification.

## Global Variables

- `RiskPercentage`: Percentage risk of account
- `StopLossDistance`: Distance to the stop loss
- `FastButtonX`: X coordinate of fast trade execution buttons
- `FastButtonY`: Y coordinate of fast trade execution buttons

## Initialization

The `OnInit` function initializes the trading tool by enabling risk-based entry functionality, calculating the lot size based on risk and stop loss distance, displaying trade information, identifying candlestick patterns on the chart, and adding fast trade execution buttons on the chart.

## Start

The `OnStart` function is called when the trading tool starts. It includes functions to move the stop loss to breakeven, place buy and sell stops, close out the most profitable position, and display the current profit/loss.

## Deinitialization

The `OnDeinit` function is called when the trading tool is deinitialized. It cleans up and releases resources used by the trading tool.

**Note:** This code is provided as a sample and may require modification and customization to fit specific trading strategies and preferences.

For more information and detailed reviews of the Price Action Toolkit, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/price-action-toolkit-a-professional-forex-traders-review-and-download-of-the-ea-for-scalpers/).
