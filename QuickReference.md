# WTT SwingTrader MTF R1.11 - Quick Reference

## Multi-Timeframe Syzygy Trading Indicator

The WTT SwingTrader MTF identifies Syzygy trading opportunities across multiple timeframes (Daily, 4-Hour, 1-Hour, and Current Timeframe) using trend alignment and momentum confirmation.

### Last Trade Type
- **D+4H+1H+CTF LONG** (Green background) - All 4 timeframes bullish
- **D+4H+1H+CTF SHORT** (Red background) - All 4 timeframes bearish
- **4H+1H+CTF LONG** (Blue background) - 4H, 1H, and CTF bullish
- **4H+1H+CTF SHORT** (Purple background) - 4H, 1H, and CTF bearish
- **1H+CTF LONG** (Orange background) - 1H and CTF bullish
- **1H+CTF SHORT** (Yellow background) - 1H and CTF bearish

### R1.11 Features
- **Trend Cloud Opacity Optimization**: Enhanced transparency settings for improved chart visibility
- **Fill Area Opacity**: 75% for optimal visual balance
- **Boundary Line Opacity**: 50% for clear contrast
- **Visual Hierarchy**: Improved chart readability without compromising trend indication

### R1.10 Features
- **Perfect Synchronization**: Triangle colors match status table row colors exactly
- **Progressive Triangle Sizing**: Large (D+4H+1H+CTF), Normal (4H+1H+CTF), Small (1H+CTF)
- **Enhanced Text Readability**: Dynamic color adjustment for yellow backgrounds
- **Original Alert Logic**: Restored detailed condition logic while maintaining synchronization

### R1.9 Features
- **Multi-Timeframe Alert System**: Three distinct signal types with timeframe alignment
- **D+4H+1H+CTF Alerts**: Highest confidence swing trades
- **4H+1H+CTF Alerts**: Medium-term trades with high confidence
- **1H+CTF Alerts**: Short-term trades with medium confidence
- **Enhanced Alert Descriptions**: Clear timeframe alignment information

### R1.8 Features
- **Syzygy Alert Renaming**: Changed from "Swing Alert" to "Syzygy alerts"
- **Color-Coded Signal Triangles**: Visual distinction for different signal types
- **Persistent Last Signal**: Status table shows last fired signal until new one
- **Perfect Synchronization**: Triangle colors and table row colors match exactly

### R1.7 Features
- **Enhanced Status Table**: Individual color-coded timeframe columns
- **Color-Coded Values**: Trend (Green/Red/Gray), RSI (Red/Green), MACD (Green/Red)
- **Persistent Signal History**: Last trade type tracking with background colors
- **Optimized Layout**: Cleaner, more focused display

### R1.6 Features
- **Dynamic Boundary Lines**: Historical reference points with horizontal extension
- **Separate Triggers**: Bullish and bearish boundary line activation
- **Continuous Updates**: Lines maintain 3-bar historical reference
- **Auto-Deletion**: Lines delete when price trades through boundaries

### R1.5 Features
- **Performance Analytics**: Consolidated indicator display
- **Exit Breakdown**: SL/PT/TS counts separately
- **Success Rate Calculation**: PT and TS exits as successful trades
- **Active Trade Indicator**: Comprehensive metrics display

### R1.4 Features
- **Multi-Timeframe Integration**: Daily trend with current timeframe signals
- **Comprehensive Alert System**: Dynamic price and indicator information
- **Volume Confirmation**: Enhanced signal validation
- **Trend Cloud Visualization**: Customizable transparency settings

### R1.3 Features
- **Trend Change Alerts**: Synchronized with visual indicators
- **ATR-Based Exit Signals**: Diamond-shaped markers
- **Enhanced Visual Elements**: Trend cloud and signal markers
- **Trend Transition Detection**: Early market movement identification

### R1.2 Features
- **Enhanced Alert Messages**: Detailed price points and currency information
- **Comprehensive Market Data**: RSI and MACD values in alerts
- **Alert Frequency Management**: Better signal quality
- **User Notification System**: Improved trade management

### R1.1 Features
- **Professional Color Scheme**: Orange (bullish), Purple (bearish), Gray (neutral)
- **Enhanced User Interface**: Better contrast and readability
- **Optimized Table Layout**: Improved information display
- **Visual Appeal**: Professional appearance

### R1.0 Features
- **Multi-timeframe Syzygy trading foundation**: Daily trend + Current timeframe signals
- **Trend detection**: EMA alignment (12, 26, 50 periods)
- **MACD and RSI momentum confirmation**: Enhanced signal validation
- **Dynamic Support/Resistance levels**: Pivot point calculations
- **Entry/Exit signals**: Comprehensive alert system
- **Volume confirmation**: Signal validation and market strength assessment
- **Conservative approach**: Default settings for reliable trading
- **Foundation**: WaveRider Trading Technologies swing trading methodology

## MULTI-TIMEFRAME ALERT SYSTEM

### D+4H+1H+CTF Alerts (Highest Confidence)
- **Visual**: Large Green/Red triangles
- **Use Case**: Major swing trades with maximum timeframe alignment
- **Risk Level**: Low (4 timeframe confirmation)

### 4H+1H+CTF Alerts (Medium Confidence)
- **Visual**: Normal Blue/Purple triangles
- **Use Case**: Medium-term trades with high confidence
- **Risk Level**: Medium (3 timeframe confirmation)

### 1H+CTF Alerts (Lower Confidence)
- **Visual**: Small Orange/Yellow triangles
- **Use Case**: Short-term trades with medium confidence
- **Risk Level**: Higher (2 timeframe confirmation)

## Visual Elements

### Signal Markers
- **Large Triangles**: D+4H+1H+CTF signals (highest confidence)
- **Normal Triangles**: 4H+1H+CTF signals (medium confidence)
- **Small Triangles**: 1H+CTF signals (lower confidence)

### Status Table
- **Color-Coded Rows**: Match triangle colors for perfect synchronization
- **Persistent Display**: Last signal remains until new one fires
- **Real-Time Updates**: Live market information and trend status

### Trend Cloud
- **Fill Area**: 75% opacity for optimal visibility
- **Boundary Lines**: 50% opacity for clear contrast
- **Dynamic Colors**: Orange (bullish), Purple (bearish), Gray (neutral)
