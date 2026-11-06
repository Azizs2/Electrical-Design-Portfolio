# ⚡ 150kV Substation Single Line Diagram (SLD)

## 📌 Project Overview
High-voltage digital substation architecture designed in strict compliance with international engineering standards (**IEC** & **EGAT**). This project covers a comprehensive configuration of 5 primary bays built for high-capacity power distribution, operational safety, and advanced protection interlocks.

---

## 🖼️ Technical Diagram Preview

![150kV Substation SLD](Images/PUT_150_GIS_E_ED_001.jpg.png)

> **Note:** The above diagram illustrates the primary circuit configuration, switching equipment, and core CT/VT parameter mapping for the 150kV substation bay arrangement.

---

## 📐 System Configuration & Scope

### 1. Bay Configurations (5 Primary Bays)
* **2x Line Bays (OHL No. 1 & OHL No. 2):** 
  * Equipped with Circuit Breakers (**Q0**), Disconnecting Switches (**Q1, Q2**), and Earth Switches (**Q8, Q9**).
  * Multi-ratio Current Transformers (**CT1 to CT5**) for protection & metering.
  * Voltage Transformers (VT), Surge Arresters (SA), and Cable Sealing Ends (**LISC**).
* **2x Transformer Bays (Trafo No. 1 & Trafo No. 2):** 
  * Dedicated CT/VT measurement and protection relay schemes.
  * Integrated Neutral Grounding Resistor (NGR) protection circuit.
* **1x Bus Coupler Bay & Bus VT/ES Configuration:** 
  * Bus interconnection switching and automatic voltage selection.
  * Dual bus bar system (**Main 1 & Main 2**) rated for high-capacity fault levels.

---

## 📊 Engineering Specifications & Technical Data

| Parameter | Specification / Standard | Details |
| :--- | :--- | :--- |
| **System Voltage** | 150 kV | High Voltage (HV) Transmission |
| **Busbar System** | Dual Busbar (Main 1 & Main 2) | High-capacity fault rating & switching flexibility |
| **Design Standards** | IEC Standards / EGAT Standards | International Grid Compliance |
| **CT/VT Core Mapping** | Multi-ratio ($V_k, R_{ct}$) | Main & Backup Protection, Tariff Metering, Bus Zone Protection |
| **Interlocking Logic** | Mechanical & Electrical | Operational safety preventing illegal switching |

---

## 🎯 Key Technical Highlights
* **Comprehensive Data Mapping:** Detailed CT/VT schedules calculating knee-point voltage ($V_k$), secondary resistance ($R_{ct}$), burden, and class accuracy for precision metering and fast fault clearing.
* **Protection Interlock Logic:** Designed with advanced safety interlocks between isolators, earthing switches, and circuit breakers to ensure zero human error during switching sequences.
* **Industrial Documentation:** Fully compliant with standard title blocks, symbol legends, and revision tracking systems used by global firms like **GE Vernova** and **Schneider Electric**.
