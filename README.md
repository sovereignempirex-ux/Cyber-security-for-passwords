<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                         HERO BANNER                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<a href="https://i.postimg.cc/t4WVDH6z/778755882-1002851589464666-5861998769997315826-n.webp" target="_blank">
  <img src="https://i.postimg.cc/t4WVDH6z/778755882-1002851589464666-5861998769997315826-n.webp" alt="Sovereign-X" width="100%" />
</a>

<br><br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      TYPING SVG HEADER                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1000&color=DC143C&center=true&vCenter=true&width=600&lines=%E2%9D%96+SOVEREIGN-X+%E2%9D%96;Portable+Security+System;Python+%E2%80%A2+Security+%E2%80%A2+Signals+%E2%80%A2+GPS" alt="Typing SVG" />

<br><br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                          BADGES                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

<img src="https://img.shields.io/badge/Python-3.8%2B-DC143C?style=for-the-badge&logo=python&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Security-Cybersecurity-8B0000?style=for-the-badge&logo=shield&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/SQLite-3.0%2B-DC143C?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Portable-Device-8B0000?style=for-the-badge&logo=raspberrypi&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Signal-Analyzer-DC143C?style=for-the-badge&logo=wifi&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Version-1.0.0-8B0000?style=for-the-badge&logo=git&logoColor=white&labelColor=0D1117" />
<img src="https://img.shields.io/badge/License-MIT-DC143C?style=for-the-badge&logo=opensourceinitiative&logoColor=white&labelColor=0D1117" />

<br><br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                           QUOTE                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="https://img.shields.io/badge/%C2%AB%22A%20portable%20system%20built%20to%20manage%2C%20analyze%2C%20and%20protect.%22%C2%BB-DC143C?style=flat-square&labelColor=0D1117&color=8B0000" width="80%" />
</p>

</div>

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!-- ═══════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png" width="100%" />
</p>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     ABOUT THE PROJECT                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f6e1_fe0f/512.webp" width="28" /> About The Project
</h2>

**Sovereign-X** is a portable security system built with **Python**, designed to serve as the core software for a compact handheld device. It unifies security tools, credential management, and wireless signal analysis within a single terminal-based environment.

The project functions as a **prototype / experimental security framework** that demonstrates the integration of:

| Module | Description |
|--------|-------------|
| 🔐 **Password Manager** | Secure credential storage with local SQLite persistence |
| 🔑 **Secure Authentication** | Master password authentication with PBKDF2 hashing |
| 🎲 **Password Generator** | Cryptographically secure password generation |
| 📡 **Wireless Signal Scanner** | Wi-Fi and Bluetooth signal discovery |
| 📊 **Signal Analysis** | RSSI collection, frequency info, and approximate distance |
| 🗺️ **GPS Integration** | Location reading with ASCII map generation |
| 📝 **Activity Logging** | Audit trail of system events and failed logins |
| 🔒 **Auto Lock** | Automatic inactivity lock for session security |
| 💻 **Portable Terminal UI** | Lightweight text-based interface for embedded use |

> ⚠️ **Disclaimer:** Sovereign-X is a **prototype / experimental security project**. It is **not** a production-grade commercial security product. The current encryption layer requires professional security review before being used to protect real-world sensitive secrets.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                       CORE FEATURES                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/2696_fe0f/512.webp" width="28" /> Core Features
</h2>

<br>

<table align="center">
  <tr>
    <td width="50%" valign="top">

### 🔐 Password Vault
- Save account credentials locally
- Encrypt sensitive password data
- Add / Delete / Update accounts
- SQLite local storage backend

### 🎲 Password Generator
- Cryptographically secure random generation using `secrets`
- Customizable character sets:
  - Uppercase (A-Z)
  - Lowercase (a-z)
  - Digits (0-9)
  - Symbols (!@#$%^&*)
- Password strength estimation

### 🛡️ Authentication
- Master password protection
- PBKDF2-HMAC-SHA256 password hashing
- Login session management
- Failed login attempt logging
- Automatic inactivity lock

</td>
    <td width="50%" valign="top">

### 📡 Signal Scanner
- Wi-Fi network scanning
- Bluetooth device discovery
- RSSI (signal strength) collection
- Frequency information capture
- Approximate distance estimation
- Signal history persistence

> ⚠️ Signal reading capabilities depend on the host operating system and available hardware. Distance calculations are **approximate** and not precision measurements.

### 🗺️ GPS & Mapping
- GPS location reading
- Latitude / Longitude capture
- Altitude data
- Saved map points
- ASCII map generation

### 📊 Signal Analytics

| Field | Description |
|-------|-------------|
| Signal Type | Wi-Fi / Bluetooth |
| RSSI | Received Signal Strength Indicator (dBm) |
| Frequency | Operating frequency band |
| Approximate Distance | Estimated range from RSSI |
| Timestamp | Discovery time |

</td>
  </tr>
</table>

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                        ARCHITECTURE                         -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/2699_fe0f/512.webp" width="28" /> Architecture
</h2>

```
                    ┌───────────────────┐
                    │       USER        │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │   Terminal UI     │
                    └─────────┬─────────┘
                              │
          ┌───────────────────┼───────────────────┐
          ▼                   ▼                   ▼
   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐
   │  Security   │    │   Signals   │    │     GPS     │
   │   System    │    │   Analyzer  │    │    / Map    │
   └──────┬──────┘    └──────┬──────┘    └──────┬──────┘
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ▼
                    ┌───────────────────┐
                    │      SQLite       │
                    │     Database      │
                    └───────────────────┘
```

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   INTERNAL ARCHITECTURE                     -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4be/512.webp" width="28" /> Internal Architecture
</h2>

The codebase is organized around the following core classes:

| Component | Responsibility |
|-----------|--------------|
| `Config` | System configuration and settings management |
| `Encryption` | Sensitive data protection layer |
| `Database` | SQLite persistence and query management |
| `Authentication` | Master authentication and session control |
| `PasswordManager` | Credential storage, retrieval, and updates |
| `PasswordGenerator` | Secure password generation with `secrets` |
| `SignalScanner` | Wireless signal discovery and scanning |
| `SignalReading` | Individual signal data structure |
| `MapManager` | GPS coordinate handling and ASCII map generation |
| `TerminalUI` | Device interface and menu rendering |

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    DATABASE ARCHITECTURE                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f5c3_fe0f/512.webp" width="28" /> Database Architecture
</h2>

Sovereign-X uses **SQLite** as its local database engine. The following tables manage application data:

| Table | Purpose |
|-------|---------|
| `passwords` | Stores encrypted account credentials, usernames, and associated metadata |
| `signal_history` | Persists discovered wireless signals with RSSI, frequency, timestamp, and distance estimates |
| `map_points` | Saves GPS coordinates (latitude, longitude, altitude) with labels |
| `auth_log` | Records authentication events, including successful logins and failed attempts |

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                       SECURITY MODEL                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f510/512.webp" width="28" /> ❖ Security Model
</h2>

```
       Master Password
              │
              ▼
    PBKDF2-HMAC-SHA256
              │
              ▼
      Authentication
              │
              ▼
   Protected Application
              │
    ┌─────────┼─────────┐
    ▼         ▼         ▼
 Password   Signal    Local
   Vault     Data    Database
```

The current security model uses **PBKDF2-HMAC-SHA256** for master password hashing. All sensitive operations require successful authentication.

> ⚠️ **Important:** This is a **prototype-level** implementation. The encryption architecture is functional for demonstration purposes but **requires professional security review and hardening** before being trusted with real-world secrets. Do not claim this is military-grade or production-grade encryption.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      SIGNAL PROCESSING                      -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4f6/512.webp" width="28" /> Signal Processing
</h2>

```
    Wireless Signal
           │
           ▼
    Signal Discovery
           │
           ▼
          RSSI
           │
    ┌──────┼──────┐
    ▼      ▼      ▼
 Frequency  Device   Timestamp
           Identifier
           │
           ▼
   Approximate Distance
           │
           ▼
    SQLite History
           │
           ▼
    Signal Analysis
```

Sovereign-X is designed to **analyze available signals** that the device is permitted to discover. It does **not** intercept communication content, extract passwords, or perform unauthorized packet capture.

> 🛡️ The system only reads publicly broadcast beacon data (SSID, BSSID, RSSI) and does not access encrypted payloads or private user data.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     PROJECT STRUCTURE                       -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4c1/512.webp" width="28" /> Project Structure
</h2>

### ◈ Current Prototype (Single File)

```
Sovereign-X/
│
├── sovereignx.py          # Main application (single-file prototype)
├── sovereignx.db          # SQLite database file
├── .master_key            # Master key storage (PBKDF2 hash)
├── logs/
│   └── sovereignx.log     # Activity and audit logs
└── README.md              # Project documentation
```

### ◈ Future Modular Architecture

```
sovereign-x/
├── core/
│   ├── config.py
│   └── logger.py
├── security/
│   ├── encryption.py
│   ├── authentication.py
│   ├── password_manager.py
│   └── password_generator.py
├── signals/
│   ├── scanner.py
│   ├── reading.py
│   └── analyzer.py
├── database/
│   └── db_manager.py
├── gps/
│   ├── gps_reader.py
│   └── map_manager.py
├── ui/
│   └── terminal_ui.py
├── config/
│   └── settings.json
└── main.py
```

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                       INSTALLATION                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4e5/512.webp" width="28" /> Installation
</h2>

### Prerequisites
- Python 3.8 or higher
- Operating system with Wi-Fi / Bluetooth hardware (for signal features)
- GPS hardware or GPSD service (for GPS features)

### Quick Start

```bash
# Clone the repository
git clone https://github.com/yourusername/sovereign-x.git

# Navigate to project directory
cd sovereign-x

# Run the application
python3 sovereignx.py
```

### Dependencies
Sovereign-X primarily uses Python standard libraries:
- `sqlite3` — Database operations
- `secrets` — Cryptographically secure random generation
- `hashlib` — PBKDF2 password hashing
- `getpass` — Secure password input
- `subprocess` / `os` — System signal scanning

> ⚠️ **Note:** Signal scanning and GPS functionality depend on underlying OS tools and hardware availability. On Linux, tools like `iwlist`, `hcitool`, or `gpsd` may be required.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     EXAMPLE TERMINAL                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f5a5_fe0f/512.webp" width="28" /> Example Terminal
</h2>

```
╔══════════════════════════════════════╗
║        SOVEREIGN-X SECURITY          ║
║     PORTABLE SECURITY SYSTEM         ║
╚══════════════════════════════════════╝

[1] Password Manager
[2] Password Generator
[3] Signal Scanner
[4] Signal Analyzer
[5] GPS / Map
[6] Activity Logs
[7] Lock Device
[0] Exit

>>> Choose: 3

[SCANNING...]
```

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    EXAMPLE SIGNAL OUTPUT                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4f1/512.webp" width="28" /> Example Signal Output
</h2>

```
╔══════════════════════════════════════╗
║          SIGNAL ANALYZER             ║
╚══════════════════════════════════════╝

Type        Name            RSSI
──────────────────────────────────────
WiFi        Network_A       -48 dBm
WiFi        Network_B       -67 dBm
Bluetooth   Device_X        -72 dBm

──────────────────────────────────────
Total Signals: 3
Average RSSI: -62.3 dBm
Strongest:    Network_A (-48 dBm)
```

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                         ROADMAP                             -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f6e0_fe0f/512.webp" width="28" /> Roadmap
</h2>

### ✅ Completed

- [x] Core Python prototype
- [x] SQLite database integration
- [x] Master authentication system
- [x] Secure password generator
- [x] Password manager (CRUD operations)
- [x] Signal scanner (Wi-Fi / Bluetooth)
- [x] GPS / ASCII map prototype
- [x] Activity logging
- [x] Auto-lock mechanism

### 🚧 Planned

- [ ] Hardware integration (Raspberry Pi / ESP32)
- [ ] Better encryption architecture (AES-256-GCM)
- [ ] Physical hardware buttons support
- [ ] OLED / LCD display interface
- [ ] Battery monitoring system
- [ ] Full modular architecture refactor
- [ ] Encrypted database at rest
- [ ] Secure hardware key storage (HSM)
- [ ] Improved Bluetooth LE support
- [ ] Advanced signal analytics dashboard
- [ ] Export / Import encrypted backups
- [ ] Multi-language UI support

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      HARDWARE VISION                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4e1/512.webp" width="28" /> ❖ Hardware Vision
</h2>

The long-term goal is to evolve Sovereign-X from a Python prototype into a **compact handheld security device**:

```
┌─────────────────────────┐
│     ◈ SOVEREIGN-X ◈     │
│                         │
│   ◈ OLED Display        │
│   ◈ Control Buttons     │
│   ◈ Wi-Fi Module        │
│   ◈ Bluetooth Module    │
│   ◈ GPS Receiver        │
│   ◈ MicroSD Storage     │
│   ◈ Rechargeable Batt   │
│                         │
│   [Prototype Vision]    │
└─────────────────────────┘
```

> ⚠️ This represents the **future hardware vision**. These physical components are not yet integrated and serve as the development roadmap for a potential embedded device.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                        PERFORMANCE                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/26a1/512.webp" width="28" /> ⚡ Lightweight by Design
</h2>

Sovereign-X is architected for **minimal resource consumption**, making it suitable for small embedded devices and portable terminals:

| Design Choice | Benefit |
|---------------|---------|
| **SQLite** | Zero-configuration, serverless database |
| **Standard Libraries** | Minimal external dependencies |
| **Background Scanning** | Non-blocking signal discovery |
| **Limited History** | Configurable retention to manage storage |
| **Terminal Interface** | Near-zero UI overhead |
| **Single-File Prototype** | Easy deployment and debugging |

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                      RESPONSIBLE USE                        -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f6e1_fe0f/512.webp" width="28" /> 🛡️ Responsible Use
</h2>

Sovereign-X is intended for:

- 📚 **Educational purposes** — Learning security concepts and Python system programming
- 🔐 **Personal data management** — Securing your own credentials locally
- 📡 **Authorized signal analysis** — Scanning wireless networks you own or have permission to analyze
- 🔧 **Hardware experimentation** — Building portable security tools on devices you control

**This project must NOT be used for:**
- Unauthorized network access or intrusion
- Intercepting private communications
- Password cracking against systems you do not own
- Any illegal or unethical security activities

> Always ensure you have **explicit permission** before scanning or analyzing any wireless network or device.

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                        DEVELOPER                            -->
<!-- ═══════════════════════════════════════════════════════════ -->

<h2 align="center">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f468_200d_1f4bb/512.webp" width="28" /> ❖ Developer
</h2>

<div align="center">

**Omar** — Software Developer

</div>

### Focus Areas

```
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│   Python    │  │   Software  │  │   Security  │
│             │  │ Development │  │  Concepts   │
└─────────────┘  └─────────────┘  └─────────────┘
┌─────────────┐  ┌─────────────┐  ┌─────────────┐
│ Automation  │  │    Bots     │  │     Web     │
│             │  │             │  │ Development │
└─────────────┘  └─────────────┘  └─────────────┘
         ┌─────────────────────┐
         │  System Architecture  │
         └─────────────────────┘
```

<br>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                         FOOTER                              -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->

<h1>❖ SOVEREIGN-X ❖</h1>

<p>
  <strong>Portable Security • Signal Analysis • Python</strong>
</p>

<br>

<p>
  <em>"Build small. Think big."</em>
</p>

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=DC143C&height=120&section=footer&text=&fontSize=0" width="100%" />

</div>
