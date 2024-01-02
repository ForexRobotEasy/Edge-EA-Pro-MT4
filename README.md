# Edge EA Pro MT4 ReadMe File

This ReadMe file provides an overview of the code for the Edge EA Pro MT4, developed by the Forex Robot Easy Team. For detailed reviews and trading results of this product, please visit [Forex Robot Easy](https://forexroboteasy.com/forex-robot-review/edge-ea-pro-mt4-review-automated-forex-trading-mastery/).

**Note: ForexRobotEasy is not the official developer of this product. We only provide a sample code that can work as described in this product. To find the official developer of this product, please use MQL5.**

## Customizable Parameters

The Edge EA Pro MT4 code contains several customizable parameters that can be adjusted to suit your trading preferences. These parameters include:

- MovingAveragePeriod: Period for the moving average indicator.
- RsiPeriod: Period for the RSI indicator.
- MacdFastEmaPeriod: Fast EMA period for the MACD indicator.
- MacdSlowEmaPeriod: Slow EMA period for the MACD indicator.
- MacdSignalSmoothing: Signal smoothing period for the MACD indicator.
- BollingerPeriod: Period for the Bollinger Bands indicator.
- BollingerDeviation: Deviation for the Bollinger Bands indicator.
- WavePatternPeriod: Period for wave pattern analysis.
- FibonacciRetracementLevel: Fibonacci retracement level.

## Technical Indicators

The code includes functions to calculate various technical indicators. These indicators are:

- Moving Average: Calculates the moving average based on the specified period.
- RSI (Relative Strength Index): Calculates the RSI based on the specified period.
- MACD (Moving Average Convergence Divergence): Calculates the MACD based on the specified fast and slow EMA periods, and the signal smoothing period.
- Bollinger Bands: Calculates the Bollinger Bands based on the specified period and deviation.

## Price Action Analysis

The code includes a function to analyze price action patterns. This function examines the historical price data to identify patterns that may indicate potential trading opportunities.

## Wave Analysis

The code includes a function to analyze wave patterns. This function examines the historical price data to identify wave patterns that may indicate potential trading opportunities. The analysis is performed based on the specified period.

## Fibonacci Areas

The code includes a function to calculate Fibonacci levels. This function calculates the Fibonacci retracement levels based on the specified retracement level.

## Neural Network Integration

The code includes functions for training and using a neural network. The TrainNeuralNetwork function is used to train the neural network, and the UseNeuralNetwork function is used to make predictions using the trained neural network.

## Main Program

The main program logic is executed in the OnStart function. This function calls the various indicator calculation functions and pattern analysis functions to obtain the necessary data for trading decisions. The neural network is also trained and used to make predictions. Based on the calculated indicators, patterns, and neural network predictions, the code implements the trading logic to place buy or sell trades.

**Note: The trading logic implementation is not provided in the code and should be added as per the trader's strategy.**

For more information and support, please visit the official developer's website on MQL5.
