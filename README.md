# Solar Weather Monitor - OpenClaw Skill 🌞

Monitor space weather conditions in real-time! Track solar flares, geomagnetic storms, aurora forecasts, and solar wind data from NOAA's Space Weather Prediction Center.

## Features

- 🌞 **Current Conditions** - Real-time space weather status
- 📅 **3-Day Forecast** - Predict upcoming solar activity
- 🌌 **Aurora Forecast** - Northern Lights visibility predictions
- 🌊 **Solar Wind** - Track solar wind and magnetic field
- 🚨 **Alerts** - Active space weather warnings
- 📊 **Summary** - Quick comprehensive overview

## Quick Start

### Installation

```bash
# Via ClawHub (once published)
clawdhub install solar-weather

# Via GitHub
git clone https://github.com/capt-marbles/solar-weather ~/.openclaw/skills/solar-weather
```

### Basic Usage

```bash
# Current space weather conditions
python3 solar-weather.py current

# 3-day forecast
python3 solar-weather.py forecast

# Aurora visibility forecast
python3 solar-weather.py aurora

# Solar wind data
python3 solar-weather.py wind

# Active alerts
python3 solar-weather.py alerts

# Complete summary
python3 solar-weather.py summary
```

## Example Output

```
🌞 Space Weather Conditions
   2026-01-27 18:38:00 UTC

   📻 R0: none ✅
      Radio Blackouts (Solar Flares)

   ☢️  S0: none ✅
      Solar Radiation Storm

   🌍 G0: none ✅
      Geomagnetic Storm

🌌 Aurora Forecast (Kp Index)
   Now: Kp 2 - Low activity
   Expected: Kp 3 in next 3 hours
```

## Perfect For

- **Ham Radio Operators** - Monitor propagation conditions
- **Aurora Chasers** - Know when to see Northern Lights
- **Photographers** - Plan aurora photography sessions
- **Satellite Operators** - Track space weather impacts
- **Power Grid Operators** - Monitor geomagnetic storm risks
- **Space Weather Enthusiasts** - Stay informed on solar activity

## Use Cases

### Ham Radio
```bash
# Check propagation before contests
python3 solar-weather.py current
```

### Aurora Photography
```bash
# Get aurora forecast for tonight
python3 solar-weather.py aurora
```

### Daily Monitoring
```bash
# Set up cron for daily digest
0 8 * * * python3 /path/to/solar-weather.py summary
```

## Data Sources

All data comes from **NOAA Space Weather Prediction Center**:
- Real-time space weather conditions
- 3-day forecasts
- Aurora forecasts (Kp index)
- Solar wind magnetic field
- Official space weather alerts

## Requirements

- Python 3.6+
- Internet connection
- No API key required (public NOAA data)

## Documentation

See [SKILL.md](SKILL.md) for complete documentation.

## License

MIT

## Author

captmarbles (KN4XYZ)

73!