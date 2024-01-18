# Manual Zone Recovery - MT4 Code

Manual Zone Recovery is a powerful tool developed by Forex Robot Easy Team to assist traders in their trading strategies. This code provides the necessary functions and logic to enable the Manual Zone Recovery tool to operate in Zone Recovery mode.

## Features
- Zone Recovery Mode: Enables the Manual Zone Recovery tool to operate in Zone Recovery mode.
- Restrict Stop Loss Modification: Prevents modification of the Stop Loss during the execution of the strategy.
- Exclude Pending Orders: Ensures that no pending orders are placed when the StartPrice is reached.
- Check Hedging Compatibility: Verifies if the trading account allows hedging before executing Zone Recovery strategies.

## How it Works
1. To enable Zone Recovery mode, call the `ZoneRecoveryMode()` function.
2. To restrict Stop Loss modification, call the `RestrictStopLossModification()` function.
3. To exclude pending orders, call the `ExcludePendingOrders()` function.
4. To check hedging compatibility, call the `CheckHedgingCompatibility()` function.
5. The `OnTick()` function is triggered when a new tick is received. Inside this function, you can implement your Zone Recovery strategies based on the `g_zoneRecoveryMode` flag.
6. The `OnDeinit()` function is triggered when the program is about to end. You can use this function for cleaning up and ending the program gracefully.

**Note:** ForexRobotEasy is not the official developer of this product. This code is provided as a sample that can work as described in the product. For detailed reviews and trading results of this product, please visit [Forex Robot Easy - Manual Zone Recovery MT4 Review](https://forexroboteasy.com/forex-robot-review/manual-zone-recovery-mt4-review-a-traders-powerful-tool/).

For the official developer of this product, please refer to MQL5.

## Usage
1. Copy the code and save it as an Expert Advisor (.mq4) file.
2. Compile the code in MetaEditor.
3. Attach the Expert Advisor to the desired chart in MetaTrader 4.
4. Customize the code according to your trading strategy within the `OnTick()` function.
5. Enable the desired features by calling the corresponding functions.
6. Start trading and monitor the performance of your Zone Recovery strategies.

For more information and support, please visit the official developer's site - [Forex Robot Easy](https://forexroboteasy.com/).

**Please note that ForexRobotEasy is not the official developer of this product. We only provide sample code for demonstration purposes.**
