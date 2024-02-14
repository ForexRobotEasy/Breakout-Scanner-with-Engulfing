# Breakout Scanner

This code is a sample implementation of a breakout scanner algorithm in MQL5. It is designed to detect and trade breakouts in the forex market. The algorithm analyzes the current symbol and timeframe to identify potential resistance and support levels. It then checks for upward and downward breakouts and executes buy or sell orders accordingly.

## Inputs

- LookbackPeriod: The number of periods to look back for detecting breakouts. Default value is 20.
- EngulfingThreshold: The threshold value for engulfing pattern detection. Default value is 0.7.

## How it Works

1. The code starts by getting the current symbol and timeframe.
2. It then calls the `GetResistanceLevel()` and `GetSupportLevel()` functions to calculate the resistance and support levels for the current symbol and timeframe.
3. The code checks for upward breakouts by calling the `BreaksResistanceLevel()` function with the resistance level as a parameter. If a breakout is detected, it executes a buy order using the `Buy()` function.
4. Similarly, it checks for downward breakouts by calling the `BreaksSupportLevel()` function with the support level as a parameter. If a breakout is detected, it executes a sell order using the `Sell()` function.

## Product Description

Breakout Scanner is a powerful forex trading tool that helps optimize trades across all symbols. It is designed to identify breakouts in the market and execute trades accordingly. With its advanced algorithm, Breakout Scanner enables traders to take advantage of price movements and maximize profits.

Key Features:
- Detects breakouts in real-time
- Works across multiple symbols and timeframes
- Adjustable lookback period for breakout detection
- Engulfing pattern detection for accurate signals
- Easy to use and implement in any trading strategy

Please note that Forex Robot Easy is not the official developer of this product. We only provide this sample code to showcase how the algorithm can work as described. For detailed reviews and trading results of the official Breakout Scanner product, please visit [here](https://forexroboteasy.com/forex-robot-review/breakout-scanner-review-optimize-forex-trades-across-all-symbols-2/). To find the official developer of this product and to access the complete and updated version, please refer to MQL5.
