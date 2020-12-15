# What are microservices?  
They are distributed computing implementation driven by the need to seperate software functionality over a network boundary so independent teams of engineers can deliver value in a loosly coupled, yet highly cohesive, approach.  If you're taking this approach, you've either calcualted the trade-off of speed-to-market vs. networking performance impact, or are experimenting and collectin data for such an approach.


## Evolution To Microservices
How do you go from your current architecture and implementation too microservices?  In a structured approach that decouples functionality from and existion system in a way which mitigates risk, and delivers return on invesment (ROI) in quick & manageable chunks.

- Refactoring the Monolith with tests - Identifying software boundaries and implementing them within the exisitng software
  - Pick a stateless funtion to start with
  - Make sure it's small and very specific; may need to abstract this funtion from an existing tightly-coupled implementation
  - Patterns - BCE - Boundary Controller Entity
- Adding Network Separation - Independent Service
  - First - Stateless Services - Functional Services, do not manage state or state devices (database, etc..)
  - Then - Stateful Services - Manage state or state devices
- First Mediation Layer - Gateway

