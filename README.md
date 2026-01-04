# airflow-task-dependencies
This repository contains simple Apache Airflow DAGs illustrating task orchestration, dependency management, scheduling with intervals, and BashOperator execution. Built for learning and demonstration purposes
## Apache Airflow DAG – Task Dependencies Example

This project demonstrates how to:
- Define an Airflow DAG
- Use BashOperator
- Configure task dependencies
- Execute multiple parallel task paths
- Use template_searchpath for Bash scripts

### DAG Structure
taskA triggers three parallel paths:
- taskA → taskB → taskE
- taskA → taskC → taskF
- taskA → taskD → taskG

### Technologies Used
- Apache Airflow
- Python
- Bash scripting
<img width="1134" height="549" alt="Screen Shot 2026-01-04 at 10 30 37 PM" src="https://github.com/user-attachments/assets/42355c33-4584-4d87-99aa-935c37ec9ef6" />
