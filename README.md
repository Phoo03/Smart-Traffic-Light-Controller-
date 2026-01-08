
---

# Smart Traffic Light Controller (STLC)

### Discrete Mathematics & Data Analytics | SLIIT

An advanced traffic management simulation designed to optimize four-way intersection flow. This project leverages multi-dimensional data modeling and quadratic flow analysis to dynamically adjust signal timing based on real-world traffic density patterns.

---

## 🚀 Overview

Traditional traffic lights operate on fixed timers, leading to inefficiency and congestion. This system uses a **6×4×24 data tensor** (Lanes × Directions × Hours) to simulate a 24-hour cycle, providing a data-driven approach to urban flow management.

## 🧠 Key Technical Features

### 1. 3D Data Modeling

The core of the system utilizes a **6×4×24 tensor** to represent traffic demand. This high-dimensional structure ensures data consistency across the simulation, allowing for granular analysis of specific lanes at specific times of the day.

### 2. Analytics & Mathematical Modeling

The project moves beyond simple counting by applying discrete mathematics to traffic flow:

* **Quadratic Flow Modeling:** The system calculates the roots of flow equations to define critical thresholds between "Acceptable" and "Congested" regimes.
* **Emergency Overrides:** Includes logic for automated ambulance prioritization (as seen in the `AutoAmbulance` module).

### 3. Data Visualization

Built-in automated reporting provides visual insights for urban planners:

* **Line Charts:** Temporal analysis of vehicle density per lane over a 24-hour period.
* **Histograms:** Frequency distribution of daily traffic to pinpoint systemic peak hours.

---

## 🛠️ System Architecture

| Component | Description |
| --- | --- |
| **Language** | MATLAB / GNU Octave |
| **Data Structure** | 3D Tensor () |
| **Analysis** | Quadratic Root Calculation & Discrete Optimization |
| **Priority Logic** | Emergency Vehicle (Ambulance) Detection & Preemption |

---

## 🚦 How to Run

1. **Prerequisites:** Ensure you have **MATLAB** or **GNU Octave** installed.
2. **Clone the Repository:** ```bash
git clone https://www.google.com/search?q=https://github.com/your-username/smart-traffic-controller.git
```

```


3. **Execution:**
* Open MATLAB/Octave.
* Navigate to the project directory.
* Run the main simulation script:


```matlab
SmartTrafficController_7_AutoAmbulance

```



---

## 📈 Future Enhancements

* Integration of real-time IoT sensor data.
* Machine Learning implementation for predictive congestion modeling.
* Expansion to multi-intersection synchronization (Green Wave optimization).

---


