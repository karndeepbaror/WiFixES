# WifiES – Architecture

****Overview:****

`WiFixES` is structured in modular Python scripts for maintainability
and scalability. Each module is responsible for specific tasks.

****Modules:****

**1. Scanner Module (`wifixes.py`):**

   - Handles passive Wi-Fi scanning
   - Collects SSID, signal strength, channel, and security info

**2. Analyzer Module:**

   - Computes Stability Index
   - Calculates Environment Health Score
   - Classifies networks into LOW / MEDIUM / HIGH risk

**3. Report Module:**

   - Formats terminal output with Rich / Colorama
   - Optional text report generation
   - Maintains scan history (`wifix_data/scan_history.json`)

**4. CLI Module:**

   - Parses command-line arguments
   - Provides professional flags (`--scan`, `--deep`, `--export`, etc.)

****Design Principles:****

- Separation of concerns
- Passive and safe operations
- Terminal-first UI
- Modular code for future extensions