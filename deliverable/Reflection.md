# Reflection – FinCloud Security Summit

## Activity Description

For this assignment I attended the FinCloud Security Summit which focused on cloud security in financial systems Zero Trust architecture 
and the risks introduced by artificial intelligence. The event emphasized how AI-driven systems can introduce new vulnerabilities that come when implementing AI into a company 
and how employees working with AI may contribute to new vulnerabilities.
My goal was to understand how modern cybersecurity systems handle these risks, particularly in cloud environments. I took notes on key concepts such as Zero Trust security, 
AI security gateways, and continuous monitoring. Based on these ideas, I created a deliverable consisting of a Zero Trust architecture diagram and a Python simulation of an AI
security gateway.

---

## Technical Decisions

 I chose to simulate a key component discussed in the event: verifying requests before they reach an AI system.
In my implementation, I included multiple verification steps such as user authentication, device trust validation, and prompt inspection to detect potential prompt injection attacks.
i also added a simple risk scoring mechanism to evaluate potentially dangerous input the decision was based on the idea that modern security systems do not trust any inputs by default 
and must continuously validate requests thats what companies want

I also designed an architecture diagram that aligns with these ideas, showing how identity management, security gateways, AI services
and monitoring systems interact in a secure cloud environment.

---
## Contributions

This activity was completed individually. I attended the event, paid attention to the presented concepts and translated them into both a system design and a working code prototype of what
was learned.
I was responsible for all aspects of the project like design decisions, implementation, and documentation.

---
## Quality Assessment

I believe my participation in the event was effective because I actively engaged with the material and applied what I learned to a practical deliverable. 
The architecture diagram and code demonstrate my understanding of how Zero Trust principles can be applied to AI systems.
If I were to improve this project i would expand the prototype to include more advanced features such as real-time monitoring, logging systems, 
or integration with external APIs to better simulate a real-world environment. 
I would also explore more sophisticated AI threat detection techniques beyond simple pattern matching. Overall id say my deliverable wasnt complex but it was very effective at communicating
the idea of what the event was about and what I got out from it.

