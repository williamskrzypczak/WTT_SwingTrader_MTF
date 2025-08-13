# WTT SwingTrader MTF R1.8 - Quick Reference Guide

## WaveRider Trading Technologies
### Multi-Timeframe Swing Trading Indicator

---

## 🚀 **R1.8 NEW FEATURES**
- **Syzygy Alert Branding**: All swing alerts now use "Syzygy" terminology
- **Enhanced Boundary Alerts**: Long entries include lower boundary price, short entries include upper boundary price
- **Improved Trade Management**: Boundary level references for better risk management

---

## 📊 **INDICATOR OVERVIEW**

### **Purpose**
Multi-timeframe swing trading indicator that combines Daily trend analysis with current timeframe signal generation for reliable swing trading opportunities.

### **Core Philosophy**
- Conservative approach as default settings
- Multi-timeframe alignment required for signal generation
- Volume confirmation for enhanced signal validation
- Dynamic boundary system for trade management

---

## ⚙️ **SETTINGS & PARAMETERS**

### **EMA Settings**
- Fast EMA: 12 periods
- Slow EMA: 26 periods  
- Trend EMA: 50 periods

### **MACD Settings**
- Fast: 12 periods
- Slow: 26 periods
- Signal: 9 periods

### **RSI Settings**
- Length: 14 periods

### **Volume Settings**
- Volume MA Length: 20 periods
- High Volume Threshold: 1.5x average

### **Display Settings**
- Show Entry/Exit Signals: ✅ Enabled
- Show Trend Direction: ✅ Enabled
- Show EMAs: ❌ Disabled (default)

### **Color Scheme**
- Bullish: Orange 🟠
- Bearish: Purple 🟣
- Neutral: Gray ⚪

---

## 📈 **SIGNAL GENERATION**

### **Long Entry Conditions** (ALL Required)
1. **Daily Trend**: Bullish (EMA alignment)
2. **4H Trend**: Bullish (EMA alignment)
3. **1H Trend**: Bullish (EMA alignment)
4. **Current TF Trend**: Bullish (EMA alignment)
5. **MACD**: Line > Signal AND Histogram increasing
6. **RSI**: Between 40-80 (not overbought)
7. **Volume**: Above 1.5x average
8. **Price**: Above Fast EMA

### **Short Entry Conditions** (ALL Required)
1. **Daily Trend**: Bearish (EMA alignment)
2. **4H Trend**: Bearish (EMA alignment)
3. **1H Trend**: Bearish (EMA alignment)
4. **Current TF Trend**: Bearish (EMA alignment)
5. **MACD**: Line < Signal AND Histogram decreasing
6. **RSI**: Between 20-60 (not oversold)
7. **Volume**: Above 1.5x average
8. **Price**: Below Fast EMA

---

## 🔔 **ALERT SYSTEM**

### **Syzygy Long Entry Alert**
```
🟢 Syzygy LONG ENTRY
[SYMBOL]
Price: [CURRENT_PRICE]
Lower Boundary: [LOWER_BOUNDARY_PRICE]
RSI: [RSI_VALUE]
MACD: [MACD_VALUE]
```

### **Syzygy Short Entry Alert**
```
🔴 Syzygy SHORT ENTRY
[SYMBOL]
Price: [CURRENT_PRICE]
Upper Boundary: [UPPER_BOUNDARY_PRICE]
RSI: [RSI_VALUE]
MACD: [MACD_VALUE]
```

### **Trend Change Alerts**
- **Bullish Transition**: When current timeframe trend changes to bullish
- **Bearish Transition**: When current timeframe trend changes to bearish
- Includes comprehensive market data (price, RSI, MACD, signal, histogram, trend status)

---

## 🎯 **VISUAL ELEMENTS**

### **Signal Markers**
- **Long Signal**: Orange triangle pointing up (below bar)
- **Short Signal**: Purple triangle pointing down (above bar)
- **Trend Change**: Small triangles with trend cloud colors

### **Trend Cloud**
- **Bullish**: Orange cloud around price
- **Bearish**: Purple cloud around price
- **Neutral**: Gray cloud around price
- Transparency: 65% fill, 50% border

### **Boundary Lines**
- **Lower Boundary**: Red dotted line for long entries
- **Upper Boundary**: Red dotted line for short entries
- **Origin**: 3 bars before current price
- **Extension**: 20 bars ahead
- **Deletion**: When price trades through boundary level

---

## 📋 **STATUS TABLE**

### **Multi-Timeframe Trend Status**
- **D**: Daily timeframe trend (BULL/BEAR/NEUT)
- **4H**: 4-hour timeframe trend (BULL/BEAR/NEUT)
- **1H**: 1-hour timeframe trend (BULL/BEAR/NEUT)
- **CTF**: Current timeframe trend (BULL/BEAR/NEUT)

### **Indicator Status**
- **RSI**: Current RSI value with color coding
- **MACD**: Bullish/Bearish status with color coding
- **ATR**: High/Normal volatility status
- **Volume**: High/Normal volume status

### **Last Trade Type**
- **SWING LONG**: Long entry signal
- **SWING SHORT**: Short entry signal
- **TREND BULLISH**: Bullish trend change
- **TREND BEARISH**: Bearish trend change
- **NONE**: No recent activity

---

## 🎨 **COLOR CODING SYSTEM**

### **Trend Status**
- **Green**: Bullish trend
- **Red**: Bearish trend
- **Gray**: Neutral trend

### **Indicator Values**
- **RSI**: Red (overbought), Green (oversold), White (normal)
- **MACD**: Green (bullish), Red (bearish)
- **ATR**: Yellow (high volatility), Gray (normal)
- **Volume**: Orange (high), Blue (low), Gray (normal)

### **Last Trade Type**
- **Orange**: Bullish trades (Long/Trend Bullish)
- **Purple**: Bearish trades (Short/Trend Bearish)
- **Gray**: Neutral/No activity

---

## 💡 **TRADING STRATEGY**

### **Entry Rules**
1. Wait for multi-timeframe alignment
2. Confirm volume is above average
3. Verify RSI is in optimal range
4. Check MACD momentum alignment
5. Enter at current market price

### **Risk Management**
- **Long Trades**: Use lower boundary as support reference
- **Short Trades**: Use upper boundary as resistance reference
- **Stop Loss**: Consider boundary levels for placement
- **Position Sizing**: Conservative approach recommended

### **Exit Strategy**
- **Profit Target**: Based on market structure
- **Stop Loss**: Boundary level breaches
- **Trailing Stop**: ATR-based or percentage-based
- **Trend Change**: Exit on opposite trend signals

---

## 🔧 **TROUBLESHOOTING**

### **No Signals Generated**
- Check if all timeframes are aligned
- Verify volume is above threshold
- Ensure RSI is in optimal range
- Confirm MACD momentum direction

### **Frequent False Signals**
- Consider tightening volume requirements
- Adjust RSI range parameters
- Review multi-timeframe alignment criteria
- Check for market volatility conditions

### **Boundary Lines Not Appearing**
- Verify signal conditions are met
- Check if price has traded through boundary
- Ensure trend cloud is enabled
- Review boundary line settings

---

## 📝 **VERSION HISTORY**

### **R1.8** (Current)
- Syzygy alert branding implementation
- Enhanced boundary price alerts
- Improved trade management features

### **R1.7**
- Enhanced status table with color coding
- Individual timeframe trend columns
- Color-coded indicator values

### **R1.6**
- Dynamic boundary line system
- Historical reference points
- Boundary evolution tracking

### **R1.5**
- Performance analytics enhancement
- Consolidated indicator display
- Success rate calculations

### **R1.4**
- Comprehensive feature integration
- Multi-timeframe functionality
- Alert system implementation

### **R1.3**
- Visual enhancement and alert system
- ATR-based exit signals
- Trend cloud visualization

### **R1.2**
- Alert system enhancement
- Detailed price point information
- Market data integration

### **R1.1**
- Visual design and user interface
- Professional color scheme
- Enhanced readability

### **R1.0**
- Initial release
- Multi-timeframe swing trading foundation
- WaveRider Trading Technologies methodology

---

## 📞 **SUPPORT**

For questions, issues, or feature requests, please refer to the WaveRider Trading Technologies documentation or contact the development team.

---

*WaveRider Trading Technologies - Professional Trading Solutions*
