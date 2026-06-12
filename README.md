<h1 align="center">🖥️ System Hardware & Environment Monitor</h1>

<p align="center">
  A lightweight Python-based command-line tool that retrieves and displays detailed system hardware, network, and environment information in real time.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Type-CLI%20Tool-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-lightgrey?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Stable-success?style=for-the-badge">
</p>

---

<h2>📌 Project Overview</h2>

<p>
This project is a <b>Python command-line system monitoring tool</b>.  
It runs directly in the terminal or any Python-supported IDE and does not require compilation or installation as a standalone software.
</p>

<p>
It collects real-time system data using Python libraries and Windows system commands.
</p>

---

<h2>⚙️ Features</h2>

<ul>
  <li>🪟 Operating System detection (Windows version)</li>
  <li>🧠 CPU information (name, cores, threads, frequency, usage)</li>
  <li>🎮 GPU name and utilization</li>
  <li>📦 RAM usage (total, available, percentage)</li>
  <li>💾 Storage information (C drive)</li>
  <li>🌐 Network details (hostname and IP address)</li>
  <li>📡 Internet connectivity status check</li>
  <li>⏱️ System boot time</li>
</ul>

---

<h2>🚀 How to Run</h2>

<pre>
# Clone the repository
git clone https://github.com/nahiansiam/SYSTEM-HARDWARE-ENVIRONMENT-MONITOR

# Navigate to project folder
cd SYSTEM-HARDWARE-ENVIRONMENT-MONITOR

# Install required dependencies
pip install psutil py-cpuinfo

# Run the script
python main.py
</pre>

---

<h2>📦 Requirements</h2>

<pre>
Python 3.8+
psutil
py-cpuinfo
</pre>

---

<h2>🧠 Technical Details</h2>

<ul>
  <li>Built using Python standard libraries and system APIs</li>
  <li>Uses <b>psutil</b> for hardware monitoring</li>
  <li>Uses <b>cpuinfo</b> for CPU identification</li>
  <li>Uses Windows <b>WMIC</b> commands for GPU detection</li>
  <li>Designed for terminal-based execution (no GUI)</li>
</ul>

---

<h2>👨‍💻 Author</h2>

<p>
<b>Nahian Kabir Siam</b><br>
Computer Science & Engineering (CSE)
</p>

<p>
🔗 GitHub: <a href="https://github.com/nahiansiam/SYSTEM-HARDWARE-ENVIRONMENT-MONITOR">Project Repository</a>
</p>

---

<h2>⭐ Support</h2>

<p>
If you find this project useful, consider giving it a ⭐ on GitHub.
</p>
