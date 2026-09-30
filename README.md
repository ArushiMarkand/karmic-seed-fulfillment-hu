# karmic-seed-fulfillment-hu
# XYZ Fulfillment Hub — Operational Solution

**Author:** Arushi Markand  
**Role:** Operations Analyst Take-Home Project | **Company:** Karmic Seed  

---

## Project Overview
This project presents an interactive **Fulfillment Hub Application** built inside Jupyter Notebook using `pandas` and `ipywidgets`. It is designed to streamline XYZ's e-commerce operations, eliminate SLA breaches, prevent warehouse picking freezes, and provide real-time courier visibility.

---

## 4 Core Operational Priorities Solved

1. **Priority SLA Management:** Live KPI tracking with forced top-of-queue sorting and distinct red visual highlighting for high-priority orders to prevent missed cutoffs.
2. **Low-Friction Warehouse UI:** A clean, single-screen interactive terminal with simple dropdown status filters designed specifically for non-technical floor operators.
3. **Stock Replenishment Triggers:** Automated inventory monitoring that detects Main Warehouse stock depletion and calculates exact transfer quantities required from Secondary Overflow storage before picking freezes occur.
4. **Courier & Dispatch Visibility:** Comprehensive performance monitoring that tracks pending order volume, pickup cutoffs, and carrier SLA compliance across couriers (Delhivery, Blue Dart, Ecom Express, DTDC).

---

## Repository Structure

* `XYZ_Fulfillment_Hub.ipynb` — Interactive Python notebook containing the operational application code.
* `XYZ_Fulfillment_Hub.html` — Exported static HTML view for instant browser review without running code.
* `orders.csv` — Order placement data including SLA deadlines, priority status, and order stages.
* `inventory.csv` — Stock levels across Main and Secondary Overflow warehouses.
* `products.csv` — Product metadata, category, variant info, and pricing.
* `couriers.csv` — Courier operational metadata, cutoffs, and reliability metrics.

---

## How to Run the Application

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/karmic-seed-fulfillment-hub.git](https://github.com/YOUR_GITHUB_USERNAME/karmic-seed-fulfillment-hub.git)
   cd karmic-seed-fulfillment-hub
