# ICT Core Content Tools - PSI Full Version

This code is a sample script that demonstrates the usage of ICT Core Content Tools - PSI Full Version. These tools are a set of custom indicators developed by Forex Robot Easy Team.

## Product Description
ICT Core Content Tools - PSI Full Version is a comprehensive package of tools designed to assist traders in making trading decisions based on ICT Core content concepts. These tools provide various indicators and calculations to generate trading signals.

This code utilizes the following tools:
1. CBDR Tool - Calculates the CBDR value.
2. Asian Range Tool - Retrieves the Asian Range value.
3. Seek & Destroy Tool - Retrieves the Seek & Destroy value.
4. IPDA Tool - Retrieves the IPDA value.
5. GMT0 Line Tool - Retrieves the GMT0 Line value.
6. Daily Divider Tool - Retrieves the Daily Divider value.

The script subscribes to these tools and retrieves their values to calculate a trading signal. The trading signal is determined by summing up the values of all the tools. If the signal is positive, a buy trade is executed with a volume of 0.1 lots. If the signal is negative, a sell trade is executed with a volume of 0.1 lots.

Additionally, the script subscribes to the position close event and retrieves information about the closed position. This information can be further processed or analyzed as per the user's requirements.

Please note that ForexRobotEasy is not the official developer of this product. This code is provided as a sample to demonstrate the functionality of ICT Core Content Tools - PSI Full Version. For detailed reviews and trading results of this product, please visit the official developer's website: [ICT Core Forex Software Review: Unveiling PSI Full Version Tools](https://forexroboteasy.com/forex-robot-review/ict-core-forex-software-review-unveiling-psi-full-version-tools/). To find the official developer of this product, please refer to the MQL5 platform.

## Usage
1. Include the necessary libraries: Trade.mqh, PositionInfo.mqh, and SymbolInfo.mqh.
2. Define the constants for the tool IDs.
3. Initialize the trade, positionInfo, and symbolInfo objects.
4. In the OnStart() function:
   - Set the expert magic number.
   - Subscribe to the necessary tools.
   - Check if the tools are available.
   - Subscribe to the position close event.
   - Calculate the trading signal.
   - Place a trade based on the trading signal.
5. Implement the CalculateTradingSignal() function to retrieve the tool values and calculate the trading signal.
6. Implement the OnPositionClose() function to handle the position close event and process the closed position data.

For detailed instructions and usage examples, please refer to the official documentation of ICT Core Content Tools - PSI Full Version.

## Disclaimer
Please note that ForexRobotEasy is not the official developer of ICT Core Content Tools - PSI Full Version. The provided code is a sample that demonstrates the functionality of the tools. For the official and complete product, please refer to the MQL5 platform or visit the official developer's website mentioned above.
