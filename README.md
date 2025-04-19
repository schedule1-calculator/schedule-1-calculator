# 🧪 Schedule 1 Calculator

[![Visit Site](https://img.shields.io/badge/Launch-schedule--1--calculator.com-blue?style=flat-square)](https://schedule-1-calculator.com)
[![Status](https://img.shields.io/badge/status-live-green?style=flat-square)](https://schedule-1-calculator.com)
[![License](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)](#license)

This repository contains a simple, standalone HTML-based calculator for experimenting with substance mixes in the game Schedule 1. It allows you to select a base product, add substances, and see the estimated results, including effects, cost, sell price, profit, and addiction.

This tool is designed for quick, basic experimentation and runs entirely in your web browser locally.

For the most accurate calculations, advanced features (like Reverse calculators, Best mixes database), and the complete set of rules, please use the full online [Schedule 1 Calculator](https://schedule-1-calculator.com/?utm_source=github) ⬅️

![schedule 1 basic calculator screenshot](https://raw.githubusercontent.com/schedule1-calculator/schedule-1-calculator/refs/heads/main/schedule-1-calculator-basic.webp)

## Features

* Select from available base products (e.g., OG Kush, Meth).
* Add up to 8 substances to your mix.
* Drag and drop substances to add, remove, or reorder them in your mix.
* Calculates estimated results:
    * Resulting Effects (Displays full names)
    * Total Cost
    * Estimated Sell Price
    * Estimated Profit
    * Profit Margin (%)
    * Addiction (%)
* User-friendly interface.
* Runs offline directly from the `index.html` file.

## How to Use Locally

1.  **Download:**
    * Go to the main page of this GitHub repository.
    * Click the green `<> Code` button.
    * Select `Download ZIP`.
    * Extract the downloaded ZIP file to a location on your computer.
2.  **Open:**
    * Navigate into the extracted folder.
    * Find the `index.html` file.
    * Double-click `index.html`, or right-click and choose "Open with" your preferred web browser (like Chrome, Firefox, Edge, Safari).

The calculator will load in your browser, and you can start creating mixes!

## How It Works

This calculator uses data and simplified logic derived from the Schedule 1 game mechanics:

1.  **Select Product:** Choose a base product from the dropdown menu. This sets the initial effects and base price.
2.  **Add Substances:** Drag substances from the "Available Substances" list to the "Selected Mix" list. You can add up to 8 substances.
3.  **Order Substances:** Drag substances within the "Selected Mix" list to change their order. *Note: While you can reorder substances, the simplified logic in this basic calculator doesn't implement the complex, order-dependent rule interactions found in the full game or advanced calculators.*
4.  **Calculate:** Click the "Calculate Mix" button.
5.  **View Results:** The tool calculates:
    * **Cost:** Sum of the prices of the selected substances.
    * **Effects:** Starts with the product's base effects, adds effects from substances (up to 8 total), and applies a *simplified* set of transformation rules.
    * **Sell Price:** Calculated based on the product's base price and the value multiplier of the final effects.
    * **Profit:** Sell Price - Cost.
    * **Profit Margin:** (Profit / Sell Price) * 100.
    * **Addiction:** Sum of the addiction values of the final effects.

## Data Used

The calculator includes the following data based on the game:

### Products

* OG Kush
* Sour Diesel
* Green Crack
* Grandaddy Purple
* Meth
* Cocaine

### Substances

* Cuke
* Flu Medicine
* Gasoline
* Donut
* Energy Drink
* Mouth Wash
* Motor Oil
* Banana
* Chili
* Iodine
* Paracetamol
* Viagra
* Horse Semen
* Mega Bean
* Addy
* Battery

### Effects (and their base value/addiction)

* Calming, Refreshing, Energizing, Sedating, Bright-Eyed, Calorie-Dense, Euphoric, Toxic, Athletic, Balding, Anti-Gravity, Munchies, Slippery, Gingeritis, Sneaky, Thought-Provoking, Spicy, Paranoia, Tropic Thunder, Glowing, Cyclopean, Foggy, Explosive, Laxative, Long Faced, Jennerising, Electrifying, Disorienting, Schizophrenia, Seizure-Inducing, Zombifying, Focused, Smelly, Shrinking.

### Rules

This calculator implements a *very limited* set of the effect transformation rules found in the game. For example:
* Flu Medicine might change 'Calming' to 'Bright-Eyed' if 'Calming' is present.
* Cuke might change 'Euphoric' to 'Laxative' if 'Euphoric' is present.

**Important:** The complex interactions and full set of rules are *not* implemented in this basic version. Results may differ significantly from the actual game or more advanced calculators.

## ✨ Need More Power? Use the Advanced Calculator! ✨

This basic HTML tool is great for quick offline checks, but for the most accurate calculations, advanced features, and the complete set of rules, please use the full online Schedule 1 Calculator:

➡️ **[Visit the Schedule 1 Calculator](https://schedule-1-calculator.com/)** ⬅️

The advanced calculator offers:

* Accurate implementation of all known rules and interactions.
* Reverse calculators (find mixes for desired effects).
* Best mixes database.
* Detailed breakdown of calculations.
* And much more!

## Disclaimer

This is a fan-made tool created for educational and experimental purposes related to the game Schedule 1. It is not affiliated with, authorized, maintained, sponsored, or endorsed by the developers of the game. All game-related content, including names and mechanics, belongs to the respective game developers. Use this tool as a guideline, as game mechanics can change.

---

## 🧾 License

MIT — feel free to fork, extend, or remix (credit appreciated).
