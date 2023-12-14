# osTicket-Exploration

## Project Overview
In this project, I designed and managed an osTicket system for a simulated company, Americorp, to closely mirror a real-world IT support environment. The aim was to set up a structured ticketing system that efficiently categorizes and manages public inquiries and technical issues across various IT domains. Through this project, I wanted to gain more insight on the dynamics of a ticketing system, enhancing my skills in strategic planning, user role management, and effective communication within a client-service framework.


## Objectives
- **Department Structuring:** Organize agents into appropriate Teams and Departments
- **Agent Setup:** Create agents and configure access based on team membership.
- **Ticket Simulation:** Generate tickets to be processed by agents.
- **Severity Level Configuration:** Create different levels of severity for ticket triage. 

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


- The differentiation in access and abilities between the admins and agents, as well as between the Tier 1 and Tier 2 agents, is designed to reflect a real-world IT support structure. Agents operate within their scope of expertise, contributing to their respective department's functionality, while admins provide overarching management and support, crucial for maintaining operational integrity and service quality.

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
Completing the osTicket project has significantly enhanced my understanding of an efficient ticketing system's operations. Stepping into the shoes of an admin, albeit in a simulated environment, has opened my eyes to the multifaceted responsibilities that real-world administrators tackle daily. Although initially challenging due to my limited experience in such a role, the project proved to be a profound learning opportunity. It not only bolstered my knowledge of IT department structures, gleaned from extensive research, but also drew numerous parallels to Active Directory, reinforcing my comprehension of hierarchical systems.

This project has been instrumental in building upon my existing AD knowledge and has solidified my grasp of key administrative principles. The hands-on experience gained through this simulation was invaluable, far surpassing what could be learned from theoretical study alone. As I move forward, the practical skills and insights acquired here will undoubtedly be a cornerstone in my professional toolkit. I am confident that the competencies developed through this project will significantly benefit my future employment endeavors, allowing me to contribute more effectively in my positions. 

