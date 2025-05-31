
# TinyGS on LilyGo T-Deck Plus ESP32-S3

[![TinyGS Stations](https://img.shields.io/badge/Ground%20Stations-3%20Ready-green)](https://tinygs.com/stations) [![Pull Request](https://img.shields.io/badge/Device-LILYGO®%20T--Deck%20Plus-blue)](https://lilygo.cc/products/t-deck-plus-1) [![MCU](https://img.shields.io/badge/MCU-ESP32--S3-red)](https://www.espressif.com/en/products/socs/esp32-s3) [![LoRa Module](https://img.shields.io/badge/LoRa%20Module-SX1262-orange)](https://www.semtech.com/products/wireless-rf/lora-connect/sx1262)

> TinyGS satellite ground station on the **LilyGo T-Deck Plus ESP32-S3** with SX1262 LoRa module.

##  Live Stations

Our operational stations contributing to the global TinyGS network:

-   **[PiTAYA_gs_001](https://tinygs.com/station/PiTAYA_gs_001@393436548)** - Ariel, Israel 📍
-   **[PiTAYA_gs_002](https://tinygs.com/station/PiTAYA_gs_002@393436548)** - Haifa, Israel 📍
-   **[test_Intro2SDR_AU](https://tinygs.com/station/test_Intro2SDR_AU@393436548)** - Ariel University (Educational Demo) 📍

##  Quick Start Guide

### Step 1: Install PlatformIO

Install PlatformIO Core via command line:

```bash
# Install PlatformIO Core via pip
pip install -U platformio

# Verify installation
pio --version

```

### Step 2: Clone and Build

```bash
# Clone this repository
git clone https://github.com/iMRUM/t-deck-plus-tinygs.git
cd t-deck-plus-tinygs

# Connect your T-Deck Plus via USB-C
# The T-Deck Plus environment is already configured in platformio.ini

# Upload firmware
pio run -e lilygo_t_deck_plus_s3 -t upload

```

### Step 3: Initial Configuration

After successful upload, your T-Deck Plus will:

1.  **Boot up** and show TinyGS splash screen
2.  **Create WiFi Access Point** named "My TinyGS" or "TinyGS-xxxxxx"
3.  **Wait for configuration** via web interface

### Step 4: Web Configuration

1.  **Connect to AP**: Join the "My TinyGS" WiFi network (usually no password)
    
2.  **Open Browser**: Navigate to `http://192.168.4.1/`
    
3.  **Configure Station**:
    
    -   **Ground Station Name**: Choose unique name (appears on global map)
    -   **Board Type**: Select **"433MHz LilyGo T-Deck Plus SX1262"** from dropdown
    -   **Location**: Enter latitude/longitude coordinates
    -   **WiFi**: Your WiFi credentials for internet access
    -   **MQTT**: Get credentials from [TinyGS Personal Bot](https://t.me/tinygs_personal_bot)
4.  **Save Configuration**: Device will restart and connect to internet
    

### Step 5: Verify Operation

-   **Global Map**: Your station appears on [TinyGS map](https://tinygs.com/stations)
-   **Dashboard**: Access local dashboard at your device's IP address
-   **Radio Status**: Should show "READY" (green)
-   **Packets**: Begin receiving satellite telemetry automatically

### Commits Made
-   [Add T-Deck Plus ESP32-S3 board support with correct pin mappings (no OLED pins, pins 11 and 16 were configured for OLED pseudo-support)](https://github.com/G4lile0/tinyGS/commit/89acfcfc8a67934adc27844fd8d9255e2074b2e7)
-   [Add T-Deck Plus to ESP32-S3 board enum](https://github.com/G4lile0/tinyGS/commit/46611b95b09cfbc87426601bef6e5438e590102f)
-   [Add T-Deck Plus to board selection dropdown for ESP32-S3](https://github.com/G4lile0/tinyGS/commit/da861c42294cdeceebb34a8ca5e6ebde961d4492)
-   [Add `lilygo_t_deck_plus_s3` build environment](https://github.com/G4lile0/tinyGS/commit/ebabc8cb8b3ebc27f36096e643eb0db1ea9b033c)

## 🔗 Resources and Links

### TinyGS Community

-   **[TinyGS Main Repository](https://github.com/G4lile0/tinyGS)** - Original project
-   **[TinyGS Website](https://tinygs.com/)** - Global network dashboard
-   **[TinyGS Telegram](https://t.me/joinchat/DmYSElZahiJGwHX6jCzB3Q)** - Community support
-   **[TinyGS Personal Bot](https://t.me/tinygs_personal_bot)** - Get MQTT credentials

### Technical Documentation

-   **[LilyGo T-Deck Plus Product Page](https://lilygo.cc/products/t-deck-plus-1)** - Device Specs
-   **[LilyGo T-Deck Plus Official Repo](https://github.com/Xinyuan-LilyGO/T-Deck)** - Sample code and more detailed information about this board


## 🙏 Acknowledgments

-   **Prof. Ben-Moshe** (Ariel University) - Equipment provision, project motivation, and introduction to TinyGS and LoRa technologies and many more...
-   **TinyGS Community** - Original project development and global satellite tracking network
-   **[@G4lile0](https://github.com/G4lile0)** - TinyGS project creator and maintainer


## 📜 License

This project maintains the same license as the original TinyGS project:

-   **GNU General Public License v3.0**
-   See LICENSE file for details

----------

**Built with ❤️ for the global space community**  

----------

_This guide represents a community contribution to expand TinyGS hardware support. For general TinyGS questions, please refer to the [main project documentation](https://github.com/G4lile0/tinyGS)._
