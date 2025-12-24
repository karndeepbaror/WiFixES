
***🛰️ WifiES — Wi-Fi Evaluation System***

A Passive Wireless Environment Analyzer for Ethical Hackers & Cybersecurity Learners  

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-Python_3-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Developer-Karndeep_Baror-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Network-WiFi-0A84FF?style=for-the-badge">
</p>

***🔍 What is WiFixES?***

*WiFixES* `(Wi-Fi Evaluation System)` is a lightweight, terminal-based wireless scanning tool designed for ethical monitoring, educational purposes, and wireless risk analysis.

It passively scans nearby Wi-Fi networks and helps you `understand the wireless environment` around you — analyzing `signal strength, frequency, encryption, congestion`, and assigning `risk levels` based on key metrics.

⚠️ *WiFixES* does `not perform any attack` or disruption — making it 100% `legal, safe`, and `college-friendly`.



***🎯 Purpose:***

- Understand Wi-Fi signal behavior in real-time
- Identify congested or unstable wireless zones
- Evaluate the `security levels` of surrounding networks
- Help learners & researchers explore wireless behavior passively
- Ideal for `college projects`, `cybersecurity demos`, and `research reports`



***✨ Core Features:***

- ✅ Passive scanning (no network connection required)
- 📶 Display SSID, BSSID, Channel, Signal Strength (RSSI), Security Type
- ⚙️ Analyze frequency distribution and channel congestion
- 📊 Calculate `Stability Index` & `Risk Score`
- 🚦 Classify networks into `LOW`, `MEDIUM`, `HIGH` risk
- 🧠 Health Score of entire wireless environment
- 🗂️ Store scan history `(JSON-based)`
- 🧾 Optional text report generation



***🧑‍💻 Technologies Used:***

| Component      | Role                                   |
|----------------|---------------------------------------|
| Python 3       | Core scripting language                |
| pywifi         | Wireless interface access                |
| Linux OS       | Required for raw wireless operations  |
| JSON           | Data storage & history tracking       |



***💻 Terminal Preview:***
  
```
SSID           | Signal  | Security | Channel | Risk
---------------|---------|----------|---------|-------
Home_Network   | -45 dBm | WPA2     | 6       | LOW
Cafe_WiFi      | -72 dBm | Open     | 1       | HIGH
```


***📦 Installation:***

```
git clone https://github.com/karndeepbaror/WiFixES.git
cd WiFixES
cd WiFixES
pip install -r requirements.txt
```

**Run the tool:**

```
sudo python3 wifixes.py
```

`(Sudo is required for Wi-Fi interface access on Linux)`



***📝 Output Details:***

After every scan, `WifiES` displays:

- 🔹 SSID & BSSID
- 🔹 Signal Strength (in dBm)
- 🔹 Security Protocol `(WEP/WPA/WPA2/Open)`
- 🔹 Channel / Frequency
- 🔹 Congestion Level
- 🔹 Stability Score
- 🔹 Network Risk Classification
- 🔹 Optional Report Export `(JSON or .txt)`



***📚 Use Cases:***

- 🏫 College mini/major cybersecurity projects
- 🛡️ Ethical hacking demonstrations
- 📡 Wireless signal visualization
- 🕵️ Digital forensics support (passive observation)
- 🧪 Research on Wi-Fi behavior and network density



***🔐 Legal & Ethical Compliance:***

`WiFixES` performs *only passive monitoring* — it does *NOT*:

- Connect to any Wi-Fi network
- Inject, jam, or disrupt traffic
- Deauthenticate clients
- Interfere with network operations

✅ Fully aligned with `Indian IT Act`, `ethical hacking guidelines`, and global cybersecurity norms.



***🙋 Who Should Use WifiES?***

- Cybersecurity students & hobbyists  
- Networking & digital forensics learners  
- Professors & mentors `(for lab use)` 
- College teams needing ethical wireless analysis
- Tech creators looking to build on real-world problems



***🤝 Contribution:***

Pull requests, issues, and suggestions are welcome!  
If you'd like to contribute or improve this tool, just `fork & go 💻`



***📄 License:***

This project is licensed under the `MIT License`.  

***🧑‍💻 Author***

Made with 🖤 by *Karndeep Baror*

📎 LinkedIn: [ Connect On LinkedIn](https://www.linkedin.com/in/karndeepbaror)

⚡ Instgram: [ Follow on Instagram ](https://www.instagram.com/karndeepbaror)



***🌟 Star the Repo:***

If you found `WiFixES` helpful, do consider giving it a ⭐ on GitHub and sharing it with your cybersecurity circle
