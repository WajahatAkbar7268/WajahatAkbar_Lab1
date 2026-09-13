# AI Lab 1 – ISPBot & Smart Travel Agent

This repository contains two parts of an Artificial Intelligence lab assignment: a conceptual AI agent write-up (ISPBot) and a coded AI agent (Travel Agent).

## Part 1: ISPBot – Smart ISP Recommendation Agent (PDF)

A simple rule-based intelligent agent that recommends the best Internet Service Provider (ISP) plan based on a user's budget, required speed, and usage type.

ISPBot follows the classic **sense → think → act** agent cycle:

1. **Senses** the user's requirements (budget, minimum speed, usage type).
2. **Reasons** over a database of available ISP plans to find suitable matches.
3. **Acts** by recommending the best matching plan to the user.

### Agent Formulation

| Component | Description |
|---|---|
| **Environment** | ISP market data: providers, prices, speeds, and usage types |
| **Sensors (Inputs)** | Budget, speed requirement, usage type, location |
| **Actuators (Outputs)** | Display recommendation, price & speed, comparison, alerts |

### Types of Environment

| Property | Type |
|---|---|
| Observability | Fully Observable |
| Determinism | Deterministic |
| Episodes | Episodic |
| Change | Static |
| Values | Discrete |
| Agents | Single-Agent |

### PEAS Framework

- **P (Performance):** Accurate recommendation, cost-effectiveness, user satisfaction
- **E (Environment):** ISP plans database, user requirements, market prices
- **A (Actuators):** Display output, comparison table, alerts
- **S (Sensors):** Budget, speed, usage type, location inputs

📄 Full write-up with the graphical workflow diagram, agent formulation, environment types, PEAS table, complete code, and a line-by-line code explanation: **`AI_Agent_Assignment_Wajahat_Akbar.pdf`**

## Part 2: Smart Travel Agent (Code)

A separate rule-based agent that recommends a travel destination based on the user's **budget**, **available days**, and **preferred trip type** (Beach, Mountain, City, Adventure). It follows the same sense → think → act cycle as ISPBot, applied to trip planning.

### How it works

1. Filters a destination database down to trips that fit the user's budget, days, and trip type.
2. Picks the best matching destination from the filtered list.
3. Displays the recommended destination, trip type, duration, and estimated cost.

**Output:**
```
Searching best travel destination for your trip...
Recommended Destination: Murree
Trip Type: Mountain
Duration: 2 days
Estimated Cost: PKR 15000
```

## 📁 Repository Contents

| File | Description |
|---|---|
| `AI_Agent_Assignment_Wajahat_Akbar.pdf` | Full ISPBot report (Part 1 deliverable) |
| `travel_agent.py` | Travel Agent Python script (Part 2 deliverable) |
| `travel_agent.ipynb` | Travel Agent Colab notebook (Part 2 deliverable) |
| `README.md` | This file |

## 👤 Author

**Muhammad Wajahat Akbar**
S/O Muhammad Akbar
Section C, 6th Semester BSCS
Seat No: 23122145
Federal Urdu University of Arts, Science and Technology

Submitted to: Ms. Uzma Afzal
