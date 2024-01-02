# SuperTrend Etradro ReadMe File

This is the ReadMe file for the SuperTrend Etradro code. The SuperTrend Etradro is a custom indicator for MetaTrader 5 that is designed to provide accurate volatility-based trading signals. This code is provided as a sample and is not the official product of Forex Robot Easy Team. To find the official developer of this product, please use MQL5.

## Product Description

The SuperTrend Etradro is an advanced volatility-based trading indicator for MetaTrader 5. It is designed to identify trend reversals and provide entry and exit signals for traders. The indicator uses the Average True Range (ATR) and price gaps to calculate the trend and determine the stop and reversal lines.

Key Features:

- Accurate volatility-based trading signals
- Customizable input parameters for ATR period, ATR multiplier, gap period, and gap threshold
- Provides Supertrend, stop line, and reversal line values
- Easy to use and implement in MetaTrader 5

For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/supertrend-etradro-review-accurate-volatility-based-forex-indicator/). Please note that Forex Robot Easy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, please use MQL5.

## Code Details

The code consists of two main functions: `OnInit()` and `OnCalculate()`. Here is a detailed description of how the code works:

### OnInit()

- Sets the indicator buffers for `supertrend`, `stopLine`, and `reversalLine`.
- Sets the indicator label as 'Supertrend Etradro'.
- Initializes the `atrBuffer` array with the size of the bars.
- Returns `INIT_SUCCEEDED` to indicate successful initialization.

### OnCalculate()

- Calculates the Average True Range (ATR) for each bar using the high, low, and close prices.
- Calculates the price gaps between each bar.
- Calculates the Supertrend values based on the ATR and price gaps.
- Calculates the stop line values as the highest high within a specified period.
- Calculates the reversal line values as the lowest low within a specified period.
- Returns the total number of rates.

Please note that this code is provided as a sample and may need further customization or optimization to fit your specific trading strategy.

## Additional Information

For detailed reviews and trading results of the SuperTrend Etradro indicator, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/supertrend-etradro-review-accurate-volatility-based-forex-indicator/). Please remember that Forex Robot Easy is not the official developer of this product. We only provide the sample code that can work as described in this product. To find the official developer of this product, please use MQL5.
