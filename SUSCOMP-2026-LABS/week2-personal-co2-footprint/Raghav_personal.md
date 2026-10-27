# Personal CO2 Footprint Estimation - Week 2 Lab Notes

**Author:** Raghav[cite: 1]  
**Course:** Sustainable Computing (SUSCOMP-2026)[cite: 1]  
**Location:** Ljubljana, Slovenia  
**Carbon Intensity Source:** ~220 g CO₂e/kWh (Slovenian electricity grid baseline, European Environment Agency / Electricity Maps)

---

## 1. Device Inventory & Real-world Usage

### Device 1: Apple MacBook Air 13" (M1 chip, 2020)
* **What it is:** My main workhorse machine. I’ve been using this same MacBook Air for the last 5–6 years now, and as a CS student, it stays open practically all day for programming, lab work, terminal sessions, and coursework[cite: 1]. In my free time, I use it to upskill on Udemy or YouTube, or just watch random content.
* **Usage habits:** 
  * I log around **8.5 hours a day** of active screen work (varying between 7 to 10 hours depending on workload and lab days).
  * I **never shut it down**; I just close the lid and let it sleep.
  * Following our professor's suggestion during our Sustainable Computing lectures, I keep it permanently on **Low Power Mode / Energy Saver** in macOS settings. Since my daily tasks aren't heavy rendering (mainly VS Code, terminal, browser tabs, lightweight AI workflows, and video), the M1 runs completely silent and cool without drawing unnecessary power.
* **Usage breakdown:**
  * Active use: **8.5 hours/day** (59.5 hours/week | 3,102.5 hours/year)
  * Sleep mode (lid shut, background tasks): **15.5 hours/day** (108.5 hours/week | 5,657.5 hours/year)
  * Powered completely off: **0 hours**
* **Power ratings:**
  * Active power (Low Power Mode on, code editor, browser, video streaming, ~60% brightness): **~7.5 W**
  * Sleep mode (lid closed, connected to Wi-Fi for background push): **~0.25 W**
  * Turned off: **0.0 W**

**Calculations:**
* Daily energy:  
  $$(8.5\text{ h} \times 7.5\text{ W}) + (15.5\text{ h} \times 0.25\text{ W}) = 63.75\text{ Wh} + 3.875\text{ Wh} = 67.625\text{ Wh} = \mathbf{0.0676\text{ kWh/day}}$$
* Weekly energy:  
  $$0.0676\text{ kWh} \times 7 = \mathbf{0.4734\text{ kWh/week}}$$
* Yearly energy:  
  $$0.0676\text{ kWh} \times 365 = \mathbf{24.684\text{ kWh/year}}$$

---

### Device 2: Smartphone (Apple iPhone 16)
* **What it is:** My primary mobile phone, now about 2 years old. It has a battery capacity of roughly 3,560 mAh (~13.7 Wh).
* **Usage habits:**
  * Even though I constantly tell myself I want to cut down screen time, my average still sits right around **6 hours a day**.
  * Most of that time goes into staying connected (calls, messaging friends/family), but frankly, a big chunk is mindless social media scrolling. A bad habit I have is having the phone open right next to my MacBook while working on assignments, letting reels or feeds run simultaneously in the background—classic dual-screening and doomscrolling.
  * Charging behavior: I usually charge it once a day. I rarely top it off to 100%, usually stopping around 70–80% because of battery health tips I came across online.
* **Usage breakdown:**
  * Active screen-on time: **6.0 hours/day** (42.0 hours/week | 2,190.0 hours/year)
  * Idle / Standby (in pocket, desk, background notifications active): **18.0 hours/day** (126.0 hours/week | 6,570.0 hours/year)
  * Powered off: **0 hours**
* **Power ratings:**
  * Active power (display on, continuous 5G/Wi-Fi data transfer, video/social apps): **~2.6 W**
  * Idle / Standby mode: **~0.15 W**
  * Turned off: **0.0 W**

**Calculations:**
* Daily energy:  
  $$(6.0\text{ h} \times 2.6\text{ W}) + (18.0\text{ h} \times 0.15\text{ W}) = 15.6\text{ Wh} + 2.7\text{ Wh} = 18.3\text{ Wh} = \mathbf{0.0183\text{ kWh/day}}$$
* Weekly energy:  
  $$0.0183\text{ kWh} \times 7 = \mathbf{0.1281\text{ kWh/week}}$$
* Yearly energy:  
  $$0.0183\text{ kWh} \times 365 = \mathbf{6.680\text{ kWh/year}}$$

---

### Device 3: Home Wi-Fi Router
* **What it is:** Standard dual-band Wi-Fi router in the apartment keeping my laptop and phone connected.
* **Usage habits:** Runs **24 hours a day, 365 days a year**. Nobody ever unplugs it.
* **Power ratings:**
  * Constant active draw: **8.0 W**
  * Standby / Idle: **8.0 W** (always actively routing background packets)
  * Turned off: **0.0 W**

**Calculations:**
* Daily: $24.0 \times 8.0 = 192.0\text{ Wh} = \mathbf{0.1920\text{ kWh/day}}$
* Weekly: $0.1920 \times 7 = \mathbf{1.3440\text{ kWh/week}}$
* Yearly: $0.1920 \times 365 = \mathbf{70.080\text{ kWh/year}}$

---

## 2. Summary Table

$$\text{Annual CO}_2\text{e} = \text{kWh yearly} \times 0.220\text{ kg CO}_2\text{e/kWh}$$

| Device | Active Power (W) | Idle / Standby (W) | Off (W) | kWh Daily | kWh Weekly | kWh Yearly | Annual Footprint (kg CO₂e) |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **iPhone 16** (6h doomscroll/daily) | 2.60 W | 0.15 W | 0 W | 0.018 | 0.128 | 6.68 | 1.47 kg |
| **MacBook Air M1** (Energy Saver) | 7.50 W | 0.25 W | 0 W | 0.068 | 0.473 | 24.68 | 5.43 kg |
| **Wi-Fi Router** | 8.00 W | 8.00 W | 0 W | 0.192 | 1.344 | 70.08 | 15.42 kg |
| **Total** | — | — | — | **0.278** | **1.945** | **101.44** | **22.32 kg** |

---

## 3. Comparison with Household Appliances

To put my digital footprint (**101.44 kWh / year**) into perspective against typical domestic appliances:
* **Modern Refrigerator (70–120 kWh/year):**  
  My Wi-Fi router alone (~70.1 kWh/year) consumes as much electricity as an energy-efficient fridge. The continuous 24/7 draw of a simple 8 W network gateway quietly adds up to an entire cooling appliance's annual footprint.
* **Washing Machine (80–150 kWh/year):**  
  My entire three-device digital ecosystem (laptop, phone, and router) uses **~101.4 kWh/year**, which sits right in the middle of a typical household's annual washing machine usage (~3–4 loads per week).
* **Relative Share:**  
  The router accounts for roughly **69%** of my total direct digital electricity consumption, while my primary work tool (MacBook) accounts for **24%**, and my phone accounts for less than **7%**.

---

## 4. Reflections

Stripping my inventory down to just my personal computing devices and home connectivity highlights a stark contrast between user-facing hardware and always-on networking equipment:

1. **Duration Overpowers Active Watts:** I use my MacBook for up to 10 hours a day and my phone for 6 hours a day, yet the Wi-Fi router dwarfs both combined. The router pulls only 8 W, but because it runs all 8,760 hours of the year without any low-power or sleep state, it uses nearly triple the energy of my MacBook (~24.7 kWh) and over ten times that of my iPhone (~6.7 kWh).
2. **Apple Silicon & Energy Saver Impact:** Keeping the MacBook Air on Low Power Mode as recommended in lectures keeps the SoC operating at optimal efficiency points (~7.5 W during daily development, reading, and video tasks). Leaving the laptop sleeping with the lid closed draws only 0.25 W, meaning sleep mode contributes less than 1 kWh across an entire year. Not shutting down the machine has virtually no real penalty.
3. **The Insignificance of Direct Phone Charging:** Despite the guilt of doomscrolling and dual-screening while studying, the direct wall electricity required to keep a phone alive is surprisingly small (under 7 kWh/year). The true environmental consequence of smartphone habits does not lie in the battery charging cycle, but in the network data infrastructure required to deliver endless media feeds.

---

## 5. Extension: Network Traffic vs. Direct Energy

Direct device power is only a fraction of the story. While my iPhone and MacBook draw relatively little energy from the socket, streaming coursework, YouTube tutorials, and doomscrolling through video feeds creates continuous data movement through local and core telecom networks.

* **Estimated data use:** Roughly **10 GB/day** across laptop browsing, coding packages, and heavy mobile video streaming:
  $$10\text{ GB/day} \times 365\text{ days} = 3,650\text{ GB/year}$$
* **Network energy metric:** Using the standard fixed/mobile broadband network transmission intensity metric of **~0.06 kWh per GB** (Aslan et al.):
  $$3,650\text{ GB} \times 0.06\text{ kWh/GB} = \mathbf{219.0\text{ kWh/year}}$$

### Takeaway
The upstream electricity needed to route and transmit my data over the network (**219.0 kWh/year**) is **more than double the total direct electricity of all three devices combined** (101.4 kWh/year). 

While mobile chips and laptops have become extraordinarily power-efficient, every high-definition video streamed or reel scrolled requires edge cell towers, optical repeaters, and internet exchange switches to move those packets. From a sustainability standpoint, changing digital habits (like cutting down mindless background video feeds) has a far greater carbon impact than adjusting device screen brightness or unplugging a phone charger.