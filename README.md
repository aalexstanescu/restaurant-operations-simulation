# Restaurant Operations Simulation

## Overview

Developed a discrete-event simulation of a five-station restaurant operation using Simio to analyze 16,000 historical customer orders and evaluate staffing decisions under varying demand conditions.

---

## Objective

The objective of this project was to evaluate how staffing policies and customer demand patterns affect restaurant throughput, queue lengths, resource utilization, and customer time in system while maintaining a 90% service-level target.

---

## Tools & Methods

- Simio
- Microsoft Excel
- Discrete-event Simulation
- Statistical Input Analysis
- Queuing Analysis

---

## Model Features

- Five sequential service stations
- Separate in-person and online customer workflows
- Hourly arrival-rate scheduling
- Stochastic service-time distributions
- Resource-constrained worker assignments
- Customer balking behavior
- Promise-time logic for online orders
- Multiple simulation replications
- Staffing scenario analysis

---

## Simio Model

The simulation models a five-station restaurant operation that processes both in-person and online customer orders while accounting for resource constraints, worker movement, and queuing behavior.

![Simio Model](images/simio-model.png)

The facility model represents customer flow through five sequential processing stations while incorporating worker movement, queuing behavior, and operational constraints.

---

## Process Flow

The process flow illustrates how customer orders move through the restaurant, including separate paths for in-person customers, prepaid online orders, and online customers paying in person.

![Process Flow](images/process-flow.png)

---

## High-Level Process Map

This high-level process map summarizes the end-to-end operational workflow from customer arrivals through order completion and restaurant exit.

![High Level PMAP](images/high-level-pmap.png)

---

## Data Analysis

Historical restaurant data covering a 30-day period was analyzed to determine arrival rates and service-time distributions for the simulation model.

### Hourly Arrival Analysis

![Arrival Analysis](images/arrival-analysis.png)

### Service Time Analysis

![Distribution Analysis](images/distribution-analysis.png)

---

## Key Experiment Results

Simulation experiments compared the existing operation against a scenario where 90% of online customers prepaid before arriving.

Increasing the proportion of prepaid online orders substantially reduced congestion at the payment station, resulting in lower customer time in system and improved overall operational performance.

| Metric | Original System | Proposed System |
|---------|----------------:|----------------:|
| Average Time in System | 14.21 min | 3.64 min |
| Pay Station Queue Length | 0.100 | 0.002 |
| Pay Station Utilization | 29.14% | 6.16% |

![Experiment Results](images/experiment-results.png)

---

## Skills Demonstrated

- Discrete-Event Simulation
- Process Modeling
- Queuing Systems
- Operations Research
- Capacity Planning
- Experimental Design
- Statistical Input Analysis
- Simulation Verification & Validation

---

## Repository Contents

- FinalSimioFreshMexProject.spfx — Simio simulation model
- SimioFreshMexDataset.xlsx — Historical dataset used for model inputs
- images/ — Process maps, simulation screenshots, and experiment figures

---

## Project Attribution

This simulation was completed as part of a team project. This repository highlights my individual contributions.

My contributions included:
- Building the Simio simulation model
- Implementing simulation logic and routing behavior
- Analyzing operational performance
- Conducting simulation experiments
- Supporting model verification and validation

---

## Future Improvements

Potential future enhancements include:

- Dynamic staffing optimization
- Additional operational policy experiments
- Simulation-based optimization of staffing levels and resource allocation
- Analysis of alternative customer demand scenarios
