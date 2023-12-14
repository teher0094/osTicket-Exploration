# osTicket-Exploration

## Project Overview



## Objectives
- **Ticket Simulation:** Generate tickets to be processed by agents.
- **Department Structuring:** Organize agents into appropriate Teams and Departments
- **Severity Level Configuration:** Create different levels of severity for ticket triage. 
- **Agent Setup:** Create agents and configure access based on team membership.

## Technologies Used
- Remote Desktop Connection
- Microsoft Azure
- Windows 10 Pro
- osTicket

## Structure and Setup
- In the osTicket setup for Americorp, I created a total of 12 users and organized them into six distinct departments reflective of a typical IT department in a real-world company. These departments include Support, Feedback and Improvement, Helpdesk Support, Network Performance and Monitoring, Security and Compliance, and Technical Issues.
- The entire IT staff was managed my 2 admins. Each department was structured with a specific team comprising two users, a team lead and their junior technician. This team size was chosen to simulate a balance between efficient workload distribution and effective collaboration. For instance, the Support team was tasked with overarching system management, while the Feedback and Improvement team focused on analyzing user feedback to enhance service quality.
- The decision to include these particular departments was driven by their relevance and importance in a standard IT operation, ensuring that the Americorp simulation covered a broad spectrum of IT functionalities. This organizational structure provided valuable insights into the dynamics of IT support and service management, closely mirroring the intricacies of a real-world business setup.

![image](https://github.com/teher0094/osTicket-Exploration/assets/153027290/490360b7-3852-45c2-b74b-296d65e2bb26)


## Agent Setup 
- In the Americorp osTicket system, the agent structure consists of 12 members, including 2 admins, 5 team leads and 5 junior technicians. Each agent had varying levels of access and capabilities tailored to their roles.

**Agent Roles and Abilities:**
- Tier 1 Agents: Assigned to handle general inquiries and basic troubleshooting. Their abilities encompass creating tickets, closing tickets, reassigning them to the appropriate department or agent, and editing tickets by adding comments or updates to the ticket thread.
- Tier 2 Agents: Equipped with more advanced capabilities, Tier 2 agents possess all the abilities of Tier 1 with the additional capabilities of deleting tickets and editing thread items created by other agents.

- Junior technicians who are responsible for the fundamental aspects of ticket management has Tier 1 abilities. Team leads have Tier 2 abilities for better oversight and ticket management. 
- The Admins also have Tier 2 abilities along with special Extended Access. This Extended Access allows them to view and manage tickets across all departments, a capability not available to other agents. Admins oversees the entire ticketing operation, perform system configuration, ensure smooth workflow across departments, and intervene in situations that require higher-level attention or system-wide changes.

The differentiation in access and abilities between the admins and agents, as well as between the Tier 1 and Tier 2 agents, is designed to reflect a real-world IT support structure. Agents operate within their scope of expertise, contributing to their respective department's functionality, while admins provide overarching management and support, crucial for maintaining operational integrity and service quality.

## Ticket Lifecycle Simulation and Help Topics
- In the osTicket system, the ticket lifecycle begins with the client side, where users can create tickets, and transitions to the staff side for resolution. To understand this process fully, I simulated both roles.
- As a client, ticket creation involves selecting an appropriate help topic – such as 'Critical Error' or 'Software Troubleshooting' – and providing a detailed description of the issue. This categorization via help topics is crucial, as it guides the user in accurately conveying their problem, facilitating more efficient ticket handling.
- Once a ticket is created, its urgency determines the automatic assignment: urgent matters are directed to the Technical Issues department, while general queries go to Helpdesk Support, where they can be reassigned if necessary. As a staff member, I simulated the process of receiving these tickets, reviewing their content, and updating the ticket with progress notes. The ticket is marked as resolved and closed once the issue is completely addressed.
- Although actual troubleshooting was beyond the scope of this exercise, engaging in this simulation provided me with a hands-on understanding of the ticketing system's operation. It highlighted the importance of clear communication between clients and staff, and efficient ticket categorization and handling. This experience has equipped me with practical knowledge that will undoubtedly be valuable in managing real-world IT support scenarios.

![image](https://github.com/teher0094/osTicket-Exploration/assets/153027290/4dfc32a6-9383-4f0c-bf72-9a86f110f229)  
![image](https://github.com/teher0094/osTicket-Exploration/assets/153027290/a3e4ac87-096e-4719-8a1d-da3b9094eb3e)


## Service Level Agreements (SLAs)
- In my osTicket setup, I implemented three distinct levels of Service Level Agreements (SLAs) to streamline ticket resolution based on urgency and importance.

- Severity A (Urgent): Designed for critical issues, like a reported data breach, where swift action is imperative. Agents are allocated a 24-hour window to resolve these high-priority tickets. An example of such a ticket could be a system outage impacting multiple users.
- Severity B (Regular): For standard issues, such as clients seeking clarification on services or minor technical glitches. These tickets are given a resolution time of 48 hours. A typical case might involve a user needing assistance with account settings.
- Severity C (Low Priority): Addresses less urgent matters like general feedback or service dissatisfaction, with a more relaxed 72-hour resolution timeframe. For instance, a customer providing suggestions for service improvement would fall into this category.

![image](https://github.com/teher0094/osTicket-Exploration/assets/153027290/5905e58d-1539-471d-866a-58fbea3bf8d0)

- Clients initially categorize their tickets, but agents have the discretion to reassess and adjust the severity based on the issue's actual urgency and impact. This flexibility ensures that tickets are triaged effectively, balancing the need for prompt responses to critical issues with the practicalities of day-to-day operations.
- Implementing these varied SLA levels has proved crucial in enhancing ticket triaging efficiency. It allows the team to prioritize resources effectively, ensuring that urgent matters are addressed promptly while still managing regular and low-priority inquiries, thereby optimizing customer satisfaction and operational efficiency.


## Conclusion and Learnings
Reflecting on the project, I gained valuable insights into the setup and management of a ticketing system. This experience highlighted the importance of strategic planning, efficient categorization, and effective communication in a client-focused environment.

