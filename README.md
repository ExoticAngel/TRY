key principles of DevOps
2.
Automation: DevOps promotes automating everything possible—building, testing, deployment, 
infrastructure provisioning, and monitoring. This removes manual, error-prone tasks,
boosts efficiency, and guarantees consistency and repeatability.
3.
Continuous Integration and Continuous Delivery (CI/CD): CI is the practice of developers frequently merging code changes into a central repository,
triggering automated builds and tests. CD extends this by automatically deploying all code changes to a testing or production environment after the build stage, 
making deployments predictable, low-risk events.
4.
Infrastructure as Code (IaC): IaC is the management of infrastructure through machine-readable rather than physical hardware configuration or interactive configuration tools.
The benefits include versioning and consistent environments from development to production, eliminating problems.
benefits 
->Increased Deployment Frequency: Automation and CI/CD enable teams to release new features and bug fixes much faster, 
from quarterly releases to multiple deployments per day.
->Faster Time to Market: By streamlining the entire software delivery process,
organizations can respond more quickly to market changes and customer feedback.
->Improved Collaboration and Morale: Breaking down silos reduces blame culture and fosters a more collaborative,
efficient, and innovative environment.

Advantages and Challenges of Infrastructure as Code
Advantages:
•
Speed and Efficiency: Automating infrastructure provisioning is orders of magnitude faster than manual processes.
Development, staging, and production environments can be spun up or down in minutes.
•
Version Control & Documentation: Infrastructure definitions are versioned alongside application code. 
You have a complete history of who changed what and when. The code itself serves as documentation.

A release strategy is a planned approach for organizing software updates in a controlled manner,
minimizing downtime, minimizing risks, and ensuring reliability.

Canary deployment releases the new feature to a small subclass of users before full rollout, 
allowing monitoring and proof with minimal risk. It is suitable when gradual validation and feedback are needed.
•
Blue-green deployment runs two identical production environments, blue and green; 
traffic switches instantly from old blue to new green after deployment
