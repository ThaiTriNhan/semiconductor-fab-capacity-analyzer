# Semiconductor FAB Capacity Analyzer

A portfolio project for learning Industrial Engineering applications in semiconductor manufacturing.

## Project Goal

Build a capacity planning and bottleneck analysis system using synthetic semiconductor FAB data.

The project will use:

- Python
- SQL
- Manufacturing capacity analysis
- Bottleneck detection
- Scenario analysis
- Data visualization

## Project Status

🚧 Work in progress


## Current Dataset

The project currently contains synthetic semiconductor FAB tool data created for educational and portfolio purposes.

### Tool Master Data

- 30 synthetic manufacturing tools
- 5 semiconductor process areas
- Theoretical WPH for each tool
- Toolset classification

### Tool Calendar

- 26 weeks of simulated operation
- Scheduled hours
- Preventive maintenance hours
- Downtime hours
- Available hours
- Effective capacity

### Capacity Model

Available Hours:

Available Hours = Scheduled Hours - PM Hours - Downtime Hours

Effective Capacity:

Effective Capacity = Theoretical WPH × Available Hours

### Current Analysis Scope

The current stage focuses on modeling tool-level manufacturing capacity.

The next stage will introduce:

- Production demand
- Product routing
- Process workload
- Capacity utilization
- Bottleneck identification

> All manufacturing data in this project is synthetic and created for educational and portfolio purposes.
