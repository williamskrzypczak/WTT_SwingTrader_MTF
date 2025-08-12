# WTT Swing Trader MTF - Quick Reference

## Overview
Multi-timeframe swing trading indicator for WaveRider Trading Technologies that combines daily trend analysis with current timeframe signals.

## Current Version
**R1.5** - Updated performance stats to base on SL, PT, and TS

## Key Features
- **Multi-timeframe Analysis**: Daily trend + Current timeframe signals
- **Trend Detection**: EMA alignment (12, 26, 50 periods)
- **Momentum Confirmation**: MACD and RSI
- **Risk Management**: Dynamic SL, PT, and TS based on ATR
- **Performance Tracking**: Separate metrics for SL, PT, and TS exits
- **Visual Indicators**: Trend cloud, signal markers, risk/reward lines
- **Comprehensive Alerts**: Entry, exit, and trend change notifications

## Performance Metrics
- **Success Rate**: Based on PT and TS exits (considered successful)
- **Exit Types**: 
  - SL (Stop Loss): 2x ATR from entry
  - PT (Profit Target): 3.5x ATR from entry  
  - TS (Trailing Stop): Activates at 50% of PT, trails at 1x ATR

## Signal Types
- **Daily Signals**: Full trend + momentum + volume confirmation
- **Current Timeframe Signals**: Simplified trend + MACD confirmation
- **Exit Signals**: ATR-based volatility exits

## Color Scheme
- **Bullish**: Orange (#FF4500)
- **Bearish**: Purple (#8A2BE2)
- **Neutral**: Gray

## Alert Types
- Entry signals (Long/Short)
- Trend change notifications
- Dynamic messages with price, RSI, and MACD values

## Recent Updates
- R1.5: Performance stats now based on SL, PT, and TS exits
- R1.4: Comprehensive features and visual enhancements
- R1.3: Trend change alerts and visual indicators
- R1.2: Enhanced alerts with price points and currency info
- R1.1: Improved visual elements and color scheme
- R1.0: Initial release

## Usage Notes
- Conservative approach as default settings
- Avoids multi-timeframe complexity for reliability
- Uses alert() function with alert.freq_once_per_bar
- Performance tracking provides detailed exit analysis
