# Zinlanthor's Digital Cookbook 🐢

Welcome to the **Zinlanthor Recipe Repository**. This project hosts structured recipe data (JSON-LD) wrapped in HTML, specifically engineered for seamless voice-guided cooking on **Google Home** and **Nest Hub** smart displays.

---

## 🚀 Quick Start: Syncing to Your Device
1. **Open the Index:** Navigate to the [Master Index](https://zinlanthor.github.io/recipes/) on your mobile device.
2. **Use the Google App:** Ensure you open the specific recipe page within the **Google App** (not just a standard browser shell) to trigger the sync.
3. **Save:** Tap the **"Add to Cookbook"** or **"Start Cooking"** button.
4. **Invoke:** Once saved, stand in your kitchen and say:
   > *"Hey Google, start cooking [Recipe Name]"*

---

## 🗣️ Overlapping Naming Protocols (The "ZIN" Method)
To solve the friction of remembering exact titles, this repo uses an extensive `alternateName` strategy:
* **The List Effect:** If multiple recipes share a generic name like **"Zinlanthor's Pasta"**, your device will present a visual selection menu.
* **Fuzzy Search:** Recipes include 60+ search tags ranging from ingredients (*"Sausage Dish"*) to situational vibes (*"Emergency Pantry Meal"*).

---

## ⏲️ Timer Protocols
Precision is handled via integrated voice commands. When a step requires timing, the instruction will include the exact phrase to use.
* **Naming Convention:** Timers are named by task (e.g., "Pasta Timer") to allow for multiple concurrent countdowns.
* **Standard Command:** *"Hey Google, set a [Task] Timer for [X] minutes."*

---

## 🥗 Substitutions & Optional Ingredients
We use a "Developer-Lite" documentation style for ingredients:
* **Format:** `[Ingredient Name] (Optional) [Substitution below]`
* **Logic:** A dedicated line starting with `SUBSTITUTION:` follows immediately, ensuring the Google Assistant reads the alternative during the automated ingredient readout.

---

## 🧪 Measurement & Quantity Vernacular
All recipes utilize dual-measurements (**Imperial & Metric SI**) for precision.

| Vernacular | Exact Imperial | Metric Equivalent |
| :--- | :--- | :--- |
| **A Smidgen** | 1/32 tsp | 0.15 ml |
| **A Pinch** | 1/16 tsp | 0.3 ml |
| **A Dash** | 1/8 tsp | 0.6 ml |
| **Standard Cup** | 8 fl oz | 236 ml |
| **Standard Tbsp** | 0.5 fl oz | 15 ml |
| **Standard Tsp** | 0.16 fl oz | 5 ml |

---

## 🍳 Technical Cooking Glossary (ZIN Standard)
* **Blanching:** Briefly boiling food, then immediately "shocking" in an ice bath to stop cooking and preserve color/texture.
* **The Roux:** A foundational thickener of equal parts flour and fat.
* **The Liaison:** Tempering egg yolks and liquid into a dish. **[SAFETY: TURN HEAT TO LOW/OFF TO PREVENT SCRAMBLING]**.
* **Mise en Place:** Prepping all ingredients and tools before applying heat.
* **Deglaze:** Using liquid to lift the "fond" (flavor bits) from the bottom of a hot pan.
* **Emulsify:** Binding oil and water into a smooth sauce, usually via starchy pasta water.
* **Reduction:** Simmering liquid to thicken it and intensify flavor.
* **Sweat:** Softening vegetables in fat over low heat without browning them.
* **Al Dente:** "To the tooth"—firm but cooked pasta.

---

## 🛠️ Google Home Tips & Troubleshooting
* **Refresh Sync:** If you update a recipe and your device shows the old version, say: *"Hey Google, sync my devices."*
* **The "My Recipe" Prompt:** If Google ignores your file for a web search, say: *"Hey Google, start cooking MY recipe for [Name]."*
* **Voice Navigation:** Use *"Hey Google, Next Step"*, *"Hey Google, Repeat Step"*, or *"Hey Google, Scroll Down"* for hands-free control.

---

## 📜 Version History
| Version | Date | Highlights |
| :--- | :--- | :--- |
| **v1.6** | 2026-01-18 | Integrated **Metric SI** & **Timer Commands**; Expanded Glossary. |
| **v1.5** | 2026-01-18 | Standardized author to **Zinlanthor**; Added 60+ alternate naming tags. |
| **v1.4** | 2026-01-18 | Implemented strict **SUBSTITUTION** ingredient formatting. |

---

## 🐢 About the Author
**Zinlanthor** is a self-taught programmer (novice-intermediate) dedicated to high-fidelity culinary automation.
