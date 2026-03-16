# queue_simulation_project
A Python-based simulation tool for modeling service systems and waiting lines using queueing theory and Monte Carlo simulation.

The project was developed to apply theoretical concepts from statistics, operations research and queueing theory to real-world systems such as:
	•	retail checkout lines
	•	airport passport control
	•	service centers
	•	ticket counters
	•	any multi-server queue system

The simulator estimates waiting times and determines the minimum number of servers required to satisfy a target Service Level Agreement (SLA).

**Key Concepts Used**
The project applies concepts studied in queueing theory courses:
	•	Poisson arrival processes
	•	Exponential service time distributions
	•	Utilization factor (ρ)
	•	Monte Carlo simulation
	•	Service Level Agreements (SLA)
	•	Stochastic modeling of service systems

**Features**
	•	Simulation of customer arrivals using Poisson processes
	•	Realistic service time modeling using a truncated exponential distribution
	•	Monte Carlo simulation of daily operations
	•	Calculation of:
	•	average waiting time
	•	maximum waiting time
	•	total time in system
	•	SLA probability estimation
	•	Automatic calculation of required number of servers by hour
	•	Heatmap visualization of:
	•	waiting time
	•	SLA success probability
	•	Export of simulation results to CSV files

**Example Outputs**
The simulator produces:
	•	Average waiting time matrix
	•	SLA probability matrix
	•	Required number of servers by hour
	•	Heatmaps for visual analysis

**Technologies**
The project is implemented in Python using:
	•	Python
	•	NumPy
	•	Matplotlib
	•	CSV export for analytics

**How It Works**
	1. User enters system parameters:
	•	operating hours
	•	expected daily demand
	•	service time parameters
	•	SLA target
	•	hourly traffic weights
	2. The simulator generates:
	•	stochastic customer arrivals
	•	random service times
	3. Multiple simulations are executed to estimate:
	•	waiting time distributions
	•	SLA success probability
	4. The system determines the minimum staffing required to satisfy SLA constraints.

**Example Use Cases**
The simulator can model many real-world systems:
	•	retail stores
	•	airport security / passport control
	•	hospital reception
	•	call centers
	•	public service offices
	•	ticket booths
	•	customer support desks

**Future Improvements**
The current version of the simulator focuses on modeling queue dynamics and estimating staffing requirements. Several extensions could further improve the model and analytical capabilities:
	•	Waiting time distribution analysis
Add visualizations of waiting time distributions and queue length distributions to better understand system performance.
	•	Sensitivity analysis
Explore how system performance changes with different demand levels, service time variability, and staffing policies.
	•	Comparison with analytical queueing models
Compare simulation results with theoretical results from classical queueing models (e.g., M/M/s) to validate the simulation.
	•	Interactive analysis in Jupyter Notebook
Provide a notebook version of the simulator for easier experimentation, visualization, and explanation of the model.
	•	Scenario testing
Allow users to test different operational scenarios such as peak hours, demand shocks, or alternative staffing strategies.
	•	Improved visualization
Add additional charts and dashboards to better communicate simulation results and operational insights.

**Authors**
	•	Egor Balandin (github.com/tau-rt)
	•	Xeniya Mikheyeva (github.com/DeaDragonfly)
