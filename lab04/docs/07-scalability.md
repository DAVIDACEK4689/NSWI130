## Scalability

The system should be able to handle increased workload without degradation in performance, with a scalable architecture that allows for the addition or removal of resources as needed to meet changing demand.

### Type
**Run-time**

**Authors:**
- Jan Jevčák
- Jan Svojanský

### Scenario

| Key                | Value |
|--------------------|-------|
| Source of Stimulus | Enrolled Students |
| Stimulus           | Increase the number of students and courses at the start of new academic year |
| Artifact           | Enrollment Database |
| Environment        | Normal operating conditions |
| Response           | The system scales to accomodate the increase in data and request |
| Measure            | System handles 100% of request without degradation |

### Conclusion
⚠️

### Reason/Solution
Adopt horizontal scaling.
