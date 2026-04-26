# Bookstore Queue Simulation (Modeling & Simulation)

## Overview

This project simulates a **queue system** for a bookstore ("Book Nook") with a single checkout counter.

The simulation models customer arrivals and service times using **probability distributions** and evaluates system performance using key metrics.

---

## Author

**Habiba Abouraya**

---

## Objectives

* Simulate customer flow in a queue system
* Model interarrival and service times
* Analyze system performance
* Apply probability distributions in simulation

---

## Problem Description

The bookstore operates with:

* **1 checkout counter (server)**
* Customers arrive at random intervals
* Each customer requires a random service time

### Input Data

#### Interarrival Time Distribution

| Time (min) | Probability |
| ---------- | ----------- |
| 0          | 0.1         |
| 1          | 0.2         |
| 2          | 0.3         |
| 3          | 0.2         |
| 4          | 0.1         |
| 5          | 0.1         |

#### Service Time Distribution

| Time (min) | Probability |
| ---------- | ----------- |
| 2          | 0.1         |
| 3          | 0.25        |
| 4          | 0.3         |
| 5          | 0.2         |
| 6          | 0.15        |

---

## Simulation Approach

The system is implemented using:

1. **Deterministic Input**

   * Using exact given values

2. **Random Input**

   * Generated using random numbers based on probability distributions

---

## Simulation Details

* Number of customers: **50**
* Single-server queue model
* First-Come, First-Served (FCFS)

---

## Performance Metrics

The following metrics are calculated:

* Average time in queue
* Average time in system
* Average queue length
* Server utilization
* Average waiting time
* Probability of waiting
* Probability of server being idle
* Average service time
* Average time between arrivals
* Average waiting time (for those who wait)

---

## How It Works

1. Generate arrival times
2. Generate service times
3. Compute:

   * Start time
   * Waiting time
   * Finish time
4. Track queue behavior
5. Calculate final statistics

---

##  How to Run

1. Open the project
2. Run the program
3. View simulation table and results

---

