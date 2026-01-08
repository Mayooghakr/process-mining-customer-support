# Process Mining & Event Log Analysis – Customer Support Tickets

# Objective
Analyze event-level customer support data to identify process bottlenecks,
cycle-time inefficiencies, and deviations using process mining techniques.

# Dataset
Customer support ticket dataset containing ticket IDs, ticket status,
creation time, first response time, and resolution time.

# Methodology
- Transformed raw ticket data into event logs (case IDs, activities, timestamps)
- Applied process discovery using PM4Py
- Performed cycle-time and bottleneck analysis
- Visualized process flows and performance metrics

# Key Insights
- Bottleneck observed between First Response and Ticket Closed stages
- High variability in ticket resolution times
- Process deviations identified in a subset of tickets

# Tools & Technologies
- Python
- PM4Py
- Pandas
- Matplotlib
- Seaborn

# Business Value
The analysis highlights opportunities to improve customer support efficiency
by reducing resolution delays and standardizing process workflows.
