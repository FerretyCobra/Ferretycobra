<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=700&size=32&duration=3000&pause=1000&color=6C63FF&center=true&vCenter=true&random=false&width=650&lines=Hi%2C+I'm+Om+Santosh+Lokhande+%F0%9F%91%8B;Software+Developer+%40+FrostFire+Tronics;Founder%2C+Fundless+Studio;Flutter+%C2%B7+Python+%C2%B7+Java+%C2%B7+Unity" alt="Typing SVG" />
</h1>

<p align="center">
  <strong>Software Developer @ FrostFire Tronics · Founder, Fundless Studio · Pune, India</strong>
</p>

<p align="center">
  <a href="https://linkedin.com/in/om-lokhande"><img src="https://img.shields.io/badge/LinkedIn-om--lokhande-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:Omlokhande04@gmail.com"><img src="https://img.shields.io/badge/Email-Omlokhande04%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 🧑‍💻 About Me

I build and ship software end to end, usually for a real client with a deadline. My work runs at housing-society gates, shop counters, hospital wards and on Bluetooth thermal printers.

- 🏢 **Software Developer at FrostFire Tronics**: I work across a twelve-product portfolio (billing, token queueing, IoT gate security, society management, thermal printing) and lead the FF Billing move from Xamarin.Forms to Flutter
- 🏥 **Ex-intern at ICMR-NITVAR, Pune**: sole developer of the data-capture platform for a national ICMR hospital study (React, Firebase), signed off and handed over with SOPs
- 🎮 **Founder of Fundless Studio**: building **Horizon's Edge**, a one-thumb highway racer for Android
- 🎓 **B.E. Computer Engineering, Honours in Data Science**: Dr. D. Y. Patil College of Engineering & Innovation, SPPU (2022–2026)

---

## 🏎️ Horizon's Edge · Fundless Studio

> An endless, one-thumb highway racer for Android. Weave through dense traffic at dusk; the closer you pass, the more you score. **Entering Google Play internal testing.**

![Unity](https://img.shields.io/badge/Unity_6-000000?style=flat&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![URP](https://img.shields.io/badge/URP-222C37?style=flat)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat&logo=blender&logoColor=white)
![NUnit](https://img.shields.io/badge/NUnit-25A162?style=flat)

- **Designed and directed the game end to end**: near-miss scoring, one-thumb gesture controls, a 16-car fleet defined as data and a six-district city-to-ocean route, tuned through on-device playtests
- **Built for low-end phones**: three quality tiers (render scale, shadows, draw distance, light budgets) targeting 30–60 fps on Android, checked with Unity Profiler
- **Release-ready**: automated EditMode and PlayMode tests, Google Play Games integration, a licence audit of every shipped 3D asset and the Play Store build pipeline

---

## 🏗️ Featured Projects

### 🌐 [Internet Separator](https://github.com/FerretyCobra/InternetSeparator)
> Use Wi-Fi, Ethernet and USB tethering at the same time, and choose which app uses which connection. [**⬇ Download for Windows**](https://github.com/FerretyCobra/InternetSeparator/releases/latest)

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-0078D4?style=flat&logo=windows&logoColor=white)

- **Per-app routing**: runs mihomo in TUN mode and sends each process out through the adapter you picked
- **Pins that survive**: pinned apps keep their connection across restarts, and wait when a network is unplugged
- **Live view**: one column per connection with download/upload speed and a health check
- **Single self-contained exe** that starts minimised in the tray at sign-in

---

### 🖨️ [FF PrintFlow / MyThermalPrint](https://github.com/FerretyCobra/MyThermalPrint)
> Print anything from Android to a Bluetooth thermal printer. **Published to Google Play (public beta).**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-34A853?style=flat&logo=android&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

- **ESC/POS pipeline**: fixed failing long prints by sending bitmaps in 200 px strips with per-strip flow control
- **3 binarisation algorithms**: gamma threshold · Otsu adaptive · Floyd–Steinberg dithering, chosen per job
- **Print from any app** through the Android share menu
- **Server-side licensing**: PHP/MySQL API with device authentication, subscription tiers and time-limited grants

---

### 📡 [NoiseLogger](https://github.com/FerretyCobra/Noise_Logger)
> Crowdsourced urban noise mapping with real-time safety alerts. **Copyright granted, sole author.**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Android](https://img.shields.io/badge/Android-34A853?style=flat&logo=android&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Leaflet.js](https://img.shields.io/badge/Leaflet.js-199900?style=flat&logo=leaflet&logoColor=white)

- **Calibrated 0–120 dB readings** from 16-bit PCM audio, skipping the first 250 ms of each capture to remove mic gain artefacts
- **87 dB safety alerts** with vibration and notifications, from a foreground service that survives reboots
- **Hotspot detection**: GPS-tagged readings grouped into ~11 m grid cells on a Leaflet dashboard

---

## 🏢 Work at FrostFire Tronics

<sub>Company code is private. These are the products I build and maintain.</sub>

| Product | What it is | Stack |
|---|---|---|
| **FF Billing** | GST billing app; leading an eight-phase rewrite from Xamarin.Forms to Flutter with a unit-testable billing engine | Flutter, Riverpod, NestJS |
| **FGS Guard** | Gate-guard tablet app for Frostfire Gated Security; redesigned 20+ screens with motion | Flutter, Raspberry Pi 5, WebSocket |
| **Gym Management System** | Desktop gym suite with hardware-locked licensing and an offline installer | Flutter Desktop, Flask, Ed25519 |
| **FF Tracker** | Self-hosted project tracker that derives worked time from an event log | Fastify, PostgreSQL, Flutter |
| **FF Token** | Token and POS dashboard for counters and restaurants | Flutter |
| **Society Admin** | 19-screen society management app with multi-tenant isolation and three-tier roles | Flutter, Flask, SQLAlchemy |

---

## 🛠️ Tech Stack

<table>
<tr>
<td><b>Languages</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)

</td>
</tr>
<tr>
<td><b>Mobile & Frontend</b></td>
<td>

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-0553B1?style=flat)
![Android](https://img.shields.io/badge/Android-34A853?style=flat&logo=android&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![WPF](https://img.shields.io/badge/WPF-0078D4?style=flat&logo=windows&logoColor=white)
![Leaflet.js](https://img.shields.io/badge/Leaflet.js-199900?style=flat&logo=leaflet&logoColor=white)

</td>
</tr>
<tr>
<td><b>Backend & Data</b></td>
<td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DD0031?style=flat&logo=redis&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

</td>
</tr>
<tr>
<td><b>Games & 3D</b></td>
<td>

![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat&logo=blender&logoColor=white)

</td>
</tr>
<tr>
<td><b>DevOps & Hardware</b></td>
<td>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat&logo=raspberrypi&logoColor=white)
![ESC/POS](https://img.shields.io/badge/Bluetooth_ESC%2FPOS-0082FC?style=flat&logo=bluetooth&logoColor=white)

</td>
</tr>
</table>

---

<p align="center">
  <b>Open to software engineering roles · Pune, open to relocation</b>
</p>

<p align="center">
  <a href="https://linkedin.com/in/om-lokhande"><img src="https://img.shields.io/badge/Let's_Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:Omlokhande04@gmail.com"><img src="https://img.shields.io/badge/Email-Omlokhande04%40gmail.com-6C63FF?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
