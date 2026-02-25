# ASEAN Maritime Bunkering Infrastructure & Economic Model
**A comparative System Dynamics study of maritime infrastructure development in Southeast Asia.**

## 📌 Project Overview
This Vensim model simulates the relationship between economic stability, investment levels, and the availability of bunkering infrastructure across five key ASEAN nations:
* 🇸🇬 **Singapore**
* 🇲🇾 **Malaysia**
* 🇵🇭 **Philippines**
* 🇹🇭 **Thailand**
* 🇻🇳 **Vietnam**

The model uses historical lookups for **Balance of Payments** and **Access to Finance** (2019-2023) to drive the growth of maritime infrastructure stocks.

## 📊 Model Structure & Logic
The model tracks the stock of **Availability of Bunkering Infra** for each country using the following core logic:

* **Stock:** `Availability of Bunkering Infra = INTEG (Inflow + Effect of Economic Stability - Effect on Investment, Initial_Value)`
* **Economic Drivers:** Uses detailed `WITH LOOKUP` functions for regional Balance of Payments and financial access metrics.
* **Key Interdependencies:** Analyzes how infrastructure availability feeds back into the national level of investment.

### Model Visualization


![ASEAN Model Structure](https://raw.githubusercontent.com/karungokihara/SEAN-Maritime-Bunkering-Infrastructure-Model/main/IMAGE.png)


## 📂 Repository Contents
* `ASEAN_Bunkering_Model.mdl`: The Vensim source file.
* `IMAGE.PNG`: Visual representation of the model's feedback loops.

## 🚀 Getting Started
1. **Requirements:** You will need **Vensim PLE** or higher to run the simulation.
2. **Execution:** Open the `.mdl` file, click **SyntheSim**, and toggle between countries to compare infrastructure growth trajectories based on their specific economic data.

---

## 📩 Contact
**Email:** [karungokihara@gmail.com](mailto:karungokihara@gmail.com)

## ☕ Support
If you find this maritime research helpful:
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/karungokihara)