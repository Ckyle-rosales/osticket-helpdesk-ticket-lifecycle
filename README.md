# osTicket Help Desk Ticket Lifecycle Simulation

## Project Summary

This project demonstrates a simulated help desk ticketing environment using osTicket. I configured a fake company environment, departments, agents, roles, SLA plans, and support tickets to show how IT support teams receive, prioritize, assign, document, troubleshoot, and resolve user issues.

## Tools Used

- osTicket
- XAMPP
- Apache
- MySQL / phpMyAdmin
- Web Browser
- GitHub

## Skills Demonstrated

- Help desk ticket management
- Ticket lifecycle documentation
- SLA priority handling
- User account troubleshooting
- Printer troubleshooting
- Ticket assignment and escalation
- Internal notes and agent communication
- Role-based permissions
- Technical documentation
  
## 1. I configured the company profile for the simulated help desk environment.
<img width="1298" height="493" alt="Screenshot 2026-05-19 052851" src="https://github.com/user-attachments/assets/8faf9eb2-5574-4d5f-996f-203885ad674e" />

## 2. Department Configuration

I created multiple departments to simulate how tickets are routed in a real IT support environment. Departments help separate general support, IT issues, network issues, and HR-related requests.
<img width="1119" height="829" alt="Screenshot 2026-05-19 053118" src="https://github.com/user-attachments/assets/20b800c0-6bfc-4fd8-b497-422a2c10a068" />
<img width="878" height="874" alt="Screenshot 2026-05-20 073131" src="https://github.com/user-attachments/assets/c8d920d4-3828-4d6d-b648-2cbad22190d5" />

## 3. Role and Permission Configuration

I created different agent roles with different permissions. This simulates role-based access control, where help desk technicians, IT managers, and network technicians have different levels of access inside the ticketing system.
<img width="1179" height="509" alt="Screenshot 2026-05-19 053417" src="https://github.com/user-attachments/assets/23393820-c4cc-44c7-a6da-4f84a14ffdde" />
<img width="1062" height="290" alt="Screenshot 2026-05-19 053754" src="https://github.com/user-attachments/assets/3398ebe6-668e-4199-83a1-13b80f28a308" />
<img width="1226" height="541" alt="Screenshot 2026-05-19 053540" src="https://github.com/user-attachments/assets/7bd513aa-dead-4534-88fb-bb09289058ae" />
## 4. Agent Configuration

I created support agents and assigned them to different roles and departments. This demonstrates how tickets can be assigned to specific technicians based on the issue type.
<img width="998" height="220" alt="Screenshot 2026-05-19 054659" src="https://github.com/user-attachments/assets/14e0d578-aec3-41e1-b735-2b2248d3e3d0" />
<img width="1396" height="854" alt="Screenshot 2026-05-19 054042" src="https://github.com/user-attachments/assets/dc485c3a-7066-4912-9192-d89a398723bd" />
## 5. SLA Configuration

I created SLA plans to show how help desk teams prioritize tickets based on urgency and business impact. Critical issues have shorter response windows, while lower priority requests have longer response times.
<img width="1306" height="483" alt="Screenshot 2026-05-19 055226" src="https://github.com/user-attachments/assets/b9f1b755-25cb-466e-9fef-6de362597b4f" />
<img width="1225" height="592" alt="Screenshot 2026-05-19 055143" src="https://github.com/user-attachments/assets/af6840c2-98f8-49f3-8ff8-792a8f7831ba" />
<img width="1203" height="587" alt="Screenshot 2026-05-19 055136" src="https://github.com/user-attachments/assets/c00a54c5-be44-4558-a392-2f7d7dbbfb69" />
<img width="1268" height="673" alt="Screenshot 2026-05-19 054955" src="https://github.com/user-attachments/assets/12dab4b7-6f30-4db8-b833-c3d01f0fc598" />
## 6. Ticket Scenario 1: Email Login Issue

A user reported being unable to log into their company email account. The ticket was assigned a high priority because the user needed access before a meeting.

### Troubleshooting Steps

- Verified the user's login issue
- Documented that the account was locked after multiple failed attempts
- Simulated unlocking the account
- Simulated issuing a temporary password
- Instructed the user to reset their password at next login
- Added an internal note and agent response

### Outcome

The issue was documented as resolved after the user regained access to company email.

<img width="861" height="743" alt="Screenshot 2026-05-19 060347" src="https://github.com/user-attachments/assets/06efe059-d27b-4951-a5f6-fce8d54ddaba" />

## 7. Ticket Scenario 2: Front Desk Printer Issue

A user reported that the front desk printer was not printing and that multiple staff members were affected. The ticket was assigned to Network Support under a normal SLA priority.

### Troubleshooting Steps

- Confirmed the printer issue affected multiple users
- Checked printer status
- Cleared the stuck print queue
- Verified network connectivity
- Restarted the printer
- Documented that printing was restored

### Outcome

The printer issue was documented as resolved after clearing the queue, verifying connectivity, and restarting the printer.

<img width="721" height="586" alt="image" src="https://github.com/user-attachments/assets/ba61ce5f-2b2f-418f-b222-92e51616bc40" />

## What I Learned

This project helped me understand how a real help desk ticketing system works. I practiced configuring departments, roles, agents, SLA plans, and documenting tickets from creation to resolution.



